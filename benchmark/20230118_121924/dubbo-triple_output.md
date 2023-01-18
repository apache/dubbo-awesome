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
# Warmup Iteration   1: 2.575 ops/ms
# Warmup Iteration   2: 6.033 ops/ms
# Warmup Iteration   3: 9.016 ops/ms
Iteration   1: 9.921 ops/ms
Iteration   2: 9.918 ops/ms
Iteration   3: 10.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.952 ±(99.9%) 1.020 ops/ms [Average]
  (min, avg, max) = (9.918, 9.952, 10.016), stdev = 0.056
  CI (99.9%): [8.932, 10.971] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.579 ops/ms
# Warmup Iteration   2: 9.364 ops/ms
# Warmup Iteration   3: 10.096 ops/ms
Iteration   1: 9.902 ops/ms
Iteration   2: 10.206 ops/ms
Iteration   3: 10.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.115 ±(99.9%) 3.381 ops/ms [Average]
  (min, avg, max) = (9.902, 10.115, 10.237), stdev = 0.185
  CI (99.9%): [6.734, 13.496] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.409 ops/ms
# Warmup Iteration   2: 8.996 ops/ms
# Warmup Iteration   3: 9.723 ops/ms
Iteration   1: 10.053 ops/ms
Iteration   2: 10.177 ops/ms
Iteration   3: 10.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.111 ±(99.9%) 1.138 ops/ms [Average]
  (min, avg, max) = (10.053, 10.111, 10.177), stdev = 0.062
  CI (99.9%): [8.974, 11.249] (assumes normal distribution)


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
# Warmup Iteration   1: 3.621 ops/ms
# Warmup Iteration   2: 7.814 ops/ms
# Warmup Iteration   3: 8.321 ops/ms
Iteration   1: 8.423 ops/ms
Iteration   2: 8.477 ops/ms
Iteration   3: 8.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.522 ±(99.9%) 2.320 ops/ms [Average]
  (min, avg, max) = (8.423, 8.522, 8.665), stdev = 0.127
  CI (99.9%): [6.202, 10.842] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.856 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.004 ms/op
Iteration   1: 3.379 ±(99.9%) 0.006 ms/op
Iteration   2: 3.224 ±(99.9%) 0.004 ms/op
Iteration   3: 3.105 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.236 ±(99.9%) 2.516 ms/op [Average]
  (min, avg, max) = (3.105, 3.236, 3.379), stdev = 0.138
  CI (99.9%): [0.720, 5.752] (assumes normal distribution)


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
# Warmup Iteration   1: 8.640 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.425 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.006 ms/op
Iteration   1: 3.109 ±(99.9%) 0.006 ms/op
Iteration   2: 3.099 ±(99.9%) 0.005 ms/op
Iteration   3: 3.083 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.097 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (3.083, 3.097, 3.109), stdev = 0.013
  CI (99.9%): [2.853, 3.341] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.434 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.409 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.005 ms/op
Iteration   1: 3.262 ±(99.9%) 0.006 ms/op
Iteration   2: 3.292 ±(99.9%) 0.006 ms/op
Iteration   3: 3.261 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.272 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (3.261, 3.272, 3.292), stdev = 0.017
  CI (99.9%): [2.956, 3.587] (assumes normal distribution)


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
# Warmup Iteration   1: 8.885 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.816 ±(99.9%) 0.011 ms/op
Iteration   1: 3.850 ±(99.9%) 0.006 ms/op
Iteration   2: 3.662 ±(99.9%) 0.011 ms/op
Iteration   3: 3.702 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.738 ±(99.9%) 1.802 ms/op [Average]
  (min, avg, max) = (3.662, 3.738, 3.850), stdev = 0.099
  CI (99.9%): [1.936, 5.540] (assumes normal distribution)


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
# Warmup Iteration   1: 8.306 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.718 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.010 ms/op
Iteration   1: 3.207 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.403 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  12.325 ms/op
                 createUser·p0.9999: 18.776 ms/op
                 createUser·p1.00:   19.431 ms/op

Iteration   2: 3.233 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.548 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  10.176 ms/op
                 createUser·p0.9999: 27.565 ms/op
                 createUser·p1.00:   28.213 ms/op

Iteration   3: 3.227 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  18.379 ms/op
                 createUser·p0.9999: 30.147 ms/op
                 createUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297852
  mean =      3.222 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24118 
    [ 2.500,  5.000) = 268537 
    [ 5.000,  7.500) = 4277 
    [ 7.500, 10.000) = 447 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 162 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     16.951 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     30.936 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.042 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.403 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.007 ms/op
Iteration   1: 3.136 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  8.520 ms/op
                 existUser·p0.9999: 18.612 ms/op
                 existUser·p1.00:   19.399 ms/op

Iteration   2: 3.116 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  8.447 ms/op
                 existUser·p0.9999: 19.301 ms/op
                 existUser·p1.00:   23.495 ms/op

Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.161 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.293 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  11.895 ms/op
                 existUser·p0.9999: 20.251 ms/op
                 existUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308185
  mean =      3.111 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30249 
    [ 2.500,  5.000) = 271542 
    [ 5.000,  7.500) = 5686 
    [ 7.500, 10.000) = 347 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.273 ms/op
     p(95.0000) =      3.547 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     11.424 ms/op
     p(99.9900) =     19.831 ms/op
     p(99.9990) =     21.163 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 7.655 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.515 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.010 ms/op
Iteration   1: 3.223 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  14.307 ms/op
                 getUser·p0.9999: 24.642 ms/op
                 getUser·p1.00:   25.133 ms/op

Iteration   2: 3.178 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.489 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  19.801 ms/op
                 getUser·p0.9999: 22.247 ms/op
                 getUser·p1.00:   22.938 ms/op

Iteration   3: 3.144 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.588 ms/op
                 getUser·p0.99:   5.766 ms/op
                 getUser·p0.999:  12.960 ms/op
                 getUser·p0.9999: 18.658 ms/op
                 getUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301705
  mean =      3.181 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9412 
    [ 2.500,  5.000) = 285577 
    [ 5.000,  7.500) = 5812 
    [ 7.500, 10.000) = 488 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     23.964 ms/op
     p(99.9990) =     25.033 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


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
# Warmup Iteration   1: 9.421 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.812 ±(99.9%) 0.011 ms/op
Iteration   1: 3.721 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.923 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  14.255 ms/op
                 listUser·p0.9999: 23.691 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   2: 3.734 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.075 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  15.483 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   3: 3.755 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.974 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   7.082 ms/op
                 listUser·p0.999:  13.976 ms/op
                 listUser·p0.9999: 16.687 ms/op
                 listUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256689
  mean =      3.737 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 248543 
    [ 5.000,  7.500) = 6081 
    [ 7.500, 10.000) = 1351 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.923 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      7.013 ms/op
     p(99.9000) =     14.292 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     24.241 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.952 ± 1.020  ops/ms
ClientPb.existUser                       thrpt       3  10.115 ± 3.381  ops/ms
ClientPb.getUser                         thrpt       3  10.111 ± 1.138  ops/ms
ClientPb.listUser                        thrpt       3   8.522 ± 2.320  ops/ms
ClientPb.createUser                       avgt       3   3.236 ± 2.516   ms/op
ClientPb.existUser                        avgt       3   3.097 ± 0.244   ms/op
ClientPb.getUser                          avgt       3   3.272 ± 0.316   ms/op
ClientPb.listUser                         avgt       3   3.738 ± 1.802   ms/op
ClientPb.createUser                     sample  297852   3.222 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.854           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.461           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.562           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.951           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.313           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.130           ms/op
ClientPb.existUser                      sample  308185   3.111 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.771           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.464           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.424           ms/op
ClientPb.existUser:existUser·p0.9999    sample          19.831           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.495           ms/op
ClientPb.getUser                        sample  301705   3.181 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.808           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.490           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.748           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.710           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.204           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.964           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.133           ms/op
ClientPb.listUser                       sample  256689   3.737 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.923           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.026           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.013           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.292           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.315           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.068           ms/op
