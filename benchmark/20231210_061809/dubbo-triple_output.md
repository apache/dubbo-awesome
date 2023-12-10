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
# Warmup Iteration   1: 4.610 ops/ms
# Warmup Iteration   2: 12.081 ops/ms
# Warmup Iteration   3: 12.270 ops/ms
Iteration   1: 12.631 ops/ms
Iteration   2: 12.680 ops/ms
Iteration   3: 12.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.685 ±(99.9%) 1.044 ops/ms [Average]
  (min, avg, max) = (12.631, 12.685, 12.745), stdev = 0.057
  CI (99.9%): [11.642, 13.729] (assumes normal distribution)


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
# Warmup Iteration   1: 8.512 ops/ms
# Warmup Iteration   2: 13.206 ops/ms
# Warmup Iteration   3: 13.244 ops/ms
Iteration   1: 13.294 ops/ms
Iteration   2: 13.233 ops/ms
Iteration   3: 13.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.262 ±(99.9%) 0.552 ops/ms [Average]
  (min, avg, max) = (13.233, 13.262, 13.294), stdev = 0.030
  CI (99.9%): [12.711, 13.814] (assumes normal distribution)


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
# Warmup Iteration   1: 7.846 ops/ms
# Warmup Iteration   2: 12.840 ops/ms
# Warmup Iteration   3: 12.896 ops/ms
Iteration   1: 13.015 ops/ms
Iteration   2: 12.869 ops/ms
Iteration   3: 12.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.890 ±(99.9%) 2.128 ops/ms [Average]
  (min, avg, max) = (12.785, 12.890, 13.015), stdev = 0.117
  CI (99.9%): [10.762, 15.018] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.341 ops/ms
# Warmup Iteration   2: 10.626 ops/ms
# Warmup Iteration   3: 10.699 ops/ms
Iteration   1: 10.724 ops/ms
Iteration   2: 10.781 ops/ms
Iteration   3: 10.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.732 ±(99.9%) 0.827 ops/ms [Average]
  (min, avg, max) = (10.691, 10.732, 10.781), stdev = 0.045
  CI (99.9%): [9.905, 11.559] (assumes normal distribution)


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
# Warmup Iteration   1: 3.957 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.664 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.588 ±(99.9%) 0.004 ms/op
Iteration   1: 2.563 ±(99.9%) 0.005 ms/op
Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
Iteration   3: 2.574 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.564 ±(99.9%) 0.161 ms/op [Average]
  (min, avg, max) = (2.556, 2.564, 2.574), stdev = 0.009
  CI (99.9%): [2.403, 2.725] (assumes normal distribution)


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
# Warmup Iteration   1: 3.673 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.444 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.421 ±(99.9%) 0.004 ms/op
Iteration   1: 2.429 ±(99.9%) 0.004 ms/op
Iteration   2: 2.430 ±(99.9%) 0.004 ms/op
Iteration   3: 2.419 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.426 ±(99.9%) 0.113 ms/op [Average]
  (min, avg, max) = (2.419, 2.426, 2.430), stdev = 0.006
  CI (99.9%): [2.312, 2.539] (assumes normal distribution)


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
# Warmup Iteration   1: 3.795 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.004 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
Iteration   3: 2.511 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.507 ±(99.9%) 0.086 ms/op [Average]
  (min, avg, max) = (2.502, 2.507, 2.511), stdev = 0.005
  CI (99.9%): [2.421, 2.593] (assumes normal distribution)


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
# Warmup Iteration   1: 4.534 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
Iteration   1: 2.996 ±(99.9%) 0.005 ms/op
Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
Iteration   3: 2.984 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.996 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (2.984, 2.996, 3.010), stdev = 0.013
  CI (99.9%): [2.755, 3.238] (assumes normal distribution)


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
# Warmup Iteration   1: 4.043 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.006 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  11.157 ms/op
                 createUser·p0.9999: 14.012 ms/op
                 createUser·p1.00:   14.451 ms/op

Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.613 ms/op
                 createUser·p0.999:  9.321 ms/op
                 createUser·p0.9999: 11.343 ms/op
                 createUser·p1.00:   11.846 ms/op

Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  8.281 ms/op
                 createUser·p0.9999: 10.879 ms/op
                 createUser·p1.00:   13.713 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381307
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 182546 
    [ 2.500,  3.750) = 195225 
    [ 3.750,  5.000) = 2785 
    [ 5.000,  6.250) = 264 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      8.357 ms/op
     p(99.9900) =     13.349 ms/op
     p(99.9990) =     14.293 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


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
# Warmup Iteration   1: 3.725 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
Iteration   1: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.441 ms/op
                 existUser·p0.999:  6.671 ms/op
                 existUser·p0.9999: 13.858 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   2: 2.415 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  8.825 ms/op
                 existUser·p0.9999: 14.881 ms/op
                 existUser·p1.00:   15.991 ms/op

Iteration   3: 2.417 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  7.743 ms/op
                 existUser·p0.9999: 11.199 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396259
  mean =      2.420 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 198853 
    [ 2.500,  3.750) = 194622 
    [ 3.750,  5.000) = 1853 
    [ 5.000,  6.250) = 401 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.506 ms/op
     p(99.9000) =      7.993 ms/op
     p(99.9900) =     14.172 ms/op
     p(99.9990) =     15.402 ms/op
     p(99.9999) =     15.991 ms/op
    p(100.0000) =     15.991 ms/op


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.656 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.592 ms/op
                 getUser·p0.999:  9.060 ms/op
                 getUser·p0.9999: 14.139 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.629 ms/op
                 getUser·p0.999:  9.896 ms/op
                 getUser·p0.9999: 12.757 ms/op
                 getUser·p1.00:   13.206 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  6.167 ms/op
                 getUser·p0.9999: 11.052 ms/op
                 getUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386418
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 191868 
    [ 2.500,  3.750) = 191284 
    [ 3.750,  5.000) = 2523 
    [ 5.000,  6.250) = 266 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      6.664 ms/op
     p(99.9900) =     13.637 ms/op
     p(99.9990) =     14.850 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


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
# Warmup Iteration   1: 4.725 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.008 ms/op
Iteration   1: 2.977 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.778 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.863 ms/op
                 listUser·p0.9999: 11.829 ms/op
                 listUser·p1.00:   12.763 ms/op

Iteration   2: 2.960 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.816 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.777 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.863 ms/op
                 listUser·p0.9999: 12.567 ms/op
                 listUser·p1.00:   13.140 ms/op

Iteration   3: 2.957 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.317 ms/op
                 listUser·p0.999:  9.503 ms/op
                 listUser·p0.9999: 11.366 ms/op
                 listUser·p1.00:   13.746 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323496
  mean =      2.965 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 100549 
    [ 2.500,  3.750) = 187489 
    [ 3.750,  5.000) = 29254 
    [ 5.000,  6.250) = 4849 
    [ 6.250,  7.500) = 529 
    [ 7.500,  8.750) = 151 
    [ 8.750, 10.000) = 267 
    [10.000, 11.250) = 190 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.440 ms/op
     p(99.9000) =      9.757 ms/op
     p(99.9900) =     11.873 ms/op
     p(99.9990) =     12.914 ms/op
     p(99.9999) =     13.746 ms/op
    p(100.0000) =     13.746 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.685 ± 1.044  ops/ms
ClientPb.existUser                       thrpt       3  13.262 ± 0.552  ops/ms
ClientPb.getUser                         thrpt       3  12.890 ± 2.128  ops/ms
ClientPb.listUser                        thrpt       3  10.732 ± 0.827  ops/ms
ClientPb.createUser                       avgt       3   2.564 ± 0.161   ms/op
ClientPb.existUser                        avgt       3   2.426 ± 0.113   ms/op
ClientPb.getUser                          avgt       3   2.507 ± 0.086   ms/op
ClientPb.listUser                         avgt       3   2.996 ± 0.241   ms/op
ClientPb.createUser                     sample  381307   2.515 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.814           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.357           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.349           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.451           ms/op
ClientPb.existUser                      sample  396259   2.420 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.679           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.506           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.993           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.172           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.991           ms/op
ClientPb.getUser                        sample  386418   2.482 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.656           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.650           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.664           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.637           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.024           ms/op
ClientPb.listUser                       sample  323496   2.965 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.778           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.805           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.440           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.757           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.873           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.746           ms/op
