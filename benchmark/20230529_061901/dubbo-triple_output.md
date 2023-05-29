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
# Warmup Iteration   1: 1.897 ops/ms
# Warmup Iteration   2: 5.543 ops/ms
# Warmup Iteration   3: 8.295 ops/ms
Iteration   1: 9.312 ops/ms
Iteration   2: 9.095 ops/ms
Iteration   3: 9.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.158 ±(99.9%) 2.457 ops/ms [Average]
  (min, avg, max) = (9.065, 9.158, 9.312), stdev = 0.135
  CI (99.9%): [6.700, 11.615] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.030 ops/ms
# Warmup Iteration   2: 8.238 ops/ms
# Warmup Iteration   3: 9.275 ops/ms
Iteration   1: 9.740 ops/ms
Iteration   2: 9.883 ops/ms
Iteration   3: 9.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.676 ±(99.9%) 4.468 ops/ms [Average]
  (min, avg, max) = (9.406, 9.676, 9.883), stdev = 0.245
  CI (99.9%): [5.208, 14.144] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.619 ops/ms
# Warmup Iteration   2: 8.100 ops/ms
# Warmup Iteration   3: 9.003 ops/ms
Iteration   1: 9.358 ops/ms
Iteration   2: 8.990 ops/ms
Iteration   3: 8.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.998 ±(99.9%) 6.505 ops/ms [Average]
  (min, avg, max) = (8.645, 8.998, 9.358), stdev = 0.357
  CI (99.9%): [2.493, 15.503] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.444 ops/ms
# Warmup Iteration   2: 7.098 ops/ms
# Warmup Iteration   3: 7.644 ops/ms
Iteration   1: 7.645 ops/ms
Iteration   2: 7.957 ops/ms
Iteration   3: 8.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.884 ±(99.9%) 3.877 ops/ms [Average]
  (min, avg, max) = (7.645, 7.884, 8.050), stdev = 0.213
  CI (99.9%): [4.007, 11.761] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.615 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.144 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.003 ms/op
Iteration   1: 3.450 ±(99.9%) 0.006 ms/op
Iteration   2: 3.383 ±(99.9%) 0.010 ms/op
Iteration   3: 3.517 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.450 ±(99.9%) 1.223 ms/op [Average]
  (min, avg, max) = (3.383, 3.450, 3.517), stdev = 0.067
  CI (99.9%): [2.227, 4.673] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.370 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.644 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.007 ms/op
Iteration   1: 3.350 ±(99.9%) 0.008 ms/op
Iteration   2: 3.305 ±(99.9%) 0.011 ms/op
Iteration   3: 3.362 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.339 ±(99.9%) 0.541 ms/op [Average]
  (min, avg, max) = (3.305, 3.339, 3.362), stdev = 0.030
  CI (99.9%): [2.798, 3.880] (assumes normal distribution)


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
# Warmup Iteration   1: 9.923 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.796 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.531 ±(99.9%) 0.005 ms/op
Iteration   1: 3.574 ±(99.9%) 0.007 ms/op
Iteration   2: 3.409 ±(99.9%) 0.008 ms/op
Iteration   3: 3.450 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.477 ±(99.9%) 1.568 ms/op [Average]
  (min, avg, max) = (3.409, 3.477, 3.574), stdev = 0.086
  CI (99.9%): [1.910, 5.045] (assumes normal distribution)


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
# Warmup Iteration   1: 11.412 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.381 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.278 ±(99.9%) 0.008 ms/op
Iteration   1: 4.104 ±(99.9%) 0.008 ms/op
Iteration   2: 4.053 ±(99.9%) 0.013 ms/op
Iteration   3: 3.878 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.012 ±(99.9%) 2.164 ms/op [Average]
  (min, avg, max) = (3.878, 4.012, 4.104), stdev = 0.119
  CI (99.9%): [1.847, 6.176] (assumes normal distribution)


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
# Warmup Iteration   1: 10.695 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.241 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.014 ms/op
Iteration   1: 3.530 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.162 ms/op
                 createUser·p0.95:   4.484 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  21.603 ms/op
                 createUser·p0.9999: 28.246 ms/op
                 createUser·p1.00:   29.131 ms/op

Iteration   2: 3.459 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   5.929 ms/op
                 createUser·p0.999:  23.898 ms/op
                 createUser·p0.9999: 27.157 ms/op
                 createUser·p1.00:   27.689 ms/op

Iteration   3: 3.541 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.702 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  22.237 ms/op
                 createUser·p0.9999: 28.704 ms/op
                 createUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273518
  mean =      3.510 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5965 
    [ 2.500,  5.000) = 260475 
    [ 5.000,  7.500) = 6148 
    [ 7.500, 10.000) = 493 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 136 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     22.036 ms/op
     p(99.9900) =     28.246 ms/op
     p(99.9990) =     29.558 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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
# Warmup Iteration   1: 9.001 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.663 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.012 ms/op
Iteration   1: 3.390 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.038 ms/op
                 existUser·p0.999:  21.028 ms/op
                 existUser·p0.9999: 24.533 ms/op
                 existUser·p1.00:   25.428 ms/op

Iteration   2: 3.302 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.610 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  8.621 ms/op
                 existUser·p0.9999: 35.521 ms/op
                 existUser·p1.00:   37.552 ms/op

Iteration   3: 3.343 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.776 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   5.617 ms/op
                 existUser·p0.999:  23.468 ms/op
                 existUser·p0.9999: 36.241 ms/op
                 existUser·p1.00:   37.552 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287077
  mean =      3.344 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3544 
    [ 2.500,  5.000) = 277429 
    [ 5.000,  7.500) = 5437 
    [ 7.500, 10.000) = 316 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     11.698 ms/op
     p(99.9900) =     35.521 ms/op
     p(99.9990) =     37.438 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


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
# Warmup Iteration   1: 10.015 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.859 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.013 ms/op
Iteration   1: 3.405 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  22.086 ms/op
                 getUser·p0.9999: 24.600 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   2: 3.518 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.364 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.933 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   6.460 ms/op
                 getUser·p0.999:  24.046 ms/op
                 getUser·p0.9999: 26.984 ms/op
                 getUser·p1.00:   27.623 ms/op

Iteration   3: 3.467 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  19.378 ms/op
                 getUser·p0.9999: 29.642 ms/op
                 getUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277234
  mean =      3.463 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6478 
    [ 2.500,  5.000) = 262875 
    [ 5.000,  7.500) = 6538 
    [ 7.500, 10.000) = 802 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.364 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     20.164 ms/op
     p(99.9900) =     28.428 ms/op
     p(99.9990) =     30.038 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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
# Warmup Iteration   1: 12.319 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.692 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.238 ±(99.9%) 0.015 ms/op
Iteration   1: 4.099 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.726 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  22.441 ms/op
                 listUser·p0.9999: 29.975 ms/op
                 listUser·p1.00:   32.145 ms/op

Iteration   2: 4.098 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  17.070 ms/op
                 listUser·p0.9999: 18.579 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   3: 3.987 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.056 ms/op
                 listUser·p0.999:  15.188 ms/op
                 listUser·p0.9999: 17.007 ms/op
                 listUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236258
  mean =      4.060 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 228312 
    [ 5.000,  7.500) = 6058 
    [ 7.500, 10.000) = 1037 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 227 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.726 ms/op
     p(50.0000) =      3.965 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     29.123 ms/op
     p(99.9990) =     32.044 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.158 ± 2.457  ops/ms
ClientPb.existUser                       thrpt       3   9.676 ± 4.468  ops/ms
ClientPb.getUser                         thrpt       3   8.998 ± 6.505  ops/ms
ClientPb.listUser                        thrpt       3   7.884 ± 3.877  ops/ms
ClientPb.createUser                       avgt       3   3.450 ± 1.223   ms/op
ClientPb.existUser                        avgt       3   3.339 ± 0.541   ms/op
ClientPb.getUser                          avgt       3   3.477 ± 1.568   ms/op
ClientPb.listUser                         avgt       3   4.012 ± 2.164   ms/op
ClientPb.createUser                     sample  273518   3.510 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.741           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.096           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.415           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.070           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.036           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.246           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.343           ms/op
ClientPb.existUser                      sample  287077   3.344 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.356           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.808           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.698           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.521           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.552           ms/op
ClientPb.getUser                        sample  277234   3.463 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.364           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.398           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.164           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.428           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.343           ms/op
ClientPb.listUser                       sample  236258   4.060 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.726           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.965           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.111           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.941           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.123           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.145           ms/op
