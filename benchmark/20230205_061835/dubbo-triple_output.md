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
# Warmup Iteration   1: 2.158 ops/ms
# Warmup Iteration   2: 5.465 ops/ms
# Warmup Iteration   3: 8.439 ops/ms
Iteration   1: 9.512 ops/ms
Iteration   2: 9.277 ops/ms
Iteration   3: 9.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.390 ±(99.9%) 2.154 ops/ms [Average]
  (min, avg, max) = (9.277, 9.390, 9.512), stdev = 0.118
  CI (99.9%): [7.236, 11.544] (assumes normal distribution)


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
# Warmup Iteration   1: 3.441 ops/ms
# Warmup Iteration   2: 9.233 ops/ms
# Warmup Iteration   3: 9.294 ops/ms
Iteration   1: 10.201 ops/ms
Iteration   2: 10.015 ops/ms
Iteration   3: 9.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.996 ±(99.9%) 3.926 ops/ms [Average]
  (min, avg, max) = (9.772, 9.996, 10.201), stdev = 0.215
  CI (99.9%): [6.070, 13.922] (assumes normal distribution)


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
# Warmup Iteration   1: 3.492 ops/ms
# Warmup Iteration   2: 8.723 ops/ms
# Warmup Iteration   3: 9.361 ops/ms
Iteration   1: 9.370 ops/ms
Iteration   2: 9.610 ops/ms
Iteration   3: 9.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.469 ±(99.9%) 2.290 ops/ms [Average]
  (min, avg, max) = (9.370, 9.469, 9.610), stdev = 0.126
  CI (99.9%): [7.179, 11.759] (assumes normal distribution)


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
# Warmup Iteration   1: 3.122 ops/ms
# Warmup Iteration   2: 7.570 ops/ms
# Warmup Iteration   3: 7.947 ops/ms
Iteration   1: 8.091 ops/ms
Iteration   2: 8.264 ops/ms
Iteration   3: 8.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.126 ±(99.9%) 2.274 ops/ms [Average]
  (min, avg, max) = (8.022, 8.126, 8.264), stdev = 0.125
  CI (99.9%): [5.852, 10.401] (assumes normal distribution)


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
# Warmup Iteration   1: 8.299 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.009 ms/op
Iteration   1: 3.310 ±(99.9%) 0.004 ms/op
Iteration   2: 3.330 ±(99.9%) 0.009 ms/op
Iteration   3: 3.327 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.323 ±(99.9%) 0.195 ms/op [Average]
  (min, avg, max) = (3.310, 3.323, 3.330), stdev = 0.011
  CI (99.9%): [3.127, 3.518] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.555 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.456 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.006 ms/op
Iteration   1: 3.309 ±(99.9%) 0.005 ms/op
Iteration   2: 3.308 ±(99.9%) 0.007 ms/op
Iteration   3: 3.336 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.318 ±(99.9%) 0.293 ms/op [Average]
  (min, avg, max) = (3.308, 3.318, 3.336), stdev = 0.016
  CI (99.9%): [3.025, 3.611] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.337 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.533 ±(99.9%) 0.003 ms/op
Iteration   1: 3.392 ±(99.9%) 0.011 ms/op
Iteration   2: 3.317 ±(99.9%) 0.008 ms/op
Iteration   3: 3.401 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.370 ±(99.9%) 0.848 ms/op [Average]
  (min, avg, max) = (3.317, 3.370, 3.401), stdev = 0.046
  CI (99.9%): [2.522, 4.218] (assumes normal distribution)


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
# Warmup Iteration   1: 10.222 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.011 ms/op
Iteration   1: 3.824 ±(99.9%) 0.015 ms/op
Iteration   2: 3.912 ±(99.9%) 0.008 ms/op
Iteration   3: 3.943 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.893 ±(99.9%) 1.126 ms/op [Average]
  (min, avg, max) = (3.824, 3.893, 3.943), stdev = 0.062
  CI (99.9%): [2.767, 5.019] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.891 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.951 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.010 ms/op
Iteration   1: 3.375 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.401 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  19.972 ms/op
                 createUser·p0.9999: 22.646 ms/op
                 createUser·p1.00:   23.167 ms/op

Iteration   2: 3.413 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  22.100 ms/op
                 createUser·p0.9999: 24.499 ms/op
                 createUser·p1.00:   25.231 ms/op

Iteration   3: 3.291 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.278 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  16.728 ms/op
                 createUser·p0.9999: 23.757 ms/op
                 createUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285548
  mean =      3.359 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19551 
    [ 2.500,  5.000) = 259716 
    [ 5.000,  7.500) = 5089 
    [ 7.500, 10.000) = 665 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.172 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     16.938 ms/op
     p(99.9900) =     23.724 ms/op
     p(99.9990) =     24.703 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 7.637 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.554 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.009 ms/op
Iteration   1: 3.242 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.434 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  9.503 ms/op
                 existUser·p0.9999: 21.725 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   2: 3.165 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   5.318 ms/op
                 existUser·p0.999:  9.546 ms/op
                 existUser·p0.9999: 24.543 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   3: 3.367 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  20.485 ms/op
                 existUser·p0.9999: 25.723 ms/op
                 existUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294764
  mean =      3.256 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4786 
    [ 2.500,  5.000) = 285096 
    [ 5.000,  7.500) = 4259 
    [ 7.500, 10.000) = 262 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     12.157 ms/op
     p(99.9900) =     24.626 ms/op
     p(99.9990) =     26.099 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 9.191 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.570 ±(99.9%) 0.013 ms/op
Iteration   1: 3.527 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.166 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  20.349 ms/op
                 getUser·p0.9999: 22.411 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   2: 3.478 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.454 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.018 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  21.793 ms/op
                 getUser·p0.9999: 24.360 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   3: 3.531 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.767 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.267 ms/op
                 getUser·p0.999:  19.617 ms/op
                 getUser·p0.9999: 26.749 ms/op
                 getUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273294
  mean =      3.512 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10976 
    [ 2.500,  5.000) = 253579 
    [ 5.000,  7.500) = 7613 
    [ 7.500, 10.000) = 668 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 160 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     20.175 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     27.399 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 9.441 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.244 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.014 ms/op
Iteration   1: 4.026 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.843 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   7.814 ms/op
                 listUser·p0.999:  20.299 ms/op
                 listUser·p0.9999: 22.710 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   2: 4.007 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.872 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  15.340 ms/op
                 listUser·p0.9999: 17.663 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   3: 4.087 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  15.344 ms/op
                 listUser·p0.9999: 20.125 ms/op
                 listUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237651
  mean =      4.040 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 227655 
    [ 5.000,  7.500) = 7307 
    [ 7.500, 10.000) = 1813 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 208 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.843 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.700 ms/op
     p(99.9000) =     16.373 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     22.913 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.390 ± 2.154  ops/ms
ClientPb.existUser                       thrpt       3   9.996 ± 3.926  ops/ms
ClientPb.getUser                         thrpt       3   9.469 ± 2.290  ops/ms
ClientPb.listUser                        thrpt       3   8.126 ± 2.274  ops/ms
ClientPb.createUser                       avgt       3   3.323 ± 0.195   ms/op
ClientPb.existUser                        avgt       3   3.318 ± 0.293   ms/op
ClientPb.getUser                          avgt       3   3.370 ± 0.848   ms/op
ClientPb.listUser                         avgt       3   3.893 ± 1.126   ms/op
ClientPb.createUser                     sample  285548   3.359 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.204           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.172           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.718           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.938           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.724           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.231           ms/op
ClientPb.existUser                      sample  294764   3.256 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.059           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.920           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.489           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.157           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.626           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.263           ms/op
ClientPb.getUser                        sample  273294   3.512 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.959           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.275           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.175           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.428           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.623           ms/op
ClientPb.listUser                       sample  237651   4.040 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.843           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.700           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.373           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.151           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.003           ms/op
