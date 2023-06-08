# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.258 ops/ms
# Warmup Iteration   2: 2.653 ops/ms
# Warmup Iteration   3: 5.444 ops/ms
Iteration   1: 5.340 ops/ms
Iteration   2: 5.787 ops/ms
Iteration   3: 6.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.737 ±(99.9%) 6.819 ops/ms [Average]
  (min, avg, max) = (5.340, 5.737, 6.083), stdev = 0.374
  CI (99.9%): [≈ 0, 12.555] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.808 ops/ms
# Warmup Iteration   2: 5.503 ops/ms
# Warmup Iteration   3: 6.490 ops/ms
Iteration   1: 6.548 ops/ms
Iteration   2: 6.514 ops/ms
Iteration   3: 6.385 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.483 ±(99.9%) 1.570 ops/ms [Average]
  (min, avg, max) = (6.385, 6.483, 6.548), stdev = 0.086
  CI (99.9%): [4.913, 8.052] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.643 ops/ms
# Warmup Iteration   2: 4.469 ops/ms
# Warmup Iteration   3: 6.188 ops/ms
Iteration   1: 6.213 ops/ms
Iteration   2: 6.052 ops/ms
Iteration   3: 6.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.126 ±(99.9%) 1.475 ops/ms [Average]
  (min, avg, max) = (6.052, 6.126, 6.213), stdev = 0.081
  CI (99.9%): [4.651, 7.601] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.778 ops/ms
# Warmup Iteration   2: 4.340 ops/ms
# Warmup Iteration   3: 5.424 ops/ms
Iteration   1: 5.103 ops/ms
Iteration   2: 5.170 ops/ms
Iteration   3: 5.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.194 ±(99.9%) 1.921 ops/ms [Average]
  (min, avg, max) = (5.103, 5.194, 5.310), stdev = 0.105
  CI (99.9%): [3.273, 7.115] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 15.530 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.840 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.499 ±(99.9%) 0.005 ms/op
Iteration   1: 4.370 ±(99.9%) 0.012 ms/op
Iteration   2: 4.205 ±(99.9%) 0.018 ms/op
Iteration   3: 4.344 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.306 ±(99.9%) 1.618 ms/op [Average]
  (min, avg, max) = (4.205, 4.306, 4.370), stdev = 0.089
  CI (99.9%): [2.688, 5.924] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 12.107 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.299 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.356 ±(99.9%) 0.007 ms/op
Iteration   1: 4.096 ±(99.9%) 0.016 ms/op
Iteration   2: 3.966 ±(99.9%) 0.014 ms/op
Iteration   3: 3.954 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.005 ±(99.9%) 1.432 ms/op [Average]
  (min, avg, max) = (3.954, 4.005, 4.096), stdev = 0.078
  CI (99.9%): [2.573, 5.437] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.233 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.698 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.436 ±(99.9%) 0.006 ms/op
Iteration   1: 4.183 ±(99.9%) 0.015 ms/op
Iteration   2: 4.058 ±(99.9%) 0.016 ms/op
Iteration   3: 4.287 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.176 ±(99.9%) 2.099 ms/op [Average]
  (min, avg, max) = (4.058, 4.176, 4.287), stdev = 0.115
  CI (99.9%): [2.078, 6.275] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.062 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.758 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.082 ±(99.9%) 0.009 ms/op
Iteration   1: 5.051 ±(99.9%) 0.013 ms/op
Iteration   2: 5.060 ±(99.9%) 0.018 ms/op
Iteration   3: 5.112 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.074 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (5.051, 5.074, 5.112), stdev = 0.033
  CI (99.9%): [4.476, 5.673] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.321 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 4.971 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.522 ±(99.9%) 0.014 ms/op
Iteration   1: 4.348 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.614 ms/op
                 createUser·p0.50:   4.112 ms/op
                 createUser·p0.90:   5.382 ms/op
                 createUser·p0.95:   6.046 ms/op
                 createUser·p0.99:   7.463 ms/op
                 createUser·p0.999:  17.138 ms/op
                 createUser·p0.9999: 20.140 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   2: 4.421 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.911 ms/op
                 createUser·p0.50:   4.260 ms/op
                 createUser·p0.90:   5.366 ms/op
                 createUser·p0.95:   5.800 ms/op
                 createUser·p0.99:   7.242 ms/op
                 createUser·p0.999:  10.239 ms/op
                 createUser·p0.9999: 21.178 ms/op
                 createUser·p1.00:   22.282 ms/op

Iteration   3: 4.259 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.866 ms/op
                 createUser·p0.50:   4.080 ms/op
                 createUser·p0.90:   5.095 ms/op
                 createUser·p0.95:   5.562 ms/op
                 createUser·p0.99:   7.422 ms/op
                 createUser·p0.999:  13.710 ms/op
                 createUser·p0.9999: 23.658 ms/op
                 createUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 221047
  mean =      4.342 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 276 
    [ 2.500,  5.000) = 187342 
    [ 5.000,  7.500) = 31410 
    [ 7.500, 10.000) = 1605 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.614 ms/op
     p(50.0000) =      4.149 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     16.170 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     23.921 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.584 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.521 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.288 ±(99.9%) 0.012 ms/op
Iteration   1: 4.262 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.536 ms/op
                 existUser·p0.50:   4.051 ms/op
                 existUser·p0.90:   5.210 ms/op
                 existUser·p0.95:   5.882 ms/op
                 existUser·p0.99:   7.913 ms/op
                 existUser·p0.999:  14.286 ms/op
                 existUser·p0.9999: 21.586 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   2: 4.187 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.884 ms/op
                 existUser·p0.50:   3.998 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   5.538 ms/op
                 existUser·p0.99:   7.078 ms/op
                 existUser·p0.999:  23.694 ms/op
                 existUser·p0.9999: 28.217 ms/op
                 existUser·p1.00:   29.164 ms/op

Iteration   3: 4.171 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.847 ms/op
                 existUser·p0.50:   3.990 ms/op
                 existUser·p0.90:   4.923 ms/op
                 existUser·p0.95:   5.456 ms/op
                 existUser·p0.99:   7.556 ms/op
                 existUser·p0.999:  18.886 ms/op
                 existUser·p0.9999: 26.061 ms/op
                 existUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 228245
  mean =      4.206 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 324 
    [ 2.500,  5.000) = 203298 
    [ 5.000,  7.500) = 22209 
    [ 7.500, 10.000) = 1686 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 66 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      4.010 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     27.407 ms/op
     p(99.9990) =     29.056 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 13.348 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 4.903 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.498 ±(99.9%) 0.016 ms/op
Iteration   1: 4.538 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.378 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.571 ms/op
                 getUser·p0.95:   6.529 ms/op
                 getUser·p0.99:   8.798 ms/op
                 getUser·p0.999:  20.939 ms/op
                 getUser·p0.9999: 25.723 ms/op
                 getUser·p1.00:   26.804 ms/op

Iteration   2: 4.396 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.761 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   5.202 ms/op
                 getUser·p0.95:   6.185 ms/op
                 getUser·p0.99:   7.856 ms/op
                 getUser·p0.999:  14.557 ms/op
                 getUser·p0.9999: 26.509 ms/op
                 getUser·p1.00:   26.673 ms/op

Iteration   3: 4.519 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.407 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.431 ms/op
                 getUser·p0.95:   6.054 ms/op
                 getUser·p0.99:   8.897 ms/op
                 getUser·p0.999:  22.907 ms/op
                 getUser·p0.9999: 27.228 ms/op
                 getUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 214138
  mean =      4.484 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 179112 
    [ 5.000,  7.500) = 31055 
    [ 7.500, 10.000) = 2831 
    [10.000, 12.500) = 558 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 100 

  Percentiles, ms/op:
      p(0.0000) =      0.407 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      6.259 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     21.192 ms/op
     p(99.9900) =     26.804 ms/op
     p(99.9990) =     27.760 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 13.743 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 5.539 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.248 ±(99.9%) 0.018 ms/op
Iteration   1: 5.135 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   4.850 ms/op
                 listUser·p0.90:   6.177 ms/op
                 listUser·p0.95:   7.160 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  22.899 ms/op
                 listUser·p0.9999: 28.049 ms/op
                 listUser·p1.00:   29.393 ms/op

Iteration   2: 5.148 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   4.858 ms/op
                 listUser·p0.90:   6.242 ms/op
                 listUser·p0.95:   7.127 ms/op
                 listUser·p0.99:   9.503 ms/op
                 listUser·p0.999:  21.755 ms/op
                 listUser·p0.9999: 25.068 ms/op
                 listUser·p1.00:   28.082 ms/op

Iteration   3: 5.252 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.716 ms/op
                 listUser·p0.50:   5.079 ms/op
                 listUser·p0.90:   6.021 ms/op
                 listUser·p0.95:   6.652 ms/op
                 listUser·p0.99:   9.519 ms/op
                 listUser·p0.999:  17.859 ms/op
                 listUser·p0.9999: 25.982 ms/op
                 listUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 185331
  mean =      5.178 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 99397 
    [ 5.000,  7.500) = 79322 
    [ 7.500, 10.000) = 5242 
    [10.000, 12.500) = 753 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      2.367 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      6.136 ms/op
     p(95.0000) =      6.980 ms/op
     p(99.0000) =      9.486 ms/op
     p(99.9000) =     22.097 ms/op
     p(99.9900) =     26.918 ms/op
     p(99.9990) =     28.946 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.737 ± 6.819  ops/ms
ClientPb.existUser                       thrpt       3   6.483 ± 1.570  ops/ms
ClientPb.getUser                         thrpt       3   6.126 ± 1.475  ops/ms
ClientPb.listUser                        thrpt       3   5.194 ± 1.921  ops/ms
ClientPb.createUser                       avgt       3   4.306 ± 1.618   ms/op
ClientPb.existUser                        avgt       3   4.005 ± 1.432   ms/op
ClientPb.getUser                          avgt       3   4.176 ± 2.099   ms/op
ClientPb.listUser                         avgt       3   5.074 ± 0.598   ms/op
ClientPb.createUser                     sample  221047   4.342 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.614           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.149           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.284           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.808           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.389           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.170           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.086           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.019           ms/op
ClientPb.existUser                      sample  228245   4.206 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.536           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.010           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.063           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.602           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.907           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.407           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.164           ms/op
ClientPb.getUser                        sample  214138   4.484 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.407           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.415           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.259           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.569           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.192           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.804           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.377           ms/op
ClientPb.listUser                       sample  185331   5.178 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.367           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.948           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.136           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.980           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.486           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.097           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.918           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.393           ms/op
