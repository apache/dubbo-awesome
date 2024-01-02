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
# Warmup Iteration   1: 3.512 ops/ms
# Warmup Iteration   2: 11.694 ops/ms
# Warmup Iteration   3: 12.151 ops/ms
Iteration   1: 12.443 ops/ms
Iteration   2: 12.555 ops/ms
Iteration   3: 12.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.542 ±(99.9%) 1.696 ops/ms [Average]
  (min, avg, max) = (12.443, 12.542, 12.628), stdev = 0.093
  CI (99.9%): [10.846, 14.238] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.699 ops/ms
# Warmup Iteration   2: 12.921 ops/ms
# Warmup Iteration   3: 12.791 ops/ms
Iteration   1: 13.089 ops/ms
Iteration   2: 13.135 ops/ms
Iteration   3: 13.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.082 ±(99.9%) 1.045 ops/ms [Average]
  (min, avg, max) = (13.021, 13.082, 13.135), stdev = 0.057
  CI (99.9%): [12.037, 14.127] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.522 ops/ms
# Warmup Iteration   2: 12.560 ops/ms
# Warmup Iteration   3: 12.670 ops/ms
Iteration   1: 12.754 ops/ms
Iteration   2: 12.689 ops/ms
Iteration   3: 12.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.753 ±(99.9%) 1.165 ops/ms [Average]
  (min, avg, max) = (12.689, 12.753, 12.817), stdev = 0.064
  CI (99.9%): [11.588, 13.918] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.716 ops/ms
# Warmup Iteration   2: 10.426 ops/ms
# Warmup Iteration   3: 10.484 ops/ms
Iteration   1: 10.548 ops/ms
Iteration   2: 10.493 ops/ms
Iteration   3: 10.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.509 ±(99.9%) 0.617 ops/ms [Average]
  (min, avg, max) = (10.487, 10.509, 10.548), stdev = 0.034
  CI (99.9%): [9.892, 11.126] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.062 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.560 ±(99.9%) 0.004 ms/op
Iteration   1: 2.543 ±(99.9%) 0.004 ms/op
Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.508 ±(99.9%) 0.550 ms/op [Average]
  (min, avg, max) = (2.486, 2.508, 2.543), stdev = 0.030
  CI (99.9%): [1.958, 3.058] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.676 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.444 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.003 ms/op
Iteration   1: 2.468 ±(99.9%) 0.004 ms/op
Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
Iteration   3: 2.490 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.477 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (2.468, 2.477, 2.490), stdev = 0.012
  CI (99.9%): [2.260, 2.693] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.826 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.004 ms/op
Iteration   1: 2.497 ±(99.9%) 0.003 ms/op
Iteration   2: 2.537 ±(99.9%) 0.005 ms/op
Iteration   3: 2.487 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.507 ±(99.9%) 0.481 ms/op [Average]
  (min, avg, max) = (2.487, 2.507, 2.537), stdev = 0.026
  CI (99.9%): [2.026, 2.988] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.626 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
Iteration   1: 3.047 ±(99.9%) 0.006 ms/op
Iteration   2: 3.062 ±(99.9%) 0.006 ms/op
Iteration   3: 3.043 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.051 ±(99.9%) 0.182 ms/op [Average]
  (min, avg, max) = (3.043, 3.051, 3.062), stdev = 0.010
  CI (99.9%): [2.869, 3.233] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.205 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.679 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
Iteration   1: 2.509 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.867 ms/op
                 createUser·p0.999:  11.469 ms/op
                 createUser·p0.9999: 13.767 ms/op
                 createUser·p1.00:   14.172 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.543 ms/op
                 createUser·p0.999:  8.606 ms/op
                 createUser·p0.9999: 10.512 ms/op
                 createUser·p1.00:   11.223 ms/op

Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.895 ms/op
                 createUser·p0.999:  8.684 ms/op
                 createUser·p0.9999: 13.828 ms/op
                 createUser·p1.00:   15.254 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381312
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 184350 
    [ 2.500,  3.750) = 193035 
    [ 3.750,  5.000) = 2769 
    [ 5.000,  6.250) = 630 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 92 
    [ 8.750, 10.000) = 116 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      8.634 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     14.249 ms/op
     p(99.9999) =     15.254 ms/op
    p(100.0000) =     15.254 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.785 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
Iteration   1: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  5.706 ms/op
                 existUser·p0.9999: 14.156 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  6.391 ms/op
                 existUser·p0.9999: 12.925 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  8.503 ms/op
                 existUser·p0.9999: 12.535 ms/op
                 existUser·p1.00:   15.155 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390520
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 194547 
    [ 2.500,  3.750) = 193051 
    [ 3.750,  5.000) = 2203 
    [ 5.000,  6.250) = 187 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 129 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      8.454 ms/op
     p(99.9900) =     13.647 ms/op
     p(99.9990) =     14.386 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.991 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.006 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.629 ms/op
                 getUser·p0.999:  10.002 ms/op
                 getUser·p0.9999: 14.286 ms/op
                 getUser·p1.00:   15.041 ms/op

Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.912 ms/op
                 getUser·p0.999:  6.894 ms/op
                 getUser·p0.9999: 12.403 ms/op
                 getUser·p1.00:   13.140 ms/op

Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.822 ms/op
                 getUser·p0.999:  8.734 ms/op
                 getUser·p0.9999: 12.359 ms/op
                 getUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381564
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 187772 
    [ 2.500,  3.750) = 189562 
    [ 3.750,  5.000) = 3342 
    [ 5.000,  6.250) = 368 
    [ 6.250,  7.500) = 99 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 154 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      6.898 ms/op
     p(99.9900) =     13.383 ms/op
     p(99.9990) =     14.929 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.862 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.009 ms/op
Iteration   1: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.054 ms/op
                 listUser·p0.9999: 10.777 ms/op
                 listUser·p1.00:   11.403 ms/op

Iteration   2: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.800 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  10.377 ms/op
                 listUser·p0.9999: 11.507 ms/op
                 listUser·p1.00:   11.977 ms/op

Iteration   3: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.820 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.657 ms/op
                 listUser·p0.9999: 11.857 ms/op
                 listUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319506
  mean =      3.001 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 171 
    [ 1.250,  2.500) = 91819 
    [ 2.500,  3.750) = 188737 
    [ 3.750,  5.000) = 31871 
    [ 5.000,  6.250) = 5512 
    [ 6.250,  7.500) = 702 
    [ 7.500,  8.750) = 211 
    [ 8.750, 10.000) = 226 
    [10.000, 11.250) = 210 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.658 ms/op
     p(99.9900) =     11.470 ms/op
     p(99.9990) =     12.137 ms/op
     p(99.9999) =     12.714 ms/op
    p(100.0000) =     12.714 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.542 ± 1.696  ops/ms
ClientPb.existUser                       thrpt       3  13.082 ± 1.045  ops/ms
ClientPb.getUser                         thrpt       3  12.753 ± 1.165  ops/ms
ClientPb.listUser                        thrpt       3  10.509 ± 0.617  ops/ms
ClientPb.createUser                       avgt       3   2.508 ± 0.550   ms/op
ClientPb.existUser                        avgt       3   2.477 ± 0.217   ms/op
ClientPb.getUser                          avgt       3   2.507 ± 0.481   ms/op
ClientPb.listUser                         avgt       3   3.051 ± 0.182   ms/op
ClientPb.createUser                     sample  381312   2.515 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.891           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.634           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.713           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.254           ms/op
ClientPb.existUser                      sample  390520   2.455 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.930           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.454           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.647           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.155           ms/op
ClientPb.getUser                        sample  381564   2.514 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.907           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.789           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.898           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.383           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.041           ms/op
ClientPb.listUser                       sample  319506   3.001 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.800           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.658           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.470           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.714           ms/op
