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
# Warmup Iteration   1: 4.540 ops/ms
# Warmup Iteration   2: 11.877 ops/ms
# Warmup Iteration   3: 12.232 ops/ms
Iteration   1: 12.514 ops/ms
Iteration   2: 12.141 ops/ms
Iteration   3: 12.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.381 ±(99.9%) 3.797 ops/ms [Average]
  (min, avg, max) = (12.141, 12.381, 12.514), stdev = 0.208
  CI (99.9%): [8.583, 16.178] (assumes normal distribution)


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
# Warmup Iteration   1: 7.473 ops/ms
# Warmup Iteration   2: 12.704 ops/ms
# Warmup Iteration   3: 12.887 ops/ms
Iteration   1: 13.092 ops/ms
Iteration   2: 13.187 ops/ms
Iteration   3: 13.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.128 ±(99.9%) 0.949 ops/ms [Average]
  (min, avg, max) = (13.092, 13.128, 13.187), stdev = 0.052
  CI (99.9%): [12.179, 14.077] (assumes normal distribution)


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
# Warmup Iteration   1: 6.780 ops/ms
# Warmup Iteration   2: 11.886 ops/ms
# Warmup Iteration   3: 12.418 ops/ms
Iteration   1: 12.527 ops/ms
Iteration   2: 12.639 ops/ms
Iteration   3: 12.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.631 ±(99.9%) 1.834 ops/ms [Average]
  (min, avg, max) = (12.527, 12.631, 12.727), stdev = 0.101
  CI (99.9%): [10.797, 14.465] (assumes normal distribution)


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
# Warmup Iteration   1: 6.721 ops/ms
# Warmup Iteration   2: 10.626 ops/ms
# Warmup Iteration   3: 10.812 ops/ms
Iteration   1: 10.788 ops/ms
Iteration   2: 10.991 ops/ms
Iteration   3: 10.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.869 ±(99.9%) 1.959 ops/ms [Average]
  (min, avg, max) = (10.788, 10.869, 10.991), stdev = 0.107
  CI (99.9%): [8.910, 12.828] (assumes normal distribution)


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
# Warmup Iteration   1: 4.010 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.008 ms/op
Iteration   1: 2.494 ±(99.9%) 0.008 ms/op
Iteration   2: 2.509 ±(99.9%) 0.007 ms/op
Iteration   3: 2.490 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.498 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (2.490, 2.498, 2.509), stdev = 0.010
  CI (99.9%): [2.311, 2.684] (assumes normal distribution)


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
# Warmup Iteration   1: 3.701 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.004 ms/op
Iteration   1: 2.459 ±(99.9%) 0.003 ms/op
Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
Iteration   3: 2.449 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.459 ±(99.9%) 0.195 ms/op [Average]
  (min, avg, max) = (2.449, 2.459, 2.470), stdev = 0.011
  CI (99.9%): [2.264, 2.655] (assumes normal distribution)


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
# Warmup Iteration   1: 4.010 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.004 ms/op
Iteration   1: 2.504 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.534 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.516 ±(99.9%) 0.289 ms/op [Average]
  (min, avg, max) = (2.504, 2.516, 2.534), stdev = 0.016
  CI (99.9%): [2.227, 2.805] (assumes normal distribution)


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
# Warmup Iteration   1: 4.819 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.005 ms/op
Iteration   1: 2.998 ±(99.9%) 0.007 ms/op
Iteration   2: 2.988 ±(99.9%) 0.005 ms/op
Iteration   3: 2.993 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.993 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (2.988, 2.993, 2.998), stdev = 0.005
  CI (99.9%): [2.894, 3.092] (assumes normal distribution)


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
# Warmup Iteration   1: 4.136 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.659 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  10.965 ms/op
                 createUser·p0.9999: 13.271 ms/op
                 createUser·p1.00:   14.025 ms/op

Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  9.406 ms/op
                 createUser·p0.9999: 11.620 ms/op
                 createUser·p1.00:   12.059 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.036 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  9.208 ms/op
                 createUser·p0.9999: 11.212 ms/op
                 createUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383924
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 185309 
    [ 2.500,  5.000) = 197975 
    [ 5.000,  7.500) = 237 
    [ 7.500, 10.000) = 100 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      9.209 ms/op
     p(99.9900) =     13.084 ms/op
     p(99.9990) =     13.773 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.445 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
Iteration   1: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.838 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.450 ms/op
                 existUser·p0.999:  9.013 ms/op
                 existUser·p0.9999: 14.680 ms/op
                 existUser·p1.00:   15.548 ms/op

Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.979 ms/op
                 existUser·p0.50:   2.617 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  5.710 ms/op
                 existUser·p0.9999: 13.697 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.171 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.576 ms/op
                 existUser·p0.999:  6.678 ms/op
                 existUser·p0.9999: 12.287 ms/op
                 existUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390619
  mean =      2.456 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 188648 
    [ 2.500,  3.750) = 199006 
    [ 3.750,  5.000) = 2029 
    [ 5.000,  6.250) = 534 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.551 ms/op
     p(99.9000) =      6.136 ms/op
     p(99.9900) =     13.762 ms/op
     p(99.9990) =     14.844 ms/op
     p(99.9999) =     15.548 ms/op
    p(100.0000) =     15.548 ms/op


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
# Warmup Iteration   1: 4.076 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.006 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.654 ms/op
                 getUser·p0.999:  7.566 ms/op
                 getUser·p0.9999: 14.197 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  9.290 ms/op
                 getUser·p0.9999: 12.936 ms/op
                 getUser·p1.00:   13.550 ms/op

Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  6.225 ms/op
                 getUser·p0.9999: 11.030 ms/op
                 getUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385054
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 190281 
    [ 2.500,  3.750) = 189929 
    [ 3.750,  5.000) = 3754 
    [ 5.000,  6.250) = 616 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      7.061 ms/op
     p(99.9900) =     13.746 ms/op
     p(99.9990) =     14.486 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


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
# Warmup Iteration   1: 4.825 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.009 ms/op
Iteration   1: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.845 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.775 ms/op
                 listUser·p0.999:  8.815 ms/op
                 listUser·p0.9999: 11.729 ms/op
                 listUser·p1.00:   11.993 ms/op

Iteration   2: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.646 ms/op
                 listUser·p0.999:  9.880 ms/op
                 listUser·p0.9999: 11.738 ms/op
                 listUser·p1.00:   12.599 ms/op

Iteration   3: 3.053 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.833 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.786 ms/op
                 listUser·p0.9999: 52.953 ms/op
                 listUser·p1.00:   54.002 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316412
  mean =      3.031 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 308329 
    [ 5.000, 10.000) = 7846 
    [10.000, 15.000) = 194 
    [15.000, 20.000) = 8 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 6 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     31.645 ms/op
     p(99.9990) =     53.477 ms/op
     p(99.9999) =     54.002 ms/op
    p(100.0000) =     54.002 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.381 ± 3.797  ops/ms
ClientPb.existUser                       thrpt       3  13.128 ± 0.949  ops/ms
ClientPb.getUser                         thrpt       3  12.631 ± 1.834  ops/ms
ClientPb.listUser                        thrpt       3  10.869 ± 1.959  ops/ms
ClientPb.createUser                       avgt       3   2.498 ± 0.187   ms/op
ClientPb.existUser                        avgt       3   2.459 ± 0.195   ms/op
ClientPb.getUser                          avgt       3   2.516 ± 0.289   ms/op
ClientPb.listUser                         avgt       3   2.993 ± 0.099   ms/op
ClientPb.createUser                     sample  383924   2.497 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.931           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.674           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.209           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.084           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.364           ms/op
ClientPb.existUser                      sample  390619   2.456 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.838           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.589           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.136           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.762           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.548           ms/op
ClientPb.getUser                        sample  385054   2.491 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.731           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.061           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.746           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.844           ms/op
ClientPb.listUser                       sample  316412   3.031 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.833           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.535           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.645           ms/op
ClientPb.listUser:listUser·p1.00        sample          54.002           ms/op
