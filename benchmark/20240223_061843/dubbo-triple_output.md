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
# Warmup Iteration   1: 4.491 ops/ms
# Warmup Iteration   2: 11.647 ops/ms
# Warmup Iteration   3: 12.305 ops/ms
Iteration   1: 12.393 ops/ms
Iteration   2: 12.409 ops/ms
Iteration   3: 12.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.466 ±(99.9%) 2.057 ops/ms [Average]
  (min, avg, max) = (12.393, 12.466, 12.596), stdev = 0.113
  CI (99.9%): [10.409, 14.523] (assumes normal distribution)


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
# Warmup Iteration   1: 7.790 ops/ms
# Warmup Iteration   2: 12.760 ops/ms
# Warmup Iteration   3: 12.938 ops/ms
Iteration   1: 12.840 ops/ms
Iteration   2: 12.930 ops/ms
Iteration   3: 12.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.874 ±(99.9%) 0.894 ops/ms [Average]
  (min, avg, max) = (12.840, 12.874, 12.930), stdev = 0.049
  CI (99.9%): [11.980, 13.768] (assumes normal distribution)


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
# Warmup Iteration   1: 7.880 ops/ms
# Warmup Iteration   2: 12.573 ops/ms
# Warmup Iteration   3: 12.690 ops/ms
Iteration   1: 12.720 ops/ms
Iteration   2: 12.566 ops/ms
Iteration   3: 12.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.697 ±(99.9%) 2.211 ops/ms [Average]
  (min, avg, max) = (12.566, 12.697, 12.805), stdev = 0.121
  CI (99.9%): [10.486, 14.908] (assumes normal distribution)


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
# Warmup Iteration   1: 6.846 ops/ms
# Warmup Iteration   2: 10.344 ops/ms
# Warmup Iteration   3: 10.472 ops/ms
Iteration   1: 10.617 ops/ms
Iteration   2: 10.577 ops/ms
Iteration   3: 10.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.604 ±(99.9%) 0.427 ops/ms [Average]
  (min, avg, max) = (10.577, 10.604, 10.618), stdev = 0.023
  CI (99.9%): [10.177, 11.031] (assumes normal distribution)


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
# Warmup Iteration   1: 4.092 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.004 ms/op
Iteration   1: 2.524 ±(99.9%) 0.004 ms/op
Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
Iteration   3: 2.503 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.510 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (2.502, 2.510, 2.524), stdev = 0.012
  CI (99.9%): [2.282, 2.738] (assumes normal distribution)


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
# Warmup Iteration   1: 3.814 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.003 ms/op
Iteration   1: 2.470 ±(99.9%) 0.004 ms/op
Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
Iteration   3: 2.442 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.458 ±(99.9%) 0.258 ms/op [Average]
  (min, avg, max) = (2.442, 2.458, 2.470), stdev = 0.014
  CI (99.9%): [2.199, 2.716] (assumes normal distribution)


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
# Warmup Iteration   1: 3.892 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.005 ms/op
Iteration   1: 2.545 ±(99.9%) 0.005 ms/op
Iteration   2: 2.535 ±(99.9%) 0.003 ms/op
Iteration   3: 2.528 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.536 ±(99.9%) 0.155 ms/op [Average]
  (min, avg, max) = (2.528, 2.536, 2.545), stdev = 0.008
  CI (99.9%): [2.381, 2.691] (assumes normal distribution)


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
# Warmup Iteration   1: 4.643 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
Iteration   1: 3.010 ±(99.9%) 0.005 ms/op
Iteration   2: 3.009 ±(99.9%) 0.005 ms/op
Iteration   3: 3.026 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.015 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (3.009, 3.015, 3.026), stdev = 0.010
  CI (99.9%): [2.841, 3.189] (assumes normal distribution)


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
# Warmup Iteration   1: 4.103 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.663 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
Iteration   1: 2.530 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.985 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  12.249 ms/op
                 createUser·p0.9999: 16.810 ms/op
                 createUser·p1.00:   17.170 ms/op

Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  9.159 ms/op
                 createUser·p0.9999: 12.594 ms/op
                 createUser·p1.00:   13.074 ms/op

Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.801 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.912 ms/op
                 createUser·p0.999:  8.084 ms/op
                 createUser·p0.9999: 10.476 ms/op
                 createUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379336
  mean =      2.528 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 183161 
    [ 2.500,  3.750) = 192253 
    [ 3.750,  5.000) = 3031 
    [ 5.000,  6.250) = 364 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 97 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      8.629 ms/op
     p(99.9900) =     14.844 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 3.870 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  6.238 ms/op
                 existUser·p0.9999: 16.548 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   2.621 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  8.134 ms/op
                 existUser·p0.9999: 12.226 ms/op
                 existUser·p1.00:   12.354 ms/op

Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   3.064 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.736 ms/op
                 existUser·p0.999:  6.493 ms/op
                 existUser·p0.9999: 12.550 ms/op
                 existUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384013
  mean =      2.498 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 186370 
    [ 2.500,  3.750) = 194474 
    [ 3.750,  5.000) = 2346 
    [ 5.000,  6.250) = 392 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      7.045 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 3.999 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.005 ms/op
Iteration   1: 2.576 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  11.616 ms/op
                 getUser·p0.9999: 13.267 ms/op
                 getUser·p1.00:   13.599 ms/op

Iteration   2: 2.567 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   2.605 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  9.421 ms/op
                 getUser·p0.9999: 13.353 ms/op
                 getUser·p1.00:   14.434 ms/op

Iteration   3: 2.557 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  8.667 ms/op
                 getUser·p0.9999: 12.018 ms/op
                 getUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 373672
  mean =      2.567 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 181430 
    [ 2.500,  3.750) = 186465 
    [ 3.750,  5.000) = 4290 
    [ 5.000,  6.250) = 960 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 123 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      8.738 ms/op
     p(99.9900) =     13.073 ms/op
     p(99.9990) =     14.279 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


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
# Warmup Iteration   1: 4.666 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.009 ms/op
Iteration   1: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 11.621 ms/op
                 listUser·p1.00:   12.747 ms/op

Iteration   2: 3.034 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.071 ms/op
                 listUser·p0.9999: 12.744 ms/op
                 listUser·p1.00:   13.582 ms/op

Iteration   3: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.711 ms/op
                 listUser·p0.9999: 11.411 ms/op
                 listUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316544
  mean =      3.030 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 86417 
    [ 2.500,  3.750) = 190243 
    [ 3.750,  5.000) = 32912 
    [ 5.000,  6.250) = 5690 
    [ 6.250,  7.500) = 513 
    [ 7.500,  8.750) = 184 
    [ 8.750, 10.000) = 273 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     11.819 ms/op
     p(99.9990) =     13.334 ms/op
     p(99.9999) =     13.582 ms/op
    p(100.0000) =     13.582 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.466 ± 2.057  ops/ms
ClientPb.existUser                       thrpt       3  12.874 ± 0.894  ops/ms
ClientPb.getUser                         thrpt       3  12.697 ± 2.211  ops/ms
ClientPb.listUser                        thrpt       3  10.604 ± 0.427  ops/ms
ClientPb.createUser                       avgt       3   2.510 ± 0.228   ms/op
ClientPb.existUser                        avgt       3   2.458 ± 0.258   ms/op
ClientPb.getUser                          avgt       3   2.536 ± 0.155   ms/op
ClientPb.listUser                         avgt       3   3.015 ± 0.174   ms/op
ClientPb.createUser                     sample  379336   2.528 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.801           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.629           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.844           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.170           ms/op
ClientPb.existUser                      sample  384013   2.498 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.755           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.589           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.045           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.713           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.072           ms/op
ClientPb.getUser                        sample  373672   2.567 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.957           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.593           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.137           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.738           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.073           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.434           ms/op
ClientPb.listUser                       sample  316544   3.030 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.890           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.421           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.819           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.582           ms/op
