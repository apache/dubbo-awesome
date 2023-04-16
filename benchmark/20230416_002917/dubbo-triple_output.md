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
# Warmup Iteration   1: 2.325 ops/ms
# Warmup Iteration   2: 5.674 ops/ms
# Warmup Iteration   3: 8.968 ops/ms
Iteration   1: 9.120 ops/ms
Iteration   2: 9.427 ops/ms
Iteration   3: 9.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.274 ±(99.9%) 2.803 ops/ms [Average]
  (min, avg, max) = (9.120, 9.274, 9.427), stdev = 0.154
  CI (99.9%): [6.470, 12.077] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.287 ops/ms
# Warmup Iteration   2: 8.751 ops/ms
# Warmup Iteration   3: 9.349 ops/ms
Iteration   1: 9.719 ops/ms
Iteration   2: 9.812 ops/ms
Iteration   3: 9.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.712 ±(99.9%) 1.904 ops/ms [Average]
  (min, avg, max) = (9.604, 9.712, 9.812), stdev = 0.104
  CI (99.9%): [7.808, 11.615] (assumes normal distribution)


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
# Warmup Iteration   1: 3.076 ops/ms
# Warmup Iteration   2: 8.904 ops/ms
# Warmup Iteration   3: 9.152 ops/ms
Iteration   1: 9.446 ops/ms
Iteration   2: 9.575 ops/ms
Iteration   3: 9.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.459 ±(99.9%) 2.016 ops/ms [Average]
  (min, avg, max) = (9.355, 9.459, 9.575), stdev = 0.111
  CI (99.9%): [7.443, 11.475] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.031 ops/ms
# Warmup Iteration   2: 7.445 ops/ms
# Warmup Iteration   3: 7.907 ops/ms
Iteration   1: 8.129 ops/ms
Iteration   2: 8.481 ops/ms
Iteration   3: 7.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.199 ±(99.9%) 4.636 ops/ms [Average]
  (min, avg, max) = (7.987, 8.199, 8.481), stdev = 0.254
  CI (99.9%): [3.563, 12.835] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.510 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.005 ms/op
Iteration   1: 3.544 ±(99.9%) 0.003 ms/op
Iteration   2: 3.411 ±(99.9%) 0.009 ms/op
Iteration   3: 3.368 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.441 ±(99.9%) 1.677 ms/op [Average]
  (min, avg, max) = (3.368, 3.441, 3.544), stdev = 0.092
  CI (99.9%): [1.764, 5.117] (assumes normal distribution)


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
# Warmup Iteration   1: 7.967 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.005 ms/op
Iteration   1: 3.359 ±(99.9%) 0.004 ms/op
Iteration   2: 3.197 ±(99.9%) 0.008 ms/op
Iteration   3: 3.321 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.292 ±(99.9%) 1.539 ms/op [Average]
  (min, avg, max) = (3.197, 3.292, 3.359), stdev = 0.084
  CI (99.9%): [1.753, 4.831] (assumes normal distribution)


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
# Warmup Iteration   1: 8.723 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.005 ms/op
Iteration   1: 3.366 ±(99.9%) 0.007 ms/op
Iteration   2: 3.408 ±(99.9%) 0.009 ms/op
Iteration   3: 3.411 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.395 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (3.366, 3.395, 3.411), stdev = 0.025
  CI (99.9%): [2.937, 3.853] (assumes normal distribution)


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
# Warmup Iteration   1: 8.936 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.386 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.003 ms/op
Iteration   1: 3.958 ±(99.9%) 0.008 ms/op
Iteration   2: 4.000 ±(99.9%) 0.006 ms/op
Iteration   3: 3.916 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.958 ±(99.9%) 0.767 ms/op [Average]
  (min, avg, max) = (3.916, 3.958, 4.000), stdev = 0.042
  CI (99.9%): [3.192, 4.725] (assumes normal distribution)


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
# Warmup Iteration   1: 9.871 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.203 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.701 ±(99.9%) 0.011 ms/op
Iteration   1: 3.498 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.291 ms/op
                 createUser·p0.999:  20.992 ms/op
                 createUser·p0.9999: 23.749 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   2: 3.497 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.747 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  22.298 ms/op
                 createUser·p0.9999: 25.085 ms/op
                 createUser·p1.00:   25.592 ms/op

Iteration   3: 3.550 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.125 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  22.282 ms/op
                 createUser·p0.9999: 28.246 ms/op
                 createUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272877
  mean =      3.515 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10847 
    [ 2.500,  5.000) = 254714 
    [ 5.000,  7.500) = 6072 
    [ 7.500, 10.000) = 783 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 142 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     21.270 ms/op
     p(99.9900) =     26.804 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 8.294 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.813 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.265 ±(99.9%) 0.007 ms/op
Iteration   1: 3.287 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.741 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  18.786 ms/op
                 existUser·p0.9999: 22.881 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   2: 3.341 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.033 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   6.078 ms/op
                 existUser·p0.999:  21.922 ms/op
                 existUser·p0.9999: 24.707 ms/op
                 existUser·p1.00:   25.428 ms/op

Iteration   3: 3.322 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.233 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  16.409 ms/op
                 existUser·p0.9999: 28.881 ms/op
                 existUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289263
  mean =      3.317 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11646 
    [ 2.500,  5.000) = 271076 
    [ 5.000,  7.500) = 5677 
    [ 7.500, 10.000) = 427 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     17.063 ms/op
     p(99.9900) =     27.268 ms/op
     p(99.9990) =     29.396 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 8.720 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.629 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.010 ms/op
Iteration   1: 3.452 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   7.029 ms/op
                 getUser·p0.999:  20.004 ms/op
                 getUser·p0.9999: 22.503 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   2: 3.478 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.368 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  22.020 ms/op
                 getUser·p0.9999: 25.506 ms/op
                 getUser·p1.00:   26.411 ms/op

Iteration   3: 3.451 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  20.098 ms/op
                 getUser·p0.9999: 26.730 ms/op
                 getUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277391
  mean =      3.460 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9094 
    [ 2.500,  5.000) = 261119 
    [ 5.000,  7.500) = 6032 
    [ 7.500, 10.000) = 685 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 66 

  Percentiles, ms/op:
      p(0.0000) =      0.368 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     20.172 ms/op
     p(99.9900) =     26.420 ms/op
     p(99.9990) =     26.812 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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
# Warmup Iteration   1: 10.669 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.555 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.164 ±(99.9%) 0.013 ms/op
Iteration   1: 4.101 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.771 ms/op
                 listUser·p0.999:  19.530 ms/op
                 listUser·p0.9999: 24.956 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   2: 3.960 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  14.670 ms/op
                 listUser·p0.9999: 16.808 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   3: 3.957 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.564 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  14.650 ms/op
                 listUser·p0.9999: 17.856 ms/op
                 listUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239475
  mean =      4.005 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 231772 
    [ 5.000,  7.500) = 5587 
    [ 7.500, 10.000) = 1417 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     15.385 ms/op
     p(99.9900) =     23.146 ms/op
     p(99.9990) =     25.646 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.274 ± 2.803  ops/ms
ClientPb.existUser                       thrpt       3   9.712 ± 1.904  ops/ms
ClientPb.getUser                         thrpt       3   9.459 ± 2.016  ops/ms
ClientPb.listUser                        thrpt       3   8.199 ± 4.636  ops/ms
ClientPb.createUser                       avgt       3   3.441 ± 1.677   ms/op
ClientPb.existUser                        avgt       3   3.292 ± 1.539   ms/op
ClientPb.getUser                          avgt       3   3.395 ± 0.458   ms/op
ClientPb.listUser                         avgt       3   3.958 ± 0.767   ms/op
ClientPb.createUser                     sample  272877   3.515 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.809           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.396           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.399           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.062           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.270           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.804           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.508           ms/op
ClientPb.existUser                      sample  289263   3.317 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.033           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.014           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.800           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.063           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.268           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.655           ms/op
ClientPb.getUser                        sample  277391   3.460 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.368           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.365           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.172           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.420           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.132           ms/op
ClientPb.listUser                       sample  239475   4.005 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.325           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.315           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.385           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.146           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.116           ms/op
