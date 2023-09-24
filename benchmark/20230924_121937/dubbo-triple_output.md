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
# Warmup Iteration   1: 2.289 ops/ms
# Warmup Iteration   2: 5.495 ops/ms
# Warmup Iteration   3: 8.621 ops/ms
Iteration   1: 9.209 ops/ms
Iteration   2: 9.374 ops/ms
Iteration   3: 9.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.400 ±(99.9%) 3.734 ops/ms [Average]
  (min, avg, max) = (9.209, 9.400, 9.616), stdev = 0.205
  CI (99.9%): [5.666, 13.134] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.823 ops/ms
# Warmup Iteration   2: 9.100 ops/ms
# Warmup Iteration   3: 9.419 ops/ms
Iteration   1: 9.615 ops/ms
Iteration   2: 9.620 ops/ms
Iteration   3: 9.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.580 ±(99.9%) 1.204 ops/ms [Average]
  (min, avg, max) = (9.504, 9.580, 9.620), stdev = 0.066
  CI (99.9%): [8.376, 10.784] (assumes normal distribution)


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
# Warmup Iteration   1: 3.130 ops/ms
# Warmup Iteration   2: 8.823 ops/ms
# Warmup Iteration   3: 9.346 ops/ms
Iteration   1: 9.115 ops/ms
Iteration   2: 9.269 ops/ms
Iteration   3: 9.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.257 ±(99.9%) 2.502 ops/ms [Average]
  (min, avg, max) = (9.115, 9.257, 9.389), stdev = 0.137
  CI (99.9%): [6.756, 11.759] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.996 ops/ms
# Warmup Iteration   2: 7.232 ops/ms
# Warmup Iteration   3: 7.689 ops/ms
Iteration   1: 7.682 ops/ms
Iteration   2: 7.660 ops/ms
Iteration   3: 7.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.662 ±(99.9%) 0.348 ops/ms [Average]
  (min, avg, max) = (7.645, 7.662, 7.682), stdev = 0.019
  CI (99.9%): [7.314, 8.010] (assumes normal distribution)


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
# Warmup Iteration   1: 10.184 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.005 ms/op
Iteration   1: 3.523 ±(99.9%) 0.002 ms/op
Iteration   2: 3.371 ±(99.9%) 0.006 ms/op
Iteration   3: 3.306 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.400 ±(99.9%) 2.036 ms/op [Average]
  (min, avg, max) = (3.306, 3.400, 3.523), stdev = 0.112
  CI (99.9%): [1.364, 5.436] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.970 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.519 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.004 ms/op
Iteration   1: 3.409 ±(99.9%) 0.006 ms/op
Iteration   2: 3.272 ±(99.9%) 0.006 ms/op
Iteration   3: 3.320 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.334 ±(99.9%) 1.265 ms/op [Average]
  (min, avg, max) = (3.272, 3.334, 3.409), stdev = 0.069
  CI (99.9%): [2.069, 4.599] (assumes normal distribution)


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
# Warmup Iteration   1: 10.498 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.824 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.006 ms/op
Iteration   1: 3.489 ±(99.9%) 0.003 ms/op
Iteration   2: 3.541 ±(99.9%) 0.003 ms/op
Iteration   3: 3.475 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.502 ±(99.9%) 0.633 ms/op [Average]
  (min, avg, max) = (3.475, 3.502, 3.541), stdev = 0.035
  CI (99.9%): [2.869, 4.135] (assumes normal distribution)


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
# Warmup Iteration   1: 9.324 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.256 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.285 ±(99.9%) 0.006 ms/op
Iteration   1: 4.117 ±(99.9%) 0.005 ms/op
Iteration   2: 4.118 ±(99.9%) 0.005 ms/op
Iteration   3: 4.024 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.087 ±(99.9%) 0.986 ms/op [Average]
  (min, avg, max) = (4.024, 4.087, 4.118), stdev = 0.054
  CI (99.9%): [3.100, 5.073] (assumes normal distribution)


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
# Warmup Iteration   1: 9.885 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.959 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.010 ms/op
Iteration   1: 3.429 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.360 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  19.348 ms/op
                 createUser·p0.9999: 22.839 ms/op
                 createUser·p1.00:   24.117 ms/op

Iteration   2: 3.350 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  21.282 ms/op
                 createUser·p0.9999: 24.110 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   3: 3.346 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  17.171 ms/op
                 createUser·p0.9999: 24.737 ms/op
                 createUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284290
  mean =      3.375 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5345 
    [ 2.500,  5.000) = 274184 
    [ 5.000,  7.500) = 3949 
    [ 7.500, 10.000) = 253 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     24.314 ms/op
     p(99.9990) =     24.929 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


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
# Warmup Iteration   1: 7.584 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.491 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.355 ±(99.9%) 0.009 ms/op
Iteration   1: 3.348 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  11.526 ms/op
                 existUser·p0.9999: 22.100 ms/op
                 existUser·p1.00:   23.003 ms/op

Iteration   2: 3.326 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.266 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  18.943 ms/op
                 existUser·p0.9999: 27.485 ms/op
                 existUser·p1.00:   30.474 ms/op

Iteration   3: 3.350 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  18.959 ms/op
                 existUser·p0.9999: 25.592 ms/op
                 existUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287096
  mean =      3.341 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12277 
    [ 2.500,  5.000) = 269472 
    [ 5.000,  7.500) = 4319 
    [ 7.500, 10.000) = 489 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     12.321 ms/op
     p(99.9900) =     26.833 ms/op
     p(99.9990) =     30.229 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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
# Warmup Iteration   1: 8.603 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.698 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.570 ±(99.9%) 0.012 ms/op
Iteration   1: 3.531 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.418 ms/op
                 getUser·p0.999:  20.134 ms/op
                 getUser·p0.9999: 22.801 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   2: 3.477 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.300 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  20.711 ms/op
                 getUser·p0.9999: 23.095 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   3: 3.503 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.468 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  18.493 ms/op
                 getUser·p0.9999: 24.083 ms/op
                 getUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273803
  mean =      3.503 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3777 
    [ 2.500,  5.000) = 263145 
    [ 5.000,  7.500) = 5885 
    [ 7.500, 10.000) = 454 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 175 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     24.462 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 12.126 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.732 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.382 ±(99.9%) 0.013 ms/op
Iteration   1: 4.240 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.561 ms/op
                 listUser·p0.50:   4.112 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   7.553 ms/op
                 listUser·p0.999:  19.927 ms/op
                 listUser·p0.9999: 22.902 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   2: 4.196 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.052 ms/op
                 listUser·p0.50:   4.076 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  15.089 ms/op
                 listUser·p0.9999: 16.855 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   3: 4.070 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  13.976 ms/op
                 listUser·p0.9999: 17.306 ms/op
                 listUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230278
  mean =      4.167 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 219021 
    [ 5.000,  7.500) = 9226 
    [ 7.500, 10.000) = 1142 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 299 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.561 ms/op
     p(50.0000) =      4.002 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     15.446 ms/op
     p(99.9900) =     21.626 ms/op
     p(99.9990) =     23.508 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.400 ± 3.734  ops/ms
ClientPb.existUser                       thrpt       3   9.580 ± 1.204  ops/ms
ClientPb.getUser                         thrpt       3   9.257 ± 2.502  ops/ms
ClientPb.listUser                        thrpt       3   7.662 ± 0.348  ops/ms
ClientPb.createUser                       avgt       3   3.400 ± 2.036   ms/op
ClientPb.existUser                        avgt       3   3.334 ± 1.265   ms/op
ClientPb.getUser                          avgt       3   3.502 ± 0.633   ms/op
ClientPb.listUser                         avgt       3   4.087 ± 0.986   ms/op
ClientPb.createUser                     sample  284290   3.375 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.874           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.710           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.514           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.314           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.247           ms/op
ClientPb.existUser                      sample  287096   3.341 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.744           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.874           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.321           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.833           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.474           ms/op
ClientPb.getUser                        sample  273803   3.503 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.227           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.226           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.333           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.331           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.838           ms/op
ClientPb.listUser                       sample  230278   4.167 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.561           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.989           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.266           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.446           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.626           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.986           ms/op
