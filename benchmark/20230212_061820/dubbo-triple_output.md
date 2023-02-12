# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.690 ops/ms
# Warmup Iteration   2: 6.080 ops/ms
# Warmup Iteration   3: 9.036 ops/ms
Iteration   1: 9.644 ops/ms
Iteration   2: 9.752 ops/ms
Iteration   3: 9.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.713 ±(99.9%) 1.088 ops/ms [Average]
  (min, avg, max) = (9.644, 9.713, 9.752), stdev = 0.060
  CI (99.9%): [8.625, 10.801] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.736 ops/ms
# Warmup Iteration   2: 9.218 ops/ms
# Warmup Iteration   3: 9.824 ops/ms
Iteration   1: 10.683 ops/ms
Iteration   2: 10.582 ops/ms
Iteration   3: 10.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.429 ±(99.9%) 6.488 ops/ms [Average]
  (min, avg, max) = (10.023, 10.429, 10.683), stdev = 0.356
  CI (99.9%): [3.941, 16.917] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.602 ops/ms
# Warmup Iteration   2: 9.035 ops/ms
# Warmup Iteration   3: 9.144 ops/ms
Iteration   1: 9.818 ops/ms
Iteration   2: 10.407 ops/ms
Iteration   3: 10.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.161 ±(99.9%) 5.585 ops/ms [Average]
  (min, avg, max) = (9.818, 10.161, 10.407), stdev = 0.306
  CI (99.9%): [4.576, 15.746] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 3.652 ops/ms
# Warmup Iteration   2: 7.417 ops/ms
# Warmup Iteration   3: 8.340 ops/ms
Iteration   1: 8.691 ops/ms
Iteration   2: 8.666 ops/ms
Iteration   3: 8.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.602 ±(99.9%) 2.427 ops/ms [Average]
  (min, avg, max) = (8.449, 8.602, 8.691), stdev = 0.133
  CI (99.9%): [6.175, 11.029] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.347 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.416 ±(99.9%) 0.002 ms/op
Iteration   1: 3.327 ±(99.9%) 0.008 ms/op
Iteration   2: 3.172 ±(99.9%) 0.003 ms/op
Iteration   3: 3.447 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.316 ±(99.9%) 2.512 ms/op [Average]
  (min, avg, max) = (3.172, 3.316, 3.447), stdev = 0.138
  CI (99.9%): [0.803, 5.828] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 6.832 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.006 ms/op
Iteration   1: 3.050 ±(99.9%) 0.002 ms/op
Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
Iteration   3: 3.150 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.081 ±(99.9%) 1.102 ms/op [Average]
  (min, avg, max) = (3.042, 3.081, 3.150), stdev = 0.060
  CI (99.9%): [1.979, 4.183] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.630 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.600 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.005 ms/op
Iteration   1: 3.142 ±(99.9%) 0.004 ms/op
Iteration   2: 3.082 ±(99.9%) 0.003 ms/op
Iteration   3: 3.148 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.124 ±(99.9%) 0.663 ms/op [Average]
  (min, avg, max) = (3.082, 3.124, 3.148), stdev = 0.036
  CI (99.9%): [2.462, 3.787] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 9.084 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.741 ±(99.9%) 0.005 ms/op
Iteration   1: 3.729 ±(99.9%) 0.008 ms/op
Iteration   2: 3.766 ±(99.9%) 0.004 ms/op
Iteration   3: 3.690 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.728 ±(99.9%) 0.688 ms/op [Average]
  (min, avg, max) = (3.690, 3.728, 3.766), stdev = 0.038
  CI (99.9%): [3.040, 4.416] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.122 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.008 ms/op
Iteration   1: 3.235 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.194 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   6.218 ms/op
                 createUser·p0.999:  9.294 ms/op
                 createUser·p0.9999: 21.922 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 3.288 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  14.200 ms/op
                 createUser·p0.9999: 22.577 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   3: 3.189 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  15.909 ms/op
                 createUser·p0.9999: 25.493 ms/op
                 createUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296408
  mean =      3.237 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18342 
    [ 2.500,  5.000) = 271578 
    [ 5.000,  7.500) = 5566 
    [ 7.500, 10.000) = 564 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 154 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     24.084 ms/op
     p(99.9990) =     26.085 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.596 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.308 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.008 ms/op
Iteration   1: 3.271 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  11.523 ms/op
                 existUser·p0.9999: 20.321 ms/op
                 existUser·p1.00:   21.103 ms/op

Iteration   2: 3.070 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.346 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  16.146 ms/op
                 existUser·p0.9999: 23.449 ms/op
                 existUser·p1.00:   24.281 ms/op

Iteration   3: 3.170 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  13.844 ms/op
                 existUser·p0.9999: 22.801 ms/op
                 existUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302677
  mean =      3.168 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23604 
    [ 2.500,  5.000) = 271458 
    [ 5.000,  7.500) = 6743 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     22.863 ms/op
     p(99.9990) =     24.179 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 8.127 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.491 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.009 ms/op
Iteration   1: 3.192 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.616 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  15.085 ms/op
                 getUser·p0.9999: 20.183 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   2: 3.170 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   5.415 ms/op
                 getUser·p0.999:  10.586 ms/op
                 getUser·p0.9999: 24.868 ms/op
                 getUser·p1.00:   25.952 ms/op

Iteration   3: 3.203 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.333 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  17.243 ms/op
                 getUser·p0.9999: 24.969 ms/op
                 getUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300861
  mean =      3.188 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12772 
    [ 2.500,  5.000) = 282833 
    [ 5.000,  7.500) = 4414 
    [ 7.500, 10.000) = 361 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     16.157 ms/op
     p(99.9900) =     24.674 ms/op
     p(99.9990) =     25.428 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.667 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.875 ±(99.9%) 0.012 ms/op
Iteration   1: 3.774 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.446 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  18.842 ms/op
                 listUser·p0.9999: 26.970 ms/op
                 listUser·p1.00:   27.853 ms/op

Iteration   2: 3.724 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.894 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.149 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  12.552 ms/op
                 listUser·p0.9999: 16.810 ms/op
                 listUser·p1.00:   16.908 ms/op

Iteration   3: 3.659 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.017 ms/op
                 listUser·p0.50:   3.535 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.153 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  11.223 ms/op
                 listUser·p0.9999: 15.004 ms/op
                 listUser·p1.00:   15.319 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258049
  mean =      3.718 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 98 
    [ 2.500,  5.000) = 251050 
    [ 5.000,  7.500) = 5366 
    [ 7.500, 10.000) = 908 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     25.834 ms/op
     p(99.9990) =     27.487 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.713 ± 1.088  ops/ms
ClientPb.existUser                       thrpt       3  10.429 ± 6.488  ops/ms
ClientPb.getUser                         thrpt       3  10.161 ± 5.585  ops/ms
ClientPb.listUser                        thrpt       3   8.602 ± 2.427  ops/ms
ClientPb.createUser                       avgt       3   3.316 ± 2.512   ms/op
ClientPb.existUser                        avgt       3   3.081 ± 1.102   ms/op
ClientPb.getUser                          avgt       3   3.124 ± 0.663   ms/op
ClientPb.listUser                         avgt       3   3.728 ± 0.688   ms/op
ClientPb.createUser                     sample  296408   3.237 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.108           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.270           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.084           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.313           ms/op
ClientPb.existUser                      sample  302677   3.168 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.202           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.461           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.844           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.863           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.281           ms/op
ClientPb.getUser                        sample  300861   3.188 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.323           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.506           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.587           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.157           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.674           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.952           ms/op
ClientPb.listUser                       sample  258049   3.718 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.446           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.641           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.994           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.660           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.812           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.834           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.853           ms/op
