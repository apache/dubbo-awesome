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
# Warmup Iteration   1: 4.823 ops/ms
# Warmup Iteration   2: 12.562 ops/ms
# Warmup Iteration   3: 12.570 ops/ms
Iteration   1: 12.863 ops/ms
Iteration   2: 12.754 ops/ms
Iteration   3: 12.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.833 ±(99.9%) 1.273 ops/ms [Average]
  (min, avg, max) = (12.754, 12.833, 12.884), stdev = 0.070
  CI (99.9%): [11.560, 14.107] (assumes normal distribution)


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
# Warmup Iteration   1: 8.144 ops/ms
# Warmup Iteration   2: 13.136 ops/ms
# Warmup Iteration   3: 13.009 ops/ms
Iteration   1: 13.195 ops/ms
Iteration   2: 12.908 ops/ms
Iteration   3: 13.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.056 ±(99.9%) 2.615 ops/ms [Average]
  (min, avg, max) = (12.908, 13.056, 13.195), stdev = 0.143
  CI (99.9%): [10.441, 15.671] (assumes normal distribution)


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
# Warmup Iteration   1: 7.672 ops/ms
# Warmup Iteration   2: 12.623 ops/ms
# Warmup Iteration   3: 12.744 ops/ms
Iteration   1: 12.814 ops/ms
Iteration   2: 12.704 ops/ms
Iteration   3: 12.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.732 ±(99.9%) 1.323 ops/ms [Average]
  (min, avg, max) = (12.677, 12.732, 12.814), stdev = 0.073
  CI (99.9%): [11.409, 14.055] (assumes normal distribution)


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
# Warmup Iteration   1: 6.922 ops/ms
# Warmup Iteration   2: 10.655 ops/ms
# Warmup Iteration   3: 10.647 ops/ms
Iteration   1: 10.714 ops/ms
Iteration   2: 10.738 ops/ms
Iteration   3: 10.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.728 ±(99.9%) 0.230 ops/ms [Average]
  (min, avg, max) = (10.714, 10.728, 10.738), stdev = 0.013
  CI (99.9%): [10.499, 10.958] (assumes normal distribution)


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.536 ±(99.9%) 0.005 ms/op
Iteration   2: 2.553 ±(99.9%) 0.004 ms/op
Iteration   3: 2.509 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.533 ±(99.9%) 0.402 ms/op [Average]
  (min, avg, max) = (2.509, 2.533, 2.553), stdev = 0.022
  CI (99.9%): [2.131, 2.934] (assumes normal distribution)


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.445 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.004 ms/op
Iteration   1: 2.437 ±(99.9%) 0.004 ms/op
Iteration   2: 2.443 ±(99.9%) 0.003 ms/op
Iteration   3: 2.449 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.443 ±(99.9%) 0.111 ms/op [Average]
  (min, avg, max) = (2.437, 2.443, 2.449), stdev = 0.006
  CI (99.9%): [2.332, 2.554] (assumes normal distribution)


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.004 ms/op
Iteration   1: 2.552 ±(99.9%) 0.005 ms/op
Iteration   2: 2.518 ±(99.9%) 0.004 ms/op
Iteration   3: 2.522 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.530 ±(99.9%) 0.336 ms/op [Average]
  (min, avg, max) = (2.518, 2.530, 2.552), stdev = 0.018
  CI (99.9%): [2.194, 2.866] (assumes normal distribution)


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
# Warmup Iteration   1: 4.723 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.006 ms/op
Iteration   1: 3.020 ±(99.9%) 0.006 ms/op
Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
Iteration   3: 3.016 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.017 ±(99.9%) 0.051 ms/op [Average]
  (min, avg, max) = (3.015, 3.017, 3.020), stdev = 0.003
  CI (99.9%): [2.966, 3.068] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.107 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.675 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
Iteration   1: 2.550 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  12.036 ms/op
                 createUser·p0.9999: 13.707 ms/op
                 createUser·p1.00:   15.139 ms/op

Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  9.707 ms/op
                 createUser·p0.9999: 13.462 ms/op
                 createUser·p1.00:   14.270 ms/op

Iteration   3: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.867 ms/op
                 createUser·p0.999:  7.832 ms/op
                 createUser·p0.9999: 10.387 ms/op
                 createUser·p1.00:   11.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377384
  mean =      2.542 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 181318 
    [ 2.500,  3.750) = 191974 
    [ 3.750,  5.000) = 2952 
    [ 5.000,  6.250) = 705 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      7.901 ms/op
     p(99.9900) =     13.402 ms/op
     p(99.9990) =     14.643 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


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
# Warmup Iteration   1: 3.577 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
Iteration   1: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.387 ms/op
                 existUser·p0.999:  6.649 ms/op
                 existUser·p0.9999: 13.449 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.954 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.420 ms/op
                 existUser·p0.999:  7.879 ms/op
                 existUser·p0.9999: 13.247 ms/op
                 existUser·p1.00:   14.008 ms/op

Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.519 ms/op
                 existUser·p0.999:  6.306 ms/op
                 existUser·p0.9999: 11.626 ms/op
                 existUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393190
  mean =      2.439 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 193857 
    [ 2.500,  3.750) = 196854 
    [ 3.750,  5.000) = 1784 
    [ 5.000,  6.250) = 228 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.441 ms/op
     p(99.9000) =      7.730 ms/op
     p(99.9900) =     13.304 ms/op
     p(99.9990) =     13.706 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.952 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
Iteration   1: 2.514 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  6.516 ms/op
                 getUser·p0.9999: 13.653 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   2: 2.558 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   2.630 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.995 ms/op
                 getUser·p0.9999: 17.482 ms/op
                 getUser·p1.00:   18.088 ms/op

Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.867 ms/op
                 getUser·p0.999:  7.449 ms/op
                 getUser·p0.9999: 12.304 ms/op
                 getUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378897
  mean =      2.531 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 185264 
    [ 2.500,  3.750) = 188100 
    [ 3.750,  5.000) = 4043 
    [ 5.000,  6.250) = 1022 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      4.080 ms/op
     p(99.9000) =      7.056 ms/op
     p(99.9900) =     13.815 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 4.722 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.009 ms/op
Iteration   1: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  8.569 ms/op
                 listUser·p0.9999: 10.512 ms/op
                 listUser·p1.00:   10.961 ms/op

Iteration   2: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  10.027 ms/op
                 listUser·p0.9999: 11.729 ms/op
                 listUser·p1.00:   12.583 ms/op

Iteration   3: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  9.148 ms/op
                 listUser·p0.9999: 11.092 ms/op
                 listUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320323
  mean =      2.994 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 98361 
    [ 2.500,  3.750) = 183730 
    [ 3.750,  5.000) = 30393 
    [ 5.000,  6.250) = 6207 
    [ 6.250,  7.500) = 830 
    [ 7.500,  8.750) = 268 
    [ 8.750, 10.000) = 229 
    [10.000, 11.250) = 155 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     11.239 ms/op
     p(99.9990) =     12.501 ms/op
     p(99.9999) =     12.583 ms/op
    p(100.0000) =     12.583 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.833 ± 1.273  ops/ms
ClientPb.existUser                       thrpt       3  13.056 ± 2.615  ops/ms
ClientPb.getUser                         thrpt       3  12.732 ± 1.323  ops/ms
ClientPb.listUser                        thrpt       3  10.728 ± 0.230  ops/ms
ClientPb.createUser                       avgt       3   2.533 ± 0.402   ms/op
ClientPb.existUser                        avgt       3   2.443 ± 0.111   ms/op
ClientPb.getUser                          avgt       3   2.530 ± 0.336   ms/op
ClientPb.listUser                         avgt       3   3.017 ± 0.051   ms/op
ClientPb.createUser                     sample  377384   2.542 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.918           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.634           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.901           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.402           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.139           ms/op
ClientPb.existUser                      sample  393190   2.439 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.954           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.441           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.730           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.304           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.008           ms/op
ClientPb.getUser                        sample  378897   2.531 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.845           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.589           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.056           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.815           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.088           ms/op
ClientPb.listUser                       sample  320323   2.994 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.862           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.175           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.239           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.583           ms/op
