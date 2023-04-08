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
# Warmup Iteration   1: 2.146 ops/ms
# Warmup Iteration   2: 5.239 ops/ms
# Warmup Iteration   3: 8.596 ops/ms
Iteration   1: 9.249 ops/ms
Iteration   2: 9.089 ops/ms
Iteration   3: 9.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.240 ±(99.9%) 2.684 ops/ms [Average]
  (min, avg, max) = (9.089, 9.240, 9.383), stdev = 0.147
  CI (99.9%): [6.556, 11.925] (assumes normal distribution)


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
# Warmup Iteration   1: 3.402 ops/ms
# Warmup Iteration   2: 8.878 ops/ms
# Warmup Iteration   3: 9.649 ops/ms
Iteration   1: 9.917 ops/ms
Iteration   2: 9.895 ops/ms
Iteration   3: 9.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.827 ±(99.9%) 2.509 ops/ms [Average]
  (min, avg, max) = (9.669, 9.827, 9.917), stdev = 0.138
  CI (99.9%): [7.318, 12.337] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.778 ops/ms
# Warmup Iteration   2: 8.383 ops/ms
# Warmup Iteration   3: 8.909 ops/ms
Iteration   1: 9.194 ops/ms
Iteration   2: 9.725 ops/ms
Iteration   3: 9.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.331 ±(99.9%) 6.311 ops/ms [Average]
  (min, avg, max) = (9.075, 9.331, 9.725), stdev = 0.346
  CI (99.9%): [3.021, 15.642] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.814 ops/ms
# Warmup Iteration   2: 6.958 ops/ms
# Warmup Iteration   3: 8.047 ops/ms
Iteration   1: 7.787 ops/ms
Iteration   2: 8.311 ops/ms
Iteration   3: 7.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.025 ±(99.9%) 4.844 ops/ms [Average]
  (min, avg, max) = (7.787, 8.025, 8.311), stdev = 0.266
  CI (99.9%): [3.181, 12.868] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.930 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.005 ms/op
Iteration   1: 3.331 ±(99.9%) 0.012 ms/op
Iteration   2: 3.526 ±(99.9%) 0.006 ms/op
Iteration   3: 3.306 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.388 ±(99.9%) 2.198 ms/op [Average]
  (min, avg, max) = (3.306, 3.388, 3.526), stdev = 0.120
  CI (99.9%): [1.190, 5.586] (assumes normal distribution)


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
# Warmup Iteration   1: 7.729 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.008 ms/op
Iteration   1: 3.298 ±(99.9%) 0.005 ms/op
Iteration   2: 3.283 ±(99.9%) 0.005 ms/op
Iteration   3: 3.180 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.253 ±(99.9%) 1.170 ms/op [Average]
  (min, avg, max) = (3.180, 3.253, 3.298), stdev = 0.064
  CI (99.9%): [2.084, 4.423] (assumes normal distribution)


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
# Warmup Iteration   1: 7.493 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.731 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.006 ms/op
Iteration   1: 3.365 ±(99.9%) 0.004 ms/op
Iteration   2: 3.294 ±(99.9%) 0.008 ms/op
Iteration   3: 3.292 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.317 ±(99.9%) 0.760 ms/op [Average]
  (min, avg, max) = (3.292, 3.317, 3.365), stdev = 0.042
  CI (99.9%): [2.556, 4.077] (assumes normal distribution)


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
# Warmup Iteration   1: 9.757 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.370 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.095 ±(99.9%) 0.006 ms/op
Iteration   1: 4.001 ±(99.9%) 0.007 ms/op
Iteration   2: 3.968 ±(99.9%) 0.010 ms/op
Iteration   3: 3.902 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.957 ±(99.9%) 0.922 ms/op [Average]
  (min, avg, max) = (3.902, 3.957, 4.001), stdev = 0.051
  CI (99.9%): [3.035, 4.878] (assumes normal distribution)


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
# Warmup Iteration   1: 8.966 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.948 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.010 ms/op
Iteration   1: 3.402 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  19.627 ms/op
                 createUser·p0.9999: 21.286 ms/op
                 createUser·p1.00:   22.479 ms/op

Iteration   2: 3.335 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.403 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  21.496 ms/op
                 createUser·p0.9999: 28.390 ms/op
                 createUser·p1.00:   28.934 ms/op

Iteration   3: 3.362 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  18.707 ms/op
                 createUser·p0.9999: 23.560 ms/op
                 createUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285044
  mean =      3.366 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11517 
    [ 2.500,  5.000) = 269113 
    [ 5.000,  7.500) = 3516 
    [ 7.500, 10.000) = 512 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     18.775 ms/op
     p(99.9900) =     26.657 ms/op
     p(99.9990) =     28.692 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


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
# Warmup Iteration   1: 8.275 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.389 ±(99.9%) 0.009 ms/op
Iteration   1: 3.286 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  9.677 ms/op
                 existUser·p0.9999: 22.610 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   2: 3.347 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.599 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  20.826 ms/op
                 existUser·p0.9999: 25.705 ms/op
                 existUser·p1.00:   26.313 ms/op

Iteration   3: 3.395 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.149 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  18.780 ms/op
                 existUser·p0.9999: 27.151 ms/op
                 existUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287197
  mean =      3.342 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19760 
    [ 2.500,  5.000) = 262259 
    [ 5.000,  7.500) = 4293 
    [ 7.500, 10.000) = 485 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 78 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     12.419 ms/op
     p(99.9900) =     26.182 ms/op
     p(99.9990) =     27.579 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 9.922 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.735 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.478 ±(99.9%) 0.010 ms/op
Iteration   1: 3.354 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.315 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.365 ms/op
                 getUser·p0.999:  17.138 ms/op
                 getUser·p0.9999: 20.132 ms/op
                 getUser·p1.00:   21.201 ms/op

Iteration   2: 3.334 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  19.183 ms/op
                 getUser·p0.9999: 21.994 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   3: 3.396 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.751 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  16.688 ms/op
                 getUser·p0.9999: 26.436 ms/op
                 getUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 285535
  mean =      3.361 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6296 
    [ 2.500,  5.000) = 273183 
    [ 5.000,  7.500) = 5035 
    [ 7.500, 10.000) = 589 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      6.043 ms/op
     p(99.9000) =     16.726 ms/op
     p(99.9900) =     25.308 ms/op
     p(99.9990) =     27.113 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 9.790 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.400 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.012 ms/op
Iteration   1: 3.942 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.632 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.360 ms/op
                 listUser·p0.999:  18.561 ms/op
                 listUser·p0.9999: 23.000 ms/op
                 listUser·p1.00:   23.790 ms/op

Iteration   2: 3.854 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  15.519 ms/op
                 listUser·p0.9999: 20.215 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 3.851 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.907 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.713 ms/op
                 listUser·p0.9999: 16.597 ms/op
                 listUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247083
  mean =      3.882 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 240040 
    [ 5.000,  7.500) = 4948 
    [ 7.500, 10.000) = 1140 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.632 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     14.893 ms/op
     p(99.9900) =     22.274 ms/op
     p(99.9990) =     23.597 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.240 ± 2.684  ops/ms
ClientPb.existUser                       thrpt       3   9.827 ± 2.509  ops/ms
ClientPb.getUser                         thrpt       3   9.331 ± 6.311  ops/ms
ClientPb.listUser                        thrpt       3   8.025 ± 4.844  ops/ms
ClientPb.createUser                       avgt       3   3.388 ± 2.198   ms/op
ClientPb.existUser                        avgt       3   3.253 ± 1.170   ms/op
ClientPb.getUser                          avgt       3   3.317 ± 0.760   ms/op
ClientPb.listUser                         avgt       3   3.957 ± 0.922   ms/op
ClientPb.createUser                     sample  285044   3.366 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.792           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.305           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.661           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.775           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.657           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.934           ms/op
ClientPb.existUser                      sample  287197   3.342 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.149           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.489           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.419           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.182           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.787           ms/op
ClientPb.getUser                        sample  285535   3.361 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.952           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.006           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.043           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.726           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.308           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.361           ms/op
ClientPb.listUser                       sample  247083   3.882 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.632           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.756           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.012           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.893           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.274           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.790           ms/op
