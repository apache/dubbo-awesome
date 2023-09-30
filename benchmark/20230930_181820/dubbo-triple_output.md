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
# Warmup Iteration   1: 2.025 ops/ms
# Warmup Iteration   2: 5.531 ops/ms
# Warmup Iteration   3: 8.443 ops/ms
Iteration   1: 9.006 ops/ms
Iteration   2: 9.261 ops/ms
Iteration   3: 9.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.111 ±(99.9%) 2.435 ops/ms [Average]
  (min, avg, max) = (9.006, 9.111, 9.261), stdev = 0.133
  CI (99.9%): [6.676, 11.546] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.884 ops/ms
# Warmup Iteration   2: 8.563 ops/ms
# Warmup Iteration   3: 9.515 ops/ms
Iteration   1: 9.499 ops/ms
Iteration   2: 9.644 ops/ms
Iteration   3: 9.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.442 ±(99.9%) 4.281 ops/ms [Average]
  (min, avg, max) = (9.185, 9.442, 9.644), stdev = 0.235
  CI (99.9%): [5.161, 13.723] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.790 ops/ms
# Warmup Iteration   2: 8.465 ops/ms
# Warmup Iteration   3: 9.248 ops/ms
Iteration   1: 9.282 ops/ms
Iteration   2: 9.222 ops/ms
Iteration   3: 9.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.213 ±(99.9%) 1.335 ops/ms [Average]
  (min, avg, max) = (9.136, 9.213, 9.282), stdev = 0.073
  CI (99.9%): [7.879, 10.548] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.676 ops/ms
# Warmup Iteration   2: 7.317 ops/ms
# Warmup Iteration   3: 7.733 ops/ms
Iteration   1: 7.476 ops/ms
Iteration   2: 7.900 ops/ms
Iteration   3: 7.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.729 ±(99.9%) 4.082 ops/ms [Average]
  (min, avg, max) = (7.476, 7.729, 7.900), stdev = 0.224
  CI (99.9%): [3.648, 11.811] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.346 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.720 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.005 ms/op
Iteration   1: 3.516 ±(99.9%) 0.008 ms/op
Iteration   2: 3.476 ±(99.9%) 0.004 ms/op
Iteration   3: 3.500 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.497 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (3.476, 3.497, 3.516), stdev = 0.020
  CI (99.9%): [3.124, 3.871] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.602 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.005 ms/op
Iteration   1: 3.387 ±(99.9%) 0.005 ms/op
Iteration   2: 3.316 ±(99.9%) 0.006 ms/op
Iteration   3: 3.356 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.353 ±(99.9%) 0.653 ms/op [Average]
  (min, avg, max) = (3.316, 3.353, 3.387), stdev = 0.036
  CI (99.9%): [2.700, 4.006] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 10.745 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.854 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.006 ms/op
Iteration   1: 3.606 ±(99.9%) 0.006 ms/op
Iteration   2: 3.564 ±(99.9%) 0.005 ms/op
Iteration   3: 3.477 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.549 ±(99.9%) 1.197 ms/op [Average]
  (min, avg, max) = (3.477, 3.549, 3.606), stdev = 0.066
  CI (99.9%): [2.353, 4.746] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.802 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.361 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.201 ±(99.9%) 0.006 ms/op
Iteration   1: 4.132 ±(99.9%) 0.007 ms/op
Iteration   2: 4.060 ±(99.9%) 0.007 ms/op
Iteration   3: 4.159 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.117 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (4.060, 4.117, 4.159), stdev = 0.051
  CI (99.9%): [3.178, 5.056] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.524 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.964 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.784 ±(99.9%) 0.014 ms/op
Iteration   1: 3.464 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.571 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   6.660 ms/op
                 createUser·p0.999:  19.520 ms/op
                 createUser·p0.9999: 21.932 ms/op
                 createUser·p1.00:   22.610 ms/op

Iteration   2: 3.570 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   6.717 ms/op
                 createUser·p0.999:  12.059 ms/op
                 createUser·p0.9999: 24.741 ms/op
                 createUser·p1.00:   27.820 ms/op

Iteration   3: 3.581 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.988 ms/op
                 createUser·p0.999:  22.231 ms/op
                 createUser·p0.9999: 29.458 ms/op
                 createUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271219
  mean =      3.538 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5629 
    [ 2.500,  5.000) = 256619 
    [ 5.000,  7.500) = 7632 
    [ 7.500, 10.000) = 642 
    [10.000, 12.500) = 256 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.941 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     19.988 ms/op
     p(99.9900) =     27.820 ms/op
     p(99.9990) =     29.950 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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
# Warmup Iteration   1: 7.236 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.485 ±(99.9%) 0.011 ms/op
Iteration   1: 3.460 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.415 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   4.014 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   6.562 ms/op
                 existUser·p0.999:  12.815 ms/op
                 existUser·p0.9999: 23.282 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   2: 3.383 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.329 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   6.775 ms/op
                 existUser·p0.999:  23.130 ms/op
                 existUser·p0.9999: 25.366 ms/op
                 existUser·p1.00:   26.083 ms/op

Iteration   3: 3.372 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.276 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   6.496 ms/op
                 existUser·p0.999:  18.321 ms/op
                 existUser·p0.9999: 26.657 ms/op
                 existUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281860
  mean =      3.404 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9626 
    [ 2.500,  5.000) = 263127 
    [ 5.000,  7.500) = 7999 
    [ 7.500, 10.000) = 602 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 132 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      0.329 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     15.809 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     27.909 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.552 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.640 ±(99.9%) 0.011 ms/op
Iteration   1: 3.585 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.649 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   5.784 ms/op
                 getUser·p0.99:   7.365 ms/op
                 getUser·p0.999:  20.734 ms/op
                 getUser·p0.9999: 22.547 ms/op
                 getUser·p1.00:   23.757 ms/op

Iteration   2: 3.434 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  22.605 ms/op
                 getUser·p0.9999: 24.838 ms/op
                 getUser·p1.00:   25.854 ms/op

Iteration   3: 3.465 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.493 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   7.258 ms/op
                 getUser·p0.999:  23.560 ms/op
                 getUser·p0.9999: 26.273 ms/op
                 getUser·p1.00:   38.142 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274632
  mean =      3.493 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6224 
    [ 2.500,  5.000) = 257400 
    [ 5.000,  7.500) = 9127 
    [ 7.500, 10.000) = 1280 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 171 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     21.135 ms/op
     p(99.9900) =     25.330 ms/op
     p(99.9990) =     29.729 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.116 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.423 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.270 ±(99.9%) 0.013 ms/op
Iteration   1: 4.171 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 23.187 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   2: 4.148 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.761 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.859 ms/op
                 listUser·p0.999:  15.973 ms/op
                 listUser·p0.9999: 28.668 ms/op
                 listUser·p1.00:   29.852 ms/op

Iteration   3: 4.165 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   8.339 ms/op
                 listUser·p0.999:  14.909 ms/op
                 listUser·p0.9999: 21.069 ms/op
                 listUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230573
  mean =      4.161 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 105 
    [ 2.500,  5.000) = 220401 
    [ 5.000,  7.500) = 7175 
    [ 7.500, 10.000) = 1833 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 385 
    [15.000, 17.500) = 251 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      8.045 ms/op
     p(99.9000) =     16.171 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     29.136 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.111 ± 2.435  ops/ms
ClientPb.existUser                       thrpt       3   9.442 ± 4.281  ops/ms
ClientPb.getUser                         thrpt       3   9.213 ± 1.335  ops/ms
ClientPb.listUser                        thrpt       3   7.729 ± 4.082  ops/ms
ClientPb.createUser                       avgt       3   3.497 ± 0.374   ms/op
ClientPb.existUser                        avgt       3   3.353 ± 0.653   ms/op
ClientPb.getUser                          avgt       3   3.549 ± 1.197   ms/op
ClientPb.listUser                         avgt       3   4.117 ± 0.939   ms/op
ClientPb.createUser                     sample  271219   3.538 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.941           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.416           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.808           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.988           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.820           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.704           ms/op
ClientPb.existUser                      sample  281860   3.404 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.329           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.578           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.809           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.428           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.017           ms/op
ClientPb.getUser                        sample  274632   3.493 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.190           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.318           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.399           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.053           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.135           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.330           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.142           ms/op
ClientPb.listUser                       sample  230573   4.161 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.846           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.014           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.045           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.171           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.331           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.852           ms/op
