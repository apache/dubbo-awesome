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
# Warmup Iteration   1: 5.010 ops/ms
# Warmup Iteration   2: 12.176 ops/ms
# Warmup Iteration   3: 12.135 ops/ms
Iteration   1: 12.320 ops/ms
Iteration   2: 12.532 ops/ms
Iteration   3: 12.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.455 ±(99.9%) 2.136 ops/ms [Average]
  (min, avg, max) = (12.320, 12.455, 12.532), stdev = 0.117
  CI (99.9%): [10.319, 14.591] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.864 ops/ms
# Warmup Iteration   2: 12.922 ops/ms
# Warmup Iteration   3: 13.096 ops/ms
Iteration   1: 13.104 ops/ms
Iteration   2: 13.087 ops/ms
Iteration   3: 13.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.096 ±(99.9%) 0.157 ops/ms [Average]
  (min, avg, max) = (13.087, 13.096, 13.104), stdev = 0.009
  CI (99.9%): [12.939, 13.252] (assumes normal distribution)


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
# Warmup Iteration   1: 7.790 ops/ms
# Warmup Iteration   2: 12.725 ops/ms
# Warmup Iteration   3: 12.906 ops/ms
Iteration   1: 13.059 ops/ms
Iteration   2: 12.985 ops/ms
Iteration   3: 13.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.056 ±(99.9%) 1.283 ops/ms [Average]
  (min, avg, max) = (12.985, 13.056, 13.125), stdev = 0.070
  CI (99.9%): [11.773, 14.339] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.060 ops/ms
# Warmup Iteration   2: 10.521 ops/ms
# Warmup Iteration   3: 10.593 ops/ms
Iteration   1: 10.716 ops/ms
Iteration   2: 10.591 ops/ms
Iteration   3: 10.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.586 ±(99.9%) 2.414 ops/ms [Average]
  (min, avg, max) = (10.452, 10.586, 10.716), stdev = 0.132
  CI (99.9%): [8.173, 13.000] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.222 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.626 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.004 ms/op
Iteration   1: 2.572 ±(99.9%) 0.004 ms/op
Iteration   2: 2.549 ±(99.9%) 0.003 ms/op
Iteration   3: 2.577 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.566 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (2.549, 2.566, 2.577), stdev = 0.015
  CI (99.9%): [2.295, 2.837] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.766 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.004 ms/op
Iteration   1: 2.480 ±(99.9%) 0.004 ms/op
Iteration   2: 2.445 ±(99.9%) 0.004 ms/op
Iteration   3: 2.464 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.463 ±(99.9%) 0.317 ms/op [Average]
  (min, avg, max) = (2.445, 2.463, 2.480), stdev = 0.017
  CI (99.9%): [2.146, 2.780] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.028 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.004 ms/op
Iteration   1: 2.518 ±(99.9%) 0.005 ms/op
Iteration   2: 2.515 ±(99.9%) 0.004 ms/op
Iteration   3: 2.532 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.522 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (2.515, 2.522, 2.532), stdev = 0.009
  CI (99.9%): [2.354, 2.690] (assumes normal distribution)


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
# Warmup Iteration   1: 4.950 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.004 ms/op
Iteration   1: 2.982 ±(99.9%) 0.005 ms/op
Iteration   2: 3.006 ±(99.9%) 0.006 ms/op
Iteration   3: 3.027 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.005 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (2.982, 3.005, 3.027), stdev = 0.022
  CI (99.9%): [2.595, 3.415] (assumes normal distribution)


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
# Warmup Iteration   1: 4.269 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.678 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  11.878 ms/op
                 createUser·p0.9999: 14.300 ms/op
                 createUser·p1.00:   15.073 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.664 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  10.110 ms/op
                 createUser·p0.9999: 13.242 ms/op
                 createUser·p1.00:   13.484 ms/op

Iteration   3: 2.532 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   4.147 ms/op
                 createUser·p0.999:  8.696 ms/op
                 createUser·p0.9999: 16.908 ms/op
                 createUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380982
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 184478 
    [ 2.500,  3.750) = 191921 
    [ 3.750,  5.000) = 3520 
    [ 5.000,  6.250) = 525 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      8.700 ms/op
     p(99.9900) =     14.564 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 3.967 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
Iteration   1: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  8.185 ms/op
                 existUser·p0.9999: 14.057 ms/op
                 existUser·p1.00:   14.877 ms/op

Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  5.662 ms/op
                 existUser·p0.9999: 13.793 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.970 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  7.742 ms/op
                 existUser·p0.9999: 11.013 ms/op
                 existUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388093
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 192918 
    [ 2.500,  3.750) = 192082 
    [ 3.750,  5.000) = 2348 
    [ 5.000,  6.250) = 276 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 118 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =      7.191 ms/op
     p(99.9900) =     13.720 ms/op
     p(99.9990) =     14.706 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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
# Warmup Iteration   1: 3.945 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.596 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.805 ms/op
                 getUser·p0.999:  11.895 ms/op
                 getUser·p0.9999: 13.681 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   2: 2.510 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.108 ms/op
                 getUser·p0.999:  9.402 ms/op
                 getUser·p0.9999: 14.675 ms/op
                 getUser·p1.00:   15.614 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  8.618 ms/op
                 getUser·p0.9999: 13.967 ms/op
                 getUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382153
  mean =      2.510 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 189726 
    [ 2.500,  3.750) = 186311 
    [ 3.750,  5.000) = 5192 
    [ 5.000,  6.250) = 424 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 136 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      4.067 ms/op
     p(99.9000) =      8.632 ms/op
     p(99.9900) =     14.005 ms/op
     p(99.9990) =     15.290 ms/op
     p(99.9999) =     15.614 ms/op
    p(100.0000) =     15.614 ms/op


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
# Warmup Iteration   1: 4.845 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.009 ms/op
Iteration   1: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.227 ms/op
                 listUser·p0.9999: 11.289 ms/op
                 listUser·p1.00:   11.895 ms/op

Iteration   2: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.937 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 11.255 ms/op
                 listUser·p1.00:   12.435 ms/op

Iteration   3: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.836 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.437 ms/op
                 listUser·p0.9999: 10.803 ms/op
                 listUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317061
  mean =      3.025 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 140 
    [ 1.250,  2.500) = 87615 
    [ 2.500,  3.750) = 188631 
    [ 3.750,  5.000) = 33395 
    [ 5.000,  6.250) = 6038 
    [ 6.250,  7.500) = 595 
    [ 7.500,  8.750) = 191 
    [ 8.750, 10.000) = 273 
    [10.000, 11.250) = 158 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     11.113 ms/op
     p(99.9990) =     11.963 ms/op
     p(99.9999) =     12.435 ms/op
    p(100.0000) =     12.435 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.455 ± 2.136  ops/ms
ClientPb.existUser                       thrpt       3  13.096 ± 0.157  ops/ms
ClientPb.getUser                         thrpt       3  13.056 ± 1.283  ops/ms
ClientPb.listUser                        thrpt       3  10.586 ± 2.414  ops/ms
ClientPb.createUser                       avgt       3   2.566 ± 0.271   ms/op
ClientPb.existUser                        avgt       3   2.463 ± 0.317   ms/op
ClientPb.getUser                          avgt       3   2.522 ± 0.168   ms/op
ClientPb.listUser                         avgt       3   3.005 ± 0.410   ms/op
ClientPb.createUser                     sample  380982   2.518 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.664           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.700           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.564           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.776           ms/op
ClientPb.existUser                      sample  388093   2.471 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.761           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.191           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.720           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.877           ms/op
ClientPb.getUser                        sample  382153   2.510 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.962           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.067           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.632           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.005           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.614           ms/op
ClientPb.listUser                       sample  317061   3.025 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.836           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.355           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.113           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.435           ms/op
