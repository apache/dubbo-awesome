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
# Warmup Iteration   1: 2.794 ops/ms
# Warmup Iteration   2: 6.294 ops/ms
# Warmup Iteration   3: 9.331 ops/ms
Iteration   1: 10.099 ops/ms
Iteration   2: 9.902 ops/ms
Iteration   3: 10.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.133 ±(99.9%) 4.558 ops/ms [Average]
  (min, avg, max) = (9.902, 10.133, 10.398), stdev = 0.250
  CI (99.9%): [5.575, 14.692] (assumes normal distribution)


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
# Warmup Iteration   1: 3.375 ops/ms
# Warmup Iteration   2: 9.164 ops/ms
# Warmup Iteration   3: 10.512 ops/ms
Iteration   1: 10.257 ops/ms
Iteration   2: 10.195 ops/ms
Iteration   3: 10.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.370 ±(99.9%) 4.579 ops/ms [Average]
  (min, avg, max) = (10.195, 10.370, 10.657), stdev = 0.251
  CI (99.9%): [5.791, 14.948] (assumes normal distribution)


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
# Warmup Iteration   1: 3.570 ops/ms
# Warmup Iteration   2: 9.307 ops/ms
# Warmup Iteration   3: 9.912 ops/ms
Iteration   1: 10.333 ops/ms
Iteration   2: 10.038 ops/ms
Iteration   3: 10.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.149 ±(99.9%) 2.937 ops/ms [Average]
  (min, avg, max) = (10.038, 10.149, 10.333), stdev = 0.161
  CI (99.9%): [7.212, 13.085] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.361 ops/ms
# Warmup Iteration   2: 7.775 ops/ms
# Warmup Iteration   3: 8.365 ops/ms
Iteration   1: 8.447 ops/ms
Iteration   2: 8.617 ops/ms
Iteration   3: 8.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.495 ±(99.9%) 1.952 ops/ms [Average]
  (min, avg, max) = (8.420, 8.495, 8.617), stdev = 0.107
  CI (99.9%): [6.543, 10.447] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.399 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.490 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.003 ms/op
Iteration   1: 3.123 ±(99.9%) 0.007 ms/op
Iteration   2: 3.093 ±(99.9%) 0.009 ms/op
Iteration   3: 3.169 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.128 ±(99.9%) 0.691 ms/op [Average]
  (min, avg, max) = (3.093, 3.128, 3.169), stdev = 0.038
  CI (99.9%): [2.437, 3.820] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.553 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.352 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.004 ms/op
Iteration   1: 2.989 ±(99.9%) 0.002 ms/op
Iteration   2: 3.037 ±(99.9%) 0.008 ms/op
Iteration   3: 2.990 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.005 ±(99.9%) 0.494 ms/op [Average]
  (min, avg, max) = (2.989, 3.005, 3.037), stdev = 0.027
  CI (99.9%): [2.512, 3.499] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.583 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.350 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.005 ms/op
Iteration   1: 3.119 ±(99.9%) 0.006 ms/op
Iteration   2: 3.202 ±(99.9%) 0.004 ms/op
Iteration   3: 3.188 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.169 ±(99.9%) 0.813 ms/op [Average]
  (min, avg, max) = (3.119, 3.169, 3.202), stdev = 0.045
  CI (99.9%): [2.357, 3.982] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.330 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.974 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.006 ms/op
Iteration   1: 3.626 ±(99.9%) 0.008 ms/op
Iteration   2: 3.716 ±(99.9%) 0.006 ms/op
Iteration   3: 3.621 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.655 ±(99.9%) 0.978 ms/op [Average]
  (min, avg, max) = (3.621, 3.655, 3.716), stdev = 0.054
  CI (99.9%): [2.677, 4.632] (assumes normal distribution)


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
# Warmup Iteration   1: 7.583 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.009 ms/op
Iteration   1: 3.088 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.318 ms/op
                 createUser·p0.95:   3.568 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  12.111 ms/op
                 createUser·p0.9999: 19.548 ms/op
                 createUser·p1.00:   20.972 ms/op

Iteration   2: 3.143 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   5.501 ms/op
                 createUser·p0.999:  9.358 ms/op
                 createUser·p0.9999: 22.719 ms/op
                 createUser·p1.00:   23.331 ms/op

Iteration   3: 3.096 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.265 ms/op
                 createUser·p0.95:   3.543 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  17.698 ms/op
                 createUser·p0.9999: 26.499 ms/op
                 createUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 308545
  mean =      3.109 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24936 
    [ 2.500,  5.000) = 279740 
    [ 5.000,  7.500) = 2947 
    [ 7.500, 10.000) = 428 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     16.424 ms/op
     p(99.9900) =     25.508 ms/op
     p(99.9990) =     26.867 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 7.081 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.351 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.008 ms/op
Iteration   1: 3.075 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  7.995 ms/op
                 existUser·p0.9999: 21.463 ms/op
                 existUser·p1.00:   23.462 ms/op

Iteration   2: 3.031 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.401 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  9.028 ms/op
                 existUser·p0.9999: 20.480 ms/op
                 existUser·p1.00:   22.282 ms/op

Iteration   3: 3.043 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.587 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   5.578 ms/op
                 existUser·p0.999:  15.565 ms/op
                 existUser·p0.9999: 21.840 ms/op
                 existUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314635
  mean =      3.049 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15675 
    [ 2.500,  5.000) = 294055 
    [ 5.000,  7.500) = 4133 
    [ 7.500, 10.000) = 300 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      5.235 ms/op
     p(99.9000) =     15.456 ms/op
     p(99.9900) =     21.513 ms/op
     p(99.9990) =     22.586 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 8.228 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.010 ms/op
Iteration   1: 3.247 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.233 ms/op
                 getUser·p0.999:  18.268 ms/op
                 getUser·p0.9999: 23.603 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   2: 3.235 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  9.674 ms/op
                 getUser·p0.9999: 26.156 ms/op
                 getUser·p1.00:   26.509 ms/op

Iteration   3: 3.250 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.157 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  10.273 ms/op
                 getUser·p0.9999: 20.943 ms/op
                 getUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296034
  mean =      3.244 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20631 
    [ 2.500,  5.000) = 266700 
    [ 5.000,  7.500) = 7660 
    [ 7.500, 10.000) = 659 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     16.203 ms/op
     p(99.9900) =     25.048 ms/op
     p(99.9990) =     26.415 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 8.200 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.053 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.792 ±(99.9%) 0.011 ms/op
Iteration   1: 3.781 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.806 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 18.319 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   2: 3.827 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.569 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 20.054 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   3: 3.754 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.334 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  14.123 ms/op
                 listUser·p0.9999: 19.709 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253544
  mean =      3.787 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 83 
    [ 2.500,  5.000) = 244412 
    [ 5.000,  7.500) = 6832 
    [ 7.500, 10.000) = 1445 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 296 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.334 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     14.737 ms/op
     p(99.9900) =     19.670 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.133 ± 4.558  ops/ms
ClientPb.existUser                       thrpt       3  10.370 ± 4.579  ops/ms
ClientPb.getUser                         thrpt       3  10.149 ± 2.937  ops/ms
ClientPb.listUser                        thrpt       3   8.495 ± 1.952  ops/ms
ClientPb.createUser                       avgt       3   3.128 ± 0.691   ms/op
ClientPb.existUser                        avgt       3   3.005 ± 0.494   ms/op
ClientPb.getUser                          avgt       3   3.169 ± 0.813   ms/op
ClientPb.listUser                         avgt       3   3.655 ± 0.978   ms/op
ClientPb.createUser                     sample  308545   3.109 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.888           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.604           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.333           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.424           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.508           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.968           ms/op
ClientPb.existUser                      sample  314635   3.049 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.915           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.535           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.235           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.456           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.513           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.462           ms/op
ClientPb.getUser                        sample  296034   3.244 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.972           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.682           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.939           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.203           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.048           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.509           ms/op
ClientPb.listUser                       sample  253544   3.787 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.334           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.666           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.225           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.737           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.670           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.251           ms/op
