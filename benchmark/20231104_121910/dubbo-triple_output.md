# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.175 ops/ms
# Warmup Iteration   2: 4.986 ops/ms
# Warmup Iteration   3: 8.132 ops/ms
Iteration   1: 9.131 ops/ms
Iteration   2: 9.304 ops/ms
Iteration   3: 9.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.171 ±(99.9%) 2.141 ops/ms [Average]
  (min, avg, max) = (9.079, 9.171, 9.304), stdev = 0.117
  CI (99.9%): [7.031, 11.312] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.926 ops/ms
# Warmup Iteration   2: 8.924 ops/ms
# Warmup Iteration   3: 9.477 ops/ms
Iteration   1: 9.550 ops/ms
Iteration   2: 9.661 ops/ms
Iteration   3: 9.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.678 ±(99.9%) 2.499 ops/ms [Average]
  (min, avg, max) = (9.550, 9.678, 9.823), stdev = 0.137
  CI (99.9%): [7.179, 12.177] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.378 ops/ms
# Warmup Iteration   2: 8.590 ops/ms
# Warmup Iteration   3: 8.823 ops/ms
Iteration   1: 9.227 ops/ms
Iteration   2: 9.264 ops/ms
Iteration   3: 9.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.270 ±(99.9%) 0.832 ops/ms [Average]
  (min, avg, max) = (9.227, 9.270, 9.318), stdev = 0.046
  CI (99.9%): [8.438, 10.101] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.654 ops/ms
# Warmup Iteration   2: 7.253 ops/ms
# Warmup Iteration   3: 7.598 ops/ms
Iteration   1: 7.755 ops/ms
Iteration   2: 7.748 ops/ms
Iteration   3: 7.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.780 ±(99.9%) 0.893 ops/ms [Average]
  (min, avg, max) = (7.748, 7.780, 7.836), stdev = 0.049
  CI (99.9%): [6.887, 8.673] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.607 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.732 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.590 ±(99.9%) 0.006 ms/op
Iteration   1: 3.480 ±(99.9%) 0.004 ms/op
Iteration   2: 3.473 ±(99.9%) 0.003 ms/op
Iteration   3: 3.468 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.474 ±(99.9%) 0.116 ms/op [Average]
  (min, avg, max) = (3.468, 3.474, 3.480), stdev = 0.006
  CI (99.9%): [3.358, 3.590] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.587 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.003 ms/op
Iteration   1: 3.289 ±(99.9%) 0.003 ms/op
Iteration   2: 3.398 ±(99.9%) 0.005 ms/op
Iteration   3: 3.462 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.383 ±(99.9%) 1.597 ms/op [Average]
  (min, avg, max) = (3.289, 3.383, 3.462), stdev = 0.088
  CI (99.9%): [1.786, 4.980] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.525 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.424 ±(99.9%) 0.004 ms/op
Iteration   1: 3.478 ±(99.9%) 0.006 ms/op
Iteration   2: 3.380 ±(99.9%) 0.005 ms/op
Iteration   3: 3.404 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.421 ±(99.9%) 0.937 ms/op [Average]
  (min, avg, max) = (3.380, 3.421, 3.478), stdev = 0.051
  CI (99.9%): [2.484, 4.357] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.535 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.360 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.281 ±(99.9%) 0.004 ms/op
Iteration   1: 4.189 ±(99.9%) 0.004 ms/op
Iteration   2: 4.092 ±(99.9%) 0.007 ms/op
Iteration   3: 4.078 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.119 ±(99.9%) 1.105 ms/op [Average]
  (min, avg, max) = (4.078, 4.119, 4.189), stdev = 0.061
  CI (99.9%): [3.014, 5.225] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.445 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.851 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.010 ms/op
Iteration   1: 3.453 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.645 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  20.871 ms/op
                 createUser·p0.9999: 24.076 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   2: 3.531 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.202 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  22.635 ms/op
                 createUser·p0.9999: 25.227 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   3: 3.436 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  17.295 ms/op
                 createUser·p0.9999: 26.338 ms/op
                 createUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276488
  mean =      3.473 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3205 
    [ 2.500,  5.000) = 268392 
    [ 5.000,  7.500) = 3690 
    [ 7.500, 10.000) = 510 
    [10.000, 12.500) = 290 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 159 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     17.777 ms/op
     p(99.9900) =     25.395 ms/op
     p(99.9990) =     27.186 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.888 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.582 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.009 ms/op
Iteration   1: 3.427 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.722 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  7.462 ms/op
                 existUser·p0.9999: 23.309 ms/op
                 existUser·p1.00:   23.953 ms/op

Iteration   2: 3.384 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  21.297 ms/op
                 existUser·p0.9999: 24.528 ms/op
                 existUser·p1.00:   24.936 ms/op

Iteration   3: 3.353 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   6.906 ms/op
                 existUser·p0.999:  18.133 ms/op
                 existUser·p0.9999: 26.036 ms/op
                 existUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283324
  mean =      3.388 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6699 
    [ 2.500,  5.000) = 269811 
    [ 5.000,  7.500) = 5736 
    [ 7.500, 10.000) = 476 
    [10.000, 12.500) = 330 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     12.124 ms/op
     p(99.9900) =     24.936 ms/op
     p(99.9990) =     26.548 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.418 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.652 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.553 ±(99.9%) 0.010 ms/op
Iteration   1: 3.553 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.272 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.283 ms/op
                 getUser·p0.999:  20.807 ms/op
                 getUser·p0.9999: 23.429 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   2: 3.533 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.290 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.742 ms/op
                 getUser·p0.999:  9.262 ms/op
                 getUser·p0.9999: 26.247 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   3: 3.582 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   6.922 ms/op
                 getUser·p0.999:  19.356 ms/op
                 getUser·p0.9999: 30.640 ms/op
                 getUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269856
  mean =      3.556 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2803 
    [ 2.500,  5.000) = 257146 
    [ 5.000,  7.500) = 8776 
    [ 7.500, 10.000) = 709 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     17.564 ms/op
     p(99.9900) =     29.296 ms/op
     p(99.9990) =     30.976 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.465 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.431 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.013 ms/op
Iteration   1: 4.216 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   4.092 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  19.726 ms/op
                 listUser·p0.9999: 23.929 ms/op
                 listUser·p1.00:   24.412 ms/op

Iteration   2: 4.038 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.948 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  15.024 ms/op
                 listUser·p0.9999: 17.468 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   3: 4.097 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.519 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  14.973 ms/op
                 listUser·p0.9999: 16.079 ms/op
                 listUser·p1.00:   16.138 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233224
  mean =      4.116 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 224421 
    [ 5.000,  7.500) = 7213 
    [ 7.500, 10.000) = 837 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 321 
    [15.000, 17.500) = 186 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.663 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     15.221 ms/op
     p(99.9900) =     22.622 ms/op
     p(99.9990) =     24.281 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.171 ± 2.141  ops/ms
ClientPb.existUser                       thrpt       3   9.678 ± 2.499  ops/ms
ClientPb.getUser                         thrpt       3   9.270 ± 0.832  ops/ms
ClientPb.listUser                        thrpt       3   7.780 ± 0.893  ops/ms
ClientPb.createUser                       avgt       3   3.474 ± 0.116   ms/op
ClientPb.existUser                        avgt       3   3.383 ± 1.597   ms/op
ClientPb.getUser                          avgt       3   3.421 ± 0.937   ms/op
ClientPb.listUser                         avgt       3   4.119 ± 1.105   ms/op
ClientPb.createUser                     sample  276488   3.473 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.954           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.988           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.777           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.395           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.394           ms/op
ClientPb.existUser                      sample  283324   3.388 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.122           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.178           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.038           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.124           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.936           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.903           ms/op
ClientPb.getUser                        sample  269856   3.556 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.272           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.408           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.767           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.564           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.296           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.195           ms/op
ClientPb.listUser                       sample  233224   4.116 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.663           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.922           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.221           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.622           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.412           ms/op
