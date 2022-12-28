# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.051 ops/ms
# Warmup Iteration   2: 5.882 ops/ms
# Warmup Iteration   3: 8.601 ops/ms
Iteration   1: 9.197 ops/ms
Iteration   2: 8.987 ops/ms
Iteration   3: 9.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.135 ±(99.9%) 2.352 ops/ms [Average]
  (min, avg, max) = (8.987, 9.135, 9.220), stdev = 0.129
  CI (99.9%): [6.783, 11.486] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.895 ops/ms
# Warmup Iteration   2: 8.799 ops/ms
# Warmup Iteration   3: 9.819 ops/ms
Iteration   1: 9.619 ops/ms
Iteration   2: 9.433 ops/ms
Iteration   3: 9.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.493 ±(99.9%) 1.987 ops/ms [Average]
  (min, avg, max) = (9.427, 9.493, 9.619), stdev = 0.109
  CI (99.9%): [7.507, 11.480] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.728 ops/ms
# Warmup Iteration   2: 7.335 ops/ms
# Warmup Iteration   3: 9.293 ops/ms
Iteration   1: 9.308 ops/ms
Iteration   2: 9.301 ops/ms
Iteration   3: 9.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.279 ±(99.9%) 0.791 ops/ms [Average]
  (min, avg, max) = (9.229, 9.279, 9.308), stdev = 0.043
  CI (99.9%): [8.488, 10.071] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.623 ops/ms
# Warmup Iteration   2: 7.150 ops/ms
# Warmup Iteration   3: 7.716 ops/ms
Iteration   1: 8.007 ops/ms
Iteration   2: 8.096 ops/ms
Iteration   3: 8.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.045 ±(99.9%) 0.839 ops/ms [Average]
  (min, avg, max) = (8.007, 8.045, 8.096), stdev = 0.046
  CI (99.9%): [7.206, 8.884] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.040 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.844 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.007 ms/op
Iteration   1: 3.393 ±(99.9%) 0.007 ms/op
Iteration   2: 3.477 ±(99.9%) 0.007 ms/op
Iteration   3: 3.515 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.462 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (3.393, 3.462, 3.515), stdev = 0.062
  CI (99.9%): [2.327, 4.597] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.990 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.655 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.610 ±(99.9%) 0.008 ms/op
Iteration   1: 3.354 ±(99.9%) 0.006 ms/op
Iteration   2: 3.415 ±(99.9%) 0.006 ms/op
Iteration   3: 3.249 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.339 ±(99.9%) 1.538 ms/op [Average]
  (min, avg, max) = (3.249, 3.339, 3.415), stdev = 0.084
  CI (99.9%): [1.801, 4.878] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.976 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.499 ±(99.9%) 0.012 ms/op
Iteration   1: 3.316 ±(99.9%) 0.005 ms/op
Iteration   2: 3.435 ±(99.9%) 0.003 ms/op
Iteration   3: 3.371 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.374 ±(99.9%) 1.086 ms/op [Average]
  (min, avg, max) = (3.316, 3.374, 3.435), stdev = 0.060
  CI (99.9%): [2.288, 4.460] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.794 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.010 ms/op
Iteration   1: 4.127 ±(99.9%) 0.009 ms/op
Iteration   2: 3.905 ±(99.9%) 0.008 ms/op
Iteration   3: 4.054 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.029 ±(99.9%) 2.066 ms/op [Average]
  (min, avg, max) = (3.905, 4.029, 4.127), stdev = 0.113
  CI (99.9%): [1.963, 6.094] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.758 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 3.929 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.530 ±(99.9%) 0.011 ms/op
Iteration   1: 3.442 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.239 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  20.381 ms/op
                 createUser·p0.9999: 24.468 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   2: 3.353 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.794 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  23.142 ms/op
                 createUser·p0.9999: 27.329 ms/op
                 createUser·p1.00:   28.344 ms/op

Iteration   3: 3.402 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.647 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  27.232 ms/op
                 createUser·p0.9999: 31.544 ms/op
                 createUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282199
  mean =      3.399 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5251 
    [ 2.500,  5.000) = 271136 
    [ 5.000,  7.500) = 4741 
    [ 7.500, 10.000) = 592 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     20.546 ms/op
     p(99.9900) =     30.263 ms/op
     p(99.9990) =     32.315 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.381 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.839 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.008 ms/op
Iteration   1: 3.370 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.339 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  20.575 ms/op
                 existUser·p0.9999: 24.379 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   2: 3.246 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.446 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  14.638 ms/op
                 existUser·p0.9999: 27.301 ms/op
                 existUser·p1.00:   28.475 ms/op

Iteration   3: 3.247 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.262 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  10.522 ms/op
                 existUser·p0.9999: 26.060 ms/op
                 existUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292000
  mean =      3.286 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16936 
    [ 2.500,  5.000) = 268549 
    [ 5.000,  7.500) = 5442 
    [ 7.500, 10.000) = 569 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 127 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     16.253 ms/op
     p(99.9900) =     26.503 ms/op
     p(99.9990) =     28.295 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.381 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.518 ±(99.9%) 0.011 ms/op
Iteration   1: 3.480 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  22.124 ms/op
                 getUser·p0.9999: 27.944 ms/op
                 getUser·p1.00:   28.639 ms/op

Iteration   2: 3.397 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.589 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   5.579 ms/op
                 getUser·p0.999:  23.257 ms/op
                 getUser·p0.9999: 26.739 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   3: 3.529 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.714 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  19.923 ms/op
                 getUser·p0.9999: 27.914 ms/op
                 getUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276931
  mean =      3.468 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9630 
    [ 2.500,  5.000) = 258982 
    [ 5.000,  7.500) = 7059 
    [ 7.500, 10.000) = 717 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 112 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     20.775 ms/op
     p(99.9900) =     27.797 ms/op
     p(99.9990) =     28.753 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.238 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.459 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.226 ±(99.9%) 0.015 ms/op
Iteration   1: 4.046 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.645 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.971 ms/op
                 listUser·p0.999:  19.497 ms/op
                 listUser·p0.9999: 26.122 ms/op
                 listUser·p1.00:   26.935 ms/op

Iteration   2: 4.183 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.690 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   8.102 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 19.169 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   3: 3.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.466 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  14.483 ms/op
                 listUser·p0.9999: 17.072 ms/op
                 listUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236081
  mean =      4.065 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 225759 
    [ 5.000,  7.500) = 7645 
    [ 7.500, 10.000) = 1767 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.645 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     24.471 ms/op
     p(99.9990) =     26.648 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.135 ± 2.352  ops/ms
ClientPb.existUser                       thrpt       3   9.493 ± 1.987  ops/ms
ClientPb.getUser                         thrpt       3   9.279 ± 0.791  ops/ms
ClientPb.listUser                        thrpt       3   8.045 ± 0.839  ops/ms
ClientPb.createUser                       avgt       3   3.462 ± 1.135   ms/op
ClientPb.existUser                        avgt       3   3.339 ± 1.538   ms/op
ClientPb.getUser                          avgt       3   3.374 ± 1.086   ms/op
ClientPb.listUser                         avgt       3   4.029 ± 2.066   ms/op
ClientPb.createUser                     sample  282199   3.399 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.239           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.710           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.546           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.263           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.408           ms/op
ClientPb.existUser                      sample  292000   3.286 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.262           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.498           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.854           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.734           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.253           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.503           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.475           ms/op
ClientPb.getUser                        sample  276931   3.468 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.276           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.316           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.775           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.797           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.360           ms/op
ClientPb.listUser                       sample  236081   4.065 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.645           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.758           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.105           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.471           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.935           ms/op
