# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.668 ops/ms
# Warmup Iteration   2: 6.387 ops/ms
# Warmup Iteration   3: 9.285 ops/ms
Iteration   1: 10.045 ops/ms
Iteration   2: 9.957 ops/ms
Iteration   3: 9.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.950 ±(99.9%) 1.805 ops/ms [Average]
  (min, avg, max) = (9.848, 9.950, 10.045), stdev = 0.099
  CI (99.9%): [8.146, 11.755] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.409 ops/ms
# Warmup Iteration   2: 9.164 ops/ms
# Warmup Iteration   3: 9.971 ops/ms
Iteration   1: 9.805 ops/ms
Iteration   2: 9.837 ops/ms
Iteration   3: 10.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.002 ±(99.9%) 5.715 ops/ms [Average]
  (min, avg, max) = (9.805, 10.002, 10.363), stdev = 0.313
  CI (99.9%): [4.287, 15.717] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.501 ops/ms
# Warmup Iteration   2: 8.532 ops/ms
# Warmup Iteration   3: 9.304 ops/ms
Iteration   1: 10.092 ops/ms
Iteration   2: 9.949 ops/ms
Iteration   3: 9.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.874 ±(99.9%) 4.826 ops/ms [Average]
  (min, avg, max) = (9.580, 9.874, 10.092), stdev = 0.265
  CI (99.9%): [5.048, 14.700] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.375 ops/ms
# Warmup Iteration   2: 7.593 ops/ms
# Warmup Iteration   3: 8.161 ops/ms
Iteration   1: 8.539 ops/ms
Iteration   2: 8.393 ops/ms
Iteration   3: 8.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.487 ±(99.9%) 1.489 ops/ms [Average]
  (min, avg, max) = (8.393, 8.487, 8.539), stdev = 0.082
  CI (99.9%): [6.998, 9.976] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.150 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.700 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.004 ms/op
Iteration   1: 3.378 ±(99.9%) 0.007 ms/op
Iteration   2: 3.290 ±(99.9%) 0.006 ms/op
Iteration   3: 3.244 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.304 ±(99.9%) 1.247 ms/op [Average]
  (min, avg, max) = (3.244, 3.304, 3.378), stdev = 0.068
  CI (99.9%): [2.058, 4.551] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.257 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.465 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.005 ms/op
Iteration   1: 3.053 ±(99.9%) 0.006 ms/op
Iteration   2: 3.210 ±(99.9%) 0.004 ms/op
Iteration   3: 3.102 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.122 ±(99.9%) 1.467 ms/op [Average]
  (min, avg, max) = (3.053, 3.122, 3.210), stdev = 0.080
  CI (99.9%): [1.655, 4.589] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.163 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.570 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.003 ms/op
Iteration   1: 3.172 ±(99.9%) 0.005 ms/op
Iteration   2: 3.279 ±(99.9%) 0.005 ms/op
Iteration   3: 3.248 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.233 ±(99.9%) 1.008 ms/op [Average]
  (min, avg, max) = (3.172, 3.233, 3.279), stdev = 0.055
  CI (99.9%): [2.225, 4.241] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.977 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.126 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.005 ms/op
Iteration   1: 3.794 ±(99.9%) 0.007 ms/op
Iteration   2: 3.786 ±(99.9%) 0.005 ms/op
Iteration   3: 3.692 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.757 ±(99.9%) 1.034 ms/op [Average]
  (min, avg, max) = (3.692, 3.757, 3.794), stdev = 0.057
  CI (99.9%): [2.724, 4.791] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.305 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.914 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.467 ±(99.9%) 0.010 ms/op
Iteration   1: 3.242 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  18.332 ms/op
                 createUser·p0.9999: 23.733 ms/op
                 createUser·p1.00:   25.166 ms/op

Iteration   2: 3.417 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.448 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  19.347 ms/op
                 createUser·p0.9999: 31.630 ms/op
                 createUser·p1.00:   32.506 ms/op

Iteration   3: 3.207 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.122 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  18.861 ms/op
                 createUser·p0.9999: 33.557 ms/op
                 createUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291815
  mean =      3.286 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19589 
    [ 2.500,  5.000) = 267804 
    [ 5.000,  7.500) = 3429 
    [ 7.500, 10.000) = 416 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     18.815 ms/op
     p(99.9900) =     32.571 ms/op
     p(99.9990) =     36.181 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.720 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.400 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.008 ms/op
Iteration   1: 3.141 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.184 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  10.220 ms/op
                 existUser·p0.9999: 21.266 ms/op
                 existUser·p1.00:   22.151 ms/op

Iteration   2: 3.041 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.087 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  9.762 ms/op
                 existUser·p0.9999: 21.856 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   3: 3.122 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.329 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   5.857 ms/op
                 existUser·p0.999:  14.318 ms/op
                 existUser·p0.9999: 19.686 ms/op
                 existUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309398
  mean =      3.101 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18156 
    [ 2.500,  5.000) = 287133 
    [ 5.000,  7.500) = 3186 
    [ 7.500, 10.000) = 351 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     21.629 ms/op
     p(99.9990) =     22.389 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.799 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.010 ms/op
Iteration   1: 3.366 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  19.590 ms/op
                 getUser·p0.9999: 24.265 ms/op
                 getUser·p1.00:   25.723 ms/op

Iteration   2: 3.232 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.477 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   5.399 ms/op
                 getUser·p0.999:  16.276 ms/op
                 getUser·p0.9999: 23.400 ms/op
                 getUser·p1.00:   24.642 ms/op

Iteration   3: 3.330 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.563 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  17.371 ms/op
                 getUser·p0.9999: 25.461 ms/op
                 getUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290108
  mean =      3.308 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17779 
    [ 2.500,  5.000) = 266211 
    [ 5.000,  7.500) = 5150 
    [ 7.500, 10.000) = 524 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 143 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     18.740 ms/op
     p(99.9900) =     24.608 ms/op
     p(99.9990) =     25.723 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.638 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.140 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.955 ±(99.9%) 0.013 ms/op
Iteration   1: 3.917 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.987 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.815 ms/op
                 listUser·p0.999:  18.687 ms/op
                 listUser·p0.9999: 22.680 ms/op
                 listUser·p1.00:   23.855 ms/op

Iteration   2: 3.908 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  14.041 ms/op
                 listUser·p0.9999: 16.965 ms/op
                 listUser·p1.00:   17.367 ms/op

Iteration   3: 3.875 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  12.917 ms/op
                 listUser·p0.9999: 14.287 ms/op
                 listUser·p1.00:   15.614 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246086
  mean =      3.900 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 235919 
    [ 5.000,  7.500) = 7775 
    [ 7.500, 10.000) = 1600 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 296 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.987 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     14.287 ms/op
     p(99.9900) =     21.593 ms/op
     p(99.9990) =     23.248 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.950 ± 1.805  ops/ms
ClientPb.existUser                       thrpt       3  10.002 ± 5.715  ops/ms
ClientPb.getUser                         thrpt       3   9.874 ± 4.826  ops/ms
ClientPb.listUser                        thrpt       3   8.487 ± 1.489  ops/ms
ClientPb.createUser                       avgt       3   3.304 ± 1.247   ms/op
ClientPb.existUser                        avgt       3   3.122 ± 1.467   ms/op
ClientPb.getUser                          avgt       3   3.233 ± 1.008   ms/op
ClientPb.listUser                         avgt       3   3.757 ± 1.034   ms/op
ClientPb.createUser                     sample  291815   3.286 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.010           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.141           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.538           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.815           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.571           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.241           ms/op
ClientPb.existUser                      sample  309398   3.101 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.087           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.391           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.399           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.139           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.629           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.675           ms/op
ClientPb.getUser                        sample  290108   3.308 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.014           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.734           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.740           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.608           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.116           ms/op
ClientPb.listUser                       sample  246086   3.900 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.987           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.768           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.430           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.287           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.593           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.855           ms/op
