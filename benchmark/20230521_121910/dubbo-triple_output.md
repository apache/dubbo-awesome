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
# Warmup Iteration   1: 2.471 ops/ms
# Warmup Iteration   2: 6.212 ops/ms
# Warmup Iteration   3: 8.911 ops/ms
Iteration   1: 9.526 ops/ms
Iteration   2: 9.552 ops/ms
Iteration   3: 9.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.633 ±(99.9%) 2.978 ops/ms [Average]
  (min, avg, max) = (9.526, 9.633, 9.821), stdev = 0.163
  CI (99.9%): [6.655, 12.611] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.484 ops/ms
# Warmup Iteration   2: 9.478 ops/ms
# Warmup Iteration   3: 9.955 ops/ms
Iteration   1: 10.150 ops/ms
Iteration   2: 10.245 ops/ms
Iteration   3: 9.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.003 ±(99.9%) 6.209 ops/ms [Average]
  (min, avg, max) = (9.614, 10.003, 10.245), stdev = 0.340
  CI (99.9%): [3.794, 16.213] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.075 ops/ms
# Warmup Iteration   2: 8.372 ops/ms
# Warmup Iteration   3: 9.122 ops/ms
Iteration   1: 9.646 ops/ms
Iteration   2: 9.659 ops/ms
Iteration   3: 9.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.701 ±(99.9%) 1.538 ops/ms [Average]
  (min, avg, max) = (9.646, 9.701, 9.798), stdev = 0.084
  CI (99.9%): [8.164, 11.239] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.998 ops/ms
# Warmup Iteration   2: 7.494 ops/ms
# Warmup Iteration   3: 7.972 ops/ms
Iteration   1: 8.176 ops/ms
Iteration   2: 8.293 ops/ms
Iteration   3: 8.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.232 ±(99.9%) 1.069 ops/ms [Average]
  (min, avg, max) = (8.176, 8.232, 8.293), stdev = 0.059
  CI (99.9%): [7.163, 9.301] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.774 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.544 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.368 ±(99.9%) 0.001 ms/op
Iteration   1: 3.215 ±(99.9%) 0.011 ms/op
Iteration   2: 3.243 ±(99.9%) 0.004 ms/op
Iteration   3: 3.212 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.223 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (3.212, 3.223, 3.243), stdev = 0.017
  CI (99.9%): [2.908, 3.538] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.703 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.528 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.004 ms/op
Iteration   1: 3.017 ±(99.9%) 0.005 ms/op
Iteration   2: 3.084 ±(99.9%) 0.005 ms/op
Iteration   3: 3.054 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.052 ±(99.9%) 0.616 ms/op [Average]
  (min, avg, max) = (3.017, 3.052, 3.084), stdev = 0.034
  CI (99.9%): [2.436, 3.668] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.136 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.560 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.003 ms/op
Iteration   1: 3.256 ±(99.9%) 0.002 ms/op
Iteration   2: 3.373 ±(99.9%) 0.007 ms/op
Iteration   3: 3.206 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.278 ±(99.9%) 1.563 ms/op [Average]
  (min, avg, max) = (3.206, 3.278, 3.373), stdev = 0.086
  CI (99.9%): [1.715, 4.841] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.764 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.265 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.833 ±(99.9%) 0.007 ms/op
Iteration   1: 3.774 ±(99.9%) 0.006 ms/op
Iteration   2: 3.707 ±(99.9%) 0.012 ms/op
Iteration   3: 3.764 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.748 ±(99.9%) 0.666 ms/op [Average]
  (min, avg, max) = (3.707, 3.748, 3.774), stdev = 0.036
  CI (99.9%): [3.083, 4.414] (assumes normal distribution)


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
# Warmup Iteration   1: 8.297 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.009 ms/op
Iteration   1: 3.199 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.608 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  14.926 ms/op
                 createUser·p0.9999: 22.381 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   2: 3.187 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.356 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  10.543 ms/op
                 createUser·p0.9999: 23.560 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   3: 3.202 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.210 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  17.761 ms/op
                 createUser·p0.9999: 24.642 ms/op
                 createUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300284
  mean =      3.196 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17931 
    [ 2.500,  5.000) = 277539 
    [ 5.000,  7.500) = 3721 
    [ 7.500, 10.000) = 588 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      5.678 ms/op
     p(99.9000) =     17.194 ms/op
     p(99.9900) =     23.559 ms/op
     p(99.9990) =     25.263 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.756 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.460 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.008 ms/op
Iteration   1: 3.292 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.465 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  12.516 ms/op
                 existUser·p0.9999: 23.144 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   2: 3.371 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.537 ms/op
                 existUser·p0.999:  23.495 ms/op
                 existUser·p0.9999: 27.575 ms/op
                 existUser·p1.00:   28.475 ms/op

Iteration   3: 3.231 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.747 ms/op
                 existUser·p0.999:  9.946 ms/op
                 existUser·p0.9999: 23.003 ms/op
                 existUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290921
  mean =      3.297 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18248 
    [ 2.500,  5.000) = 267064 
    [ 5.000,  7.500) = 4741 
    [ 7.500, 10.000) = 553 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     11.746 ms/op
     p(99.9900) =     26.733 ms/op
     p(99.9990) =     28.174 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 8.686 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.686 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.008 ms/op
Iteration   1: 3.279 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  10.196 ms/op
                 getUser·p0.9999: 19.905 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   2: 3.246 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.380 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  12.596 ms/op
                 getUser·p0.9999: 22.413 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   3: 3.393 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   6.149 ms/op
                 getUser·p0.999:  16.050 ms/op
                 getUser·p0.9999: 22.891 ms/op
                 getUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290604
  mean =      3.305 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8354 
    [ 2.500,  5.000) = 274577 
    [ 5.000,  7.500) = 6708 
    [ 7.500, 10.000) = 608 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     12.596 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     23.331 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 9.417 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.352 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.011 ms/op
Iteration   1: 3.876 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.745 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  18.743 ms/op
                 listUser·p0.9999: 26.378 ms/op
                 listUser·p1.00:   29.557 ms/op

Iteration   2: 3.742 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 14.959 ms/op
                 listUser·p1.00:   15.466 ms/op

Iteration   3: 3.928 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  12.272 ms/op
                 listUser·p0.9999: 16.262 ms/op
                 listUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249246
  mean =      3.847 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 240481 
    [ 5.000,  7.500) = 6337 
    [ 7.500, 10.000) = 1767 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.745 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     14.529 ms/op
     p(99.9900) =     23.837 ms/op
     p(99.9990) =     28.419 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.633 ± 2.978  ops/ms
ClientPb.existUser                       thrpt       3  10.003 ± 6.209  ops/ms
ClientPb.getUser                         thrpt       3   9.701 ± 1.538  ops/ms
ClientPb.listUser                        thrpt       3   8.232 ± 1.069  ops/ms
ClientPb.createUser                       avgt       3   3.223 ± 0.315   ms/op
ClientPb.existUser                        avgt       3   3.052 ± 0.616   ms/op
ClientPb.getUser                          avgt       3   3.278 ± 1.563   ms/op
ClientPb.listUser                         avgt       3   3.748 ± 0.666   ms/op
ClientPb.createUser                     sample  300284   3.196 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.210           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.498           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.678           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.194           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.559           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.428           ms/op
ClientPb.existUser                      sample  290921   3.297 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.465           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.055           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.947           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.746           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.733           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.475           ms/op
ClientPb.getUser                        sample  290604   3.305 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.167           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.768           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.980           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.596           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.217           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.331           ms/op
ClientPb.listUser                       sample  249246   3.847 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.745           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.406           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.529           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.837           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.557           ms/op
