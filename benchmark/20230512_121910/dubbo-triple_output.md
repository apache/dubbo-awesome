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
# Warmup Iteration   1: 2.596 ops/ms
# Warmup Iteration   2: 6.366 ops/ms
# Warmup Iteration   3: 9.435 ops/ms
Iteration   1: 9.553 ops/ms
Iteration   2: 10.132 ops/ms
Iteration   3: 9.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.755 ±(99.9%) 5.958 ops/ms [Average]
  (min, avg, max) = (9.553, 9.755, 10.132), stdev = 0.327
  CI (99.9%): [3.797, 15.713] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.040 ops/ms
# Warmup Iteration   2: 9.542 ops/ms
# Warmup Iteration   3: 10.319 ops/ms
Iteration   1: 10.034 ops/ms
Iteration   2: 10.191 ops/ms
Iteration   3: 10.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.176 ±(99.9%) 2.466 ops/ms [Average]
  (min, avg, max) = (10.034, 10.176, 10.304), stdev = 0.135
  CI (99.9%): [7.710, 12.642] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.372 ops/ms
# Warmup Iteration   2: 8.798 ops/ms
# Warmup Iteration   3: 9.964 ops/ms
Iteration   1: 10.215 ops/ms
Iteration   2: 9.704 ops/ms
Iteration   3: 10.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.974 ±(99.9%) 4.681 ops/ms [Average]
  (min, avg, max) = (9.704, 9.974, 10.215), stdev = 0.257
  CI (99.9%): [5.293, 14.655] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.635 ops/ms
# Warmup Iteration   2: 8.079 ops/ms
# Warmup Iteration   3: 8.417 ops/ms
Iteration   1: 8.613 ops/ms
Iteration   2: 8.440 ops/ms
Iteration   3: 8.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.627 ±(99.9%) 3.537 ops/ms [Average]
  (min, avg, max) = (8.440, 8.627, 8.828), stdev = 0.194
  CI (99.9%): [5.090, 12.165] (assumes normal distribution)


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
# Warmup Iteration   1: 8.375 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.594 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.005 ms/op
Iteration   1: 3.313 ±(99.9%) 0.004 ms/op
Iteration   2: 3.151 ±(99.9%) 0.003 ms/op
Iteration   3: 3.081 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.182 ±(99.9%) 2.170 ms/op [Average]
  (min, avg, max) = (3.081, 3.182, 3.313), stdev = 0.119
  CI (99.9%): [1.012, 5.352] (assumes normal distribution)


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
# Warmup Iteration   1: 7.456 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.312 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.005 ms/op
Iteration   1: 3.133 ±(99.9%) 0.003 ms/op
Iteration   2: 3.065 ±(99.9%) 0.008 ms/op
Iteration   3: 2.984 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.061 ±(99.9%) 1.362 ms/op [Average]
  (min, avg, max) = (2.984, 3.061, 3.133), stdev = 0.075
  CI (99.9%): [1.698, 4.423] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.396 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.433 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.003 ms/op
Iteration   1: 3.144 ±(99.9%) 0.008 ms/op
Iteration   2: 3.139 ±(99.9%) 0.002 ms/op
Iteration   3: 3.137 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.140 ±(99.9%) 0.065 ms/op [Average]
  (min, avg, max) = (3.137, 3.140, 3.144), stdev = 0.004
  CI (99.9%): [3.075, 3.205] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.832 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.961 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.004 ms/op
Iteration   1: 3.783 ±(99.9%) 0.006 ms/op
Iteration   2: 3.692 ±(99.9%) 0.006 ms/op
Iteration   3: 3.662 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.712 ±(99.9%) 1.144 ms/op [Average]
  (min, avg, max) = (3.662, 3.712, 3.783), stdev = 0.063
  CI (99.9%): [2.568, 4.856] (assumes normal distribution)


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
# Warmup Iteration   1: 7.960 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.687 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
Iteration   1: 3.123 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.301 ms/op
                 createUser·p0.95:   3.543 ms/op
                 createUser·p0.99:   5.454 ms/op
                 createUser·p0.999:  18.856 ms/op
                 createUser·p0.9999: 25.035 ms/op
                 createUser·p1.00:   25.690 ms/op

Iteration   2: 3.270 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.645 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  8.634 ms/op
                 createUser·p0.9999: 23.837 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   3: 3.259 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  14.352 ms/op
                 createUser·p0.9999: 16.783 ms/op
                 createUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298584
  mean =      3.216 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23221 
    [ 2.500,  5.000) = 270104 
    [ 5.000,  7.500) = 4632 
    [ 7.500, 10.000) = 226 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     15.352 ms/op
     p(99.9900) =     24.089 ms/op
     p(99.9990) =     25.495 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


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
# Warmup Iteration   1: 7.408 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.271 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.220 ±(99.9%) 0.009 ms/op
Iteration   1: 3.105 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.174 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   5.391 ms/op
                 existUser·p0.999:  15.450 ms/op
                 existUser·p0.9999: 18.153 ms/op
                 existUser·p1.00:   18.743 ms/op

Iteration   2: 3.102 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  11.349 ms/op
                 existUser·p0.9999: 25.133 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   3: 3.039 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  15.481 ms/op
                 existUser·p0.9999: 28.851 ms/op
                 existUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311393
  mean =      3.081 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29854 
    [ 2.500,  5.000) = 276034 
    [ 5.000,  7.500) = 4751 
    [ 7.500, 10.000) = 347 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.256 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     14.731 ms/op
     p(99.9900) =     26.996 ms/op
     p(99.9990) =     29.538 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


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
# Warmup Iteration   1: 8.238 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.392 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.333 ±(99.9%) 0.010 ms/op
Iteration   1: 3.201 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.348 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   6.283 ms/op
                 getUser·p0.999:  17.731 ms/op
                 getUser·p0.9999: 20.677 ms/op
                 getUser·p1.00:   21.791 ms/op

Iteration   2: 3.120 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  14.896 ms/op
                 getUser·p0.9999: 21.160 ms/op
                 getUser·p1.00:   21.725 ms/op

Iteration   3: 3.256 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.403 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   5.795 ms/op
                 getUser·p0.999:  10.387 ms/op
                 getUser·p0.9999: 22.589 ms/op
                 getUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300575
  mean =      3.192 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16094 
    [ 2.500,  5.000) = 276397 
    [ 5.000,  7.500) = 7053 
    [ 7.500, 10.000) = 556 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     11.452 ms/op
     p(99.9900) =     21.721 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 9.175 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.125 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.885 ±(99.9%) 0.013 ms/op
Iteration   1: 3.849 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.427 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  15.663 ms/op
                 listUser·p0.9999: 20.208 ms/op
                 listUser·p1.00:   20.939 ms/op

Iteration   2: 3.807 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.653 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.144 ms/op
                 listUser·p0.999:  14.041 ms/op
                 listUser·p0.9999: 20.316 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 3.849 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.366 ms/op
                 listUser·p0.999:  12.251 ms/op
                 listUser·p0.9999: 14.959 ms/op
                 listUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250236
  mean =      3.835 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 240469 
    [ 5.000,  7.500) = 7790 
    [ 7.500, 10.000) = 1279 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.427 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     14.025 ms/op
     p(99.9900) =     20.184 ms/op
     p(99.9990) =     20.889 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.755 ± 5.958  ops/ms
ClientPb.existUser                       thrpt       3  10.176 ± 2.466  ops/ms
ClientPb.getUser                         thrpt       3   9.974 ± 4.681  ops/ms
ClientPb.listUser                        thrpt       3   8.627 ± 3.537  ops/ms
ClientPb.createUser                       avgt       3   3.182 ± 2.170   ms/op
ClientPb.existUser                        avgt       3   3.061 ± 1.362   ms/op
ClientPb.getUser                          avgt       3   3.140 ± 0.065   ms/op
ClientPb.listUser                         avgt       3   3.712 ± 1.144   ms/op
ClientPb.createUser                     sample  298584   3.216 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.569           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.502           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.415           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.352           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.089           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.690           ms/op
ClientPb.existUser                      sample  311393   3.081 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.976           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.325           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.731           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.996           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.983           ms/op
ClientPb.getUser                        sample  300575   3.192 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.059           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.559           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.833           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.452           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.721           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.872           ms/op
ClientPb.listUser                       sample  250236   3.835 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.427           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.744           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.166           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.184           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.025           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.184           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.660           ms/op
