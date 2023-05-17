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
# Warmup Iteration   1: 2.162 ops/ms
# Warmup Iteration   2: 5.655 ops/ms
# Warmup Iteration   3: 8.527 ops/ms
Iteration   1: 9.448 ops/ms
Iteration   2: 9.092 ops/ms
Iteration   3: 9.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.276 ±(99.9%) 3.246 ops/ms [Average]
  (min, avg, max) = (9.092, 9.276, 9.448), stdev = 0.178
  CI (99.9%): [6.030, 12.522] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.470 ops/ms
# Warmup Iteration   2: 8.810 ops/ms
# Warmup Iteration   3: 9.465 ops/ms
Iteration   1: 9.738 ops/ms
Iteration   2: 9.546 ops/ms
Iteration   3: 9.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.733 ±(99.9%) 3.379 ops/ms [Average]
  (min, avg, max) = (9.546, 9.733, 9.916), stdev = 0.185
  CI (99.9%): [6.355, 13.112] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.325 ops/ms
# Warmup Iteration   2: 8.371 ops/ms
# Warmup Iteration   3: 8.690 ops/ms
Iteration   1: 9.477 ops/ms
Iteration   2: 9.407 ops/ms
Iteration   3: 9.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.414 ±(99.9%) 1.105 ops/ms [Average]
  (min, avg, max) = (9.356, 9.414, 9.477), stdev = 0.061
  CI (99.9%): [8.308, 10.519] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.190 ops/ms
# Warmup Iteration   2: 7.539 ops/ms
# Warmup Iteration   3: 7.840 ops/ms
Iteration   1: 7.997 ops/ms
Iteration   2: 7.953 ops/ms
Iteration   3: 8.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.093 ±(99.9%) 3.770 ops/ms [Average]
  (min, avg, max) = (7.953, 8.093, 8.331), stdev = 0.207
  CI (99.9%): [4.324, 11.863] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.180 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.628 ±(99.9%) 0.009 ms/op
Iteration   1: 3.577 ±(99.9%) 0.003 ms/op
Iteration   2: 3.567 ±(99.9%) 0.004 ms/op
Iteration   3: 3.345 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.497 ±(99.9%) 2.390 ms/op [Average]
  (min, avg, max) = (3.345, 3.497, 3.577), stdev = 0.131
  CI (99.9%): [1.106, 5.887] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.141 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.550 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.005 ms/op
Iteration   1: 3.348 ±(99.9%) 0.009 ms/op
Iteration   2: 3.377 ±(99.9%) 0.005 ms/op
Iteration   3: 3.234 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.320 ±(99.9%) 1.384 ms/op [Average]
  (min, avg, max) = (3.234, 3.320, 3.377), stdev = 0.076
  CI (99.9%): [1.936, 4.703] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.520 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.711 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.004 ms/op
Iteration   1: 3.371 ±(99.9%) 0.007 ms/op
Iteration   2: 3.404 ±(99.9%) 0.004 ms/op
Iteration   3: 3.454 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.410 ±(99.9%) 0.754 ms/op [Average]
  (min, avg, max) = (3.371, 3.410, 3.454), stdev = 0.041
  CI (99.9%): [2.655, 4.164] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.050 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.384 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.014 ms/op
Iteration   1: 3.952 ±(99.9%) 0.010 ms/op
Iteration   2: 3.930 ±(99.9%) 0.011 ms/op
Iteration   3: 4.019 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.967 ±(99.9%) 0.849 ms/op [Average]
  (min, avg, max) = (3.930, 3.967, 4.019), stdev = 0.047
  CI (99.9%): [3.118, 4.816] (assumes normal distribution)


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
# Warmup Iteration   1: 8.492 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.010 ms/op
Iteration   1: 3.473 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.425 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  20.213 ms/op
                 createUser·p0.9999: 22.538 ms/op
                 createUser·p1.00:   22.938 ms/op

Iteration   2: 3.583 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.317 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  21.452 ms/op
                 createUser·p0.9999: 25.531 ms/op
                 createUser·p1.00:   27.820 ms/op

Iteration   3: 3.303 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.575 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  17.604 ms/op
                 createUser·p0.9999: 24.805 ms/op
                 createUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278202
  mean =      3.449 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10427 
    [ 2.500,  5.000) = 260924 
    [ 5.000,  7.500) = 5971 
    [ 7.500, 10.000) = 420 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     18.691 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     26.628 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 8.012 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.008 ms/op
Iteration   1: 3.266 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.548 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  11.768 ms/op
                 existUser·p0.9999: 21.634 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   2: 3.385 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  22.020 ms/op
                 existUser·p0.9999: 24.023 ms/op
                 existUser·p1.00:   26.411 ms/op

Iteration   3: 3.306 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.341 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  20.139 ms/op
                 existUser·p0.9999: 30.824 ms/op
                 existUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288837
  mean =      3.318 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15583 
    [ 2.500,  5.000) = 267294 
    [ 5.000,  7.500) = 5028 
    [ 7.500, 10.000) = 529 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     19.508 ms/op
     p(99.9900) =     29.364 ms/op
     p(99.9990) =     31.082 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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
# Warmup Iteration   1: 9.547 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.594 ±(99.9%) 0.012 ms/op
Iteration   1: 3.491 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  19.268 ms/op
                 getUser·p0.9999: 31.054 ms/op
                 getUser·p1.00:   31.752 ms/op

Iteration   2: 3.451 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.612 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   6.097 ms/op
                 getUser·p0.999:  23.123 ms/op
                 getUser·p0.9999: 30.441 ms/op
                 getUser·p1.00:   31.457 ms/op

Iteration   3: 3.457 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.520 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  17.642 ms/op
                 getUser·p0.9999: 27.401 ms/op
                 getUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276889
  mean =      3.466 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3037 
    [ 2.500,  5.000) = 265232 
    [ 5.000,  7.500) = 7431 
    [ 7.500, 10.000) = 723 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     17.960 ms/op
     p(99.9900) =     30.190 ms/op
     p(99.9990) =     31.629 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 10.258 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.345 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.928 ±(99.9%) 0.014 ms/op
Iteration   1: 4.072 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.896 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.933 ms/op
                 listUser·p0.99:   8.167 ms/op
                 listUser·p0.999:  19.588 ms/op
                 listUser·p0.9999: 23.794 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   2: 4.022 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.077 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  16.728 ms/op
                 listUser·p0.9999: 19.206 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   3: 3.833 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  15.172 ms/op
                 listUser·p0.9999: 16.450 ms/op
                 listUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241495
  mean =      3.973 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 230902 
    [ 5.000,  7.500) = 7937 
    [ 7.500, 10.000) = 1859 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 208 
    [15.000, 17.500) = 196 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.896 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     16.384 ms/op
     p(99.9900) =     22.967 ms/op
     p(99.9990) =     24.689 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.276 ± 3.246  ops/ms
ClientPb.existUser                       thrpt       3   9.733 ± 3.379  ops/ms
ClientPb.getUser                         thrpt       3   9.414 ± 1.105  ops/ms
ClientPb.listUser                        thrpt       3   8.093 ± 3.770  ops/ms
ClientPb.createUser                       avgt       3   3.497 ± 2.390   ms/op
ClientPb.existUser                        avgt       3   3.320 ± 1.384   ms/op
ClientPb.getUser                          avgt       3   3.410 ± 0.754   ms/op
ClientPb.listUser                         avgt       3   3.967 ± 0.849   ms/op
ClientPb.createUser                     sample  278202   3.449 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.317           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.026           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.964           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.691           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.133           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.820           ms/op
ClientPb.existUser                      sample  288837   3.318 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.341           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.104           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.579           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.508           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.364           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.261           ms/op
ClientPb.getUser                        sample  276889   3.466 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.233           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.318           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.185           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.960           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.190           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.752           ms/op
ClientPb.listUser                       sample  241495   3.973 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.896           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.768           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.602           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.384           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.967           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.231           ms/op
