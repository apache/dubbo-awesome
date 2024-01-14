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
# Warmup Iteration   1: 4.710 ops/ms
# Warmup Iteration   2: 12.120 ops/ms
# Warmup Iteration   3: 12.556 ops/ms
Iteration   1: 12.625 ops/ms
Iteration   2: 12.704 ops/ms
Iteration   3: 12.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.682 ±(99.9%) 0.903 ops/ms [Average]
  (min, avg, max) = (12.625, 12.682, 12.717), stdev = 0.050
  CI (99.9%): [11.778, 13.585] (assumes normal distribution)


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
# Warmup Iteration   1: 7.928 ops/ms
# Warmup Iteration   2: 13.210 ops/ms
# Warmup Iteration   3: 13.198 ops/ms
Iteration   1: 13.207 ops/ms
Iteration   2: 13.283 ops/ms
Iteration   3: 13.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.165 ±(99.9%) 2.628 ops/ms [Average]
  (min, avg, max) = (13.005, 13.165, 13.283), stdev = 0.144
  CI (99.9%): [10.537, 15.793] (assumes normal distribution)


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
# Warmup Iteration   1: 7.702 ops/ms
# Warmup Iteration   2: 13.054 ops/ms
# Warmup Iteration   3: 12.924 ops/ms
Iteration   1: 13.016 ops/ms
Iteration   2: 12.898 ops/ms
Iteration   3: 13.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.978 ±(99.9%) 1.263 ops/ms [Average]
  (min, avg, max) = (12.898, 12.978, 13.020), stdev = 0.069
  CI (99.9%): [11.715, 14.241] (assumes normal distribution)


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
# Warmup Iteration   1: 6.525 ops/ms
# Warmup Iteration   2: 10.530 ops/ms
# Warmup Iteration   3: 10.645 ops/ms
Iteration   1: 10.652 ops/ms
Iteration   2: 10.673 ops/ms
Iteration   3: 10.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.637 ±(99.9%) 0.825 ops/ms [Average]
  (min, avg, max) = (10.586, 10.637, 10.673), stdev = 0.045
  CI (99.9%): [9.812, 11.462] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.058 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
Iteration   1: 2.476 ±(99.9%) 0.003 ms/op
Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
Iteration   3: 2.504 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.495 ±(99.9%) 0.307 ms/op [Average]
  (min, avg, max) = (2.476, 2.495, 2.506), stdev = 0.017
  CI (99.9%): [2.188, 2.802] (assumes normal distribution)


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
# Warmup Iteration   1: 3.657 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.453 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.398 ±(99.9%) 0.004 ms/op
Iteration   1: 2.422 ±(99.9%) 0.005 ms/op
Iteration   2: 2.388 ±(99.9%) 0.004 ms/op
Iteration   3: 2.431 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.414 ±(99.9%) 0.412 ms/op [Average]
  (min, avg, max) = (2.388, 2.414, 2.431), stdev = 0.023
  CI (99.9%): [2.001, 2.826] (assumes normal distribution)


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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.004 ms/op
Iteration   1: 2.461 ±(99.9%) 0.004 ms/op
Iteration   2: 2.460 ±(99.9%) 0.004 ms/op
Iteration   3: 2.455 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.459 ±(99.9%) 0.060 ms/op [Average]
  (min, avg, max) = (2.455, 2.459, 2.461), stdev = 0.003
  CI (99.9%): [2.399, 2.519] (assumes normal distribution)


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
# Warmup Iteration   1: 4.628 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.005 ms/op
Iteration   1: 2.988 ±(99.9%) 0.006 ms/op
Iteration   2: 3.011 ±(99.9%) 0.004 ms/op
Iteration   3: 3.015 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.005 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (2.988, 3.005, 3.015), stdev = 0.015
  CI (99.9%): [2.733, 3.277] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.177 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.656 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.006 ms/op
Iteration   1: 2.493 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.714 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  12.026 ms/op
                 createUser·p0.9999: 14.159 ms/op
                 createUser·p1.00:   15.352 ms/op

Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  8.260 ms/op
                 createUser·p0.9999: 12.471 ms/op
                 createUser·p1.00:   13.074 ms/op

Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.975 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  9.159 ms/op
                 createUser·p0.9999: 12.329 ms/op
                 createUser·p1.00:   15.761 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385716
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 188875 
    [ 2.500,  3.750) = 193142 
    [ 3.750,  5.000) = 2905 
    [ 5.000,  6.250) = 259 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 141 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     13.400 ms/op
     p(99.9990) =     14.818 ms/op
     p(99.9999) =     15.761 ms/op
    p(100.0000) =     15.761 ms/op


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
# Warmup Iteration   1: 3.669 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.464 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.414 ±(99.9%) 0.005 ms/op
Iteration   1: 2.408 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   2.429 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  6.360 ms/op
                 existUser·p0.9999: 16.876 ms/op
                 existUser·p1.00:   17.727 ms/op

Iteration   2: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.412 ms/op
                 existUser·p0.999:  5.464 ms/op
                 existUser·p0.9999: 13.905 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.736 ms/op
                 existUser·p0.999:  7.891 ms/op
                 existUser·p0.9999: 12.891 ms/op
                 existUser·p1.00:   13.877 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396128
  mean =      2.421 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 202285 
    [ 2.500,  3.750) = 190780 
    [ 3.750,  5.000) = 2267 
    [ 5.000,  6.250) = 251 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 112 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.568 ms/op
     p(99.9000) =      7.548 ms/op
     p(99.9900) =     15.761 ms/op
     p(99.9990) =     17.118 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 4.207 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.640 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.690 ms/op
                 getUser·p0.999:  11.231 ms/op
                 getUser·p0.9999: 15.044 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   2: 2.520 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  9.341 ms/op
                 getUser·p0.9999: 14.942 ms/op
                 getUser·p1.00:   15.794 ms/op

Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  7.833 ms/op
                 getUser·p0.9999: 10.366 ms/op
                 getUser·p1.00:   10.650 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382703
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 189169 
    [ 2.500,  3.750) = 188629 
    [ 3.750,  5.000) = 3664 
    [ 5.000,  6.250) = 674 
    [ 6.250,  7.500) = 119 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 115 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      8.110 ms/op
     p(99.9900) =     14.667 ms/op
     p(99.9990) =     15.761 ms/op
     p(99.9999) =     15.794 ms/op
    p(100.0000) =     15.794 ms/op


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
# Warmup Iteration   1: 4.622 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.009 ms/op
Iteration   1: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.594 ms/op
                 listUser·p0.9999: 11.840 ms/op
                 listUser·p1.00:   12.452 ms/op

Iteration   2: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.996 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.580 ms/op
                 listUser·p0.999:  9.666 ms/op
                 listUser·p0.9999: 11.818 ms/op
                 listUser·p1.00:   13.287 ms/op

Iteration   3: 3.011 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.035 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 10.639 ms/op
                 listUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319070
  mean =      3.006 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 138 
    [ 1.250,  2.500) = 94739 
    [ 2.500,  3.750) = 184500 
    [ 3.750,  5.000) = 32173 
    [ 5.000,  6.250) = 6254 
    [ 6.250,  7.500) = 573 
    [ 7.500,  8.750) = 194 
    [ 8.750, 10.000) = 295 
    [10.000, 11.250) = 137 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     11.438 ms/op
     p(99.9990) =     12.903 ms/op
     p(99.9999) =     13.287 ms/op
    p(100.0000) =     13.287 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.682 ± 0.903  ops/ms
ClientPb.existUser                       thrpt       3  13.165 ± 2.628  ops/ms
ClientPb.getUser                         thrpt       3  12.978 ± 1.263  ops/ms
ClientPb.listUser                        thrpt       3  10.637 ± 0.825  ops/ms
ClientPb.createUser                       avgt       3   2.495 ± 0.307   ms/op
ClientPb.existUser                        avgt       3   2.414 ± 0.412   ms/op
ClientPb.getUser                          avgt       3   2.459 ± 0.060   ms/op
ClientPb.listUser                         avgt       3   3.005 ± 0.272   ms/op
ClientPb.createUser                     sample  385716   2.486 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.714           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.544           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.388           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.400           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.761           ms/op
ClientPb.existUser                      sample  396128   2.421 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.927           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.454           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.548           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.761           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.727           ms/op
ClientPb.getUser                        sample  382703   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.833           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.110           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.667           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.794           ms/op
ClientPb.listUser                       sample  319070   3.006 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.932           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.454           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.438           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.287           ms/op
