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
# Warmup Iteration   1: 5.011 ops/ms
# Warmup Iteration   2: 11.834 ops/ms
# Warmup Iteration   3: 12.179 ops/ms
Iteration   1: 12.513 ops/ms
Iteration   2: 12.645 ops/ms
Iteration   3: 12.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.538 ±(99.9%) 1.751 ops/ms [Average]
  (min, avg, max) = (12.458, 12.538, 12.645), stdev = 0.096
  CI (99.9%): [10.787, 14.290] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.127 ops/ms
# Warmup Iteration   2: 12.987 ops/ms
# Warmup Iteration   3: 13.114 ops/ms
Iteration   1: 12.968 ops/ms
Iteration   2: 13.205 ops/ms
Iteration   3: 13.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.104 ±(99.9%) 2.229 ops/ms [Average]
  (min, avg, max) = (12.968, 13.104, 13.205), stdev = 0.122
  CI (99.9%): [10.875, 15.333] (assumes normal distribution)


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
# Warmup Iteration   1: 7.293 ops/ms
# Warmup Iteration   2: 12.400 ops/ms
# Warmup Iteration   3: 12.477 ops/ms
Iteration   1: 12.780 ops/ms
Iteration   2: 12.744 ops/ms
Iteration   3: 12.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.704 ±(99.9%) 1.863 ops/ms [Average]
  (min, avg, max) = (12.588, 12.704, 12.780), stdev = 0.102
  CI (99.9%): [10.841, 14.567] (assumes normal distribution)


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
# Warmup Iteration   1: 6.299 ops/ms
# Warmup Iteration   2: 10.605 ops/ms
# Warmup Iteration   3: 10.447 ops/ms
Iteration   1: 10.567 ops/ms
Iteration   2: 10.517 ops/ms
Iteration   3: 10.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.552 ±(99.9%) 0.562 ops/ms [Average]
  (min, avg, max) = (10.517, 10.552, 10.572), stdev = 0.031
  CI (99.9%): [9.990, 11.114] (assumes normal distribution)


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
# Warmup Iteration   1: 4.010 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
Iteration   1: 2.564 ±(99.9%) 0.004 ms/op
Iteration   2: 2.523 ±(99.9%) 0.004 ms/op
Iteration   3: 2.488 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.525 ±(99.9%) 0.697 ms/op [Average]
  (min, avg, max) = (2.488, 2.525, 2.564), stdev = 0.038
  CI (99.9%): [1.828, 3.222] (assumes normal distribution)


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
# Warmup Iteration   1: 3.708 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.451 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.004 ms/op
Iteration   1: 2.406 ±(99.9%) 0.004 ms/op
Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
Iteration   3: 2.463 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.443 ±(99.9%) 0.584 ms/op [Average]
  (min, avg, max) = (2.406, 2.443, 2.463), stdev = 0.032
  CI (99.9%): [1.859, 3.027] (assumes normal distribution)


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.004 ms/op
Iteration   1: 2.518 ±(99.9%) 0.005 ms/op
Iteration   2: 2.500 ±(99.9%) 0.004 ms/op
Iteration   3: 2.469 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.496 ±(99.9%) 0.447 ms/op [Average]
  (min, avg, max) = (2.469, 2.496, 2.518), stdev = 0.025
  CI (99.9%): [2.048, 2.943] (assumes normal distribution)


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
# Warmup Iteration   1: 4.666 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.005 ms/op
Iteration   1: 3.028 ±(99.9%) 0.005 ms/op
Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
Iteration   3: 3.017 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.021 ±(99.9%) 0.107 ms/op [Average]
  (min, avg, max) = (3.017, 3.021, 3.028), stdev = 0.006
  CI (99.9%): [2.914, 3.129] (assumes normal distribution)


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
# Warmup Iteration   1: 4.071 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.664 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.006 ms/op
Iteration   1: 2.554 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   4.125 ms/op
                 createUser·p0.999:  11.613 ms/op
                 createUser·p0.9999: 14.262 ms/op
                 createUser·p1.00:   16.400 ms/op

Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   2.675 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  9.733 ms/op
                 createUser·p0.9999: 12.698 ms/op
                 createUser·p1.00:   13.402 ms/op

Iteration   3: 2.562 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   4.184 ms/op
                 createUser·p0.999:  8.978 ms/op
                 createUser·p0.9999: 11.428 ms/op
                 createUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374774
  mean =      2.558 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 177542 
    [ 2.500,  3.750) = 191902 
    [ 3.750,  5.000) = 4148 
    [ 5.000,  6.250) = 620 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.646 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      4.018 ms/op
     p(99.9000) =      9.113 ms/op
     p(99.9900) =     13.738 ms/op
     p(99.9990) =     14.553 ms/op
     p(99.9999) =     16.400 ms/op
    p(100.0000) =     16.400 ms/op


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
# Warmup Iteration   1: 3.726 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.444 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.006 ms/op
Iteration   1: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  6.550 ms/op
                 existUser·p0.9999: 13.745 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  5.685 ms/op
                 existUser·p0.9999: 12.433 ms/op
                 existUser·p1.00:   12.960 ms/op

Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.957 ms/op
                 existUser·p0.999:  9.093 ms/op
                 existUser·p0.9999: 11.600 ms/op
                 existUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392248
  mean =      2.445 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 196876 
    [ 2.500,  3.750) = 191599 
    [ 3.750,  5.000) = 2692 
    [ 5.000,  6.250) = 622 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      6.838 ms/op
     p(99.9900) =     13.366 ms/op
     p(99.9990) =     13.959 ms/op
     p(99.9999) =     16.433 ms/op
    p(100.0000) =     16.433 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.150 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.631 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.006 ms/op
Iteration   1: 2.549 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  12.406 ms/op
                 getUser·p0.9999: 13.959 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   2: 2.530 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.145 ms/op
                 getUser·p0.999:  9.644 ms/op
                 getUser·p0.9999: 14.172 ms/op
                 getUser·p1.00:   15.237 ms/op

Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  9.142 ms/op
                 getUser·p0.9999: 10.723 ms/op
                 getUser·p1.00:   11.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377238
  mean =      2.542 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 184224 
    [ 2.500,  3.750) = 186085 
    [ 3.750,  5.000) = 5004 
    [ 5.000,  6.250) = 1363 
    [ 6.250,  7.500) = 99 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      9.233 ms/op
     p(99.9900) =     13.964 ms/op
     p(99.9990) =     14.976 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


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
# Warmup Iteration   1: 5.034 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.009 ms/op
Iteration   1: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.483 ms/op
                 listUser·p0.9999: 11.720 ms/op
                 listUser·p1.00:   12.665 ms/op

Iteration   2: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.738 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 10.376 ms/op
                 listUser·p1.00:   10.994 ms/op

Iteration   3: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.644 ms/op
                 listUser·p0.9999: 13.285 ms/op
                 listUser·p1.00:   13.910 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319952
  mean =      2.998 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 93184 
    [ 2.500,  3.750) = 188260 
    [ 3.750,  5.000) = 30799 
    [ 5.000,  6.250) = 6150 
    [ 6.250,  7.500) = 684 
    [ 7.500,  8.750) = 336 
    [ 8.750, 10.000) = 224 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     12.501 ms/op
     p(99.9990) =     13.822 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.538 ± 1.751  ops/ms
ClientPb.existUser                       thrpt       3  13.104 ± 2.229  ops/ms
ClientPb.getUser                         thrpt       3  12.704 ± 1.863  ops/ms
ClientPb.listUser                        thrpt       3  10.552 ± 0.562  ops/ms
ClientPb.createUser                       avgt       3   2.525 ± 0.697   ms/op
ClientPb.existUser                        avgt       3   2.443 ± 0.584   ms/op
ClientPb.getUser                          avgt       3   2.496 ± 0.447   ms/op
ClientPb.listUser                         avgt       3   3.021 ± 0.107   ms/op
ClientPb.createUser                     sample  374774   2.558 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.860           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.646           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.113           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.738           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.400           ms/op
ClientPb.existUser                      sample  392248   2.445 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.897           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.838           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.366           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.433           ms/op
ClientPb.getUser                        sample  377238   2.542 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.679           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.342           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.233           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.964           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.237           ms/op
ClientPb.listUser                       sample  319952   2.998 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.738           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.290           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.501           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.910           ms/op
