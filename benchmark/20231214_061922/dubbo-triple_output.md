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
# Warmup Iteration   1: 5.085 ops/ms
# Warmup Iteration   2: 12.107 ops/ms
# Warmup Iteration   3: 12.314 ops/ms
Iteration   1: 12.517 ops/ms
Iteration   2: 12.594 ops/ms
Iteration   3: 12.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.531 ±(99.9%) 1.042 ops/ms [Average]
  (min, avg, max) = (12.482, 12.531, 12.594), stdev = 0.057
  CI (99.9%): [11.489, 13.573] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.128 ops/ms
# Warmup Iteration   2: 13.185 ops/ms
# Warmup Iteration   3: 12.931 ops/ms
Iteration   1: 13.296 ops/ms
Iteration   2: 12.747 ops/ms
Iteration   3: 12.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.006 ±(99.9%) 5.029 ops/ms [Average]
  (min, avg, max) = (12.747, 13.006, 13.296), stdev = 0.276
  CI (99.9%): [7.977, 18.035] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.987 ops/ms
# Warmup Iteration   2: 12.617 ops/ms
# Warmup Iteration   3: 12.886 ops/ms
Iteration   1: 12.759 ops/ms
Iteration   2: 12.800 ops/ms
Iteration   3: 12.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.842 ±(99.9%) 2.031 ops/ms [Average]
  (min, avg, max) = (12.759, 12.842, 12.969), stdev = 0.111
  CI (99.9%): [10.811, 14.873] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.776 ops/ms
# Warmup Iteration   2: 10.643 ops/ms
# Warmup Iteration   3: 10.556 ops/ms
Iteration   1: 10.569 ops/ms
Iteration   2: 10.869 ops/ms
Iteration   3: 10.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.717 ±(99.9%) 2.740 ops/ms [Average]
  (min, avg, max) = (10.569, 10.717, 10.869), stdev = 0.150
  CI (99.9%): [7.977, 13.457] (assumes normal distribution)


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
# Warmup Iteration   1: 4.304 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.630 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.007 ms/op
Iteration   1: 2.567 ±(99.9%) 0.006 ms/op
Iteration   2: 2.630 ±(99.9%) 0.009 ms/op
Iteration   3: 2.541 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.579 ±(99.9%) 0.831 ms/op [Average]
  (min, avg, max) = (2.541, 2.579, 2.630), stdev = 0.046
  CI (99.9%): [1.748, 3.411] (assumes normal distribution)


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
# Warmup Iteration   1: 3.789 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.007 ms/op
Iteration   1: 2.500 ±(99.9%) 0.008 ms/op
Iteration   2: 2.413 ±(99.9%) 0.009 ms/op
Iteration   3: 2.406 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.440 ±(99.9%) 0.950 ms/op [Average]
  (min, avg, max) = (2.406, 2.440, 2.500), stdev = 0.052
  CI (99.9%): [1.490, 3.389] (assumes normal distribution)


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
# Warmup Iteration   1: 4.138 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.010 ms/op
Iteration   1: 2.552 ±(99.9%) 0.009 ms/op
Iteration   2: 2.484 ±(99.9%) 0.007 ms/op
Iteration   3: 2.511 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.516 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (2.484, 2.516, 2.552), stdev = 0.034
  CI (99.9%): [1.896, 3.135] (assumes normal distribution)


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
# Warmup Iteration   1: 5.161 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.011 ms/op
Iteration   1: 3.140 ±(99.9%) 0.009 ms/op
Iteration   2: 3.069 ±(99.9%) 0.008 ms/op
Iteration   3: 3.082 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.097 ±(99.9%) 0.685 ms/op [Average]
  (min, avg, max) = (3.069, 3.097, 3.140), stdev = 0.038
  CI (99.9%): [2.412, 3.782] (assumes normal distribution)


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
# Warmup Iteration   1: 4.347 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 2.763 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.603 ±(99.9%) 0.007 ms/op
Iteration   1: 2.558 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.610 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.265 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  11.699 ms/op
                 createUser·p0.9999: 14.516 ms/op
                 createUser·p1.00:   15.843 ms/op

Iteration   2: 2.625 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.362 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.882 ms/op
                 createUser·p0.999:  10.162 ms/op
                 createUser·p0.9999: 14.336 ms/op
                 createUser·p1.00:   19.497 ms/op

Iteration   3: 2.600 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.495 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  10.206 ms/op
                 createUser·p0.9999: 15.876 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 369780
  mean =      2.594 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 174951 
    [ 2.500,  5.000) = 192117 
    [ 5.000,  7.500) = 2133 
    [ 7.500, 10.000) = 191 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.362 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.712 ms/op
     p(99.9000) =     10.207 ms/op
     p(99.9900) =     15.174 ms/op
     p(99.9990) =     16.942 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 4.096 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.007 ms/op
Iteration   1: 2.419 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.611 ms/op
                 existUser·p0.50:   2.363 ms/op
                 existUser·p0.90:   3.105 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  11.395 ms/op
                 existUser·p0.9999: 18.959 ms/op
                 existUser·p1.00:   19.923 ms/op

Iteration   2: 2.430 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   2.363 ms/op
                 existUser·p0.90:   3.166 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  6.926 ms/op
                 existUser·p0.9999: 15.303 ms/op
                 existUser·p1.00:   17.203 ms/op

Iteration   3: 2.422 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.556 ms/op
                 existUser·p0.50:   2.388 ms/op
                 existUser·p0.90:   3.113 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   4.378 ms/op
                 existUser·p0.999:  9.208 ms/op
                 existUser·p0.9999: 13.694 ms/op
                 existUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395795
  mean =      2.424 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 229129 
    [ 2.500,  5.000) = 164658 
    [ 5.000,  7.500) = 1518 
    [ 7.500, 10.000) = 151 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      2.372 ms/op
     p(90.0000) =      3.129 ms/op
     p(95.0000) =      3.473 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.667 ms/op
     p(99.9900) =     16.140 ms/op
     p(99.9990) =     20.168 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 4.061 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.006 ms/op
Iteration   1: 2.543 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.420 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.322 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  12.374 ms/op
                 getUser·p0.9999: 14.713 ms/op
                 getUser·p1.00:   16.056 ms/op

Iteration   2: 2.502 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.408 ms/op
                 getUser·p0.50:   2.449 ms/op
                 getUser·p0.90:   3.244 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  7.065 ms/op
                 getUser·p0.9999: 13.337 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   3: 2.504 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.382 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   3.240 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  10.213 ms/op
                 getUser·p0.9999: 16.503 ms/op
                 getUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381156
  mean =      2.516 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 480 
    [ 1.250,  2.500) = 199046 
    [ 2.500,  3.750) = 166208 
    [ 3.750,  5.000) = 13332 
    [ 5.000,  6.250) = 1345 
    [ 6.250,  7.500) = 271 
    [ 7.500,  8.750) = 85 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 129 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.382 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      3.269 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      8.861 ms/op
     p(99.9900) =     14.978 ms/op
     p(99.9990) =     17.275 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 4.645 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.010 ms/op
Iteration   1: 3.139 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.403 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  11.717 ms/op
                 listUser·p0.9999: 14.784 ms/op
                 listUser·p1.00:   16.843 ms/op

Iteration   2: 3.137 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.385 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  11.126 ms/op
                 listUser·p0.9999: 13.511 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   3: 3.127 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.583 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   6.152 ms/op
                 listUser·p0.999:  12.090 ms/op
                 listUser·p0.9999: 16.393 ms/op
                 listUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 306050
  mean =      3.134 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 95047 
    [ 2.500,  5.000) = 196945 
    [ 5.000,  7.500) = 11974 
    [ 7.500, 10.000) = 1530 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.385 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     11.682 ms/op
     p(99.9900) =     15.889 ms/op
     p(99.9990) =     17.690 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.531 ± 1.042  ops/ms
ClientPb.existUser                       thrpt       3  13.006 ± 5.029  ops/ms
ClientPb.getUser                         thrpt       3  12.842 ± 2.031  ops/ms
ClientPb.listUser                        thrpt       3  10.717 ± 2.740  ops/ms
ClientPb.createUser                       avgt       3   2.579 ± 0.831   ms/op
ClientPb.existUser                        avgt       3   2.440 ± 0.950   ms/op
ClientPb.getUser                          avgt       3   2.516 ± 0.620   ms/op
ClientPb.listUser                         avgt       3   3.097 ± 0.685   ms/op
ClientPb.createUser                     sample  369780   2.594 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.362           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.712           ms/op
ClientPb.createUser:createUser·p0.999   sample          10.207           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.174           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.251           ms/op
ClientPb.existUser                      sample  395795   2.424 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.556           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.372           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.424           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.667           ms/op
ClientPb.existUser:existUser·p0.9999    sample          16.140           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.952           ms/op
ClientPb.getUser                        sample  381156   2.516 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.382           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.458           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.637           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.547           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.861           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.978           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.956           ms/op
ClientPb.listUser                       sample  306050   3.134 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.385           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.915           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.881           ms/op
ClientPb.listUser:listUser·p0.999       sample          11.682           ms/op
ClientPb.listUser:listUser·p0.9999      sample          15.889           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.068           ms/op
