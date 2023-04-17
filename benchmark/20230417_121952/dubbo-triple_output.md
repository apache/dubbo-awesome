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
# Warmup Iteration   1: 2.203 ops/ms
# Warmup Iteration   2: 5.496 ops/ms
# Warmup Iteration   3: 8.641 ops/ms
Iteration   1: 9.039 ops/ms
Iteration   2: 9.332 ops/ms
Iteration   3: 9.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.273 ±(99.9%) 3.845 ops/ms [Average]
  (min, avg, max) = (9.039, 9.273, 9.448), stdev = 0.211
  CI (99.9%): [5.428, 13.118] (assumes normal distribution)


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
# Warmup Iteration   1: 3.582 ops/ms
# Warmup Iteration   2: 9.262 ops/ms
# Warmup Iteration   3: 9.299 ops/ms
Iteration   1: 9.944 ops/ms
Iteration   2: 10.035 ops/ms
Iteration   3: 9.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.843 ±(99.9%) 4.704 ops/ms [Average]
  (min, avg, max) = (9.550, 9.843, 10.035), stdev = 0.258
  CI (99.9%): [5.139, 14.547] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.388 ops/ms
# Warmup Iteration   2: 8.815 ops/ms
# Warmup Iteration   3: 9.407 ops/ms
Iteration   1: 9.382 ops/ms
Iteration   2: 9.418 ops/ms
Iteration   3: 9.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.329 ±(99.9%) 2.270 ops/ms [Average]
  (min, avg, max) = (9.186, 9.329, 9.418), stdev = 0.124
  CI (99.9%): [7.059, 11.599] (assumes normal distribution)


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
# Warmup Iteration   1: 2.711 ops/ms
# Warmup Iteration   2: 6.799 ops/ms
# Warmup Iteration   3: 7.670 ops/ms
Iteration   1: 7.580 ops/ms
Iteration   2: 8.217 ops/ms
Iteration   3: 8.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.999 ±(99.9%) 6.624 ops/ms [Average]
  (min, avg, max) = (7.580, 7.999, 8.217), stdev = 0.363
  CI (99.9%): [1.375, 14.623] (assumes normal distribution)


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
# Warmup Iteration   1: 9.675 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.007 ms/op
Iteration   1: 3.366 ±(99.9%) 0.007 ms/op
Iteration   2: 3.513 ±(99.9%) 0.005 ms/op
Iteration   3: 3.417 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.432 ±(99.9%) 1.359 ms/op [Average]
  (min, avg, max) = (3.366, 3.432, 3.513), stdev = 0.075
  CI (99.9%): [2.072, 4.791] (assumes normal distribution)


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
# Warmup Iteration   1: 8.927 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.519 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.009 ms/op
Iteration   1: 3.257 ±(99.9%) 0.011 ms/op
Iteration   2: 3.203 ±(99.9%) 0.012 ms/op
Iteration   3: 3.266 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.242 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (3.203, 3.242, 3.266), stdev = 0.034
  CI (99.9%): [2.622, 3.862] (assumes normal distribution)


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
# Warmup Iteration   1: 8.074 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.562 ±(99.9%) 0.005 ms/op
Iteration   1: 3.409 ±(99.9%) 0.007 ms/op
Iteration   2: 3.366 ±(99.9%) 0.010 ms/op
Iteration   3: 3.397 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.391 ±(99.9%) 0.405 ms/op [Average]
  (min, avg, max) = (3.366, 3.391, 3.409), stdev = 0.022
  CI (99.9%): [2.985, 3.796] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.130 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.661 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.011 ms/op
Iteration   1: 3.898 ±(99.9%) 0.013 ms/op
Iteration   2: 4.045 ±(99.9%) 0.009 ms/op
Iteration   3: 3.853 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.932 ±(99.9%) 1.837 ms/op [Average]
  (min, avg, max) = (3.853, 3.932, 4.045), stdev = 0.101
  CI (99.9%): [2.095, 5.769] (assumes normal distribution)


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
# Warmup Iteration   1: 8.185 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.855 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.009 ms/op
Iteration   1: 3.483 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  20.719 ms/op
                 createUser·p0.9999: 24.564 ms/op
                 createUser·p1.00:   25.919 ms/op

Iteration   2: 3.379 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  22.252 ms/op
                 createUser·p0.9999: 27.903 ms/op
                 createUser·p1.00:   30.212 ms/op

Iteration   3: 3.592 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  16.594 ms/op
                 createUser·p0.9999: 25.890 ms/op
                 createUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275546
  mean =      3.482 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8616 
    [ 2.500,  5.000) = 260491 
    [ 5.000,  7.500) = 5107 
    [ 7.500, 10.000) = 758 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     16.701 ms/op
     p(99.9900) =     27.256 ms/op
     p(99.9990) =     28.164 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


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
# Warmup Iteration   1: 7.882 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.009 ms/op
Iteration   1: 3.370 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  9.869 ms/op
                 existUser·p0.9999: 27.673 ms/op
                 existUser·p1.00:   28.574 ms/op

Iteration   2: 3.375 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.698 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  21.630 ms/op
                 existUser·p0.9999: 23.956 ms/op
                 existUser·p1.00:   24.445 ms/op

Iteration   3: 3.326 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  17.447 ms/op
                 existUser·p0.9999: 25.625 ms/op
                 existUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285657
  mean =      3.357 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15097 
    [ 2.500,  5.000) = 265067 
    [ 5.000,  7.500) = 4660 
    [ 7.500, 10.000) = 415 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 134 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     12.720 ms/op
     p(99.9900) =     26.360 ms/op
     p(99.9990) =     28.508 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 8.436 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.584 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.499 ±(99.9%) 0.010 ms/op
Iteration   1: 3.415 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.702 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.157 ms/op
                 getUser·p0.99:   6.379 ms/op
                 getUser·p0.999:  20.459 ms/op
                 getUser·p0.9999: 28.967 ms/op
                 getUser·p1.00:   29.032 ms/op

Iteration   2: 3.434 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.356 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  20.604 ms/op
                 getUser·p0.9999: 23.268 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   3: 3.498 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.583 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  10.163 ms/op
                 getUser·p0.9999: 25.854 ms/op
                 getUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278185
  mean =      3.449 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8293 
    [ 2.500,  5.000) = 261003 
    [ 5.000,  7.500) = 7993 
    [ 7.500, 10.000) = 438 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 139 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     26.384 ms/op
     p(99.9990) =     29.000 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 10.523 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.732 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.012 ms/op
Iteration   1: 4.012 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.194 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  19.661 ms/op
                 listUser·p0.9999: 24.709 ms/op
                 listUser·p1.00:   26.673 ms/op

Iteration   2: 3.952 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.478 ms/op
                 listUser·p0.999:  14.191 ms/op
                 listUser·p0.9999: 17.498 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   3: 4.198 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.384 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   7.381 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  19.268 ms/op
                 listUser·p0.9999: 30.179 ms/op
                 listUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236926
  mean =      4.051 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 140 
    [ 2.500,  5.000) = 221449 
    [ 5.000,  7.500) = 10144 
    [ 7.500, 10.000) = 4125 
    [10.000, 12.500) = 372 
    [12.500, 15.000) = 305 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.384 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      6.128 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     29.600 ms/op
     p(99.9990) =     31.171 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.273 ± 3.845  ops/ms
ClientPb.existUser                       thrpt       3   9.843 ± 4.704  ops/ms
ClientPb.getUser                         thrpt       3   9.329 ± 2.270  ops/ms
ClientPb.listUser                        thrpt       3   7.999 ± 6.624  ops/ms
ClientPb.createUser                       avgt       3   3.432 ± 1.359   ms/op
ClientPb.existUser                        avgt       3   3.242 ± 0.620   ms/op
ClientPb.getUser                          avgt       3   3.391 ± 0.405   ms/op
ClientPb.listUser                         avgt       3   3.932 ± 1.837   ms/op
ClientPb.createUser                     sample  275546   3.482 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.737           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.701           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.256           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.212           ms/op
ClientPb.existUser                      sample  285657   3.357 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.885           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.342           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.994           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.571           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.720           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.360           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.574           ms/op
ClientPb.getUser                        sample  278185   3.449 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.356           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.314           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.431           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.384           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.032           ms/op
ClientPb.listUser                       sample  236926   4.051 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.384           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.777           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.128           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.585           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.498           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.600           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.228           ms/op
