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
# Warmup Iteration   1: 4.863 ops/ms
# Warmup Iteration   2: 11.952 ops/ms
# Warmup Iteration   3: 12.308 ops/ms
Iteration   1: 12.494 ops/ms
Iteration   2: 12.542 ops/ms
Iteration   3: 12.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.523 ±(99.9%) 0.466 ops/ms [Average]
  (min, avg, max) = (12.494, 12.523, 12.542), stdev = 0.026
  CI (99.9%): [12.058, 12.989] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.057 ops/ms
# Warmup Iteration   2: 12.725 ops/ms
# Warmup Iteration   3: 12.932 ops/ms
Iteration   1: 12.901 ops/ms
Iteration   2: 12.854 ops/ms
Iteration   3: 12.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.874 ±(99.9%) 0.438 ops/ms [Average]
  (min, avg, max) = (12.854, 12.874, 12.901), stdev = 0.024
  CI (99.9%): [12.436, 13.312] (assumes normal distribution)


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
# Warmup Iteration   1: 7.803 ops/ms
# Warmup Iteration   2: 12.229 ops/ms
# Warmup Iteration   3: 12.648 ops/ms
Iteration   1: 12.512 ops/ms
Iteration   2: 12.650 ops/ms
Iteration   3: 12.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.579 ±(99.9%) 1.262 ops/ms [Average]
  (min, avg, max) = (12.512, 12.579, 12.650), stdev = 0.069
  CI (99.9%): [11.316, 13.841] (assumes normal distribution)


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
# Warmup Iteration   1: 6.841 ops/ms
# Warmup Iteration   2: 10.199 ops/ms
# Warmup Iteration   3: 10.474 ops/ms
Iteration   1: 10.493 ops/ms
Iteration   2: 10.607 ops/ms
Iteration   3: 10.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.507 ±(99.9%) 1.704 ops/ms [Average]
  (min, avg, max) = (10.421, 10.507, 10.607), stdev = 0.093
  CI (99.9%): [8.803, 12.211] (assumes normal distribution)


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
# Warmup Iteration   1: 4.103 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.004 ms/op
Iteration   1: 2.549 ±(99.9%) 0.005 ms/op
Iteration   2: 2.569 ±(99.9%) 0.004 ms/op
Iteration   3: 2.538 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.552 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (2.538, 2.552, 2.569), stdev = 0.015
  CI (99.9%): [2.271, 2.833] (assumes normal distribution)


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
# Warmup Iteration   1: 3.610 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.004 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
Iteration   2: 2.466 ±(99.9%) 0.004 ms/op
Iteration   3: 2.476 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.471 ±(99.9%) 0.090 ms/op [Average]
  (min, avg, max) = (2.466, 2.471, 2.476), stdev = 0.005
  CI (99.9%): [2.381, 2.561] (assumes normal distribution)


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.003 ms/op
Iteration   1: 2.530 ±(99.9%) 0.004 ms/op
Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
Iteration   3: 2.549 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.535 ±(99.9%) 0.218 ms/op [Average]
  (min, avg, max) = (2.527, 2.535, 2.549), stdev = 0.012
  CI (99.9%): [2.317, 2.753] (assumes normal distribution)


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
# Warmup Iteration   1: 4.529 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.005 ms/op
Iteration   2: 3.053 ±(99.9%) 0.006 ms/op
Iteration   3: 3.032 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.036 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (3.023, 3.036, 3.053), stdev = 0.015
  CI (99.9%): [2.755, 3.317] (assumes normal distribution)


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.719 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.006 ms/op
Iteration   1: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  11.173 ms/op
                 createUser·p0.9999: 13.752 ms/op
                 createUser·p1.00:   14.729 ms/op

Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.014 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   4.030 ms/op
                 createUser·p0.999:  9.552 ms/op
                 createUser·p0.9999: 13.184 ms/op
                 createUser·p1.00:   14.434 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.186 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  8.913 ms/op
                 createUser·p0.9999: 13.189 ms/op
                 createUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378529
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 180669 
    [ 2.500,  3.750) = 193092 
    [ 3.750,  5.000) = 3924 
    [ 5.000,  6.250) = 387 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =      8.953 ms/op
     p(99.9900) =     13.522 ms/op
     p(99.9990) =     14.370 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 3.648 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  6.353 ms/op
                 existUser·p0.9999: 14.771 ms/op
                 existUser·p1.00:   15.532 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  7.809 ms/op
                 existUser·p0.9999: 15.565 ms/op
                 existUser·p1.00:   17.629 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.844 ms/op
                 existUser·p0.999:  7.135 ms/op
                 existUser·p0.9999: 11.971 ms/op
                 existUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387138
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 191210 
    [ 2.500,  3.750) = 192283 
    [ 3.750,  5.000) = 2709 
    [ 5.000,  6.250) = 433 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      7.150 ms/op
     p(99.9900) =     14.540 ms/op
     p(99.9990) =     17.408 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 4.073 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.006 ms/op
Iteration   1: 2.525 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  6.027 ms/op
                 getUser·p0.9999: 13.435 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.494 ms/op
                 getUser·p0.999:  8.863 ms/op
                 getUser·p0.9999: 15.095 ms/op
                 getUser·p1.00:   15.974 ms/op

Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  8.520 ms/op
                 getUser·p0.9999: 11.089 ms/op
                 getUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379667
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 187229 
    [ 2.500,  3.750) = 188163 
    [ 3.750,  5.000) = 3310 
    [ 5.000,  6.250) = 542 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      6.182 ms/op
     p(99.9900) =     13.648 ms/op
     p(99.9990) =     15.843 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


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
# Warmup Iteration   1: 4.538 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.008 ms/op
Iteration   1: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.812 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 12.386 ms/op
                 listUser·p1.00:   12.534 ms/op

Iteration   2: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.784 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 10.967 ms/op
                 listUser·p1.00:   13.468 ms/op

Iteration   3: 3.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.504 ms/op
                 listUser·p0.9999: 11.747 ms/op
                 listUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316780
  mean =      3.028 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 154 
    [ 1.250,  2.500) = 89787 
    [ 2.500,  3.750) = 186197 
    [ 3.750,  5.000) = 32705 
    [ 5.000,  6.250) = 6565 
    [ 6.250,  7.500) = 703 
    [ 7.500,  8.750) = 190 
    [ 8.750, 10.000) = 262 
    [10.000, 11.250) = 181 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     11.387 ms/op
     p(99.9990) =     12.465 ms/op
     p(99.9999) =     13.468 ms/op
    p(100.0000) =     13.468 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.523 ± 0.466  ops/ms
ClientPb.existUser                       thrpt       3  12.874 ± 0.438  ops/ms
ClientPb.getUser                         thrpt       3  12.579 ± 1.262  ops/ms
ClientPb.listUser                        thrpt       3  10.507 ± 1.704  ops/ms
ClientPb.createUser                       avgt       3   2.552 ± 0.281   ms/op
ClientPb.existUser                        avgt       3   2.471 ± 0.090   ms/op
ClientPb.getUser                          avgt       3   2.535 ± 0.218   ms/op
ClientPb.listUser                         avgt       3   3.036 ± 0.281   ms/op
ClientPb.createUser                     sample  378529   2.533 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.879           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.953           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.522           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.729           ms/op
ClientPb.existUser                      sample  387138   2.477 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.743           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.150           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.540           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.629           ms/op
ClientPb.getUser                        sample  379667   2.526 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.968           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.182           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.648           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.974           ms/op
ClientPb.listUser                       sample  316780   3.028 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.784           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.470           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.387           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.468           ms/op
