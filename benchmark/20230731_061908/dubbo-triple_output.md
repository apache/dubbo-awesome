# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.562 ops/ms
# Warmup Iteration   2: 6.252 ops/ms
# Warmup Iteration   3: 8.943 ops/ms
Iteration   1: 9.590 ops/ms
Iteration   2: 10.040 ops/ms
Iteration   3: 9.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.689 ±(99.9%) 5.725 ops/ms [Average]
  (min, avg, max) = (9.436, 9.689, 10.040), stdev = 0.314
  CI (99.9%): [3.964, 15.414] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.370 ops/ms
# Warmup Iteration   2: 9.429 ops/ms
# Warmup Iteration   3: 10.200 ops/ms
Iteration   1: 10.561 ops/ms
Iteration   2: 10.452 ops/ms
Iteration   3: 10.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.531 ±(99.9%) 1.267 ops/ms [Average]
  (min, avg, max) = (10.452, 10.531, 10.581), stdev = 0.069
  CI (99.9%): [9.264, 11.798] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.479 ops/ms
# Warmup Iteration   2: 9.065 ops/ms
# Warmup Iteration   3: 9.432 ops/ms
Iteration   1: 9.636 ops/ms
Iteration   2: 9.853 ops/ms
Iteration   3: 9.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.642 ±(99.9%) 3.803 ops/ms [Average]
  (min, avg, max) = (9.436, 9.642, 9.853), stdev = 0.208
  CI (99.9%): [5.838, 13.445] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.287 ops/ms
# Warmup Iteration   2: 7.448 ops/ms
# Warmup Iteration   3: 8.233 ops/ms
Iteration   1: 8.360 ops/ms
Iteration   2: 8.501 ops/ms
Iteration   3: 8.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.480 ±(99.9%) 2.031 ops/ms [Average]
  (min, avg, max) = (8.360, 8.480, 8.580), stdev = 0.111
  CI (99.9%): [6.449, 10.511] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.044 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.560 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.007 ms/op
Iteration   1: 3.257 ±(99.9%) 0.003 ms/op
Iteration   2: 3.129 ±(99.9%) 0.006 ms/op
Iteration   3: 3.253 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.213 ±(99.9%) 1.334 ms/op [Average]
  (min, avg, max) = (3.129, 3.213, 3.257), stdev = 0.073
  CI (99.9%): [1.879, 4.547] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.416 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.384 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.004 ms/op
Iteration   1: 3.146 ±(99.9%) 0.005 ms/op
Iteration   2: 2.993 ±(99.9%) 0.005 ms/op
Iteration   3: 3.088 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.076 ±(99.9%) 1.414 ms/op [Average]
  (min, avg, max) = (2.993, 3.076, 3.146), stdev = 0.077
  CI (99.9%): [1.662, 4.489] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.855 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.423 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.314 ±(99.9%) 0.002 ms/op
Iteration   1: 3.358 ±(99.9%) 0.005 ms/op
Iteration   2: 3.264 ±(99.9%) 0.002 ms/op
Iteration   3: 3.187 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.270 ±(99.9%) 1.559 ms/op [Average]
  (min, avg, max) = (3.187, 3.270, 3.358), stdev = 0.085
  CI (99.9%): [1.711, 4.828] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.139 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.360 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.005 ms/op
Iteration   1: 3.751 ±(99.9%) 0.005 ms/op
Iteration   2: 3.792 ±(99.9%) 0.008 ms/op
Iteration   3: 3.777 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.773 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (3.751, 3.773, 3.792), stdev = 0.021
  CI (99.9%): [3.399, 4.148] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.391 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.338 ±(99.9%) 0.009 ms/op
Iteration   1: 3.164 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  21.287 ms/op
                 createUser·p0.9999: 26.855 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   2: 3.263 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.128 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  15.051 ms/op
                 createUser·p0.9999: 24.287 ms/op
                 createUser·p1.00:   24.805 ms/op

Iteration   3: 3.185 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.350 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  16.860 ms/op
                 createUser·p0.9999: 31.195 ms/op
                 createUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299676
  mean =      3.203 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13917 
    [ 2.500,  5.000) = 280829 
    [ 5.000,  7.500) = 3737 
    [ 7.500, 10.000) = 717 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     18.492 ms/op
     p(99.9900) =     30.736 ms/op
     p(99.9990) =     34.210 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.246 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.007 ms/op
Iteration   1: 3.110 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.272 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  12.233 ms/op
                 existUser·p0.9999: 19.366 ms/op
                 existUser·p1.00:   21.168 ms/op

Iteration   2: 3.123 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   6.223 ms/op
                 existUser·p0.999:  15.876 ms/op
                 existUser·p0.9999: 24.434 ms/op
                 existUser·p1.00:   25.592 ms/op

Iteration   3: 3.291 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.899 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  13.337 ms/op
                 existUser·p0.9999: 22.774 ms/op
                 existUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302276
  mean =      3.173 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8748 
    [ 2.500,  5.000) = 286924 
    [ 5.000,  7.500) = 5603 
    [ 7.500, 10.000) = 527 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     13.561 ms/op
     p(99.9900) =     22.908 ms/op
     p(99.9990) =     25.492 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.620 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.388 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.009 ms/op
Iteration   1: 3.270 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.267 ms/op
                 getUser·p0.999:  11.387 ms/op
                 getUser·p0.9999: 24.911 ms/op
                 getUser·p1.00:   25.788 ms/op

Iteration   2: 3.136 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.362 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.531 ms/op
                 getUser·p0.99:   4.899 ms/op
                 getUser·p0.999:  10.700 ms/op
                 getUser·p0.9999: 21.660 ms/op
                 getUser·p1.00:   22.249 ms/op

Iteration   3: 3.243 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  10.043 ms/op
                 getUser·p0.9999: 19.825 ms/op
                 getUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298249
  mean =      3.215 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9492 
    [ 2.500,  5.000) = 282085 
    [ 5.000,  7.500) = 5812 
    [ 7.500, 10.000) = 506 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     11.043 ms/op
     p(99.9900) =     23.369 ms/op
     p(99.9990) =     25.691 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.527 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.161 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.840 ±(99.9%) 0.012 ms/op
Iteration   1: 3.775 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.190 ms/op
                 listUser·p0.999:  14.696 ms/op
                 listUser·p0.9999: 20.579 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   2: 3.802 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.464 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.566 ms/op
                 listUser·p0.999:  13.943 ms/op
                 listUser·p0.9999: 17.138 ms/op
                 listUser·p1.00:   17.236 ms/op

Iteration   3: 3.778 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  14.156 ms/op
                 listUser·p0.9999: 16.016 ms/op
                 listUser·p1.00:   16.040 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253693
  mean =      3.785 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 103 
    [ 2.500,  5.000) = 246615 
    [ 5.000,  7.500) = 4932 
    [ 7.500, 10.000) = 1283 
    [10.000, 12.500) = 367 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.882 ms/op
     p(99.9000) =     14.177 ms/op
     p(99.9900) =     20.030 ms/op
     p(99.9990) =     20.969 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.689 ± 5.725  ops/ms
ClientPb.existUser                       thrpt       3  10.531 ± 1.267  ops/ms
ClientPb.getUser                         thrpt       3   9.642 ± 3.803  ops/ms
ClientPb.listUser                        thrpt       3   8.480 ± 2.031  ops/ms
ClientPb.createUser                       avgt       3   3.213 ± 1.334   ms/op
ClientPb.existUser                        avgt       3   3.076 ± 1.414   ms/op
ClientPb.getUser                          avgt       3   3.270 ± 1.559   ms/op
ClientPb.listUser                         avgt       3   3.773 ± 0.375   ms/op
ClientPb.createUser                     sample  299676   3.203 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.110           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.555           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.456           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.492           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.736           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.537           ms/op
ClientPb.existUser                      sample  302276   3.173 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.900           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.006           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.775           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.561           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.908           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.592           ms/op
ClientPb.getUser                        sample  298249   3.215 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.296           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.568           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.685           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.043           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.369           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.788           ms/op
ClientPb.listUser                       sample  253693   3.785 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.464           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.088           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.882           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.177           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.030           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.561           ms/op
