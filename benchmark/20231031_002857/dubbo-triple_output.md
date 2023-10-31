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
# Warmup Iteration   1: 1.785 ops/ms
# Warmup Iteration   2: 4.541 ops/ms
# Warmup Iteration   3: 7.752 ops/ms
Iteration   1: 8.096 ops/ms
Iteration   2: 7.981 ops/ms
Iteration   3: 8.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.065 ±(99.9%) 1.342 ops/ms [Average]
  (min, avg, max) = (7.981, 8.065, 8.119), stdev = 0.074
  CI (99.9%): [6.723, 9.408] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.242 ops/ms
# Warmup Iteration   2: 7.138 ops/ms
# Warmup Iteration   3: 8.783 ops/ms
Iteration   1: 8.747 ops/ms
Iteration   2: 8.998 ops/ms
Iteration   3: 8.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.804 ±(99.9%) 3.153 ops/ms [Average]
  (min, avg, max) = (8.666, 8.804, 8.998), stdev = 0.173
  CI (99.9%): [5.650, 11.957] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.450 ops/ms
# Warmup Iteration   2: 7.587 ops/ms
# Warmup Iteration   3: 8.424 ops/ms
Iteration   1: 8.109 ops/ms
Iteration   2: 8.413 ops/ms
Iteration   3: 8.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.257 ±(99.9%) 2.774 ops/ms [Average]
  (min, avg, max) = (8.109, 8.257, 8.413), stdev = 0.152
  CI (99.9%): [5.483, 11.032] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.286 ops/ms
# Warmup Iteration   2: 6.051 ops/ms
# Warmup Iteration   3: 6.973 ops/ms
Iteration   1: 6.848 ops/ms
Iteration   2: 6.664 ops/ms
Iteration   3: 6.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.776 ±(99.9%) 1.795 ops/ms [Average]
  (min, avg, max) = (6.664, 6.776, 6.848), stdev = 0.098
  CI (99.9%): [4.982, 8.571] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.770 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.824 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.952 ±(99.9%) 0.007 ms/op
Iteration   1: 4.056 ±(99.9%) 0.003 ms/op
Iteration   2: 3.791 ±(99.9%) 0.006 ms/op
Iteration   3: 3.884 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.910 ±(99.9%) 2.456 ms/op [Average]
  (min, avg, max) = (3.791, 3.910, 4.056), stdev = 0.135
  CI (99.9%): [1.454, 6.366] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.541 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.210 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.708 ±(99.9%) 0.002 ms/op
Iteration   1: 3.582 ±(99.9%) 0.006 ms/op
Iteration   2: 3.482 ±(99.9%) 0.003 ms/op
Iteration   3: 3.558 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.541 ±(99.9%) 0.944 ms/op [Average]
  (min, avg, max) = (3.482, 3.541, 3.582), stdev = 0.052
  CI (99.9%): [2.596, 4.485] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.760 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.846 ±(99.9%) 0.005 ms/op
Iteration   1: 3.857 ±(99.9%) 0.006 ms/op
Iteration   2: 4.029 ±(99.9%) 0.005 ms/op
Iteration   3: 3.867 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.918 ±(99.9%) 1.764 ms/op [Average]
  (min, avg, max) = (3.857, 3.918, 4.029), stdev = 0.097
  CI (99.9%): [2.154, 5.682] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.731 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.598 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.948 ±(99.9%) 0.006 ms/op
Iteration   1: 4.881 ±(99.9%) 0.008 ms/op
Iteration   2: 4.639 ±(99.9%) 0.007 ms/op
Iteration   3: 4.685 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.735 ±(99.9%) 2.341 ms/op [Average]
  (min, avg, max) = (4.639, 4.735, 4.881), stdev = 0.128
  CI (99.9%): [2.394, 7.076] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.599 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.944 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.180 ±(99.9%) 0.015 ms/op
Iteration   1: 3.952 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.542 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   6.627 ms/op
                 createUser·p0.999:  10.019 ms/op
                 createUser·p0.9999: 20.840 ms/op
                 createUser·p1.00:   21.660 ms/op

Iteration   2: 4.002 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.888 ms/op
                 createUser·p0.50:   3.871 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   6.914 ms/op
                 createUser·p0.999:  20.906 ms/op
                 createUser·p0.9999: 23.659 ms/op
                 createUser·p1.00:   24.805 ms/op

Iteration   3: 3.933 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.860 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  22.614 ms/op
                 createUser·p0.9999: 29.126 ms/op
                 createUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242289
  mean =      3.962 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 452 
    [ 2.500,  5.000) = 233662 
    [ 5.000,  7.500) = 6679 
    [ 7.500, 10.000) = 874 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     27.939 ms/op
     p(99.9990) =     30.381 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.826 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.655 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.022 ±(99.9%) 0.011 ms/op
Iteration   1: 3.975 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   4.522 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   7.561 ms/op
                 existUser·p0.999:  11.296 ms/op
                 existUser·p0.9999: 25.819 ms/op
                 existUser·p1.00:   27.591 ms/op

Iteration   2: 3.928 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.110 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  24.379 ms/op
                 existUser·p0.9999: 27.090 ms/op
                 existUser·p1.00:   28.410 ms/op

Iteration   3: 3.909 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.905 ms/op
                 existUser·p0.50:   3.863 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  14.623 ms/op
                 existUser·p0.9999: 30.889 ms/op
                 existUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243700
  mean =      3.937 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 303 
    [ 2.500,  5.000) = 234490 
    [ 5.000,  7.500) = 7065 
    [ 7.500, 10.000) = 1217 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     16.338 ms/op
     p(99.9900) =     29.295 ms/op
     p(99.9990) =     31.261 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.868 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 4.433 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.049 ±(99.9%) 0.011 ms/op
Iteration   1: 3.968 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.995 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  12.068 ms/op
                 getUser·p0.9999: 21.594 ms/op
                 getUser·p1.00:   22.020 ms/op

Iteration   2: 3.874 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   6.807 ms/op
                 getUser·p0.999:  20.034 ms/op
                 getUser·p0.9999: 22.289 ms/op
                 getUser·p1.00:   22.938 ms/op

Iteration   3: 3.807 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.884 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   7.104 ms/op
                 getUser·p0.999:  11.076 ms/op
                 getUser·p0.9999: 22.793 ms/op
                 getUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 247309
  mean =      3.882 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 456 
    [ 2.500,  5.000) = 238351 
    [ 5.000,  7.500) = 6819 
    [ 7.500, 10.000) = 1071 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 165 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.753 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     15.181 ms/op
     p(99.9900) =     22.234 ms/op
     p(99.9990) =     23.398 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.339 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 5.095 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.842 ±(99.9%) 0.016 ms/op
Iteration   1: 4.802 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   8.339 ms/op
                 listUser·p0.999:  22.381 ms/op
                 listUser·p0.9999: 25.417 ms/op
                 listUser·p1.00:   26.837 ms/op

Iteration   2: 4.875 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 21.611 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   3: 4.747 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.847 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  16.908 ms/op
                 listUser·p0.9999: 20.358 ms/op
                 listUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199586
  mean =      4.807 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 156075 
    [ 5.000,  7.500) = 39212 
    [ 7.500, 10.000) = 3241 
    [10.000, 12.500) = 333 
    [12.500, 15.000) = 280 
    [15.000, 17.500) = 196 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.440 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     24.028 ms/op
     p(99.9990) =     26.380 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.065 ± 1.342  ops/ms
ClientPb.existUser                       thrpt       3   8.804 ± 3.153  ops/ms
ClientPb.getUser                         thrpt       3   8.257 ± 2.774  ops/ms
ClientPb.listUser                        thrpt       3   6.776 ± 1.795  ops/ms
ClientPb.createUser                       avgt       3   3.910 ± 2.456   ms/op
ClientPb.existUser                        avgt       3   3.541 ± 0.944   ms/op
ClientPb.getUser                          avgt       3   3.918 ± 1.764   ms/op
ClientPb.listUser                         avgt       3   4.735 ± 2.341   ms/op
ClientPb.createUser                     sample  242289   3.962 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.542           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.473           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.801           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.832           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.333           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.939           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.736           ms/op
ClientPb.existUser                      sample  243700   3.937 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.110           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.407           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.792           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.898           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.338           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.295           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.457           ms/op
ClientPb.getUser                        sample  247309   3.882 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.753           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.686           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.939           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.181           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.234           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.527           ms/op
ClientPb.listUser                       sample  199586   4.807 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.440           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.300           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.536           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.088           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.028           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.837           ms/op
