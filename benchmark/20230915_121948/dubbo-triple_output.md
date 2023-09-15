# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.158 ops/ms
# Warmup Iteration   2: 5.211 ops/ms
# Warmup Iteration   3: 8.535 ops/ms
Iteration   1: 8.913 ops/ms
Iteration   2: 8.933 ops/ms
Iteration   3: 9.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.980 ±(99.9%) 1.825 ops/ms [Average]
  (min, avg, max) = (8.913, 8.980, 9.095), stdev = 0.100
  CI (99.9%): [7.156, 10.805] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.822 ops/ms
# Warmup Iteration   2: 8.217 ops/ms
# Warmup Iteration   3: 9.567 ops/ms
Iteration   1: 9.469 ops/ms
Iteration   2: 9.461 ops/ms
Iteration   3: 9.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.497 ±(99.9%) 1.016 ops/ms [Average]
  (min, avg, max) = (9.461, 9.497, 9.561), stdev = 0.056
  CI (99.9%): [8.481, 10.513] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.628 ops/ms
# Warmup Iteration   2: 7.945 ops/ms
# Warmup Iteration   3: 8.850 ops/ms
Iteration   1: 9.016 ops/ms
Iteration   2: 9.056 ops/ms
Iteration   3: 9.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.137 ±(99.9%) 3.221 ops/ms [Average]
  (min, avg, max) = (9.016, 9.137, 9.340), stdev = 0.177
  CI (99.9%): [5.916, 12.358] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.767 ops/ms
# Warmup Iteration   2: 6.916 ops/ms
# Warmup Iteration   3: 7.726 ops/ms
Iteration   1: 7.632 ops/ms
Iteration   2: 7.648 ops/ms
Iteration   3: 7.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.649 ±(99.9%) 0.323 ops/ms [Average]
  (min, avg, max) = (7.632, 7.649, 7.667), stdev = 0.018
  CI (99.9%): [7.326, 7.972] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.589 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.831 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.733 ±(99.9%) 0.004 ms/op
Iteration   1: 3.536 ±(99.9%) 0.004 ms/op
Iteration   2: 3.491 ±(99.9%) 0.005 ms/op
Iteration   3: 3.394 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.474 ±(99.9%) 1.324 ms/op [Average]
  (min, avg, max) = (3.394, 3.474, 3.536), stdev = 0.073
  CI (99.9%): [2.150, 4.797] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.259 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.004 ms/op
Iteration   1: 3.361 ±(99.9%) 0.007 ms/op
Iteration   2: 3.375 ±(99.9%) 0.004 ms/op
Iteration   3: 3.346 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.361 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (3.346, 3.361, 3.375), stdev = 0.014
  CI (99.9%): [3.099, 3.623] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.667 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.799 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.571 ±(99.9%) 0.004 ms/op
Iteration   1: 3.538 ±(99.9%) 0.005 ms/op
Iteration   2: 3.436 ±(99.9%) 0.006 ms/op
Iteration   3: 3.585 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.520 ±(99.9%) 1.387 ms/op [Average]
  (min, avg, max) = (3.436, 3.520, 3.585), stdev = 0.076
  CI (99.9%): [2.133, 4.906] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.214 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.228 ±(99.9%) 0.008 ms/op
Iteration   1: 4.089 ±(99.9%) 0.012 ms/op
Iteration   2: 4.146 ±(99.9%) 0.006 ms/op
Iteration   3: 4.116 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.117 ±(99.9%) 0.518 ms/op [Average]
  (min, avg, max) = (4.089, 4.117, 4.146), stdev = 0.028
  CI (99.9%): [3.599, 4.634] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.020 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.106 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.785 ±(99.9%) 0.013 ms/op
Iteration   1: 3.641 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.434 ms/op
                 createUser·p0.50:   3.461 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   7.594 ms/op
                 createUser·p0.999:  19.802 ms/op
                 createUser·p0.9999: 22.001 ms/op
                 createUser·p1.00:   23.429 ms/op

Iteration   2: 3.635 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  21.067 ms/op
                 createUser·p0.9999: 26.778 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   3: 3.563 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.047 ms/op
                 createUser·p0.999:  19.530 ms/op
                 createUser·p0.9999: 27.722 ms/op
                 createUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 265831
  mean =      3.613 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3279 
    [ 2.500,  5.000) = 254009 
    [ 5.000,  7.500) = 6695 
    [ 7.500, 10.000) = 1162 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     19.562 ms/op
     p(99.9900) =     26.804 ms/op
     p(99.9990) =     28.542 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.443 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.480 ±(99.9%) 0.009 ms/op
Iteration   1: 3.473 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.965 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  19.065 ms/op
                 existUser·p0.9999: 21.574 ms/op
                 existUser·p1.00:   22.249 ms/op

Iteration   2: 3.550 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.362 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   8.364 ms/op
                 existUser·p0.999:  20.474 ms/op
                 existUser·p0.9999: 22.445 ms/op
                 existUser·p1.00:   23.495 ms/op

Iteration   3: 3.476 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.587 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   6.305 ms/op
                 existUser·p0.999:  13.969 ms/op
                 existUser·p0.9999: 24.379 ms/op
                 existUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 274357
  mean =      3.499 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5161 
    [ 2.500,  5.000) = 262419 
    [ 5.000,  7.500) = 4117 
    [ 7.500, 10.000) = 1757 
    [10.000, 12.500) = 435 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 175 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      7.458 ms/op
     p(99.9000) =     14.826 ms/op
     p(99.9900) =     22.989 ms/op
     p(99.9990) =     24.814 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.157 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.880 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.009 ms/op
Iteration   1: 3.576 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.366 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.088 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   7.889 ms/op
                 getUser·p0.999:  21.529 ms/op
                 getUser·p0.9999: 31.729 ms/op
                 getUser·p1.00:   32.473 ms/op

Iteration   2: 3.468 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.315 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.095 ms/op
                 getUser·p0.99:   6.147 ms/op
                 getUser·p0.999:  21.618 ms/op
                 getUser·p0.9999: 24.274 ms/op
                 getUser·p1.00:   24.740 ms/op

Iteration   3: 3.477 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.798 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  20.651 ms/op
                 getUser·p0.9999: 27.066 ms/op
                 getUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273735
  mean =      3.506 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6235 
    [ 2.500,  5.000) = 259496 
    [ 5.000,  7.500) = 6219 
    [ 7.500, 10.000) = 984 
    [10.000, 12.500) = 333 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 154 
    [22.500, 25.000) = 133 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     21.406 ms/op
     p(99.9900) =     27.140 ms/op
     p(99.9990) =     32.278 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.412 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.601 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.263 ±(99.9%) 0.012 ms/op
Iteration   1: 4.184 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.833 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.717 ms/op
                 listUser·p0.999:  22.217 ms/op
                 listUser·p0.9999: 24.850 ms/op
                 listUser·p1.00:   25.133 ms/op

Iteration   2: 4.270 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   4.194 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.093 ms/op
                 listUser·p0.999:  16.518 ms/op
                 listUser·p0.9999: 18.990 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   3: 4.249 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.991 ms/op
                 listUser·p0.50:   4.153 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  16.001 ms/op
                 listUser·p0.9999: 17.841 ms/op
                 listUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226652
  mean =      4.234 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 217136 
    [ 5.000,  7.500) = 7299 
    [ 7.500, 10.000) = 1335 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 257 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.833 ms/op
     p(50.0000) =      4.125 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     17.083 ms/op
     p(99.9900) =     23.779 ms/op
     p(99.9990) =     25.026 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.980 ± 1.825  ops/ms
ClientPb.existUser                       thrpt       3   9.497 ± 1.016  ops/ms
ClientPb.getUser                         thrpt       3   9.137 ± 3.221  ops/ms
ClientPb.listUser                        thrpt       3   7.649 ± 0.323  ops/ms
ClientPb.createUser                       avgt       3   3.474 ± 1.324   ms/op
ClientPb.existUser                        avgt       3   3.361 ± 0.262   ms/op
ClientPb.getUser                          avgt       3   3.520 ± 1.387   ms/op
ClientPb.listUser                         avgt       3   4.117 ± 0.518   ms/op
ClientPb.createUser                     sample  265831   3.613 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.085           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.445           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.149           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.497           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.996           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.562           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.804           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.229           ms/op
ClientPb.existUser                      sample  274357   3.499 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.891           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.371           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.887           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.268           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.458           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.826           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.989           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.969           ms/op
ClientPb.getUser                        sample  273735   3.506 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.315           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.816           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.406           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.140           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.473           ms/op
ClientPb.listUser                       sample  226652   4.234 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.833           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.125           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.899           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.463           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.083           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.779           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.133           ms/op
