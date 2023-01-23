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
# Warmup Iteration   1: 2.164 ops/ms
# Warmup Iteration   2: 5.772 ops/ms
# Warmup Iteration   3: 9.027 ops/ms
Iteration   1: 9.604 ops/ms
Iteration   2: 9.601 ops/ms
Iteration   3: 9.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.574 ±(99.9%) 0.907 ops/ms [Average]
  (min, avg, max) = (9.516, 9.574, 9.604), stdev = 0.050
  CI (99.9%): [8.667, 10.481] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.622 ops/ms
# Warmup Iteration   2: 8.771 ops/ms
# Warmup Iteration   3: 9.481 ops/ms
Iteration   1: 9.518 ops/ms
Iteration   2: 9.314 ops/ms
Iteration   3: 9.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.519 ±(99.9%) 3.761 ops/ms [Average]
  (min, avg, max) = (9.314, 9.519, 9.726), stdev = 0.206
  CI (99.9%): [5.758, 13.281] (assumes normal distribution)


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
# Warmup Iteration   1: 2.803 ops/ms
# Warmup Iteration   2: 8.452 ops/ms
# Warmup Iteration   3: 9.102 ops/ms
Iteration   1: 9.311 ops/ms
Iteration   2: 9.493 ops/ms
Iteration   3: 9.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.417 ±(99.9%) 1.727 ops/ms [Average]
  (min, avg, max) = (9.311, 9.417, 9.493), stdev = 0.095
  CI (99.9%): [7.690, 11.144] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.306 ops/ms
# Warmup Iteration   2: 7.479 ops/ms
# Warmup Iteration   3: 8.188 ops/ms
Iteration   1: 8.233 ops/ms
Iteration   2: 8.156 ops/ms
Iteration   3: 8.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.143 ±(99.9%) 1.763 ops/ms [Average]
  (min, avg, max) = (8.041, 8.143, 8.233), stdev = 0.097
  CI (99.9%): [6.380, 9.907] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.966 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.535 ±(99.9%) 0.008 ms/op
Iteration   1: 3.416 ±(99.9%) 0.009 ms/op
Iteration   2: 3.339 ±(99.9%) 0.009 ms/op
Iteration   3: 3.320 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.359 ±(99.9%) 0.927 ms/op [Average]
  (min, avg, max) = (3.320, 3.359, 3.416), stdev = 0.051
  CI (99.9%): [2.431, 4.286] (assumes normal distribution)


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
# Warmup Iteration   1: 7.213 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.543 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.005 ms/op
Iteration   1: 3.257 ±(99.9%) 0.009 ms/op
Iteration   2: 3.393 ±(99.9%) 0.007 ms/op
Iteration   3: 3.406 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.352 ±(99.9%) 1.504 ms/op [Average]
  (min, avg, max) = (3.257, 3.352, 3.406), stdev = 0.082
  CI (99.9%): [1.848, 4.856] (assumes normal distribution)


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
# Warmup Iteration   1: 9.144 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.003 ms/op
Iteration   1: 3.428 ±(99.9%) 0.006 ms/op
Iteration   2: 3.429 ±(99.9%) 0.009 ms/op
Iteration   3: 3.387 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.414 ±(99.9%) 0.434 ms/op [Average]
  (min, avg, max) = (3.387, 3.414, 3.429), stdev = 0.024
  CI (99.9%): [2.980, 3.849] (assumes normal distribution)


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
# Warmup Iteration   1: 10.398 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.181 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.007 ms/op
Iteration   1: 3.905 ±(99.9%) 0.010 ms/op
Iteration   2: 3.894 ±(99.9%) 0.010 ms/op
Iteration   3: 3.791 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.863 ±(99.9%) 1.146 ms/op [Average]
  (min, avg, max) = (3.791, 3.863, 3.905), stdev = 0.063
  CI (99.9%): [2.718, 5.009] (assumes normal distribution)


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
# Warmup Iteration   1: 9.660 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.009 ms/op
Iteration   1: 3.342 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  18.706 ms/op
                 createUser·p0.9999: 22.427 ms/op
                 createUser·p1.00:   22.872 ms/op

Iteration   2: 3.377 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  21.904 ms/op
                 createUser·p0.9999: 24.479 ms/op
                 createUser·p1.00:   25.330 ms/op

Iteration   3: 3.398 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.460 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  16.426 ms/op
                 createUser·p0.9999: 23.304 ms/op
                 createUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284602
  mean =      3.372 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11128 
    [ 2.500,  5.000) = 266913 
    [ 5.000,  7.500) = 5573 
    [ 7.500, 10.000) = 455 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     16.440 ms/op
     p(99.9900) =     23.840 ms/op
     p(99.9990) =     24.914 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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
# Warmup Iteration   1: 8.332 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.559 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.008 ms/op
Iteration   1: 3.349 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.530 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.857 ms/op
                 existUser·p0.999:  18.794 ms/op
                 existUser·p0.9999: 22.312 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   2: 3.292 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.497 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.177 ms/op
                 existUser·p0.999:  8.978 ms/op
                 existUser·p0.9999: 25.150 ms/op
                 existUser·p1.00:   26.313 ms/op

Iteration   3: 3.329 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.362 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  22.324 ms/op
                 existUser·p0.9999: 33.453 ms/op
                 existUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288419
  mean =      3.323 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10689 
    [ 2.500,  5.000) = 272268 
    [ 5.000,  7.500) = 4690 
    [ 7.500, 10.000) = 451 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     10.715 ms/op
     p(99.9900) =     31.914 ms/op
     p(99.9990) =     34.159 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 9.383 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.839 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.009 ms/op
Iteration   1: 3.342 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.413 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  18.678 ms/op
                 getUser·p0.9999: 27.087 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   2: 3.286 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.348 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  12.906 ms/op
                 getUser·p0.9999: 29.729 ms/op
                 getUser·p1.00:   30.212 ms/op

Iteration   3: 3.359 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  17.408 ms/op
                 getUser·p0.9999: 32.800 ms/op
                 getUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 288130
  mean =      3.329 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11875 
    [ 2.500,  5.000) = 270211 
    [ 5.000,  7.500) = 4988 
    [ 7.500, 10.000) = 574 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     17.226 ms/op
     p(99.9900) =     31.070 ms/op
     p(99.9990) =     33.514 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 10.239 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.371 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.012 ms/op
Iteration   1: 3.956 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.786 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   5.109 ms/op
                 listUser·p0.99:   7.539 ms/op
                 listUser·p0.999:  19.080 ms/op
                 listUser·p0.9999: 25.053 ms/op
                 listUser·p1.00:   26.313 ms/op

Iteration   2: 3.948 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  14.631 ms/op
                 listUser·p0.9999: 17.724 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   3: 3.914 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  13.877 ms/op
                 listUser·p0.9999: 20.120 ms/op
                 listUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243637
  mean =      3.939 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 234272 
    [ 5.000,  7.500) = 7305 
    [ 7.500, 10.000) = 1231 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 308 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     15.440 ms/op
     p(99.9900) =     22.139 ms/op
     p(99.9990) =     25.956 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.574 ± 0.907  ops/ms
ClientPb.existUser                       thrpt       3   9.519 ± 3.761  ops/ms
ClientPb.getUser                         thrpt       3   9.417 ± 1.727  ops/ms
ClientPb.listUser                        thrpt       3   8.143 ± 1.763  ops/ms
ClientPb.createUser                       avgt       3   3.359 ± 0.927   ms/op
ClientPb.existUser                        avgt       3   3.352 ± 1.504   ms/op
ClientPb.getUser                          avgt       3   3.414 ± 0.434   ms/op
ClientPb.listUser                         avgt       3   3.863 ± 1.146   ms/op
ClientPb.createUser                     sample  284602   3.372 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.430           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.849           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.440           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.840           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.330           ms/op
ClientPb.existUser                      sample  288419   3.323 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.362           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.010           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.715           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.914           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.406           ms/op
ClientPb.getUser                        sample  288130   3.329 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.167           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.505           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.226           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.070           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.144           ms/op
ClientPb.listUser                       sample  243637   3.939 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.786           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.776           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.102           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.440           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.139           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.313           ms/op
