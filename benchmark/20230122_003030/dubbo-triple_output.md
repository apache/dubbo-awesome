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
# Warmup Iteration   1: 2.524 ops/ms
# Warmup Iteration   2: 6.148 ops/ms
# Warmup Iteration   3: 9.368 ops/ms
Iteration   1: 9.703 ops/ms
Iteration   2: 9.723 ops/ms
Iteration   3: 9.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.762 ±(99.9%) 1.565 ops/ms [Average]
  (min, avg, max) = (9.703, 9.762, 9.861), stdev = 0.086
  CI (99.9%): [8.197, 11.327] (assumes normal distribution)


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
# Warmup Iteration   1: 3.876 ops/ms
# Warmup Iteration   2: 9.112 ops/ms
# Warmup Iteration   3: 10.138 ops/ms
Iteration   1: 10.492 ops/ms
Iteration   2: 10.134 ops/ms
Iteration   3: 10.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.271 ±(99.9%) 3.534 ops/ms [Average]
  (min, avg, max) = (10.134, 10.271, 10.492), stdev = 0.194
  CI (99.9%): [6.737, 13.804] (assumes normal distribution)


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
# Warmup Iteration   1: 3.706 ops/ms
# Warmup Iteration   2: 9.072 ops/ms
# Warmup Iteration   3: 9.757 ops/ms
Iteration   1: 10.181 ops/ms
Iteration   2: 9.927 ops/ms
Iteration   3: 10.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.045 ±(99.9%) 2.328 ops/ms [Average]
  (min, avg, max) = (9.927, 10.045, 10.181), stdev = 0.128
  CI (99.9%): [7.718, 12.373] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.386 ops/ms
# Warmup Iteration   2: 7.876 ops/ms
# Warmup Iteration   3: 8.542 ops/ms
Iteration   1: 8.668 ops/ms
Iteration   2: 8.590 ops/ms
Iteration   3: 8.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.526 ±(99.9%) 3.342 ops/ms [Average]
  (min, avg, max) = (8.319, 8.526, 8.668), stdev = 0.183
  CI (99.9%): [5.183, 11.868] (assumes normal distribution)


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
# Warmup Iteration   1: 8.128 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.004 ms/op
Iteration   1: 3.254 ±(99.9%) 0.006 ms/op
Iteration   2: 3.290 ±(99.9%) 0.004 ms/op
Iteration   3: 3.072 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.205 ±(99.9%) 2.137 ms/op [Average]
  (min, avg, max) = (3.072, 3.205, 3.290), stdev = 0.117
  CI (99.9%): [1.068, 5.343] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.360 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.356 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.004 ms/op
Iteration   1: 3.092 ±(99.9%) 0.004 ms/op
Iteration   2: 3.002 ±(99.9%) 0.007 ms/op
Iteration   3: 3.132 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.075 ±(99.9%) 1.215 ms/op [Average]
  (min, avg, max) = (3.002, 3.075, 3.132), stdev = 0.067
  CI (99.9%): [1.860, 4.290] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.868 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.427 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.362 ±(99.9%) 0.001 ms/op
Iteration   1: 3.276 ±(99.9%) 0.005 ms/op
Iteration   2: 3.253 ±(99.9%) 0.006 ms/op
Iteration   3: 3.286 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.272 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (3.253, 3.272, 3.286), stdev = 0.017
  CI (99.9%): [2.963, 3.581] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.221 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.279 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.003 ms/op
Iteration   1: 3.714 ±(99.9%) 0.010 ms/op
Iteration   2: 3.806 ±(99.9%) 0.009 ms/op
Iteration   3: 3.804 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.775 ±(99.9%) 0.954 ms/op [Average]
  (min, avg, max) = (3.714, 3.775, 3.806), stdev = 0.052
  CI (99.9%): [2.820, 4.729] (assumes normal distribution)


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
# Warmup Iteration   1: 8.098 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.010 ms/op
Iteration   1: 3.276 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.176 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  12.435 ms/op
                 createUser·p0.9999: 24.052 ms/op
                 createUser·p1.00:   24.674 ms/op

Iteration   2: 3.180 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.466 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  20.558 ms/op
                 createUser·p0.9999: 26.374 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   3: 3.201 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.308 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.326 ms/op
                 createUser·p0.95:   3.391 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  15.860 ms/op
                 createUser·p0.9999: 23.593 ms/op
                 createUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298153
  mean =      3.218 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22636 
    [ 2.500,  5.000) = 269018 
    [ 5.000,  7.500) = 5482 
    [ 7.500, 10.000) = 509 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.308 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     16.505 ms/op
     p(99.9900) =     25.250 ms/op
     p(99.9990) =     27.329 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.522 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.382 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.008 ms/op
Iteration   1: 3.088 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  11.325 ms/op
                 existUser·p0.9999: 20.796 ms/op
                 existUser·p1.00:   21.922 ms/op

Iteration   2: 3.143 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  12.079 ms/op
                 existUser·p0.9999: 22.708 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   3: 3.094 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.292 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.326 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  13.776 ms/op
                 existUser·p0.9999: 20.535 ms/op
                 existUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308665
  mean =      3.108 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23070 
    [ 2.500,  5.000) = 281475 
    [ 5.000,  7.500) = 3238 
    [ 7.500, 10.000) = 282 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =     13.391 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     23.126 ms/op
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
# Warmup Iteration   1: 6.725 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.266 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.300 ±(99.9%) 0.010 ms/op
Iteration   1: 3.279 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.554 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  16.203 ms/op
                 getUser·p0.9999: 20.554 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   2: 3.305 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.322 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  15.320 ms/op
                 getUser·p0.9999: 21.408 ms/op
                 getUser·p1.00:   22.708 ms/op

Iteration   3: 3.298 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.346 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  9.712 ms/op
                 getUser·p0.9999: 21.440 ms/op
                 getUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291362
  mean =      3.294 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28440 
    [ 2.500,  5.000) = 254167 
    [ 5.000,  7.500) = 7684 
    [ 7.500, 10.000) = 562 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.322 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     15.215 ms/op
     p(99.9900) =     21.295 ms/op
     p(99.9990) =     22.150 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 8.669 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.011 ms/op
Iteration   1: 3.752 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.690 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  16.067 ms/op
                 listUser·p0.9999: 18.691 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   2: 3.714 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  13.828 ms/op
                 listUser·p0.9999: 17.445 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   3: 3.694 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.523 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.145 ms/op
                 listUser·p0.99:   6.291 ms/op
                 listUser·p0.999:  12.427 ms/op
                 listUser·p0.9999: 14.909 ms/op
                 listUser·p1.00:   15.057 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258028
  mean =      3.720 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 251890 
    [ 5.000,  7.500) = 4380 
    [ 7.500, 10.000) = 957 
    [10.000, 12.500) = 345 
    [12.500, 15.000) = 251 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.690 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     18.416 ms/op
     p(99.9990) =     21.111 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.762 ± 1.565  ops/ms
ClientPb.existUser                       thrpt       3  10.271 ± 3.534  ops/ms
ClientPb.getUser                         thrpt       3  10.045 ± 2.328  ops/ms
ClientPb.listUser                        thrpt       3   8.526 ± 3.342  ops/ms
ClientPb.createUser                       avgt       3   3.205 ± 2.137   ms/op
ClientPb.existUser                        avgt       3   3.075 ± 1.215   ms/op
ClientPb.getUser                          avgt       3   3.272 ± 0.309   ms/op
ClientPb.listUser                         avgt       3   3.775 ± 0.954   ms/op
ClientPb.createUser                     sample  298153   3.218 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.308           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.535           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.505           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.250           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.427           ms/op
ClientPb.existUser                      sample  308665   3.108 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.751           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.322           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.202           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.391           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.627           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.233           ms/op
ClientPb.getUser                        sample  291362   3.294 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.322           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.005           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.215           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.295           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.708           ms/op
ClientPb.listUser                       sample  258028   3.720 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.690           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.709           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.959           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.416           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.201           ms/op
