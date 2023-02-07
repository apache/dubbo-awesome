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
# Warmup Iteration   1: 2.647 ops/ms
# Warmup Iteration   2: 7.002 ops/ms
# Warmup Iteration   3: 9.378 ops/ms
Iteration   1: 9.341 ops/ms
Iteration   2: 9.938 ops/ms
Iteration   3: 9.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.721 ±(99.9%) 6.031 ops/ms [Average]
  (min, avg, max) = (9.341, 9.721, 9.938), stdev = 0.331
  CI (99.9%): [3.691, 15.752] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.608 ops/ms
# Warmup Iteration   2: 9.460 ops/ms
# Warmup Iteration   3: 10.610 ops/ms
Iteration   1: 10.313 ops/ms
Iteration   2: 10.601 ops/ms
Iteration   3: 10.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.484 ±(99.9%) 2.764 ops/ms [Average]
  (min, avg, max) = (10.313, 10.484, 10.601), stdev = 0.151
  CI (99.9%): [7.720, 13.247] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.143 ops/ms
# Warmup Iteration   2: 9.157 ops/ms
# Warmup Iteration   3: 9.935 ops/ms
Iteration   1: 10.120 ops/ms
Iteration   2: 10.446 ops/ms
Iteration   3: 9.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.097 ±(99.9%) 6.598 ops/ms [Average]
  (min, avg, max) = (9.724, 10.097, 10.446), stdev = 0.362
  CI (99.9%): [3.499, 16.694] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.457 ops/ms
# Warmup Iteration   2: 7.792 ops/ms
# Warmup Iteration   3: 8.375 ops/ms
Iteration   1: 8.666 ops/ms
Iteration   2: 8.671 ops/ms
Iteration   3: 8.638 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.658 ±(99.9%) 0.319 ops/ms [Average]
  (min, avg, max) = (8.638, 8.658, 8.671), stdev = 0.018
  CI (99.9%): [8.339, 8.978] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.291 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.557 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.005 ms/op
Iteration   1: 3.137 ±(99.9%) 0.010 ms/op
Iteration   2: 3.251 ±(99.9%) 0.009 ms/op
Iteration   3: 3.185 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.191 ±(99.9%) 1.045 ms/op [Average]
  (min, avg, max) = (3.137, 3.191, 3.251), stdev = 0.057
  CI (99.9%): [2.146, 4.236] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.775 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.007 ms/op
Iteration   1: 2.999 ±(99.9%) 0.001 ms/op
Iteration   2: 2.979 ±(99.9%) 0.002 ms/op
Iteration   3: 3.034 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.004 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (2.979, 3.004, 3.034), stdev = 0.028
  CI (99.9%): [2.500, 3.509] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.530 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.377 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.004 ms/op
Iteration   1: 3.122 ±(99.9%) 0.005 ms/op
Iteration   2: 3.113 ±(99.9%) 0.005 ms/op
Iteration   3: 3.182 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.139 ±(99.9%) 0.682 ms/op [Average]
  (min, avg, max) = (3.113, 3.139, 3.182), stdev = 0.037
  CI (99.9%): [2.457, 3.822] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.569 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.088 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.007 ms/op
Iteration   1: 3.633 ±(99.9%) 0.006 ms/op
Iteration   2: 3.689 ±(99.9%) 0.008 ms/op
Iteration   3: 3.724 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.682 ±(99.9%) 0.831 ms/op [Average]
  (min, avg, max) = (3.633, 3.682, 3.724), stdev = 0.046
  CI (99.9%): [2.851, 4.513] (assumes normal distribution)


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
# Warmup Iteration   1: 6.747 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.607 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.008 ms/op
Iteration   1: 3.101 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.310 ms/op
                 createUser·p0.95:   3.518 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  8.117 ms/op
                 createUser·p0.9999: 21.235 ms/op
                 createUser·p1.00:   22.184 ms/op

Iteration   2: 3.177 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.014 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  9.077 ms/op
                 createUser·p0.9999: 21.686 ms/op
                 createUser·p1.00:   22.381 ms/op

Iteration   3: 3.095 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.285 ms/op
                 createUser·p0.95:   3.469 ms/op
                 createUser·p0.99:   4.825 ms/op
                 createUser·p0.999:  9.055 ms/op
                 createUser·p0.9999: 15.903 ms/op
                 createUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 307128
  mean =      3.124 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25137 
    [ 2.500,  5.000) = 278340 
    [ 5.000,  7.500) = 3191 
    [ 7.500, 10.000) = 171 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      5.194 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     22.245 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 6.547 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.348 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.009 ms/op
Iteration   1: 3.003 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.206 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.154 ms/op
                 existUser·p0.95:   3.224 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  10.405 ms/op
                 existUser·p0.9999: 19.431 ms/op
                 existUser·p1.00:   20.054 ms/op

Iteration   2: 3.021 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.118 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.162 ms/op
                 existUser·p0.95:   3.351 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  12.517 ms/op
                 existUser·p0.9999: 22.631 ms/op
                 existUser·p1.00:   23.790 ms/op

Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  13.077 ms/op
                 existUser·p0.9999: 22.332 ms/op
                 existUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314860
  mean =      3.047 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23278 
    [ 2.500,  5.000) = 286695 
    [ 5.000,  7.500) = 4120 
    [ 7.500, 10.000) = 337 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.240 ms/op
     p(95.0000) =      3.445 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     12.275 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     23.850 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.882 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.476 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.010 ms/op
Iteration   1: 3.220 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  12.939 ms/op
                 getUser·p0.9999: 29.756 ms/op
                 getUser·p1.00:   30.474 ms/op

Iteration   2: 3.196 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.303 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  9.484 ms/op
                 getUser·p0.9999: 30.703 ms/op
                 getUser·p1.00:   32.801 ms/op

Iteration   3: 3.178 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.192 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  13.651 ms/op
                 getUser·p0.9999: 27.421 ms/op
                 getUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299938
  mean =      3.198 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12958 
    [ 2.500,  5.000) = 280895 
    [ 5.000,  7.500) = 5386 
    [ 7.500, 10.000) = 349 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     12.927 ms/op
     p(99.9900) =     29.688 ms/op
     p(99.9990) =     31.589 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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
# Warmup Iteration   1: 8.637 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.753 ±(99.9%) 0.011 ms/op
Iteration   1: 3.596 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.882 ms/op
                 listUser·p0.50:   3.490 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.080 ms/op
                 listUser·p0.99:   6.398 ms/op
                 listUser·p0.999:  15.690 ms/op
                 listUser·p0.9999: 19.701 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   2: 3.724 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  13.337 ms/op
                 listUser·p0.9999: 15.188 ms/op
                 listUser·p1.00:   15.237 ms/op

Iteration   3: 3.667 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  13.661 ms/op
                 listUser·p0.9999: 17.891 ms/op
                 listUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 261991
  mean =      3.661 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 255624 
    [ 5.000,  7.500) = 4581 
    [ 7.500, 10.000) = 1101 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.882 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     19.169 ms/op
     p(99.9990) =     20.427 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.721 ± 6.031  ops/ms
ClientPb.existUser                       thrpt       3  10.484 ± 2.764  ops/ms
ClientPb.getUser                         thrpt       3  10.097 ± 6.598  ops/ms
ClientPb.listUser                        thrpt       3   8.658 ± 0.319  ops/ms
ClientPb.createUser                       avgt       3   3.191 ± 1.045   ms/op
ClientPb.existUser                        avgt       3   3.004 ± 0.504   ms/op
ClientPb.getUser                          avgt       3   3.139 ± 0.682   ms/op
ClientPb.listUser                         avgt       3   3.682 ± 0.831   ms/op
ClientPb.createUser                     sample  307128   3.124 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.014           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.568           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.194           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.028           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.939           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.381           ms/op
ClientPb.existUser                      sample  314860   3.047 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.118           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.445           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.341           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.275           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.348           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.052           ms/op
ClientPb.getUser                        sample  299938   3.198 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.192           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.546           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.927           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.688           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.801           ms/op
ClientPb.listUser                       sample  261991   3.661 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.882           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.600           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.726           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.107           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.169           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.709           ms/op
