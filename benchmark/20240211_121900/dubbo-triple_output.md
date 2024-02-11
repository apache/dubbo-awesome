# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.461 ops/ms
# Warmup Iteration   2: 12.033 ops/ms
# Warmup Iteration   3: 12.356 ops/ms
Iteration   1: 12.379 ops/ms
Iteration   2: 12.532 ops/ms
Iteration   3: 12.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.408 ±(99.9%) 2.059 ops/ms [Average]
  (min, avg, max) = (12.312, 12.408, 12.532), stdev = 0.113
  CI (99.9%): [10.349, 14.466] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.839 ops/ms
# Warmup Iteration   2: 13.016 ops/ms
# Warmup Iteration   3: 12.986 ops/ms
Iteration   1: 12.935 ops/ms
Iteration   2: 12.931 ops/ms
Iteration   3: 12.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.907 ±(99.9%) 0.832 ops/ms [Average]
  (min, avg, max) = (12.854, 12.907, 12.935), stdev = 0.046
  CI (99.9%): [12.075, 13.739] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.487 ops/ms
# Warmup Iteration   2: 12.158 ops/ms
# Warmup Iteration   3: 12.522 ops/ms
Iteration   1: 12.601 ops/ms
Iteration   2: 12.576 ops/ms
Iteration   3: 12.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.566 ±(99.9%) 0.744 ops/ms [Average]
  (min, avg, max) = (12.522, 12.566, 12.601), stdev = 0.041
  CI (99.9%): [11.823, 13.310] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.982 ops/ms
# Warmup Iteration   2: 10.345 ops/ms
# Warmup Iteration   3: 10.431 ops/ms
Iteration   1: 10.440 ops/ms
Iteration   2: 10.585 ops/ms
Iteration   3: 10.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.540 ±(99.9%) 1.587 ops/ms [Average]
  (min, avg, max) = (10.440, 10.540, 10.595), stdev = 0.087
  CI (99.9%): [8.953, 12.127] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.170 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.626 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.581 ±(99.9%) 0.004 ms/op
Iteration   1: 2.559 ±(99.9%) 0.004 ms/op
Iteration   2: 2.533 ±(99.9%) 0.004 ms/op
Iteration   3: 2.579 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.557 ±(99.9%) 0.420 ms/op [Average]
  (min, avg, max) = (2.533, 2.557, 2.579), stdev = 0.023
  CI (99.9%): [2.136, 2.977] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.744 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.003 ms/op
Iteration   2: 2.462 ±(99.9%) 0.004 ms/op
Iteration   3: 2.455 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.462 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (2.455, 2.462, 2.469), stdev = 0.007
  CI (99.9%): [2.334, 2.590] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.939 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.004 ms/op
Iteration   1: 2.528 ±(99.9%) 0.005 ms/op
Iteration   2: 2.575 ±(99.9%) 0.004 ms/op
Iteration   3: 2.562 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.555 ±(99.9%) 0.443 ms/op [Average]
  (min, avg, max) = (2.528, 2.555, 2.575), stdev = 0.024
  CI (99.9%): [2.112, 2.998] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.853 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
Iteration   1: 3.078 ±(99.9%) 0.006 ms/op
Iteration   2: 3.054 ±(99.9%) 0.006 ms/op
Iteration   3: 3.072 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.068 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (3.054, 3.068, 3.078), stdev = 0.012
  CI (99.9%): [2.846, 3.290] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.252 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.659 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.588 ±(99.9%) 0.006 ms/op
Iteration   1: 2.581 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.867 ms/op
                 createUser·p0.999:  11.896 ms/op
                 createUser·p0.9999: 13.428 ms/op
                 createUser·p1.00:   13.926 ms/op

Iteration   2: 2.599 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.214 ms/op
                 createUser·p0.50:   2.683 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  9.159 ms/op
                 createUser·p0.9999: 12.266 ms/op
                 createUser·p1.00:   12.845 ms/op

Iteration   3: 2.603 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.166 ms/op
                 createUser·p0.95:   3.293 ms/op
                 createUser·p0.99:   3.944 ms/op
                 createUser·p0.999:  9.044 ms/op
                 createUser·p0.9999: 12.206 ms/op
                 createUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 369657
  mean =      2.594 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 175304 
    [ 2.500,  3.750) = 189836 
    [ 3.750,  5.000) = 3597 
    [ 5.000,  6.250) = 417 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 133 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      2.654 ms/op
     p(90.0000) =      3.154 ms/op
     p(95.0000) =      3.273 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     13.124 ms/op
     p(99.9990) =     13.877 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.803 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  11.715 ms/op
                 existUser·p0.9999: 14.369 ms/op
                 existUser·p1.00:   15.483 ms/op

Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   2.621 ms/op
                 existUser·p0.90:   3.088 ms/op
                 existUser·p0.95:   3.207 ms/op
                 existUser·p0.99:   3.740 ms/op
                 existUser·p0.999:  6.055 ms/op
                 existUser·p0.9999: 13.130 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  8.798 ms/op
                 existUser·p0.9999: 11.935 ms/op
                 existUser·p1.00:   14.500 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 379654
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 183585 
    [ 2.500,  3.750) = 192715 
    [ 3.750,  5.000) = 2633 
    [ 5.000,  6.250) = 302 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      6.406 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     15.284 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.897 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.006 ms/op
Iteration   1: 2.544 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  11.746 ms/op
                 getUser·p0.9999: 13.531 ms/op
                 getUser·p1.00:   14.647 ms/op

Iteration   2: 2.562 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.305 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  10.328 ms/op
                 getUser·p0.9999: 15.024 ms/op
                 getUser·p1.00:   16.417 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.633 ms/op
                 getUser·p0.999:  8.216 ms/op
                 getUser·p0.9999: 11.151 ms/op
                 getUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377511
  mean =      2.541 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 184298 
    [ 2.500,  3.750) = 187170 
    [ 3.750,  5.000) = 4365 
    [ 5.000,  6.250) = 1101 
    [ 6.250,  7.500) = 104 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      8.479 ms/op
     p(99.9900) =     14.176 ms/op
     p(99.9990) =     16.240 ms/op
     p(99.9999) =     16.417 ms/op
    p(100.0000) =     16.417 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.741 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.009 ms/op
Iteration   1: 3.129 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.892 ms/op
                 listUser·p0.50:   3.056 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   5.947 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 10.748 ms/op
                 listUser·p1.00:   10.961 ms/op

Iteration   2: 3.081 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.982 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.598 ms/op
                 listUser·p0.999:  9.667 ms/op
                 listUser·p0.9999: 11.706 ms/op
                 listUser·p1.00:   12.665 ms/op

Iteration   3: 3.085 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  9.144 ms/op
                 listUser·p0.9999: 10.732 ms/op
                 listUser·p1.00:   11.092 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309550
  mean =      3.098 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 74059 
    [ 2.500,  3.750) = 190082 
    [ 3.750,  5.000) = 36863 
    [ 5.000,  6.250) = 6833 
    [ 6.250,  7.500) = 1000 
    [ 7.500,  8.750) = 181 
    [ 8.750, 10.000) = 302 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     10.962 ms/op
     p(99.9990) =     12.532 ms/op
     p(99.9999) =     12.665 ms/op
    p(100.0000) =     12.665 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.408 ± 2.059  ops/ms
ClientPb.existUser                       thrpt       3  12.907 ± 0.832  ops/ms
ClientPb.getUser                         thrpt       3  12.566 ± 0.744  ops/ms
ClientPb.listUser                        thrpt       3  10.540 ± 1.587  ops/ms
ClientPb.createUser                       avgt       3   2.557 ± 0.420   ms/op
ClientPb.existUser                        avgt       3   2.462 ± 0.128   ms/op
ClientPb.getUser                          avgt       3   2.555 ± 0.443   ms/op
ClientPb.listUser                         avgt       3   3.068 ± 0.222   ms/op
ClientPb.createUser                     sample  369657   2.594 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.921           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.654           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.110           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.124           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.926           ms/op
ClientPb.existUser                      sample  379654   2.526 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.978           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.597           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.406           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.582           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.483           ms/op
ClientPb.getUser                        sample  377511   2.541 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.830           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.137           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.479           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.176           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.417           ms/op
ClientPb.listUser                       sample  309550   3.098 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.892           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.031           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.784           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.486           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.962           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.665           ms/op
