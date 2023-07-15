# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.269 ops/ms
# Warmup Iteration   2: 5.834 ops/ms
# Warmup Iteration   3: 9.149 ops/ms
Iteration   1: 9.809 ops/ms
Iteration   2: 9.872 ops/ms
Iteration   3: 9.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.823 ±(99.9%) 0.785 ops/ms [Average]
  (min, avg, max) = (9.789, 9.823, 9.872), stdev = 0.043
  CI (99.9%): [9.038, 10.609] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.323 ops/ms
# Warmup Iteration   2: 9.200 ops/ms
# Warmup Iteration   3: 9.875 ops/ms
Iteration   1: 10.183 ops/ms
Iteration   2: 10.391 ops/ms
Iteration   3: 9.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.183 ±(99.9%) 3.784 ops/ms [Average]
  (min, avg, max) = (9.976, 10.183, 10.391), stdev = 0.207
  CI (99.9%): [6.399, 13.967] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.710 ops/ms
# Warmup Iteration   2: 9.182 ops/ms
# Warmup Iteration   3: 9.889 ops/ms
Iteration   1: 9.688 ops/ms
Iteration   2: 10.308 ops/ms
Iteration   3: 9.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.997 ±(99.9%) 5.656 ops/ms [Average]
  (min, avg, max) = (9.688, 9.997, 10.308), stdev = 0.310
  CI (99.9%): [4.341, 15.652] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.175 ops/ms
# Warmup Iteration   2: 7.411 ops/ms
# Warmup Iteration   3: 8.348 ops/ms
Iteration   1: 8.472 ops/ms
Iteration   2: 8.457 ops/ms
Iteration   3: 8.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.473 ±(99.9%) 0.299 ops/ms [Average]
  (min, avg, max) = (8.457, 8.473, 8.490), stdev = 0.016
  CI (99.9%): [8.174, 8.773] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.857 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.531 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.338 ±(99.9%) 0.003 ms/op
Iteration   1: 3.281 ±(99.9%) 0.006 ms/op
Iteration   2: 3.272 ±(99.9%) 0.005 ms/op
Iteration   3: 3.188 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.247 ±(99.9%) 0.936 ms/op [Average]
  (min, avg, max) = (3.188, 3.247, 3.281), stdev = 0.051
  CI (99.9%): [2.311, 4.183] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 6.934 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.321 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.003 ms/op
Iteration   1: 3.127 ±(99.9%) 0.007 ms/op
Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
Iteration   3: 3.048 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.082 ±(99.9%) 0.744 ms/op [Average]
  (min, avg, max) = (3.048, 3.082, 3.127), stdev = 0.041
  CI (99.9%): [2.338, 3.826] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.280 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.008 ms/op
Iteration   1: 3.257 ±(99.9%) 0.005 ms/op
Iteration   2: 3.229 ±(99.9%) 0.009 ms/op
Iteration   3: 3.212 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.233 ±(99.9%) 0.415 ms/op [Average]
  (min, avg, max) = (3.212, 3.233, 3.257), stdev = 0.023
  CI (99.9%): [2.818, 3.647] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.213 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.005 ms/op
Iteration   1: 3.700 ±(99.9%) 0.011 ms/op
Iteration   2: 3.713 ±(99.9%) 0.009 ms/op
Iteration   3: 3.797 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.737 ±(99.9%) 0.956 ms/op [Average]
  (min, avg, max) = (3.700, 3.737, 3.797), stdev = 0.052
  CI (99.9%): [2.781, 4.692] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.847 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.010 ms/op
Iteration   1: 3.329 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  17.983 ms/op
                 createUser·p0.9999: 22.544 ms/op
                 createUser·p1.00:   23.462 ms/op

Iteration   2: 3.199 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  14.042 ms/op
                 createUser·p0.9999: 23.790 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   3: 3.215 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   5.308 ms/op
                 createUser·p0.999:  16.441 ms/op
                 createUser·p0.9999: 23.462 ms/op
                 createUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295483
  mean =      3.247 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21237 
    [ 2.500,  5.000) = 267357 
    [ 5.000,  7.500) = 5992 
    [ 7.500, 10.000) = 343 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     16.344 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     26.707 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.074 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.394 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
Iteration   1: 3.110 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  9.095 ms/op
                 existUser·p0.9999: 18.996 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   2: 3.152 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  14.424 ms/op
                 existUser·p0.9999: 19.558 ms/op
                 existUser·p1.00:   20.152 ms/op

Iteration   3: 3.089 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.575 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  12.746 ms/op
                 existUser·p0.9999: 24.295 ms/op
                 existUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307937
  mean =      3.117 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13859 
    [ 2.500,  5.000) = 288205 
    [ 5.000,  7.500) = 4950 
    [ 7.500, 10.000) = 400 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     13.140 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     24.604 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.126 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.474 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.009 ms/op
Iteration   1: 3.362 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   6.750 ms/op
                 getUser·p0.999:  22.086 ms/op
                 getUser·p0.9999: 36.831 ms/op
                 getUser·p1.00:   38.207 ms/op

Iteration   2: 3.216 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  13.296 ms/op
                 getUser·p0.9999: 26.806 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   3: 3.254 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  10.309 ms/op
                 getUser·p0.9999: 23.396 ms/op
                 getUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292654
  mean =      3.276 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8056 
    [ 2.500,  5.000) = 275456 
    [ 5.000,  7.500) = 7858 
    [ 7.500, 10.000) = 635 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     18.963 ms/op
     p(99.9900) =     35.831 ms/op
     p(99.9990) =     37.950 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.999 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.285 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.011 ms/op
Iteration   1: 3.842 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.653 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.557 ms/op
                 listUser·p0.999:  17.466 ms/op
                 listUser·p0.9999: 22.108 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   2: 3.880 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.686 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   7.809 ms/op
                 listUser·p0.999:  14.223 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   17.826 ms/op

Iteration   3: 3.896 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  12.616 ms/op
                 listUser·p0.9999: 15.103 ms/op
                 listUser·p1.00:   15.745 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247752
  mean =      3.872 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 83 
    [ 2.500,  5.000) = 238578 
    [ 5.000,  7.500) = 6787 
    [ 7.500, 10.000) = 1474 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 344 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.653 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     14.619 ms/op
     p(99.9900) =     21.529 ms/op
     p(99.9990) =     22.987 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.823 ± 0.785  ops/ms
ClientPb.existUser                       thrpt       3  10.183 ± 3.784  ops/ms
ClientPb.getUser                         thrpt       3   9.997 ± 5.656  ops/ms
ClientPb.listUser                        thrpt       3   8.473 ± 0.299  ops/ms
ClientPb.createUser                       avgt       3   3.247 ± 0.936   ms/op
ClientPb.existUser                        avgt       3   3.082 ± 0.744   ms/op
ClientPb.getUser                          avgt       3   3.233 ± 0.415   ms/op
ClientPb.listUser                         avgt       3   3.737 ± 0.956   ms/op
ClientPb.createUser                     sample  295483   3.247 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.057           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.559           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.931           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.344           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.331           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.771           ms/op
ClientPb.existUser                      sample  307937   3.117 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.990           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.400           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.140           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.577           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.002           ms/op
ClientPb.getUser                        sample  292654   3.276 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.984           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.609           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.473           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.308           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.963           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.831           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.207           ms/op
ClientPb.listUser                       sample  247752   3.872 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.653           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.723           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.356           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.619           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.529           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.167           ms/op
