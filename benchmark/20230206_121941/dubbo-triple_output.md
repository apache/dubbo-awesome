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
# Warmup Iteration   1: 2.554 ops/ms
# Warmup Iteration   2: 6.524 ops/ms
# Warmup Iteration   3: 9.341 ops/ms
Iteration   1: 9.636 ops/ms
Iteration   2: 9.602 ops/ms
Iteration   3: 9.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.719 ±(99.9%) 3.189 ops/ms [Average]
  (min, avg, max) = (9.602, 9.719, 9.920), stdev = 0.175
  CI (99.9%): [6.530, 12.909] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.804 ops/ms
# Warmup Iteration   2: 9.811 ops/ms
# Warmup Iteration   3: 9.959 ops/ms
Iteration   1: 10.527 ops/ms
Iteration   2: 10.383 ops/ms
Iteration   3: 10.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.421 ±(99.9%) 1.690 ops/ms [Average]
  (min, avg, max) = (10.353, 10.421, 10.527), stdev = 0.093
  CI (99.9%): [8.731, 12.111] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.895 ops/ms
# Warmup Iteration   2: 9.423 ops/ms
# Warmup Iteration   3: 9.441 ops/ms
Iteration   1: 9.476 ops/ms
Iteration   2: 9.889 ops/ms
Iteration   3: 10.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.798 ±(99.9%) 5.248 ops/ms [Average]
  (min, avg, max) = (9.476, 9.798, 10.029), stdev = 0.288
  CI (99.9%): [4.550, 15.046] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.493 ops/ms
# Warmup Iteration   2: 7.819 ops/ms
# Warmup Iteration   3: 8.381 ops/ms
Iteration   1: 8.493 ops/ms
Iteration   2: 8.699 ops/ms
Iteration   3: 8.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.580 ±(99.9%) 1.945 ops/ms [Average]
  (min, avg, max) = (8.493, 8.580, 8.699), stdev = 0.107
  CI (99.9%): [6.635, 10.526] (assumes normal distribution)


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
# Warmup Iteration   1: 8.480 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.700 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.004 ms/op
Iteration   1: 3.186 ±(99.9%) 0.005 ms/op
Iteration   2: 3.129 ±(99.9%) 0.003 ms/op
Iteration   3: 3.216 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.177 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (3.129, 3.177, 3.216), stdev = 0.044
  CI (99.9%): [2.376, 3.978] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.361 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.391 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.006 ms/op
Iteration   1: 2.986 ±(99.9%) 0.002 ms/op
Iteration   2: 3.105 ±(99.9%) 0.006 ms/op
Iteration   3: 3.155 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.082 ±(99.9%) 1.582 ms/op [Average]
  (min, avg, max) = (2.986, 3.082, 3.155), stdev = 0.087
  CI (99.9%): [1.500, 4.664] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.777 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.513 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.007 ms/op
Iteration   1: 3.187 ±(99.9%) 0.003 ms/op
Iteration   2: 3.325 ±(99.9%) 0.003 ms/op
Iteration   3: 3.180 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.230 ±(99.9%) 1.499 ms/op [Average]
  (min, avg, max) = (3.180, 3.230, 3.325), stdev = 0.082
  CI (99.9%): [1.732, 4.729] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.991 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.006 ms/op
Iteration   1: 3.746 ±(99.9%) 0.010 ms/op
Iteration   2: 3.715 ±(99.9%) 0.008 ms/op
Iteration   3: 3.696 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.719 ±(99.9%) 0.464 ms/op [Average]
  (min, avg, max) = (3.696, 3.719, 3.746), stdev = 0.025
  CI (99.9%): [3.255, 4.183] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.794 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.269 ±(99.9%) 0.009 ms/op
Iteration   1: 3.205 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  12.435 ms/op
                 createUser·p0.9999: 21.463 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   2: 3.371 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.329 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  20.452 ms/op
                 createUser·p0.9999: 22.970 ms/op
                 createUser·p1.00:   23.298 ms/op

Iteration   3: 3.271 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.308 ms/op
                 createUser·p0.999:  16.750 ms/op
                 createUser·p0.9999: 20.651 ms/op
                 createUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292565
  mean =      3.281 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21404 
    [ 2.500,  5.000) = 265582 
    [ 5.000,  7.500) = 4667 
    [ 7.500, 10.000) = 322 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     22.536 ms/op
     p(99.9990) =     23.069 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.106 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.378 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.008 ms/op
Iteration   1: 3.069 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.550 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  9.372 ms/op
                 existUser·p0.9999: 21.731 ms/op
                 existUser·p1.00:   22.872 ms/op

Iteration   2: 3.212 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.165 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  13.746 ms/op
                 existUser·p0.9999: 23.398 ms/op
                 existUser·p1.00:   24.904 ms/op

Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  12.947 ms/op
                 existUser·p0.9999: 21.323 ms/op
                 existUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306621
  mean =      3.129 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17481 
    [ 2.500,  5.000) = 283607 
    [ 5.000,  7.500) = 4779 
    [ 7.500, 10.000) = 388 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 145 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     12.673 ms/op
     p(99.9900) =     22.304 ms/op
     p(99.9990) =     24.299 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 7.619 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.457 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.010 ms/op
Iteration   1: 3.332 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.278 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  19.290 ms/op
                 getUser·p0.9999: 22.649 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   2: 3.131 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.523 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  11.949 ms/op
                 getUser·p0.9999: 22.275 ms/op
                 getUser·p1.00:   23.069 ms/op

Iteration   3: 3.199 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  8.654 ms/op
                 getUser·p0.9999: 21.398 ms/op
                 getUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298084
  mean =      3.219 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12931 
    [ 2.500,  5.000) = 279245 
    [ 5.000,  7.500) = 5080 
    [ 7.500, 10.000) = 404 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 200 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     15.972 ms/op
     p(99.9900) =     22.321 ms/op
     p(99.9990) =     23.072 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 10.008 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.119 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.013 ms/op
Iteration   1: 3.766 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  14.352 ms/op
                 listUser·p0.9999: 20.071 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   2: 3.716 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  14.008 ms/op
                 listUser·p0.9999: 16.751 ms/op
                 listUser·p1.00:   17.334 ms/op

Iteration   3: 3.781 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.656 ms/op
                 listUser·p0.999:  13.393 ms/op
                 listUser·p0.9999: 14.902 ms/op
                 listUser·p1.00:   14.975 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255489
  mean =      3.755 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 248336 
    [ 5.000,  7.500) = 5000 
    [ 7.500, 10.000) = 1360 
    [10.000, 12.500) = 277 
    [12.500, 15.000) = 312 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      7.136 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     19.232 ms/op
     p(99.9990) =     20.477 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.719 ± 3.189  ops/ms
ClientPb.existUser                       thrpt       3  10.421 ± 1.690  ops/ms
ClientPb.getUser                         thrpt       3   9.798 ± 5.248  ops/ms
ClientPb.listUser                        thrpt       3   8.580 ± 1.945  ops/ms
ClientPb.createUser                       avgt       3   3.177 ± 0.801   ms/op
ClientPb.existUser                        avgt       3   3.082 ± 1.582   ms/op
ClientPb.getUser                          avgt       3   3.230 ± 1.499   ms/op
ClientPb.listUser                         avgt       3   3.719 ± 0.464   ms/op
ClientPb.createUser                     sample  292565   3.281 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.130           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.149           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.138           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.536           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.298           ms/op
ClientPb.existUser                      sample  306621   3.129 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.165           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.461           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.673           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.304           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.904           ms/op
ClientPb.getUser                        sample  298084   3.219 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.020           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.580           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.792           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.972           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.321           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.265           ms/op
ClientPb.listUser                       sample  255489   3.755 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.869           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.699           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.136           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.910           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.232           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.808           ms/op
