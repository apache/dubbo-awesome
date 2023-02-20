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
# Warmup Iteration   1: 2.586 ops/ms
# Warmup Iteration   2: 6.126 ops/ms
# Warmup Iteration   3: 9.320 ops/ms
Iteration   1: 9.746 ops/ms
Iteration   2: 10.173 ops/ms
Iteration   3: 9.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.942 ±(99.9%) 3.938 ops/ms [Average]
  (min, avg, max) = (9.746, 9.942, 10.173), stdev = 0.216
  CI (99.9%): [6.004, 13.880] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.568 ops/ms
# Warmup Iteration   2: 9.608 ops/ms
# Warmup Iteration   3: 10.073 ops/ms
Iteration   1: 10.532 ops/ms
Iteration   2: 9.849 ops/ms
Iteration   3: 9.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.079 ±(99.9%) 7.153 ops/ms [Average]
  (min, avg, max) = (9.849, 10.079, 10.532), stdev = 0.392
  CI (99.9%): [2.926, 17.232] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.455 ops/ms
# Warmup Iteration   2: 9.561 ops/ms
# Warmup Iteration   3: 9.778 ops/ms
Iteration   1: 9.799 ops/ms
Iteration   2: 10.229 ops/ms
Iteration   3: 10.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.104 ±(99.9%) 4.849 ops/ms [Average]
  (min, avg, max) = (9.799, 10.104, 10.284), stdev = 0.266
  CI (99.9%): [5.255, 14.953] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.120 ops/ms
# Warmup Iteration   2: 7.533 ops/ms
# Warmup Iteration   3: 8.625 ops/ms
Iteration   1: 8.811 ops/ms
Iteration   2: 8.641 ops/ms
Iteration   3: 8.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.616 ±(99.9%) 3.788 ops/ms [Average]
  (min, avg, max) = (8.398, 8.616, 8.811), stdev = 0.208
  CI (99.9%): [4.828, 12.404] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.989 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.496 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.003 ms/op
Iteration   1: 3.289 ±(99.9%) 0.008 ms/op
Iteration   2: 3.291 ±(99.9%) 0.008 ms/op
Iteration   3: 3.137 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.239 ±(99.9%) 1.616 ms/op [Average]
  (min, avg, max) = (3.137, 3.239, 3.291), stdev = 0.089
  CI (99.9%): [1.623, 4.855] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.630 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.491 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.003 ms/op
Iteration   1: 3.094 ±(99.9%) 0.007 ms/op
Iteration   2: 3.019 ±(99.9%) 0.002 ms/op
Iteration   3: 2.994 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.036 ±(99.9%) 0.950 ms/op [Average]
  (min, avg, max) = (2.994, 3.036, 3.094), stdev = 0.052
  CI (99.9%): [2.085, 3.986] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.144 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.410 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.003 ms/op
Iteration   1: 3.222 ±(99.9%) 0.002 ms/op
Iteration   2: 3.204 ±(99.9%) 0.004 ms/op
Iteration   3: 3.120 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.182 ±(99.9%) 0.987 ms/op [Average]
  (min, avg, max) = (3.120, 3.182, 3.222), stdev = 0.054
  CI (99.9%): [2.194, 4.169] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.184 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.961 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.751 ±(99.9%) 0.006 ms/op
Iteration   1: 3.699 ±(99.9%) 0.010 ms/op
Iteration   2: 3.713 ±(99.9%) 0.004 ms/op
Iteration   3: 3.686 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.699 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (3.686, 3.699, 3.713), stdev = 0.013
  CI (99.9%): [3.455, 3.943] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.689 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.008 ms/op
Iteration   1: 3.178 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.534 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  18.170 ms/op
                 createUser·p0.9999: 24.835 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   2: 3.230 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.456 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  14.533 ms/op
                 createUser·p0.9999: 22.423 ms/op
                 createUser·p1.00:   23.069 ms/op

Iteration   3: 3.195 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  15.284 ms/op
                 createUser·p0.9999: 18.939 ms/op
                 createUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299947
  mean =      3.201 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16203 
    [ 2.500,  5.000) = 277591 
    [ 5.000,  7.500) = 5131 
    [ 7.500, 10.000) = 494 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     16.500 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     24.937 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.676 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.007 ms/op
Iteration   1: 2.950 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.048 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.084 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   4.874 ms/op
                 existUser·p0.999:  7.684 ms/op
                 existUser·p0.9999: 19.169 ms/op
                 existUser·p1.00:   19.759 ms/op

Iteration   2: 3.048 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  11.456 ms/op
                 existUser·p0.9999: 21.644 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   3: 3.254 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  9.322 ms/op
                 existUser·p0.9999: 22.058 ms/op
                 existUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311751
  mean =      3.079 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25840 
    [ 2.500,  5.000) = 280875 
    [ 5.000,  7.500) = 4582 
    [ 7.500, 10.000) = 144 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 166 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.321 ms/op
     p(99.9000) =      9.429 ms/op
     p(99.9900) =     21.490 ms/op
     p(99.9990) =     22.533 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 7.832 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.358 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.216 ±(99.9%) 0.009 ms/op
Iteration   1: 3.350 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.354 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   5.210 ms/op
                 getUser·p0.99:   6.815 ms/op
                 getUser·p0.999:  16.974 ms/op
                 getUser·p0.9999: 21.819 ms/op
                 getUser·p1.00:   22.151 ms/op

Iteration   2: 3.092 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.214 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.351 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   5.267 ms/op
                 getUser·p0.999:  12.476 ms/op
                 getUser·p0.9999: 24.794 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   3: 3.139 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.405 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   5.741 ms/op
                 getUser·p0.999:  15.813 ms/op
                 getUser·p0.9999: 24.242 ms/op
                 getUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300757
  mean =      3.190 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10875 
    [ 2.500,  5.000) = 280816 
    [ 5.000,  7.500) = 7855 
    [ 7.500, 10.000) = 606 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      6.492 ms/op
     p(99.9000) =     16.339 ms/op
     p(99.9900) =     24.180 ms/op
     p(99.9990) =     25.460 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 9.122 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.144 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.011 ms/op
Iteration   1: 3.834 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   7.627 ms/op
                 listUser·p0.999:  16.050 ms/op
                 listUser·p0.9999: 29.064 ms/op
                 listUser·p1.00:   30.867 ms/op

Iteration   2: 3.801 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.036 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.202 ms/op
                 listUser·p0.999:  14.118 ms/op
                 listUser·p0.9999: 16.393 ms/op
                 listUser·p1.00:   16.417 ms/op

Iteration   3: 3.734 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.735 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  12.993 ms/op
                 listUser·p0.9999: 19.511 ms/op
                 listUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253428
  mean =      3.789 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 79 
    [ 2.500,  5.000) = 243242 
    [ 5.000,  7.500) = 8182 
    [ 7.500, 10.000) = 1196 
    [10.000, 12.500) = 315 
    [12.500, 15.000) = 244 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     13.664 ms/op
     p(99.9900) =     26.071 ms/op
     p(99.9990) =     29.701 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.942 ± 3.938  ops/ms
ClientPb.existUser                       thrpt       3  10.079 ± 7.153  ops/ms
ClientPb.getUser                         thrpt       3  10.104 ± 4.849  ops/ms
ClientPb.listUser                        thrpt       3   8.616 ± 3.788  ops/ms
ClientPb.createUser                       avgt       3   3.239 ± 1.616   ms/op
ClientPb.existUser                        avgt       3   3.036 ± 0.950   ms/op
ClientPb.getUser                          avgt       3   3.182 ± 0.987   ms/op
ClientPb.listUser                         avgt       3   3.699 ± 0.244   ms/op
ClientPb.createUser                     sample  299947   3.201 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.943           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.658           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.063           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.579           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.500           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.331           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.362           ms/op
ClientPb.existUser                      sample  311751   3.079 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.716           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.026           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.321           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.429           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.490           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.233           ms/op
ClientPb.getUser                        sample  300757   3.190 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.214           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.506           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.492           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.339           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.180           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.952           ms/op
ClientPb.listUser                       sample  253428   3.789 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.384           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.166           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.143           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.664           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.071           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.867           ms/op
