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
# Warmup Iteration   1: 1.967 ops/ms
# Warmup Iteration   2: 5.015 ops/ms
# Warmup Iteration   3: 8.508 ops/ms
Iteration   1: 9.061 ops/ms
Iteration   2: 9.058 ops/ms
Iteration   3: 9.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.103 ±(99.9%) 1.382 ops/ms [Average]
  (min, avg, max) = (9.058, 9.103, 9.191), stdev = 0.076
  CI (99.9%): [7.722, 10.485] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.889 ops/ms
# Warmup Iteration   2: 8.751 ops/ms
# Warmup Iteration   3: 9.561 ops/ms
Iteration   1: 9.715 ops/ms
Iteration   2: 9.805 ops/ms
Iteration   3: 9.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.755 ±(99.9%) 0.841 ops/ms [Average]
  (min, avg, max) = (9.715, 9.755, 9.805), stdev = 0.046
  CI (99.9%): [8.914, 10.596] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.793 ops/ms
# Warmup Iteration   2: 8.009 ops/ms
# Warmup Iteration   3: 8.898 ops/ms
Iteration   1: 9.243 ops/ms
Iteration   2: 9.259 ops/ms
Iteration   3: 9.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.326 ±(99.9%) 2.370 ops/ms [Average]
  (min, avg, max) = (9.243, 9.326, 9.476), stdev = 0.130
  CI (99.9%): [6.956, 11.696] (assumes normal distribution)


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
# Warmup Iteration   1: 2.573 ops/ms
# Warmup Iteration   2: 7.089 ops/ms
# Warmup Iteration   3: 7.732 ops/ms
Iteration   1: 7.581 ops/ms
Iteration   2: 7.837 ops/ms
Iteration   3: 7.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.805 ±(99.9%) 3.817 ops/ms [Average]
  (min, avg, max) = (7.581, 7.805, 7.996), stdev = 0.209
  CI (99.9%): [3.988, 11.622] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.537 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.006 ms/op
Iteration   1: 3.518 ±(99.9%) 0.005 ms/op
Iteration   2: 3.368 ±(99.9%) 0.006 ms/op
Iteration   3: 3.402 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.429 ±(99.9%) 1.431 ms/op [Average]
  (min, avg, max) = (3.368, 3.429, 3.518), stdev = 0.078
  CI (99.9%): [1.998, 4.860] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 11.038 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.457 ±(99.9%) 0.005 ms/op
Iteration   1: 3.357 ±(99.9%) 0.011 ms/op
Iteration   2: 3.383 ±(99.9%) 0.008 ms/op
Iteration   3: 3.310 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.350 ±(99.9%) 0.671 ms/op [Average]
  (min, avg, max) = (3.310, 3.350, 3.383), stdev = 0.037
  CI (99.9%): [2.679, 4.020] (assumes normal distribution)


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
# Warmup Iteration   1: 9.291 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.603 ±(99.9%) 0.006 ms/op
Iteration   1: 3.523 ±(99.9%) 0.004 ms/op
Iteration   2: 3.474 ±(99.9%) 0.005 ms/op
Iteration   3: 3.404 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.467 ±(99.9%) 1.091 ms/op [Average]
  (min, avg, max) = (3.404, 3.467, 3.523), stdev = 0.060
  CI (99.9%): [2.376, 4.558] (assumes normal distribution)


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
# Warmup Iteration   1: 10.768 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.008 ms/op
Iteration   1: 4.091 ±(99.9%) 0.007 ms/op
Iteration   2: 4.028 ±(99.9%) 0.008 ms/op
Iteration   3: 3.844 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.987 ±(99.9%) 2.342 ms/op [Average]
  (min, avg, max) = (3.844, 3.987, 4.091), stdev = 0.128
  CI (99.9%): [1.646, 6.329] (assumes normal distribution)


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
# Warmup Iteration   1: 10.693 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.732 ±(99.9%) 0.014 ms/op
Iteration   1: 3.464 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.488 ms/op
                 createUser·p0.999:  20.498 ms/op
                 createUser·p0.9999: 23.978 ms/op
                 createUser·p1.00:   24.674 ms/op

Iteration   2: 3.469 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  23.155 ms/op
                 createUser·p0.9999: 38.470 ms/op
                 createUser·p1.00:   38.863 ms/op

Iteration   3: 3.455 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.534 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  18.579 ms/op
                 createUser·p0.9999: 26.910 ms/op
                 createUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277191
  mean =      3.463 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8086 
    [ 2.500,  5.000) = 259610 
    [ 5.000,  7.500) = 8298 
    [ 7.500, 10.000) = 686 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.291 ms/op
     p(99.9000) =     19.032 ms/op
     p(99.9900) =     37.683 ms/op
     p(99.9990) =     38.696 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.147 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.010 ms/op
Iteration   1: 3.333 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.632 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  20.682 ms/op
                 existUser·p0.9999: 24.274 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   2: 3.290 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.774 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  10.387 ms/op
                 existUser·p0.9999: 25.723 ms/op
                 existUser·p1.00:   26.116 ms/op

Iteration   3: 3.278 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   5.766 ms/op
                 existUser·p0.999:  10.007 ms/op
                 existUser·p0.9999: 33.963 ms/op
                 existUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290825
  mean =      3.300 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18338 
    [ 2.500,  5.000) = 267323 
    [ 5.000,  7.500) = 4412 
    [ 7.500, 10.000) = 427 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     10.308 ms/op
     p(99.9900) =     33.128 ms/op
     p(99.9990) =     34.222 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 8.581 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.910 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.599 ±(99.9%) 0.012 ms/op
Iteration   1: 3.499 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.102 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  22.433 ms/op
                 getUser·p0.9999: 29.884 ms/op
                 getUser·p1.00:   31.162 ms/op

Iteration   2: 3.403 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.491 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  22.645 ms/op
                 getUser·p0.9999: 27.925 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   3: 3.385 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.661 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  25.053 ms/op
                 getUser·p0.9999: 31.064 ms/op
                 getUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279795
  mean =      3.428 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2201 
    [ 2.500,  5.000) = 269460 
    [ 5.000,  7.500) = 7215 
    [ 7.500, 10.000) = 548 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     22.617 ms/op
     p(99.9900) =     29.689 ms/op
     p(99.9990) =     31.523 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


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
# Warmup Iteration   1: 13.444 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.983 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.278 ±(99.9%) 0.013 ms/op
Iteration   1: 4.495 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.788 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   6.488 ms/op
                 listUser·p0.95:   8.282 ms/op
                 listUser·p0.99:   10.994 ms/op
                 listUser·p0.999:  25.362 ms/op
                 listUser·p0.9999: 27.427 ms/op
                 listUser·p1.00:   28.180 ms/op

Iteration   2: 3.960 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.605 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.316 ms/op
                 listUser·p0.999:  16.679 ms/op
                 listUser·p0.9999: 22.446 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   3: 4.046 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.733 ms/op
                 listUser·p0.999:  17.986 ms/op
                 listUser·p0.9999: 21.823 ms/op
                 listUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230961
  mean =      4.154 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 216806 
    [ 5.000,  7.500) = 7776 
    [ 7.500, 10.000) = 4490 
    [10.000, 12.500) = 1163 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 71 

  Percentiles, ms/op:
      p(0.0000) =      1.788 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     26.932 ms/op
     p(99.9990) =     27.882 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.103 ± 1.382  ops/ms
ClientPb.existUser                       thrpt       3   9.755 ± 0.841  ops/ms
ClientPb.getUser                         thrpt       3   9.326 ± 2.370  ops/ms
ClientPb.listUser                        thrpt       3   7.805 ± 3.817  ops/ms
ClientPb.createUser                       avgt       3   3.429 ± 1.431   ms/op
ClientPb.existUser                        avgt       3   3.350 ± 0.671   ms/op
ClientPb.getUser                          avgt       3   3.467 ± 1.091   ms/op
ClientPb.listUser                         avgt       3   3.987 ± 2.342   ms/op
ClientPb.createUser                     sample  277191   3.463 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.087           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.456           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.291           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.032           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.683           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.863           ms/op
ClientPb.existUser                      sample  290825   3.300 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.315           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.936           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.628           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.308           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.128           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.472           ms/op
ClientPb.getUser                        sample  279795   3.428 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.102           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.273           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.617           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.689           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.556           ms/op
ClientPb.listUser                       sample  230961   4.154 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.788           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.767           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.585           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.956           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.932           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.180           ms/op
