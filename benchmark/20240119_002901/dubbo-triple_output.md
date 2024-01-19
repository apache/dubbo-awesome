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
# Warmup Iteration   1: 4.453 ops/ms
# Warmup Iteration   2: 11.497 ops/ms
# Warmup Iteration   3: 11.621 ops/ms
Iteration   1: 12.314 ops/ms
Iteration   2: 12.275 ops/ms
Iteration   3: 12.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.304 ±(99.9%) 0.464 ops/ms [Average]
  (min, avg, max) = (12.275, 12.304, 12.323), stdev = 0.025
  CI (99.9%): [11.839, 12.768] (assumes normal distribution)


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
# Warmup Iteration   1: 7.592 ops/ms
# Warmup Iteration   2: 12.669 ops/ms
# Warmup Iteration   3: 12.726 ops/ms
Iteration   1: 12.809 ops/ms
Iteration   2: 12.675 ops/ms
Iteration   3: 12.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.694 ±(99.9%) 1.944 ops/ms [Average]
  (min, avg, max) = (12.598, 12.694, 12.809), stdev = 0.107
  CI (99.9%): [10.750, 14.638] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.426 ops/ms
# Warmup Iteration   2: 12.260 ops/ms
# Warmup Iteration   3: 12.546 ops/ms
Iteration   1: 12.579 ops/ms
Iteration   2: 12.507 ops/ms
Iteration   3: 12.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.516 ±(99.9%) 1.062 ops/ms [Average]
  (min, avg, max) = (12.464, 12.516, 12.579), stdev = 0.058
  CI (99.9%): [11.454, 13.579] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.584 ops/ms
# Warmup Iteration   2: 10.185 ops/ms
# Warmup Iteration   3: 10.639 ops/ms
Iteration   1: 10.436 ops/ms
Iteration   2: 10.375 ops/ms
Iteration   3: 10.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.391 ±(99.9%) 0.729 ops/ms [Average]
  (min, avg, max) = (10.361, 10.391, 10.436), stdev = 0.040
  CI (99.9%): [9.662, 11.120] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.325 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.671 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.576 ±(99.9%) 0.005 ms/op
Iteration   1: 2.611 ±(99.9%) 0.004 ms/op
Iteration   2: 2.623 ±(99.9%) 0.004 ms/op
Iteration   3: 2.569 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.601 ±(99.9%) 0.519 ms/op [Average]
  (min, avg, max) = (2.569, 2.601, 2.623), stdev = 0.028
  CI (99.9%): [2.081, 3.120] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.084 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.003 ms/op
Iteration   1: 2.506 ±(99.9%) 0.004 ms/op
Iteration   2: 2.499 ±(99.9%) 0.004 ms/op
Iteration   3: 2.483 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.496 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (2.483, 2.496, 2.506), stdev = 0.012
  CI (99.9%): [2.276, 2.717] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.176 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.630 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.004 ms/op
Iteration   1: 2.543 ±(99.9%) 0.004 ms/op
Iteration   2: 2.561 ±(99.9%) 0.004 ms/op
Iteration   3: 2.576 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.560 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (2.543, 2.560, 2.576), stdev = 0.017
  CI (99.9%): [2.258, 2.861] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.024 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.005 ms/op
Iteration   1: 3.104 ±(99.9%) 0.006 ms/op
Iteration   2: 3.064 ±(99.9%) 0.005 ms/op
Iteration   3: 3.082 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.083 ±(99.9%) 0.369 ms/op [Average]
  (min, avg, max) = (3.064, 3.083, 3.104), stdev = 0.020
  CI (99.9%): [2.714, 3.452] (assumes normal distribution)


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
# Warmup Iteration   1: 4.384 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 2.642 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.573 ±(99.9%) 0.006 ms/op
Iteration   1: 2.595 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.183 ms/op
                 createUser·p0.95:   3.330 ms/op
                 createUser·p0.99:   3.912 ms/op
                 createUser·p0.999:  12.478 ms/op
                 createUser·p0.9999: 14.462 ms/op
                 createUser·p1.00:   16.351 ms/op

Iteration   2: 2.603 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.203 ms/op
                 createUser·p0.95:   3.391 ms/op
                 createUser·p0.99:   4.125 ms/op
                 createUser·p0.999:  10.945 ms/op
                 createUser·p0.9999: 15.248 ms/op
                 createUser·p1.00:   16.499 ms/op

Iteration   3: 2.611 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.211 ms/op
                 createUser·p0.95:   3.355 ms/op
                 createUser·p0.99:   3.965 ms/op
                 createUser·p0.999:  9.850 ms/op
                 createUser·p0.9999: 11.436 ms/op
                 createUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 368393
  mean =      2.603 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 172952 
    [ 2.500,  3.750) = 189593 
    [ 3.750,  5.000) = 4707 
    [ 5.000,  6.250) = 603 
    [ 6.250,  7.500) = 91 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 79 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.199 ms/op
     p(95.0000) =      3.355 ms/op
     p(99.0000) =      4.006 ms/op
     p(99.9000) =     10.027 ms/op
     p(99.9900) =     14.584 ms/op
     p(99.9990) =     16.158 ms/op
     p(99.9999) =     16.499 ms/op
    p(100.0000) =     16.499 ms/op


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
# Warmup Iteration   1: 4.106 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.524 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.092 ms/op
                 existUser·p0.95:   3.228 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  11.092 ms/op
                 existUser·p0.9999: 15.532 ms/op
                 existUser·p1.00:   16.515 ms/op

Iteration   2: 2.552 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.125 ms/op
                 existUser·p0.95:   3.265 ms/op
                 existUser·p0.99:   3.994 ms/op
                 existUser·p0.999:  6.790 ms/op
                 existUser·p0.9999: 14.286 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   3: 2.563 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.150 ms/op
                 existUser·p0.95:   3.338 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  9.366 ms/op
                 existUser·p0.9999: 14.198 ms/op
                 existUser·p1.00:   14.942 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 376708
  mean =      2.546 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 181463 
    [ 2.500,  3.750) = 189544 
    [ 3.750,  5.000) = 4277 
    [ 5.000,  6.250) = 889 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 78 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.273 ms/op
     p(99.0000) =      4.051 ms/op
     p(99.9000) =      8.972 ms/op
     p(99.9900) =     14.500 ms/op
     p(99.9990) =     16.355 ms/op
     p(99.9999) =     16.515 ms/op
    p(100.0000) =     16.515 ms/op


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.679 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
Iteration   1: 2.503 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.834 ms/op
                 getUser·p0.999:  10.740 ms/op
                 getUser·p0.9999: 14.323 ms/op
                 getUser·p1.00:   15.385 ms/op

Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.659 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  5.485 ms/op
                 getUser·p0.9999: 14.291 ms/op
                 getUser·p1.00:   15.254 ms/op

Iteration   3: 2.543 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   3.912 ms/op
                 getUser·p0.999:  8.718 ms/op
                 getUser·p0.9999: 15.303 ms/op
                 getUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380930
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 185987 
    [ 2.500,  3.750) = 190082 
    [ 3.750,  5.000) = 3884 
    [ 5.000,  6.250) = 434 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 81 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      6.784 ms/op
     p(99.9900) =     14.744 ms/op
     p(99.9990) =     15.915 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


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
# Warmup Iteration   1: 5.356 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.010 ms/op
Iteration   1: 3.148 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   3.062 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   5.882 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 12.089 ms/op
                 listUser·p1.00:   12.304 ms/op

Iteration   2: 3.146 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.901 ms/op
                 listUser·p0.50:   3.072 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.556 ms/op
                 listUser·p0.99:   5.833 ms/op
                 listUser·p0.999:  10.650 ms/op
                 listUser·p0.9999: 12.089 ms/op
                 listUser·p1.00:   12.616 ms/op

Iteration   3: 3.116 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.927 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.849 ms/op
                 listUser·p0.999:  9.984 ms/op
                 listUser·p0.9999: 12.767 ms/op
                 listUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 305806
  mean =      3.136 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 69099 
    [ 2.500,  3.750) = 187428 
    [ 3.750,  5.000) = 40001 
    [ 5.000,  6.250) = 7378 
    [ 6.250,  7.500) = 1065 
    [ 7.500,  8.750) = 261 
    [ 8.750, 10.000) = 195 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =      9.869 ms/op
     p(99.9900) =     12.288 ms/op
     p(99.9990) =     12.926 ms/op
     p(99.9999) =     12.993 ms/op
    p(100.0000) =     12.993 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.304 ± 0.464  ops/ms
ClientPb.existUser                       thrpt       3  12.694 ± 1.944  ops/ms
ClientPb.getUser                         thrpt       3  12.516 ± 1.062  ops/ms
ClientPb.listUser                        thrpt       3  10.391 ± 0.729  ops/ms
ClientPb.createUser                       avgt       3   2.601 ± 0.519   ms/op
ClientPb.existUser                        avgt       3   2.496 ± 0.221   ms/op
ClientPb.getUser                          avgt       3   2.560 ± 0.301   ms/op
ClientPb.listUser                         avgt       3   3.083 ± 0.369   ms/op
ClientPb.createUser                     sample  368393   2.603 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.905           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.006           ms/op
ClientPb.createUser:createUser·p0.999   sample          10.027           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.584           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.499           ms/op
ClientPb.existUser                      sample  376708   2.546 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.920           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.051           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.972           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.500           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.515           ms/op
ClientPb.getUser                        sample  380930   2.518 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.659           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.784           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.744           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.269           ms/op
ClientPb.listUser                       sample  305806   3.136 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.899           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.056           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.051           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.857           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.869           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.288           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.993           ms/op
