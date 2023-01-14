# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.743 ops/ms
# Warmup Iteration   2: 6.895 ops/ms
# Warmup Iteration   3: 9.342 ops/ms
Iteration   1: 10.331 ops/ms
Iteration   2: 9.836 ops/ms
Iteration   3: 9.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.051 ±(99.9%) 4.631 ops/ms [Average]
  (min, avg, max) = (9.836, 10.051, 10.331), stdev = 0.254
  CI (99.9%): [5.420, 14.682] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.277 ops/ms
# Warmup Iteration   2: 8.592 ops/ms
# Warmup Iteration   3: 10.230 ops/ms
Iteration   1: 10.521 ops/ms
Iteration   2: 10.386 ops/ms
Iteration   3: 10.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.312 ±(99.9%) 4.626 ops/ms [Average]
  (min, avg, max) = (10.030, 10.312, 10.521), stdev = 0.254
  CI (99.9%): [5.687, 14.938] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.812 ops/ms
# Warmup Iteration   2: 8.462 ops/ms
# Warmup Iteration   3: 9.220 ops/ms
Iteration   1: 10.360 ops/ms
Iteration   2: 10.191 ops/ms
Iteration   3: 9.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.117 ±(99.9%) 5.237 ops/ms [Average]
  (min, avg, max) = (9.800, 10.117, 10.360), stdev = 0.287
  CI (99.9%): [4.880, 15.354] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.701 ops/ms
# Warmup Iteration   2: 7.941 ops/ms
# Warmup Iteration   3: 8.319 ops/ms
Iteration   1: 8.422 ops/ms
Iteration   2: 8.600 ops/ms
Iteration   3: 8.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.560 ±(99.9%) 2.241 ops/ms [Average]
  (min, avg, max) = (8.422, 8.560, 8.657), stdev = 0.123
  CI (99.9%): [6.318, 10.801] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.767 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.343 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.300 ±(99.9%) 0.006 ms/op
Iteration   1: 3.115 ±(99.9%) 0.006 ms/op
Iteration   2: 3.229 ±(99.9%) 0.009 ms/op
Iteration   3: 3.144 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.163 ±(99.9%) 1.080 ms/op [Average]
  (min, avg, max) = (3.115, 3.163, 3.229), stdev = 0.059
  CI (99.9%): [2.083, 4.243] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.776 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.005 ms/op
Iteration   1: 3.143 ±(99.9%) 0.008 ms/op
Iteration   2: 3.056 ±(99.9%) 0.007 ms/op
Iteration   3: 3.007 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.069 ±(99.9%) 1.262 ms/op [Average]
  (min, avg, max) = (3.007, 3.069, 3.143), stdev = 0.069
  CI (99.9%): [1.807, 4.330] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.636 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.311 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.006 ms/op
Iteration   1: 3.143 ±(99.9%) 0.006 ms/op
Iteration   2: 3.072 ±(99.9%) 0.005 ms/op
Iteration   3: 3.122 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.112 ±(99.9%) 0.663 ms/op [Average]
  (min, avg, max) = (3.072, 3.112, 3.143), stdev = 0.036
  CI (99.9%): [2.449, 3.776] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.615 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.061 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.787 ±(99.9%) 0.008 ms/op
Iteration   1: 3.742 ±(99.9%) 0.010 ms/op
Iteration   2: 3.710 ±(99.9%) 0.006 ms/op
Iteration   3: 3.730 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.727 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (3.710, 3.727, 3.742), stdev = 0.016
  CI (99.9%): [3.435, 4.019] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.401 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.929 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.008 ms/op
Iteration   1: 3.097 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.042 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.281 ms/op
                 createUser·p0.95:   3.580 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  18.104 ms/op
                 createUser·p0.9999: 23.778 ms/op
                 createUser·p1.00:   25.559 ms/op

Iteration   2: 3.269 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.128 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  9.995 ms/op
                 createUser·p0.9999: 23.036 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  10.065 ms/op
                 createUser·p0.9999: 21.070 ms/op
                 createUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303158
  mean =      3.169 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23191 
    [ 2.500,  5.000) = 273270 
    [ 5.000,  7.500) = 5951 
    [ 7.500, 10.000) = 365 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     15.773 ms/op
     p(99.9900) =     23.408 ms/op
     p(99.9990) =     24.313 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.547 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.007 ms/op
Iteration   1: 3.025 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.120 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.174 ms/op
                 existUser·p0.95:   3.445 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  9.942 ms/op
                 existUser·p0.9999: 26.799 ms/op
                 existUser·p1.00:   29.819 ms/op

Iteration   2: 3.026 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.375 ms/op
                 existUser·p0.99:   5.613 ms/op
                 existUser·p0.999:  12.665 ms/op
                 existUser·p0.9999: 25.831 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   3: 3.083 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.552 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  12.419 ms/op
                 existUser·p0.9999: 20.120 ms/op
                 existUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315238
  mean =      3.044 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17336 
    [ 2.500,  5.000) = 293152 
    [ 5.000,  7.500) = 3777 
    [ 7.500, 10.000) = 495 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.228 ms/op
     p(95.0000) =      3.437 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     12.415 ms/op
     p(99.9900) =     25.754 ms/op
     p(99.9990) =     29.202 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.464 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.511 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.010 ms/op
Iteration   1: 3.109 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.029 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.355 ms/op
                 getUser·p0.95:   3.539 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  10.814 ms/op
                 getUser·p0.9999: 28.390 ms/op
                 getUser·p1.00:   29.327 ms/op

Iteration   2: 3.271 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   5.913 ms/op
                 getUser·p0.999:  18.330 ms/op
                 getUser·p0.9999: 23.462 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   3: 3.234 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.425 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  10.174 ms/op
                 getUser·p0.9999: 28.515 ms/op
                 getUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299527
  mean =      3.203 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12629 
    [ 2.500,  5.000) = 279552 
    [ 5.000,  7.500) = 6542 
    [ 7.500, 10.000) = 469 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     10.837 ms/op
     p(99.9900) =     28.053 ms/op
     p(99.9990) =     29.229 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.867 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.792 ±(99.9%) 0.011 ms/op
Iteration   1: 3.768 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.976 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  15.794 ms/op
                 listUser·p0.9999: 22.692 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   2: 3.755 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.788 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  13.206 ms/op
                 listUser·p0.9999: 18.232 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   3: 3.674 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.526 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.182 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  16.608 ms/op
                 listUser·p0.9999: 20.566 ms/op
                 listUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257077
  mean =      3.732 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74 
    [ 2.500,  5.000) = 249053 
    [ 5.000,  7.500) = 6043 
    [ 7.500, 10.000) = 1314 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.526 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     14.090 ms/op
     p(99.9900) =     21.473 ms/op
     p(99.9990) =     23.429 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.051 ± 4.631  ops/ms
ClientPb.existUser                       thrpt       3  10.312 ± 4.626  ops/ms
ClientPb.getUser                         thrpt       3  10.117 ± 5.237  ops/ms
ClientPb.listUser                        thrpt       3   8.560 ± 2.241  ops/ms
ClientPb.createUser                       avgt       3   3.163 ± 1.080   ms/op
ClientPb.existUser                        avgt       3   3.069 ± 1.262   ms/op
ClientPb.getUser                          avgt       3   3.112 ± 0.663   ms/op
ClientPb.listUser                         avgt       3   3.727 ± 0.292   ms/op
ClientPb.createUser                     sample  303158   3.169 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.042           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.482           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.773           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.408           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.559           ms/op
ClientPb.existUser                      sample  315238   3.044 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.108           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.437           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.415           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.754           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.819           ms/op
ClientPb.getUser                        sample  299527   3.203 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.921           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.584           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.677           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.837           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.053           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.327           ms/op
ClientPb.listUser                       sample  257077   3.732 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.526           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.600           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.018           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.955           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.090           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.473           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.429           ms/op
