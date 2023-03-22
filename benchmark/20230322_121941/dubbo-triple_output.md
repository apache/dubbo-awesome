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
# Warmup Iteration   1: 2.645 ops/ms
# Warmup Iteration   2: 5.925 ops/ms
# Warmup Iteration   3: 9.292 ops/ms
Iteration   1: 9.680 ops/ms
Iteration   2: 9.284 ops/ms
Iteration   3: 10.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.703 ±(99.9%) 7.872 ops/ms [Average]
  (min, avg, max) = (9.284, 9.703, 10.146), stdev = 0.432
  CI (99.9%): [1.831, 17.575] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.861 ops/ms
# Warmup Iteration   2: 9.558 ops/ms
# Warmup Iteration   3: 10.610 ops/ms
Iteration   1: 10.039 ops/ms
Iteration   2: 10.592 ops/ms
Iteration   3: 10.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.246 ±(99.9%) 5.494 ops/ms [Average]
  (min, avg, max) = (10.039, 10.246, 10.592), stdev = 0.301
  CI (99.9%): [4.752, 15.740] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.412 ops/ms
# Warmup Iteration   2: 9.137 ops/ms
# Warmup Iteration   3: 9.739 ops/ms
Iteration   1: 9.891 ops/ms
Iteration   2: 9.796 ops/ms
Iteration   3: 9.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.751 ±(99.9%) 3.054 ops/ms [Average]
  (min, avg, max) = (9.565, 9.751, 9.891), stdev = 0.167
  CI (99.9%): [6.697, 12.805] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.263 ops/ms
# Warmup Iteration   2: 7.473 ops/ms
# Warmup Iteration   3: 8.527 ops/ms
Iteration   1: 8.563 ops/ms
Iteration   2: 8.610 ops/ms
Iteration   3: 8.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.567 ±(99.9%) 0.744 ops/ms [Average]
  (min, avg, max) = (8.528, 8.567, 8.610), stdev = 0.041
  CI (99.9%): [7.823, 9.311] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.998 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.005 ms/op
Iteration   1: 3.273 ±(99.9%) 0.008 ms/op
Iteration   2: 3.294 ±(99.9%) 0.007 ms/op
Iteration   3: 3.149 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.239 ±(99.9%) 1.430 ms/op [Average]
  (min, avg, max) = (3.149, 3.239, 3.294), stdev = 0.078
  CI (99.9%): [1.808, 4.669] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.969 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.358 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.006 ms/op
Iteration   1: 3.144 ±(99.9%) 0.004 ms/op
Iteration   2: 3.035 ±(99.9%) 0.003 ms/op
Iteration   3: 3.071 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.084 ±(99.9%) 1.012 ms/op [Average]
  (min, avg, max) = (3.035, 3.084, 3.144), stdev = 0.055
  CI (99.9%): [2.071, 4.096] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.198 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.003 ms/op
Iteration   1: 3.163 ±(99.9%) 0.006 ms/op
Iteration   2: 3.228 ±(99.9%) 0.004 ms/op
Iteration   3: 3.124 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.172 ±(99.9%) 0.964 ms/op [Average]
  (min, avg, max) = (3.124, 3.172, 3.228), stdev = 0.053
  CI (99.9%): [2.207, 4.136] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.358 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.007 ms/op
Iteration   1: 3.741 ±(99.9%) 0.009 ms/op
Iteration   2: 3.671 ±(99.9%) 0.010 ms/op
Iteration   3: 3.814 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.742 ±(99.9%) 1.307 ms/op [Average]
  (min, avg, max) = (3.671, 3.742, 3.814), stdev = 0.072
  CI (99.9%): [2.435, 5.049] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.239 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.717 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.009 ms/op
Iteration   1: 3.211 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  10.474 ms/op
                 createUser·p0.9999: 25.462 ms/op
                 createUser·p1.00:   27.689 ms/op

Iteration   2: 3.283 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  19.058 ms/op
                 createUser·p0.9999: 22.258 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   3: 3.306 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.233 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  14.598 ms/op
                 createUser·p0.9999: 18.820 ms/op
                 createUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293829
  mean =      3.266 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17465 
    [ 2.500,  5.000) = 268466 
    [ 5.000,  7.500) = 6994 
    [ 7.500, 10.000) = 455 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     16.095 ms/op
     p(99.9900) =     24.445 ms/op
     p(99.9990) =     27.462 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 8.218 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.303 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.008 ms/op
Iteration   1: 3.075 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.412 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  8.897 ms/op
                 existUser·p0.9999: 19.877 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  12.301 ms/op
                 existUser·p0.9999: 21.934 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   3: 3.098 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.149 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  16.264 ms/op
                 existUser·p0.9999: 26.488 ms/op
                 existUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309413
  mean =      3.102 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24011 
    [ 2.500,  5.000) = 280654 
    [ 5.000,  7.500) = 4028 
    [ 7.500, 10.000) = 366 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 189 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      5.340 ms/op
     p(99.9000) =     15.073 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     28.103 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 7.853 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.471 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.009 ms/op
Iteration   1: 3.184 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   5.963 ms/op
                 getUser·p0.999:  15.270 ms/op
                 getUser·p0.9999: 21.398 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   2: 3.131 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.556 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.568 ms/op
                 getUser·p0.99:   5.128 ms/op
                 getUser·p0.999:  9.534 ms/op
                 getUser·p0.9999: 26.706 ms/op
                 getUser·p1.00:   28.049 ms/op

Iteration   3: 3.253 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   5.782 ms/op
                 getUser·p0.999:  10.384 ms/op
                 getUser·p0.9999: 25.625 ms/op
                 getUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300827
  mean =      3.189 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16760 
    [ 2.500,  5.000) = 277914 
    [ 5.000,  7.500) = 4940 
    [ 7.500, 10.000) = 721 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     15.024 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     27.951 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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
# Warmup Iteration   1: 8.687 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.254 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.778 ±(99.9%) 0.011 ms/op
Iteration   1: 3.771 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.896 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.117 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.144 ms/op
                 listUser·p0.999:  14.320 ms/op
                 listUser·p0.9999: 20.317 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   2: 3.820 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  15.035 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   3: 3.752 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.122 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  13.038 ms/op
                 listUser·p0.9999: 17.136 ms/op
                 listUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253660
  mean =      3.781 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 73 
    [ 2.500,  5.000) = 244398 
    [ 5.000,  7.500) = 6967 
    [ 7.500, 10.000) = 1510 
    [10.000, 12.500) = 314 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.896 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     13.784 ms/op
     p(99.9900) =     19.268 ms/op
     p(99.9990) =     20.689 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.703 ± 7.872  ops/ms
ClientPb.existUser                       thrpt       3  10.246 ± 5.494  ops/ms
ClientPb.getUser                         thrpt       3   9.751 ± 3.054  ops/ms
ClientPb.listUser                        thrpt       3   8.567 ± 0.744  ops/ms
ClientPb.createUser                       avgt       3   3.239 ± 1.430   ms/op
ClientPb.existUser                        avgt       3   3.084 ± 1.012   ms/op
ClientPb.getUser                          avgt       3   3.172 ± 0.964   ms/op
ClientPb.listUser                         avgt       3   3.742 ± 1.307   ms/op
ClientPb.createUser                     sample  293829   3.266 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.085           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.620           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.095           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.445           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.689           ms/op
ClientPb.existUser                      sample  309413   3.102 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.733           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.342           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.340           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.073           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.494           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.475           ms/op
ClientPb.getUser                        sample  300827   3.189 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.815           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.527           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.669           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.024           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.051           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.049           ms/op
ClientPb.listUser                       sample  253660   3.781 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.896           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.629           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.092           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.266           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.784           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.268           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.972           ms/op
