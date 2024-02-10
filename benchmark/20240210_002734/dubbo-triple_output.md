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
# Warmup Iteration   1: 5.524 ops/ms
# Warmup Iteration   2: 12.031 ops/ms
# Warmup Iteration   3: 12.334 ops/ms
Iteration   1: 12.455 ops/ms
Iteration   2: 12.622 ops/ms
Iteration   3: 12.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.582 ±(99.9%) 2.061 ops/ms [Average]
  (min, avg, max) = (12.455, 12.582, 12.670), stdev = 0.113
  CI (99.9%): [10.521, 14.643] (assumes normal distribution)


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
# Warmup Iteration   1: 8.363 ops/ms
# Warmup Iteration   2: 13.195 ops/ms
# Warmup Iteration   3: 13.117 ops/ms
Iteration   1: 13.075 ops/ms
Iteration   2: 13.342 ops/ms
Iteration   3: 13.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.208 ±(99.9%) 2.437 ops/ms [Average]
  (min, avg, max) = (13.075, 13.208, 13.342), stdev = 0.134
  CI (99.9%): [10.771, 15.645] (assumes normal distribution)


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
# Warmup Iteration   1: 7.880 ops/ms
# Warmup Iteration   2: 12.774 ops/ms
# Warmup Iteration   3: 12.819 ops/ms
Iteration   1: 12.999 ops/ms
Iteration   2: 13.091 ops/ms
Iteration   3: 13.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.033 ±(99.9%) 0.914 ops/ms [Average]
  (min, avg, max) = (12.999, 13.033, 13.091), stdev = 0.050
  CI (99.9%): [12.119, 13.947] (assumes normal distribution)


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
# Warmup Iteration   1: 6.910 ops/ms
# Warmup Iteration   2: 10.603 ops/ms
# Warmup Iteration   3: 10.833 ops/ms
Iteration   1: 10.849 ops/ms
Iteration   2: 10.812 ops/ms
Iteration   3: 10.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.805 ±(99.9%) 0.878 ops/ms [Average]
  (min, avg, max) = (10.753, 10.805, 10.849), stdev = 0.048
  CI (99.9%): [9.927, 11.683] (assumes normal distribution)


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
# Warmup Iteration   1: 4.127 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
Iteration   3: 2.507 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.503 ±(99.9%) 0.106 ms/op [Average]
  (min, avg, max) = (2.496, 2.503, 2.507), stdev = 0.006
  CI (99.9%): [2.397, 2.609] (assumes normal distribution)


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
# Warmup Iteration   1: 3.560 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.004 ms/op
Iteration   1: 2.445 ±(99.9%) 0.004 ms/op
Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
Iteration   3: 2.447 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.449 ±(99.9%) 0.101 ms/op [Average]
  (min, avg, max) = (2.445, 2.449, 2.455), stdev = 0.006
  CI (99.9%): [2.348, 2.550] (assumes normal distribution)


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
# Warmup Iteration   1: 3.784 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.004 ms/op
Iteration   1: 2.451 ±(99.9%) 0.003 ms/op
Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
Iteration   3: 2.452 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.462 ±(99.9%) 0.337 ms/op [Average]
  (min, avg, max) = (2.451, 2.462, 2.483), stdev = 0.018
  CI (99.9%): [2.125, 2.799] (assumes normal distribution)


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
# Warmup Iteration   1: 4.634 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.005 ms/op
Iteration   1: 2.933 ±(99.9%) 0.005 ms/op
Iteration   2: 2.934 ±(99.9%) 0.005 ms/op
Iteration   3: 2.955 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.941 ±(99.9%) 0.220 ms/op [Average]
  (min, avg, max) = (2.933, 2.941, 2.955), stdev = 0.012
  CI (99.9%): [2.721, 3.161] (assumes normal distribution)


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.642 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.006 ms/op
Iteration   1: 2.476 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.588 ms/op
                 createUser·p0.999:  6.796 ms/op
                 createUser·p0.9999: 13.404 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.523 ms/op
                 createUser·p0.999:  7.841 ms/op
                 createUser·p0.9999: 12.145 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  9.126 ms/op
                 createUser·p0.9999: 13.042 ms/op
                 createUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384222
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 187571 
    [ 2.500,  3.750) = 192669 
    [ 3.750,  5.000) = 3075 
    [ 5.000,  6.250) = 417 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      9.106 ms/op
     p(99.9900) =     13.058 ms/op
     p(99.9990) =     13.972 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 3.755 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
Iteration   1: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.944 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.408 ms/op
                 existUser·p0.999:  6.251 ms/op
                 existUser·p0.9999: 13.566 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   2: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  5.368 ms/op
                 existUser·p0.9999: 12.829 ms/op
                 existUser·p1.00:   13.779 ms/op

Iteration   3: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.781 ms/op
                 existUser·p0.999:  6.808 ms/op
                 existUser·p0.9999: 11.731 ms/op
                 existUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395170
  mean =      2.427 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 197405 
    [ 2.500,  3.750) = 194621 
    [ 3.750,  5.000) = 2237 
    [ 5.000,  6.250) = 459 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 133 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      6.095 ms/op
     p(99.9900) =     12.911 ms/op
     p(99.9990) =     14.255 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 3.678 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.527 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.452 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   2.449 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.576 ms/op
                 getUser·p0.999:  6.200 ms/op
                 getUser·p0.9999: 13.353 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.021 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   4.129 ms/op
                 getUser·p0.999:  7.622 ms/op
                 getUser·p0.9999: 11.717 ms/op
                 getUser·p1.00:   12.321 ms/op

Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.633 ms/op
                 getUser·p0.999:  5.756 ms/op
                 getUser·p0.9999: 10.044 ms/op
                 getUser·p1.00:   10.355 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389612
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 197937 
    [ 2.500,  3.750) = 187489 
    [ 3.750,  5.000) = 3379 
    [ 5.000,  6.250) = 294 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 135 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      7.392 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     13.617 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.516 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.008 ms/op
Iteration   1: 2.963 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  8.702 ms/op
                 listUser·p0.9999: 9.847 ms/op
                 listUser·p1.00:   10.633 ms/op

Iteration   2: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  8.947 ms/op
                 listUser·p0.9999: 10.928 ms/op
                 listUser·p1.00:   11.534 ms/op

Iteration   3: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.933 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  9.263 ms/op
                 listUser·p0.9999: 11.836 ms/op
                 listUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322517
  mean =      2.974 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 100363 
    [ 2.500,  3.750) = 185084 
    [ 3.750,  5.000) = 30167 
    [ 5.000,  6.250) = 5481 
    [ 6.250,  7.500) = 625 
    [ 7.500,  8.750) = 307 
    [ 8.750, 10.000) = 245 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      8.978 ms/op
     p(99.9900) =     11.469 ms/op
     p(99.9990) =     12.211 ms/op
     p(99.9999) =     12.354 ms/op
    p(100.0000) =     12.354 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.582 ± 2.061  ops/ms
ClientPb.existUser                       thrpt       3  13.208 ± 2.437  ops/ms
ClientPb.getUser                         thrpt       3  13.033 ± 0.914  ops/ms
ClientPb.listUser                        thrpt       3  10.805 ± 0.878  ops/ms
ClientPb.createUser                       avgt       3   2.503 ± 0.106   ms/op
ClientPb.existUser                        avgt       3   2.449 ± 0.101   ms/op
ClientPb.getUser                          avgt       3   2.462 ± 0.337   ms/op
ClientPb.listUser                         avgt       3   2.941 ± 0.220   ms/op
ClientPb.createUser                     sample  384222   2.496 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.951           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.106           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.058           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.205           ms/op
ClientPb.existUser                      sample  395170   2.427 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.885           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.095           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.911           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.320           ms/op
ClientPb.getUser                        sample  389612   2.462 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.968           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.470           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.392           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.206           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.008           ms/op
ClientPb.listUser                       sample  322517   2.974 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.887           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.978           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.469           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.354           ms/op
