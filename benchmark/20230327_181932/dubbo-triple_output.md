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
# Warmup Iteration   1: 2.295 ops/ms
# Warmup Iteration   2: 6.129 ops/ms
# Warmup Iteration   3: 8.671 ops/ms
Iteration   1: 9.459 ops/ms
Iteration   2: 9.362 ops/ms
Iteration   3: 9.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.435 ±(99.9%) 1.175 ops/ms [Average]
  (min, avg, max) = (9.362, 9.435, 9.484), stdev = 0.064
  CI (99.9%): [8.260, 10.609] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.266 ops/ms
# Warmup Iteration   2: 8.973 ops/ms
# Warmup Iteration   3: 9.518 ops/ms
Iteration   1: 9.502 ops/ms
Iteration   2: 9.608 ops/ms
Iteration   3: 9.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.501 ±(99.9%) 1.963 ops/ms [Average]
  (min, avg, max) = (9.393, 9.501, 9.608), stdev = 0.108
  CI (99.9%): [7.538, 11.464] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.009 ops/ms
# Warmup Iteration   2: 8.688 ops/ms
# Warmup Iteration   3: 9.275 ops/ms
Iteration   1: 9.608 ops/ms
Iteration   2: 9.533 ops/ms
Iteration   3: 8.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.375 ±(99.9%) 6.223 ops/ms [Average]
  (min, avg, max) = (8.983, 9.375, 9.608), stdev = 0.341
  CI (99.9%): [3.152, 15.598] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.624 ops/ms
# Warmup Iteration   2: 7.165 ops/ms
# Warmup Iteration   3: 7.652 ops/ms
Iteration   1: 8.254 ops/ms
Iteration   2: 7.968 ops/ms
Iteration   3: 8.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.154 ±(99.9%) 2.943 ops/ms [Average]
  (min, avg, max) = (7.968, 8.154, 8.254), stdev = 0.161
  CI (99.9%): [5.212, 11.097] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.534 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.765 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.005 ms/op
Iteration   1: 3.399 ±(99.9%) 0.009 ms/op
Iteration   2: 3.543 ±(99.9%) 0.005 ms/op
Iteration   3: 3.433 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.458 ±(99.9%) 1.373 ms/op [Average]
  (min, avg, max) = (3.399, 3.458, 3.543), stdev = 0.075
  CI (99.9%): [2.085, 4.831] (assumes normal distribution)


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
# Warmup Iteration   1: 9.643 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.427 ±(99.9%) 0.010 ms/op
Iteration   1: 3.253 ±(99.9%) 0.014 ms/op
Iteration   2: 3.348 ±(99.9%) 0.005 ms/op
Iteration   3: 3.325 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.309 ±(99.9%) 0.902 ms/op [Average]
  (min, avg, max) = (3.253, 3.309, 3.348), stdev = 0.049
  CI (99.9%): [2.407, 4.211] (assumes normal distribution)


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
# Warmup Iteration   1: 11.282 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.503 ±(99.9%) 0.004 ms/op
Iteration   1: 3.531 ±(99.9%) 0.004 ms/op
Iteration   2: 3.448 ±(99.9%) 0.009 ms/op
Iteration   3: 3.519 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.499 ±(99.9%) 0.816 ms/op [Average]
  (min, avg, max) = (3.448, 3.499, 3.531), stdev = 0.045
  CI (99.9%): [2.683, 4.316] (assumes normal distribution)


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
# Warmup Iteration   1: 9.985 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.488 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.176 ±(99.9%) 0.006 ms/op
Iteration   1: 4.078 ±(99.9%) 0.009 ms/op
Iteration   2: 4.012 ±(99.9%) 0.011 ms/op
Iteration   3: 3.880 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.990 ±(99.9%) 1.835 ms/op [Average]
  (min, avg, max) = (3.880, 3.990, 4.078), stdev = 0.101
  CI (99.9%): [2.155, 5.825] (assumes normal distribution)


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
# Warmup Iteration   1: 9.468 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.047 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.010 ms/op
Iteration   1: 3.428 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  20.478 ms/op
                 createUser·p0.9999: 28.617 ms/op
                 createUser·p1.00:   29.590 ms/op

Iteration   2: 3.428 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  21.816 ms/op
                 createUser·p0.9999: 25.627 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   3: 3.404 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.755 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  19.497 ms/op
                 createUser·p0.9999: 25.120 ms/op
                 createUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280588
  mean =      3.420 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6324 
    [ 2.500,  5.000) = 267922 
    [ 5.000,  7.500) = 5173 
    [ 7.500, 10.000) = 645 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     19.695 ms/op
     p(99.9900) =     27.064 ms/op
     p(99.9990) =     29.313 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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
# Warmup Iteration   1: 8.092 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.008 ms/op
Iteration   1: 3.373 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.765 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.190 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  22.863 ms/op
                 existUser·p0.9999: 26.986 ms/op
                 existUser·p1.00:   27.984 ms/op

Iteration   2: 3.343 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.683 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  21.605 ms/op
                 existUser·p0.9999: 26.177 ms/op
                 existUser·p1.00:   27.034 ms/op

Iteration   3: 3.439 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.649 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  19.628 ms/op
                 existUser·p0.9999: 26.532 ms/op
                 existUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283506
  mean =      3.384 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14734 
    [ 2.500,  5.000) = 263553 
    [ 5.000,  7.500) = 4221 
    [ 7.500, 10.000) = 517 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 131 

  Percentiles, ms/op:
      p(0.0000) =      1.649 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     19.628 ms/op
     p(99.9900) =     26.531 ms/op
     p(99.9990) =     27.689 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


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
# Warmup Iteration   1: 8.507 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.027 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.011 ms/op
Iteration   1: 3.511 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   7.029 ms/op
                 getUser·p0.999:  14.238 ms/op
                 getUser·p0.9999: 27.259 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   2: 3.482 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.491 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  21.302 ms/op
                 getUser·p0.9999: 28.344 ms/op
                 getUser·p1.00:   28.901 ms/op

Iteration   3: 3.540 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.507 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.088 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  19.794 ms/op
                 getUser·p0.9999: 24.542 ms/op
                 getUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273469
  mean =      3.511 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4185 
    [ 2.500,  5.000) = 260020 
    [ 5.000,  7.500) = 7984 
    [ 7.500, 10.000) = 865 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     27.623 ms/op
     p(99.9990) =     28.604 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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
# Warmup Iteration   1: 10.932 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 5.017 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.013 ms/op
Iteration   1: 3.989 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  22.145 ms/op
                 listUser·p0.9999: 26.673 ms/op
                 listUser·p1.00:   27.525 ms/op

Iteration   2: 4.066 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.890 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.995 ms/op
                 listUser·p0.999:  14.189 ms/op
                 listUser·p0.9999: 20.391 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   3: 3.980 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  17.292 ms/op
                 listUser·p0.9999: 32.079 ms/op
                 listUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239112
  mean =      4.011 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 230446 
    [ 5.000,  7.500) = 6348 
    [ 7.500, 10.000) = 1414 
    [10.000, 12.500) = 314 
    [12.500, 15.000) = 222 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.388 ms/op
     p(99.9000) =     18.051 ms/op
     p(99.9900) =     26.333 ms/op
     p(99.9990) =     32.579 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.435 ± 1.175  ops/ms
ClientPb.existUser                       thrpt       3   9.501 ± 1.963  ops/ms
ClientPb.getUser                         thrpt       3   9.375 ± 6.223  ops/ms
ClientPb.listUser                        thrpt       3   8.154 ± 2.943  ops/ms
ClientPb.createUser                       avgt       3   3.458 ± 1.373   ms/op
ClientPb.existUser                        avgt       3   3.309 ± 0.902   ms/op
ClientPb.getUser                          avgt       3   3.499 ± 0.816   ms/op
ClientPb.listUser                         avgt       3   3.990 ± 1.835   ms/op
ClientPb.createUser                     sample  280588   3.420 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.268           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.297           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.956           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.695           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.064           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.590           ms/op
ClientPb.existUser                      sample  283506   3.384 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.649           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.322           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.785           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.145           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.612           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.628           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.531           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.984           ms/op
ClientPb.getUser                        sample  273469   3.511 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.491           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.521           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.877           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.623           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.901           ms/op
ClientPb.listUser                       sample  239112   4.011 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.350           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.388           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.051           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.333           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.899           ms/op
