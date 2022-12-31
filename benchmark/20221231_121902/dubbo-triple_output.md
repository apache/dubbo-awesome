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
# Warmup Iteration   1: 2.538 ops/ms
# Warmup Iteration   2: 5.573 ops/ms
# Warmup Iteration   3: 9.121 ops/ms
Iteration   1: 9.597 ops/ms
Iteration   2: 9.770 ops/ms
Iteration   3: 9.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.786 ±(99.9%) 3.609 ops/ms [Average]
  (min, avg, max) = (9.597, 9.786, 9.992), stdev = 0.198
  CI (99.9%): [6.178, 13.395] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 3.635 ops/ms
# Warmup Iteration   2: 9.480 ops/ms
# Warmup Iteration   3: 9.871 ops/ms
Iteration   1: 10.688 ops/ms
Iteration   2: 10.616 ops/ms
Iteration   3: 10.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.512 ±(99.9%) 4.467 ops/ms [Average]
  (min, avg, max) = (10.233, 10.512, 10.688), stdev = 0.245
  CI (99.9%): [6.046, 14.979] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.538 ops/ms
# Warmup Iteration   2: 8.877 ops/ms
# Warmup Iteration   3: 9.867 ops/ms
Iteration   1: 9.779 ops/ms
Iteration   2: 10.223 ops/ms
Iteration   3: 9.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.888 ±(99.9%) 5.402 ops/ms [Average]
  (min, avg, max) = (9.661, 9.888, 10.223), stdev = 0.296
  CI (99.9%): [4.486, 15.290] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.330 ops/ms
# Warmup Iteration   2: 7.607 ops/ms
# Warmup Iteration   3: 8.327 ops/ms
Iteration   1: 8.537 ops/ms
Iteration   2: 8.555 ops/ms
Iteration   3: 8.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.580 ±(99.9%) 1.086 ops/ms [Average]
  (min, avg, max) = (8.537, 8.580, 8.648), stdev = 0.060
  CI (99.9%): [7.495, 9.666] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.163 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.004 ms/op
Iteration   1: 3.201 ±(99.9%) 0.008 ms/op
Iteration   2: 3.225 ±(99.9%) 0.004 ms/op
Iteration   3: 3.164 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.197 ±(99.9%) 0.561 ms/op [Average]
  (min, avg, max) = (3.164, 3.197, 3.225), stdev = 0.031
  CI (99.9%): [2.636, 3.758] (assumes normal distribution)


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
# Warmup Iteration   1: 6.932 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.005 ms/op
Iteration   1: 3.016 ±(99.9%) 0.005 ms/op
Iteration   2: 3.106 ±(99.9%) 0.008 ms/op
Iteration   3: 3.069 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.064 ±(99.9%) 0.826 ms/op [Average]
  (min, avg, max) = (3.016, 3.064, 3.106), stdev = 0.045
  CI (99.9%): [2.238, 3.890] (assumes normal distribution)


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
# Warmup Iteration   1: 7.455 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.307 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.003 ms/op
Iteration   1: 3.281 ±(99.9%) 0.004 ms/op
Iteration   2: 3.213 ±(99.9%) 0.005 ms/op
Iteration   3: 3.211 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.235 ±(99.9%) 0.735 ms/op [Average]
  (min, avg, max) = (3.211, 3.235, 3.281), stdev = 0.040
  CI (99.9%): [2.500, 3.970] (assumes normal distribution)


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
# Warmup Iteration   1: 8.682 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.275 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.684 ±(99.9%) 0.007 ms/op
Iteration   1: 3.644 ±(99.9%) 0.010 ms/op
Iteration   2: 3.720 ±(99.9%) 0.009 ms/op
Iteration   3: 3.670 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.678 ±(99.9%) 0.708 ms/op [Average]
  (min, avg, max) = (3.644, 3.678, 3.720), stdev = 0.039
  CI (99.9%): [2.970, 4.386] (assumes normal distribution)


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
# Warmup Iteration   1: 7.574 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.749 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.008 ms/op
Iteration   1: 3.200 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  8.736 ms/op
                 createUser·p0.9999: 22.905 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   2: 3.222 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.403 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.855 ms/op
                 createUser·p0.999:  17.026 ms/op
                 createUser·p0.9999: 22.088 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   3: 3.141 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.479 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  16.250 ms/op
                 createUser·p0.9999: 19.327 ms/op
                 createUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301020
  mean =      3.187 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15332 
    [ 2.500,  5.000) = 277985 
    [ 5.000,  7.500) = 6740 
    [ 7.500, 10.000) = 440 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 178 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     16.335 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 7.016 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.008 ms/op
Iteration   1: 3.054 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  15.957 ms/op
                 existUser·p0.9999: 19.562 ms/op
                 existUser·p1.00:   20.906 ms/op

Iteration   2: 3.130 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  12.712 ms/op
                 existUser·p0.9999: 31.097 ms/op
                 existUser·p1.00:   31.425 ms/op

Iteration   3: 3.023 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.157 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.387 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  16.253 ms/op
                 existUser·p0.9999: 22.192 ms/op
                 existUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312741
  mean =      3.068 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22160 
    [ 2.500,  5.000) = 284580 
    [ 5.000,  7.500) = 5035 
    [ 7.500, 10.000) = 407 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.277 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     15.733 ms/op
     p(99.9900) =     29.998 ms/op
     p(99.9990) =     31.248 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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
# Warmup Iteration   1: 8.060 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.319 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.009 ms/op
Iteration   1: 3.244 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.625 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  16.941 ms/op
                 getUser·p0.9999: 25.535 ms/op
                 getUser·p1.00:   26.149 ms/op

Iteration   2: 3.080 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.493 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.322 ms/op
                 getUser·p0.95:   3.494 ms/op
                 getUser·p0.99:   5.243 ms/op
                 getUser·p0.999:  8.703 ms/op
                 getUser·p0.9999: 23.097 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   3: 3.324 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.589 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  14.905 ms/op
                 getUser·p0.9999: 22.413 ms/op
                 getUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298597
  mean =      3.213 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15474 
    [ 2.500,  5.000) = 275244 
    [ 5.000,  7.500) = 7016 
    [ 7.500, 10.000) = 454 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     16.381 ms/op
     p(99.9900) =     23.630 ms/op
     p(99.9990) =     26.084 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 8.563 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.815 ±(99.9%) 0.011 ms/op
Iteration   1: 3.685 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   6.398 ms/op
                 listUser·p0.999:  14.729 ms/op
                 listUser·p0.9999: 28.289 ms/op
                 listUser·p1.00:   28.967 ms/op

Iteration   2: 3.683 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.194 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  13.500 ms/op
                 listUser·p0.9999: 14.991 ms/op
                 listUser·p1.00:   15.172 ms/op

Iteration   3: 3.697 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.883 ms/op
                 listUser·p0.999:  13.582 ms/op
                 listUser·p0.9999: 16.810 ms/op
                 listUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 260103
  mean =      3.689 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 254033 
    [ 5.000,  7.500) = 4348 
    [ 7.500, 10.000) = 1090 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 290 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      2.159 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     26.443 ms/op
     p(99.9990) =     28.750 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.786 ± 3.609  ops/ms
ClientPb.existUser                       thrpt       3  10.512 ± 4.467  ops/ms
ClientPb.getUser                         thrpt       3   9.888 ± 5.402  ops/ms
ClientPb.listUser                        thrpt       3   8.580 ± 1.086  ops/ms
ClientPb.createUser                       avgt       3   3.197 ± 0.561   ms/op
ClientPb.existUser                        avgt       3   3.064 ± 0.826   ms/op
ClientPb.getUser                          avgt       3   3.235 ± 0.735   ms/op
ClientPb.listUser                         avgt       3   3.678 ± 0.708   ms/op
ClientPb.createUser                     sample  301020   3.187 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.337           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.596           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.571           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.335           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.217           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.757           ms/op
ClientPb.existUser                      sample  312741   3.068 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.157           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.733           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.998           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.425           ms/op
ClientPb.getUser                        sample  298597   3.213 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.625           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.645           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.669           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.381           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.630           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.149           ms/op
ClientPb.listUser                       sample  260103   3.689 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.159           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.629           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.644           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.746           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.443           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.967           ms/op
