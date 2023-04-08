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
# Warmup Iteration   1: 2.606 ops/ms
# Warmup Iteration   2: 5.751 ops/ms
# Warmup Iteration   3: 9.119 ops/ms
Iteration   1: 9.966 ops/ms
Iteration   2: 9.542 ops/ms
Iteration   3: 10.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.909 ±(99.9%) 6.242 ops/ms [Average]
  (min, avg, max) = (9.542, 9.909, 10.219), stdev = 0.342
  CI (99.9%): [3.668, 16.151] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.876 ops/ms
# Warmup Iteration   2: 9.248 ops/ms
# Warmup Iteration   3: 10.234 ops/ms
Iteration   1: 10.246 ops/ms
Iteration   2: 10.622 ops/ms
Iteration   3: 10.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.396 ±(99.9%) 3.636 ops/ms [Average]
  (min, avg, max) = (10.246, 10.396, 10.622), stdev = 0.199
  CI (99.9%): [6.760, 14.032] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.429 ops/ms
# Warmup Iteration   2: 8.421 ops/ms
# Warmup Iteration   3: 9.313 ops/ms
Iteration   1: 9.326 ops/ms
Iteration   2: 9.895 ops/ms
Iteration   3: 10.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.768 ±(99.9%) 7.195 ops/ms [Average]
  (min, avg, max) = (9.326, 9.768, 10.084), stdev = 0.394
  CI (99.9%): [2.574, 16.963] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.239 ops/ms
# Warmup Iteration   2: 7.423 ops/ms
# Warmup Iteration   3: 8.103 ops/ms
Iteration   1: 8.659 ops/ms
Iteration   2: 8.471 ops/ms
Iteration   3: 8.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.575 ±(99.9%) 1.742 ops/ms [Average]
  (min, avg, max) = (8.471, 8.575, 8.659), stdev = 0.095
  CI (99.9%): [6.833, 10.317] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.651 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.006 ms/op
Iteration   1: 3.164 ±(99.9%) 0.005 ms/op
Iteration   2: 3.322 ±(99.9%) 0.003 ms/op
Iteration   3: 3.214 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.233 ±(99.9%) 1.473 ms/op [Average]
  (min, avg, max) = (3.164, 3.233, 3.322), stdev = 0.081
  CI (99.9%): [1.761, 4.706] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.484 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.336 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.008 ms/op
Iteration   1: 3.076 ±(99.9%) 0.007 ms/op
Iteration   2: 3.120 ±(99.9%) 0.004 ms/op
Iteration   3: 3.030 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.075 ±(99.9%) 0.819 ms/op [Average]
  (min, avg, max) = (3.030, 3.075, 3.120), stdev = 0.045
  CI (99.9%): [2.257, 3.894] (assumes normal distribution)


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
# Warmup Iteration   1: 8.277 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.461 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.003 ms/op
Iteration   1: 3.169 ±(99.9%) 0.006 ms/op
Iteration   2: 3.156 ±(99.9%) 0.006 ms/op
Iteration   3: 3.086 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.137 ±(99.9%) 0.820 ms/op [Average]
  (min, avg, max) = (3.086, 3.137, 3.169), stdev = 0.045
  CI (99.9%): [2.318, 3.957] (assumes normal distribution)


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
# Warmup Iteration   1: 9.155 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.946 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.824 ±(99.9%) 0.007 ms/op
Iteration   1: 3.634 ±(99.9%) 0.010 ms/op
Iteration   2: 3.693 ±(99.9%) 0.005 ms/op
Iteration   3: 3.701 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.676 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (3.634, 3.676, 3.701), stdev = 0.037
  CI (99.9%): [3.009, 4.343] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.799 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.676 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.008 ms/op
Iteration   1: 3.187 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.411 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  12.049 ms/op
                 createUser·p0.9999: 20.445 ms/op
                 createUser·p1.00:   21.168 ms/op

Iteration   2: 3.170 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.479 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  15.729 ms/op
                 createUser·p0.9999: 22.378 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   3: 3.314 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.475 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  15.434 ms/op
                 createUser·p0.9999: 24.707 ms/op
                 createUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297750
  mean =      3.222 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16392 
    [ 2.500,  5.000) = 276943 
    [ 5.000,  7.500) = 3351 
    [ 7.500, 10.000) = 513 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     15.434 ms/op
     p(99.9900) =     23.040 ms/op
     p(99.9990) =     25.986 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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
# Warmup Iteration   1: 7.308 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.008 ms/op
Iteration   1: 3.095 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.399 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  8.176 ms/op
                 existUser·p0.9999: 26.062 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   2: 3.072 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.992 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  9.224 ms/op
                 existUser·p0.9999: 21.365 ms/op
                 existUser·p1.00:   21.955 ms/op

Iteration   3: 3.072 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.445 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  13.308 ms/op
                 existUser·p0.9999: 27.361 ms/op
                 existUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311741
  mean =      3.080 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23953 
    [ 2.500,  5.000) = 281922 
    [ 5.000,  7.500) = 5210 
    [ 7.500, 10.000) = 277 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.260 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     12.458 ms/op
     p(99.9900) =     25.821 ms/op
     p(99.9990) =     28.308 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 8.541 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.414 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.008 ms/op
Iteration   1: 3.472 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.403 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  18.114 ms/op
                 getUser·p0.9999: 21.015 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   2: 3.226 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  14.433 ms/op
                 getUser·p0.9999: 21.404 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   3: 3.235 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.007 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  9.901 ms/op
                 getUser·p0.9999: 20.962 ms/op
                 getUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290117
  mean =      3.307 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10239 
    [ 2.500,  5.000) = 270963 
    [ 5.000,  7.500) = 7553 
    [ 7.500, 10.000) = 886 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     16.380 ms/op
     p(99.9900) =     21.233 ms/op
     p(99.9990) =     22.813 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 8.894 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.012 ms/op
Iteration   1: 3.739 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.698 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  16.040 ms/op
                 listUser·p0.9999: 20.153 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   2: 3.738 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.874 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.190 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  14.590 ms/op
                 listUser·p0.9999: 23.149 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   3: 3.773 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.588 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  13.730 ms/op
                 listUser·p0.9999: 17.400 ms/op
                 listUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255950
  mean =      3.750 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 247837 
    [ 5.000,  7.500) = 6299 
    [ 7.500, 10.000) = 1076 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     14.420 ms/op
     p(99.9900) =     20.926 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.909 ± 6.242  ops/ms
ClientPb.existUser                       thrpt       3  10.396 ± 3.636  ops/ms
ClientPb.getUser                         thrpt       3   9.768 ± 7.195  ops/ms
ClientPb.listUser                        thrpt       3   8.575 ± 1.742  ops/ms
ClientPb.createUser                       avgt       3   3.233 ± 1.473   ms/op
ClientPb.existUser                        avgt       3   3.075 ± 0.819   ms/op
ClientPb.getUser                          avgt       3   3.137 ± 0.820   ms/op
ClientPb.listUser                         avgt       3   3.676 ± 0.667   ms/op
ClientPb.createUser                     sample  297750   3.222 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.411           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.341           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.434           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.040           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.182           ms/op
ClientPb.existUser                      sample  311741   3.080 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.811           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.366           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.458           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.821           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.377           ms/op
ClientPb.getUser                        sample  290117   3.307 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.843           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.128           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.380           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.233           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.003           ms/op
ClientPb.listUser                       sample  255950   3.750 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.588           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.674           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.824           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.420           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.926           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.233           ms/op
