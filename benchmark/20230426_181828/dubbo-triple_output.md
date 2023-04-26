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
# Warmup Iteration   1: 2.701 ops/ms
# Warmup Iteration   2: 6.494 ops/ms
# Warmup Iteration   3: 9.391 ops/ms
Iteration   1: 10.308 ops/ms
Iteration   2: 10.265 ops/ms
Iteration   3: 10.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.204 ±(99.9%) 2.634 ops/ms [Average]
  (min, avg, max) = (10.039, 10.204, 10.308), stdev = 0.144
  CI (99.9%): [7.570, 12.838] (assumes normal distribution)


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
# Warmup Iteration   1: 3.651 ops/ms
# Warmup Iteration   2: 9.325 ops/ms
# Warmup Iteration   3: 9.925 ops/ms
Iteration   1: 10.698 ops/ms
Iteration   2: 10.412 ops/ms
Iteration   3: 10.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.450 ±(99.9%) 4.225 ops/ms [Average]
  (min, avg, max) = (10.239, 10.450, 10.698), stdev = 0.232
  CI (99.9%): [6.224, 14.675] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.626 ops/ms
# Warmup Iteration   2: 9.399 ops/ms
# Warmup Iteration   3: 9.983 ops/ms
Iteration   1: 9.867 ops/ms
Iteration   2: 10.172 ops/ms
Iteration   3: 10.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.050 ±(99.9%) 2.944 ops/ms [Average]
  (min, avg, max) = (9.867, 10.050, 10.172), stdev = 0.161
  CI (99.9%): [7.106, 12.994] (assumes normal distribution)


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
# Warmup Iteration   1: 3.519 ops/ms
# Warmup Iteration   2: 7.836 ops/ms
# Warmup Iteration   3: 8.228 ops/ms
Iteration   1: 8.773 ops/ms
Iteration   2: 8.844 ops/ms
Iteration   3: 8.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.767 ±(99.9%) 1.474 ops/ms [Average]
  (min, avg, max) = (8.683, 8.767, 8.844), stdev = 0.081
  CI (99.9%): [7.293, 10.241] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.351 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.379 ±(99.9%) 0.005 ms/op
Iteration   1: 3.174 ±(99.9%) 0.009 ms/op
Iteration   2: 3.396 ±(99.9%) 0.006 ms/op
Iteration   3: 3.156 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.242 ±(99.9%) 2.443 ms/op [Average]
  (min, avg, max) = (3.156, 3.242, 3.396), stdev = 0.134
  CI (99.9%): [0.799, 5.685] (assumes normal distribution)


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
# Warmup Iteration   1: 7.174 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.319 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.007 ms/op
Iteration   1: 3.088 ±(99.9%) 0.006 ms/op
Iteration   2: 3.098 ±(99.9%) 0.005 ms/op
Iteration   3: 3.120 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.102 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (3.088, 3.102, 3.120), stdev = 0.016
  CI (99.9%): [2.811, 3.394] (assumes normal distribution)


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
# Warmup Iteration   1: 7.379 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.299 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.006 ms/op
Iteration   1: 3.316 ±(99.9%) 0.005 ms/op
Iteration   2: 3.284 ±(99.9%) 0.004 ms/op
Iteration   3: 3.071 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.224 ±(99.9%) 2.425 ms/op [Average]
  (min, avg, max) = (3.071, 3.224, 3.316), stdev = 0.133
  CI (99.9%): [0.799, 5.649] (assumes normal distribution)


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
# Warmup Iteration   1: 9.076 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.028 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.005 ms/op
Iteration   1: 3.768 ±(99.9%) 0.005 ms/op
Iteration   2: 3.618 ±(99.9%) 0.010 ms/op
Iteration   3: 3.767 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.718 ±(99.9%) 1.579 ms/op [Average]
  (min, avg, max) = (3.618, 3.718, 3.768), stdev = 0.087
  CI (99.9%): [2.139, 5.297] (assumes normal distribution)


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
# Warmup Iteration   1: 7.426 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.008 ms/op
Iteration   1: 3.253 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.214 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  11.671 ms/op
                 createUser·p0.9999: 25.215 ms/op
                 createUser·p1.00:   26.018 ms/op

Iteration   2: 3.152 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  9.117 ms/op
                 createUser·p0.9999: 22.315 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.289 ms/op
                 createUser·p0.95:   3.551 ms/op
                 createUser·p0.99:   5.145 ms/op
                 createUser·p0.999:  16.695 ms/op
                 createUser·p0.9999: 18.665 ms/op
                 createUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301833
  mean =      3.180 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27551 
    [ 2.500,  5.000) = 266746 
    [ 5.000,  7.500) = 6739 
    [ 7.500, 10.000) = 423 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     16.493 ms/op
     p(99.9900) =     24.230 ms/op
     p(99.9990) =     25.719 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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
# Warmup Iteration   1: 6.944 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.383 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.007 ms/op
Iteration   1: 3.082 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  8.077 ms/op
                 existUser·p0.9999: 24.301 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   2: 3.004 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.321 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.129 ms/op
                 existUser·p0.95:   3.277 ms/op
                 existUser·p0.99:   4.719 ms/op
                 existUser·p0.999:  12.009 ms/op
                 existUser·p0.9999: 22.110 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.386 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.351 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  12.664 ms/op
                 existUser·p0.9999: 19.064 ms/op
                 existUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314226
  mean =      3.053 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23889 
    [ 2.500,  5.000) = 287006 
    [ 5.000,  7.500) = 2612 
    [ 7.500, 10.000) = 196 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.232 ms/op
     p(95.0000) =      3.465 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =     12.006 ms/op
     p(99.9900) =     22.891 ms/op
     p(99.9990) =     25.082 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 8.476 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.409 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.008 ms/op
Iteration   1: 3.162 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   6.177 ms/op
                 getUser·p0.999:  16.036 ms/op
                 getUser·p0.9999: 25.199 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   2: 3.105 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.338 ms/op
                 getUser·p0.95:   3.494 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  19.500 ms/op
                 getUser·p0.9999: 22.109 ms/op
                 getUser·p1.00:   25.166 ms/op

Iteration   3: 3.196 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  10.535 ms/op
                 getUser·p0.9999: 16.629 ms/op
                 getUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303993
  mean =      3.154 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10948 
    [ 2.500,  5.000) = 285877 
    [ 5.000,  7.500) = 6161 
    [ 7.500, 10.000) = 590 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.018 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     23.822 ms/op
     p(99.9990) =     26.193 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 9.301 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.198 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.012 ms/op
Iteration   1: 3.709 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.042 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  18.144 ms/op
                 listUser·p0.9999: 22.503 ms/op
                 listUser·p1.00:   23.462 ms/op

Iteration   2: 3.785 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.021 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  16.769 ms/op
                 listUser·p0.9999: 22.970 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   3: 3.646 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   3.772 ms/op
                 listUser·p0.95:   4.030 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  12.845 ms/op
                 listUser·p0.9999: 13.926 ms/op
                 listUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258481
  mean =      3.713 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 251270 
    [ 5.000,  7.500) = 5475 
    [ 7.500, 10.000) = 996 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     14.894 ms/op
     p(99.9900) =     22.489 ms/op
     p(99.9990) =     23.424 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.204 ± 2.634  ops/ms
ClientPb.existUser                       thrpt       3  10.450 ± 4.225  ops/ms
ClientPb.getUser                         thrpt       3  10.050 ± 2.944  ops/ms
ClientPb.listUser                        thrpt       3   8.767 ± 1.474  ops/ms
ClientPb.createUser                       avgt       3   3.242 ± 2.443   ms/op
ClientPb.existUser                        avgt       3   3.102 ± 0.292   ms/op
ClientPb.getUser                          avgt       3   3.224 ± 2.425   ms/op
ClientPb.listUser                         avgt       3   3.718 ± 1.579   ms/op
ClientPb.createUser                     sample  301833   3.180 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.857           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.437           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.493           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.230           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.018           ms/op
ClientPb.existUser                      sample  314226   3.053 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.260           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.079           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.006           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.891           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.378           ms/op
ClientPb.getUser                        sample  303993   3.154 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.018           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.441           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.723           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.939           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.238           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.822           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.345           ms/op
ClientPb.listUser                       sample  258481   3.713 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.042           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.750           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.894           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.489           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.822           ms/op
