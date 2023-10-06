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
# Warmup Iteration   1: 1.892 ops/ms
# Warmup Iteration   2: 5.006 ops/ms
# Warmup Iteration   3: 8.363 ops/ms
Iteration   1: 8.820 ops/ms
Iteration   2: 8.885 ops/ms
Iteration   3: 8.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.891 ±(99.9%) 1.339 ops/ms [Average]
  (min, avg, max) = (8.820, 8.891, 8.967), stdev = 0.073
  CI (99.9%): [7.552, 10.229] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.760 ops/ms
# Warmup Iteration   2: 8.130 ops/ms
# Warmup Iteration   3: 9.139 ops/ms
Iteration   1: 9.443 ops/ms
Iteration   2: 9.156 ops/ms
Iteration   3: 9.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.385 ±(99.9%) 3.769 ops/ms [Average]
  (min, avg, max) = (9.156, 9.385, 9.557), stdev = 0.207
  CI (99.9%): [5.617, 13.154] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.450 ops/ms
# Warmup Iteration   2: 7.831 ops/ms
# Warmup Iteration   3: 9.120 ops/ms
Iteration   1: 9.034 ops/ms
Iteration   2: 8.946 ops/ms
Iteration   3: 9.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.025 ±(99.9%) 1.374 ops/ms [Average]
  (min, avg, max) = (8.946, 9.025, 9.096), stdev = 0.075
  CI (99.9%): [7.651, 10.399] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.706 ops/ms
# Warmup Iteration   2: 7.012 ops/ms
# Warmup Iteration   3: 7.456 ops/ms
Iteration   1: 7.544 ops/ms
Iteration   2: 7.600 ops/ms
Iteration   3: 7.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.608 ±(99.9%) 1.249 ops/ms [Average]
  (min, avg, max) = (7.544, 7.608, 7.680), stdev = 0.068
  CI (99.9%): [6.359, 8.857] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.587 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.727 ±(99.9%) 0.004 ms/op
Iteration   1: 3.528 ±(99.9%) 0.004 ms/op
Iteration   2: 3.419 ±(99.9%) 0.004 ms/op
Iteration   3: 3.572 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.506 ±(99.9%) 1.436 ms/op [Average]
  (min, avg, max) = (3.419, 3.506, 3.572), stdev = 0.079
  CI (99.9%): [2.070, 4.942] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.225 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.503 ±(99.9%) 0.003 ms/op
Iteration   1: 3.481 ±(99.9%) 0.004 ms/op
Iteration   2: 3.455 ±(99.9%) 0.006 ms/op
Iteration   3: 3.398 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.445 ±(99.9%) 0.768 ms/op [Average]
  (min, avg, max) = (3.398, 3.445, 3.481), stdev = 0.042
  CI (99.9%): [2.677, 4.213] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.154 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.004 ms/op
Iteration   1: 3.643 ±(99.9%) 0.004 ms/op
Iteration   2: 3.574 ±(99.9%) 0.005 ms/op
Iteration   3: 3.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.571 ±(99.9%) 1.355 ms/op [Average]
  (min, avg, max) = (3.495, 3.571, 3.643), stdev = 0.074
  CI (99.9%): [2.216, 4.926] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.024 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.582 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.259 ±(99.9%) 0.005 ms/op
Iteration   1: 4.193 ±(99.9%) 0.007 ms/op
Iteration   2: 4.124 ±(99.9%) 0.008 ms/op
Iteration   3: 4.163 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.160 ±(99.9%) 0.631 ms/op [Average]
  (min, avg, max) = (4.124, 4.160, 4.193), stdev = 0.035
  CI (99.9%): [3.529, 4.791] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.610 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.274 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.015 ms/op
Iteration   1: 3.457 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.303 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  17.302 ms/op
                 createUser·p0.9999: 20.357 ms/op
                 createUser·p1.00:   20.808 ms/op

Iteration   2: 3.532 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   7.274 ms/op
                 createUser·p0.999:  19.005 ms/op
                 createUser·p0.9999: 22.151 ms/op
                 createUser·p1.00:   26.051 ms/op

Iteration   3: 3.605 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.528 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   7.445 ms/op
                 createUser·p0.999:  22.062 ms/op
                 createUser·p0.9999: 26.227 ms/op
                 createUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271908
  mean =      3.530 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6996 
    [ 2.500,  5.000) = 255767 
    [ 5.000,  7.500) = 7203 
    [ 7.500, 10.000) = 1293 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     18.755 ms/op
     p(99.9900) =     25.526 ms/op
     p(99.9990) =     27.340 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.405 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 3.725 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.011 ms/op
Iteration   1: 3.379 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.511 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   7.201 ms/op
                 existUser·p0.999:  22.086 ms/op
                 existUser·p0.9999: 28.231 ms/op
                 existUser·p1.00:   31.195 ms/op

Iteration   2: 3.453 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.743 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.912 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   7.815 ms/op
                 existUser·p0.999:  13.073 ms/op
                 existUser·p0.9999: 25.854 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   3: 3.423 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   6.990 ms/op
                 existUser·p0.999:  23.994 ms/op
                 existUser·p0.9999: 31.171 ms/op
                 existUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280720
  mean =      3.418 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4976 
    [ 2.500,  5.000) = 267052 
    [ 5.000,  7.500) = 6227 
    [ 7.500, 10.000) = 1578 
    [10.000, 12.500) = 469 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     19.384 ms/op
     p(99.9900) =     29.419 ms/op
     p(99.9990) =     32.322 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.503 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 3.808 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.015 ms/op
Iteration   1: 3.618 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   7.512 ms/op
                 getUser·p0.999:  21.758 ms/op
                 getUser·p0.9999: 26.854 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   2: 3.448 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.821 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.158 ms/op
                 getUser·p0.99:   7.348 ms/op
                 getUser·p0.999:  21.823 ms/op
                 getUser·p0.9999: 23.623 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   3: 3.551 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.350 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  19.885 ms/op
                 getUser·p0.9999: 28.017 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271371
  mean =      3.538 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3739 
    [ 2.500,  5.000) = 259341 
    [ 5.000,  7.500) = 6053 
    [ 7.500, 10.000) = 1566 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      0.350 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     21.430 ms/op
     p(99.9900) =     27.783 ms/op
     p(99.9990) =     28.574 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.450 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.522 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.306 ±(99.9%) 0.015 ms/op
Iteration   1: 4.310 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.468 ms/op
                 listUser·p0.50:   4.125 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   8.740 ms/op
                 listUser·p0.999:  22.241 ms/op
                 listUser·p0.9999: 30.512 ms/op
                 listUser·p1.00:   31.228 ms/op

Iteration   2: 4.197 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.954 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   8.167 ms/op
                 listUser·p0.999:  17.163 ms/op
                 listUser·p0.9999: 22.020 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   3: 4.219 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  16.536 ms/op
                 listUser·p0.9999: 25.006 ms/op
                 listUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226341
  mean =      4.242 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 100 
    [ 2.500,  5.000) = 214728 
    [ 5.000,  7.500) = 7577 
    [ 7.500, 10.000) = 2677 
    [10.000, 12.500) = 554 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 267 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.468 ms/op
     p(50.0000) =      4.084 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     29.271 ms/op
     p(99.9990) =     30.892 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.891 ± 1.339  ops/ms
ClientPb.existUser                       thrpt       3   9.385 ± 3.769  ops/ms
ClientPb.getUser                         thrpt       3   9.025 ± 1.374  ops/ms
ClientPb.listUser                        thrpt       3   7.608 ± 1.249  ops/ms
ClientPb.createUser                       avgt       3   3.506 ± 1.436   ms/op
ClientPb.existUser                        avgt       3   3.445 ± 0.768   ms/op
ClientPb.getUser                          avgt       3   3.571 ± 1.355   ms/op
ClientPb.listUser                         avgt       3   4.160 ± 0.631   ms/op
ClientPb.createUser                     sample  271908   3.530 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.303           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.070           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.755           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.526           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.049           ms/op
ClientPb.existUser                      sample  280720   3.418 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.114           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.260           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.332           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.384           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.419           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.571           ms/op
ClientPb.getUser                        sample  271371   3.538 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.350           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.250           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.430           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.783           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.672           ms/op
ClientPb.listUser                       sample  226341   4.242 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.468           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.084           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.014           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.585           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.973           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.271           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.228           ms/op
