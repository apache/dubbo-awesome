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
# Warmup Iteration   1: 4.464 ops/ms
# Warmup Iteration   2: 11.999 ops/ms
# Warmup Iteration   3: 12.387 ops/ms
Iteration   1: 12.617 ops/ms
Iteration   2: 12.653 ops/ms
Iteration   3: 12.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.660 ±(99.9%) 0.845 ops/ms [Average]
  (min, avg, max) = (12.617, 12.660, 12.709), stdev = 0.046
  CI (99.9%): [11.814, 13.505] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.102 ops/ms
# Warmup Iteration   2: 13.116 ops/ms
# Warmup Iteration   3: 13.123 ops/ms
Iteration   1: 13.252 ops/ms
Iteration   2: 13.198 ops/ms
Iteration   3: 13.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.182 ±(99.9%) 1.444 ops/ms [Average]
  (min, avg, max) = (13.096, 13.182, 13.252), stdev = 0.079
  CI (99.9%): [11.738, 14.625] (assumes normal distribution)


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
# Warmup Iteration   1: 7.937 ops/ms
# Warmup Iteration   2: 12.588 ops/ms
# Warmup Iteration   3: 12.868 ops/ms
Iteration   1: 12.991 ops/ms
Iteration   2: 12.950 ops/ms
Iteration   3: 12.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.858 ±(99.9%) 3.570 ops/ms [Average]
  (min, avg, max) = (12.633, 12.858, 12.991), stdev = 0.196
  CI (99.9%): [9.288, 16.428] (assumes normal distribution)


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
# Warmup Iteration   1: 6.326 ops/ms
# Warmup Iteration   2: 10.425 ops/ms
# Warmup Iteration   3: 10.658 ops/ms
Iteration   1: 10.684 ops/ms
Iteration   2: 10.721 ops/ms
Iteration   3: 10.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.702 ±(99.9%) 0.339 ops/ms [Average]
  (min, avg, max) = (10.684, 10.702, 10.721), stdev = 0.019
  CI (99.9%): [10.363, 11.041] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.103 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.566 ±(99.9%) 0.005 ms/op
Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
Iteration   3: 2.499 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.531 ±(99.9%) 0.619 ms/op [Average]
  (min, avg, max) = (2.499, 2.531, 2.566), stdev = 0.034
  CI (99.9%): [1.912, 3.150] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.786 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.004 ms/op
Iteration   1: 2.444 ±(99.9%) 0.005 ms/op
Iteration   2: 2.464 ±(99.9%) 0.003 ms/op
Iteration   3: 2.432 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.447 ±(99.9%) 0.294 ms/op [Average]
  (min, avg, max) = (2.432, 2.447, 2.464), stdev = 0.016
  CI (99.9%): [2.153, 2.741] (assumes normal distribution)


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
# Warmup Iteration   1: 3.888 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.003 ms/op
Iteration   1: 2.469 ±(99.9%) 0.004 ms/op
Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
Iteration   3: 2.461 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.468 ±(99.9%) 0.121 ms/op [Average]
  (min, avg, max) = (2.461, 2.468, 2.474), stdev = 0.007
  CI (99.9%): [2.347, 2.590] (assumes normal distribution)


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
# Warmup Iteration   1: 4.600 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.004 ms/op
Iteration   1: 3.030 ±(99.9%) 0.005 ms/op
Iteration   2: 2.999 ±(99.9%) 0.006 ms/op
Iteration   3: 2.993 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.007 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (2.993, 3.007, 3.030), stdev = 0.020
  CI (99.9%): [2.646, 3.369] (assumes normal distribution)


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
# Warmup Iteration   1: 4.277 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.662 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.006 ms/op
Iteration   1: 2.541 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   4.108 ms/op
                 createUser·p0.999:  11.045 ms/op
                 createUser·p0.9999: 13.451 ms/op
                 createUser·p1.00:   14.238 ms/op

Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.978 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.576 ms/op
                 createUser·p0.999:  9.778 ms/op
                 createUser·p0.9999: 12.686 ms/op
                 createUser·p1.00:   12.976 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.585 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  9.519 ms/op
                 createUser·p0.9999: 10.983 ms/op
                 createUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379380
  mean =      2.528 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 183557 
    [ 2.500,  3.750) = 191399 
    [ 3.750,  5.000) = 3217 
    [ 5.000,  6.250) = 538 
    [ 6.250,  7.500) = 162 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 165 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      9.556 ms/op
     p(99.9900) =     12.927 ms/op
     p(99.9990) =     13.576 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 3.819 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  5.746 ms/op
                 existUser·p0.9999: 13.372 ms/op
                 existUser·p1.00:   13.959 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.461 ms/op
                 existUser·p0.999:  8.790 ms/op
                 existUser·p0.9999: 12.371 ms/op
                 existUser·p1.00:   13.091 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.732 ms/op
                 existUser·p0.999:  8.153 ms/op
                 existUser·p0.9999: 11.603 ms/op
                 existUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386702
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 191411 
    [ 2.500,  3.750) = 192339 
    [ 3.750,  5.000) = 2066 
    [ 5.000,  6.250) = 436 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      6.463 ms/op
     p(99.9900) =     13.091 ms/op
     p(99.9990) =     13.870 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.867 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  11.474 ms/op
                 getUser·p0.9999: 13.574 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   2: 2.536 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.876 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  6.472 ms/op
                 getUser·p0.9999: 12.861 ms/op
                 getUser·p1.00:   17.662 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  8.031 ms/op
                 getUser·p0.9999: 11.391 ms/op
                 getUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381171
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 187771 
    [ 2.500,  3.750) = 188223 
    [ 3.750,  5.000) = 3486 
    [ 5.000,  6.250) = 1215 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.990 ms/op
     p(99.9000) =      6.564 ms/op
     p(99.9900) =     12.927 ms/op
     p(99.9990) =     14.161 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 4.703 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
Iteration   1: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.828 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.019 ms/op
                 listUser·p0.9999: 10.525 ms/op
                 listUser·p1.00:   10.863 ms/op

Iteration   2: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.728 ms/op
                 listUser·p0.9999: 11.174 ms/op
                 listUser·p1.00:   12.861 ms/op

Iteration   3: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.743 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 10.055 ms/op
                 listUser·p1.00:   10.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316827
  mean =      3.027 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 90019 
    [ 2.500,  3.750) = 185955 
    [ 3.750,  5.000) = 32932 
    [ 5.000,  6.250) = 6390 
    [ 6.250,  7.500) = 771 
    [ 7.500,  8.750) = 196 
    [ 8.750, 10.000) = 318 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     10.699 ms/op
     p(99.9990) =     11.447 ms/op
     p(99.9999) =     12.861 ms/op
    p(100.0000) =     12.861 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.660 ± 0.845  ops/ms
ClientPb.existUser                       thrpt       3  13.182 ± 1.444  ops/ms
ClientPb.getUser                         thrpt       3  12.858 ± 3.570  ops/ms
ClientPb.listUser                        thrpt       3  10.702 ± 0.339  ops/ms
ClientPb.createUser                       avgt       3   2.531 ± 0.619   ms/op
ClientPb.existUser                        avgt       3   2.447 ± 0.294   ms/op
ClientPb.getUser                          avgt       3   2.468 ± 0.121   ms/op
ClientPb.listUser                         avgt       3   3.007 ± 0.362   ms/op
ClientPb.createUser                     sample  379380   2.528 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.585           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.556           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.927           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.238           ms/op
ClientPb.existUser                      sample  386702   2.480 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.950           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.463           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.091           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.959           ms/op
ClientPb.getUser                        sample  381171   2.516 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.876           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.564           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.927           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.662           ms/op
ClientPb.listUser                       sample  316827   3.027 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.743           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.699           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.861           ms/op
