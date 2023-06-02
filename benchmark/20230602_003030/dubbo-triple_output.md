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
# Warmup Iteration   1: 2.251 ops/ms
# Warmup Iteration   2: 6.370 ops/ms
# Warmup Iteration   3: 9.445 ops/ms
Iteration   1: 9.668 ops/ms
Iteration   2: 9.902 ops/ms
Iteration   3: 9.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.730 ±(99.9%) 2.749 ops/ms [Average]
  (min, avg, max) = (9.621, 9.730, 9.902), stdev = 0.151
  CI (99.9%): [6.982, 12.479] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.978 ops/ms
# Warmup Iteration   2: 9.755 ops/ms
# Warmup Iteration   3: 10.217 ops/ms
Iteration   1: 10.558 ops/ms
Iteration   2: 10.102 ops/ms
Iteration   3: 10.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.427 ±(99.9%) 5.181 ops/ms [Average]
  (min, avg, max) = (10.102, 10.427, 10.622), stdev = 0.284
  CI (99.9%): [5.246, 15.608] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.877 ops/ms
# Warmup Iteration   2: 9.395 ops/ms
# Warmup Iteration   3: 9.559 ops/ms
Iteration   1: 10.016 ops/ms
Iteration   2: 9.981 ops/ms
Iteration   3: 10.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.148 ±(99.9%) 4.713 ops/ms [Average]
  (min, avg, max) = (9.981, 10.148, 10.445), stdev = 0.258
  CI (99.9%): [5.435, 14.860] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.568 ops/ms
# Warmup Iteration   2: 7.945 ops/ms
# Warmup Iteration   3: 8.154 ops/ms
Iteration   1: 8.655 ops/ms
Iteration   2: 8.418 ops/ms
Iteration   3: 8.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.524 ±(99.9%) 2.204 ops/ms [Average]
  (min, avg, max) = (8.418, 8.524, 8.655), stdev = 0.121
  CI (99.9%): [6.320, 10.728] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.121 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.101 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.006 ms/op
Iteration   1: 3.195 ±(99.9%) 0.003 ms/op
Iteration   2: 3.158 ±(99.9%) 0.005 ms/op
Iteration   3: 3.094 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.149 ±(99.9%) 0.935 ms/op [Average]
  (min, avg, max) = (3.094, 3.149, 3.195), stdev = 0.051
  CI (99.9%): [2.214, 4.083] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.193 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.002 ms/op
Iteration   1: 3.087 ±(99.9%) 0.003 ms/op
Iteration   2: 3.180 ±(99.9%) 0.007 ms/op
Iteration   3: 3.008 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.092 ±(99.9%) 1.566 ms/op [Average]
  (min, avg, max) = (3.008, 3.092, 3.180), stdev = 0.086
  CI (99.9%): [1.526, 4.658] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.124 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.486 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.002 ms/op
Iteration   1: 3.371 ±(99.9%) 0.002 ms/op
Iteration   2: 3.227 ±(99.9%) 0.005 ms/op
Iteration   3: 3.340 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.313 ±(99.9%) 1.391 ms/op [Average]
  (min, avg, max) = (3.227, 3.313, 3.371), stdev = 0.076
  CI (99.9%): [1.922, 4.704] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.012 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.053 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.007 ms/op
Iteration   1: 3.901 ±(99.9%) 0.006 ms/op
Iteration   2: 3.743 ±(99.9%) 0.007 ms/op
Iteration   3: 3.688 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.777 ±(99.9%) 2.016 ms/op [Average]
  (min, avg, max) = (3.688, 3.777, 3.901), stdev = 0.110
  CI (99.9%): [1.761, 5.793] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.437 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.010 ms/op
Iteration   1: 3.298 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  14.107 ms/op
                 createUser·p0.9999: 26.238 ms/op
                 createUser·p1.00:   26.837 ms/op

Iteration   2: 3.320 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   6.382 ms/op
                 createUser·p0.999:  20.032 ms/op
                 createUser·p0.9999: 23.173 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.262 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.301 ms/op
                 createUser·p0.95:   3.387 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  13.992 ms/op
                 createUser·p0.9999: 18.448 ms/op
                 createUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295408
  mean =      3.250 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26370 
    [ 2.500,  5.000) = 262058 
    [ 5.000,  7.500) = 5961 
    [ 7.500, 10.000) = 561 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     16.246 ms/op
     p(99.9900) =     24.853 ms/op
     p(99.9990) =     26.643 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.087 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.472 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.008 ms/op
Iteration   1: 3.177 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  9.880 ms/op
                 existUser·p0.9999: 24.840 ms/op
                 existUser·p1.00:   25.428 ms/op

Iteration   2: 3.074 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  11.207 ms/op
                 existUser·p0.9999: 21.470 ms/op
                 existUser·p1.00:   22.413 ms/op

Iteration   3: 3.015 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.195 ms/op
                 existUser·p0.95:   3.412 ms/op
                 existUser·p0.99:   5.336 ms/op
                 existUser·p0.999:  11.781 ms/op
                 existUser·p0.9999: 22.112 ms/op
                 existUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310662
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16611 
    [ 2.500,  5.000) = 288614 
    [ 5.000,  7.500) = 4759 
    [ 7.500, 10.000) = 339 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.986 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     11.239 ms/op
     p(99.9900) =     22.870 ms/op
     p(99.9990) =     25.279 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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
# Warmup Iteration   1: 7.599 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.011 ms/op
Iteration   1: 3.188 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  17.957 ms/op
                 getUser·p0.9999: 20.413 ms/op
                 getUser·p1.00:   21.201 ms/op

Iteration   2: 3.169 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.505 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   5.419 ms/op
                 getUser·p0.999:  10.027 ms/op
                 getUser·p0.9999: 25.294 ms/op
                 getUser·p1.00:   26.608 ms/op

Iteration   3: 3.095 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.417 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.353 ms/op
                 getUser·p0.95:   3.572 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  9.399 ms/op
                 getUser·p0.9999: 22.533 ms/op
                 getUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304766
  mean =      3.150 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15179 
    [ 2.500,  5.000) = 283153 
    [ 5.000,  7.500) = 5723 
    [ 7.500, 10.000) = 364 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 200 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     26.378 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 9.408 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.141 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.013 ms/op
Iteration   1: 3.694 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.444 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   6.535 ms/op
                 listUser·p0.999:  16.482 ms/op
                 listUser·p0.9999: 21.726 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   2: 3.802 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.731 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  14.937 ms/op
                 listUser·p0.9999: 19.530 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   3: 3.635 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   3.772 ms/op
                 listUser·p0.95:   3.957 ms/op
                 listUser·p0.99:   5.614 ms/op
                 listUser·p0.999:  13.468 ms/op
                 listUser·p0.9999: 16.713 ms/op
                 listUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258604
  mean =      3.709 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 90 
    [ 2.500,  5.000) = 251660 
    [ 5.000,  7.500) = 5247 
    [ 7.500, 10.000) = 995 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 197 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     15.453 ms/op
     p(99.9900) =     19.595 ms/op
     p(99.9990) =     22.090 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.730 ± 2.749  ops/ms
ClientPb.existUser                       thrpt       3  10.427 ± 5.181  ops/ms
ClientPb.getUser                         thrpt       3  10.148 ± 4.713  ops/ms
ClientPb.listUser                        thrpt       3   8.524 ± 2.204  ops/ms
ClientPb.createUser                       avgt       3   3.149 ± 0.935   ms/op
ClientPb.existUser                        avgt       3   3.092 ± 1.566   ms/op
ClientPb.getUser                          avgt       3   3.313 ± 1.391   ms/op
ClientPb.listUser                         avgt       3   3.777 ± 2.016   ms/op
ClientPb.createUser                     sample  295408   3.250 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.722           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.559           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.923           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.246           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.853           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.837           ms/op
ClientPb.existUser                      sample  310662   3.087 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.986           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.400           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.366           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.239           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.870           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.428           ms/op
ClientPb.getUser                        sample  304766   3.150 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.065           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.486           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.587           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.400           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.281           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.608           ms/op
ClientPb.listUser                       sample  258604   3.709 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.444           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.750           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.453           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.595           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.807           ms/op
