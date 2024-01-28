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
# Warmup Iteration   1: 4.941 ops/ms
# Warmup Iteration   2: 11.996 ops/ms
# Warmup Iteration   3: 12.168 ops/ms
Iteration   1: 12.317 ops/ms
Iteration   2: 12.422 ops/ms
Iteration   3: 12.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.413 ±(99.9%) 1.672 ops/ms [Average]
  (min, avg, max) = (12.317, 12.413, 12.499), stdev = 0.092
  CI (99.9%): [10.741, 14.085] (assumes normal distribution)


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
# Warmup Iteration   1: 8.636 ops/ms
# Warmup Iteration   2: 13.148 ops/ms
# Warmup Iteration   3: 13.299 ops/ms
Iteration   1: 13.222 ops/ms
Iteration   2: 13.210 ops/ms
Iteration   3: 13.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.200 ±(99.9%) 0.512 ops/ms [Average]
  (min, avg, max) = (13.169, 13.200, 13.222), stdev = 0.028
  CI (99.9%): [12.688, 13.712] (assumes normal distribution)


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
# Warmup Iteration   1: 8.240 ops/ms
# Warmup Iteration   2: 12.447 ops/ms
# Warmup Iteration   3: 12.704 ops/ms
Iteration   1: 12.817 ops/ms
Iteration   2: 12.783 ops/ms
Iteration   3: 12.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.739 ±(99.9%) 1.938 ops/ms [Average]
  (min, avg, max) = (12.618, 12.739, 12.817), stdev = 0.106
  CI (99.9%): [10.801, 14.678] (assumes normal distribution)


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
# Warmup Iteration   1: 6.648 ops/ms
# Warmup Iteration   2: 10.373 ops/ms
# Warmup Iteration   3: 10.549 ops/ms
Iteration   1: 10.540 ops/ms
Iteration   2: 10.484 ops/ms
Iteration   3: 10.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.502 ±(99.9%) 0.598 ops/ms [Average]
  (min, avg, max) = (10.483, 10.502, 10.540), stdev = 0.033
  CI (99.9%): [9.904, 11.100] (assumes normal distribution)


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
# Warmup Iteration   1: 4.158 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
Iteration   1: 2.516 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.498 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.508 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (2.498, 2.508, 2.516), stdev = 0.009
  CI (99.9%): [2.343, 2.672] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.794 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.004 ms/op
Iteration   1: 2.495 ±(99.9%) 0.004 ms/op
Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
Iteration   3: 2.489 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.486 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (2.475, 2.486, 2.495), stdev = 0.010
  CI (99.9%): [2.306, 2.666] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.821 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.004 ms/op
Iteration   1: 2.467 ±(99.9%) 0.004 ms/op
Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
Iteration   3: 2.460 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.464 ±(99.9%) 0.064 ms/op [Average]
  (min, avg, max) = (2.460, 2.464, 2.467), stdev = 0.004
  CI (99.9%): [2.400, 2.528] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.922 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.005 ms/op
Iteration   1: 2.998 ±(99.9%) 0.006 ms/op
Iteration   2: 2.994 ±(99.9%) 0.005 ms/op
Iteration   3: 2.998 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.997 ±(99.9%) 0.035 ms/op [Average]
  (min, avg, max) = (2.994, 2.997, 2.998), stdev = 0.002
  CI (99.9%): [2.962, 3.031] (assumes normal distribution)


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.007 ms/op
Iteration   1: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.699 ms/op
                 createUser·p0.999:  10.867 ms/op
                 createUser·p0.9999: 13.292 ms/op
                 createUser·p1.00:   13.959 ms/op

Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  8.533 ms/op
                 createUser·p0.9999: 12.428 ms/op
                 createUser·p1.00:   13.025 ms/op

Iteration   3: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  8.381 ms/op
                 createUser·p0.9999: 11.272 ms/op
                 createUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380681
  mean =      2.519 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 183128 
    [ 2.500,  3.750) = 193759 
    [ 3.750,  5.000) = 3115 
    [ 5.000,  6.250) = 224 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      8.464 ms/op
     p(99.9900) =     12.990 ms/op
     p(99.9990) =     13.897 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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
# Warmup Iteration   1: 3.710 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.006 ms/op
Iteration   1: 2.483 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.687 ms/op
                 existUser·p0.999:  8.546 ms/op
                 existUser·p0.9999: 16.908 ms/op
                 existUser·p1.00:   17.203 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  6.324 ms/op
                 existUser·p0.9999: 12.993 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  6.973 ms/op
                 existUser·p0.9999: 12.142 ms/op
                 existUser·p1.00:   13.058 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388133
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 190695 
    [ 2.500,  3.750) = 194327 
    [ 3.750,  5.000) = 2374 
    [ 5.000,  6.250) = 267 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.596 ms/op
     p(99.9000) =      6.471 ms/op
     p(99.9900) =     15.338 ms/op
     p(99.9990) =     17.109 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 3.819 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.006 ms/op
Iteration   1: 2.531 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  11.536 ms/op
                 getUser·p0.9999: 16.269 ms/op
                 getUser·p1.00:   16.843 ms/op

Iteration   2: 2.542 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  9.507 ms/op
                 getUser·p0.9999: 12.515 ms/op
                 getUser·p1.00:   13.517 ms/op

Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  8.071 ms/op
                 getUser·p0.9999: 10.469 ms/op
                 getUser·p1.00:   10.748 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379561
  mean =      2.527 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 184950 
    [ 2.500,  3.750) = 188012 
    [ 3.750,  5.000) = 5387 
    [ 5.000,  6.250) = 724 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      8.308 ms/op
     p(99.9900) =     13.584 ms/op
     p(99.9990) =     16.784 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 4.614 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.008 ms/op
Iteration   1: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.883 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  8.838 ms/op
                 listUser·p0.9999: 10.525 ms/op
                 listUser·p1.00:   10.764 ms/op

Iteration   2: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.352 ms/op
                 listUser·p0.9999: 11.715 ms/op
                 listUser·p1.00:   13.124 ms/op

Iteration   3: 3.034 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.986 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.169 ms/op
                 listUser·p0.9999: 10.346 ms/op
                 listUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319247
  mean =      3.005 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 93757 
    [ 2.500,  3.750) = 187160 
    [ 3.750,  5.000) = 31013 
    [ 5.000,  6.250) = 5850 
    [ 6.250,  7.500) = 678 
    [ 7.500,  8.750) = 302 
    [ 8.750, 10.000) = 252 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     11.273 ms/op
     p(99.9990) =     12.444 ms/op
     p(99.9999) =     13.124 ms/op
    p(100.0000) =     13.124 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.413 ± 1.672  ops/ms
ClientPb.existUser                       thrpt       3  13.200 ± 0.512  ops/ms
ClientPb.getUser                         thrpt       3  12.739 ± 1.938  ops/ms
ClientPb.listUser                        thrpt       3  10.502 ± 0.598  ops/ms
ClientPb.createUser                       avgt       3   2.508 ± 0.164   ms/op
ClientPb.existUser                        avgt       3   2.486 ± 0.180   ms/op
ClientPb.getUser                          avgt       3   2.464 ± 0.064   ms/op
ClientPb.listUser                         avgt       3   2.997 ± 0.035   ms/op
ClientPb.createUser                     sample  380681   2.519 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.827           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.464           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.990           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.959           ms/op
ClientPb.existUser                      sample  388133   2.471 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.844           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.471           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.338           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.203           ms/op
ClientPb.getUser                        sample  379561   2.527 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.896           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.308           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.584           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.843           ms/op
ClientPb.listUser                       sample  319247   3.005 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.883           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.110           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.273           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.124           ms/op
