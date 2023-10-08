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
# Warmup Iteration   1: 2.388 ops/ms
# Warmup Iteration   2: 6.118 ops/ms
# Warmup Iteration   3: 8.901 ops/ms
Iteration   1: 9.634 ops/ms
Iteration   2: 9.572 ops/ms
Iteration   3: 9.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.604 ±(99.9%) 0.574 ops/ms [Average]
  (min, avg, max) = (9.572, 9.604, 9.634), stdev = 0.031
  CI (99.9%): [9.030, 10.178] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.595 ops/ms
# Warmup Iteration   2: 9.134 ops/ms
# Warmup Iteration   3: 9.862 ops/ms
Iteration   1: 10.156 ops/ms
Iteration   2: 10.358 ops/ms
Iteration   3: 10.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.249 ±(99.9%) 1.860 ops/ms [Average]
  (min, avg, max) = (10.156, 10.249, 10.358), stdev = 0.102
  CI (99.9%): [8.389, 12.109] (assumes normal distribution)


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
# Warmup Iteration   1: 3.701 ops/ms
# Warmup Iteration   2: 8.825 ops/ms
# Warmup Iteration   3: 9.719 ops/ms
Iteration   1: 9.556 ops/ms
Iteration   2: 9.625 ops/ms
Iteration   3: 9.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.679 ±(99.9%) 2.864 ops/ms [Average]
  (min, avg, max) = (9.556, 9.679, 9.856), stdev = 0.157
  CI (99.9%): [6.815, 12.543] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.353 ops/ms
# Warmup Iteration   2: 7.677 ops/ms
# Warmup Iteration   3: 8.098 ops/ms
Iteration   1: 8.132 ops/ms
Iteration   2: 8.488 ops/ms
Iteration   3: 8.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.362 ±(99.9%) 3.648 ops/ms [Average]
  (min, avg, max) = (8.132, 8.362, 8.488), stdev = 0.200
  CI (99.9%): [4.715, 12.010] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.944 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.003 ms/op
Iteration   1: 3.268 ±(99.9%) 0.003 ms/op
Iteration   2: 3.244 ±(99.9%) 0.004 ms/op
Iteration   3: 3.267 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.260 ±(99.9%) 0.248 ms/op [Average]
  (min, avg, max) = (3.244, 3.260, 3.268), stdev = 0.014
  CI (99.9%): [3.012, 3.507] (assumes normal distribution)


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
# Warmup Iteration   1: 8.200 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.374 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.002 ms/op
Iteration   1: 3.158 ±(99.9%) 0.004 ms/op
Iteration   2: 3.123 ±(99.9%) 0.003 ms/op
Iteration   3: 3.083 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.121 ±(99.9%) 0.691 ms/op [Average]
  (min, avg, max) = (3.083, 3.121, 3.158), stdev = 0.038
  CI (99.9%): [2.430, 3.813] (assumes normal distribution)


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
# Warmup Iteration   1: 8.296 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.002 ms/op
Iteration   1: 3.344 ±(99.9%) 0.003 ms/op
Iteration   2: 3.264 ±(99.9%) 0.003 ms/op
Iteration   3: 3.212 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.273 ±(99.9%) 1.212 ms/op [Average]
  (min, avg, max) = (3.212, 3.273, 3.344), stdev = 0.066
  CI (99.9%): [2.062, 4.485] (assumes normal distribution)


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
# Warmup Iteration   1: 9.501 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.090 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.002 ms/op
Iteration   1: 3.903 ±(99.9%) 0.003 ms/op
Iteration   2: 3.802 ±(99.9%) 0.006 ms/op
Iteration   3: 3.826 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.844 ±(99.9%) 0.968 ms/op [Average]
  (min, avg, max) = (3.802, 3.844, 3.903), stdev = 0.053
  CI (99.9%): [2.876, 4.811] (assumes normal distribution)


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
# Warmup Iteration   1: 8.549 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.008 ms/op
Iteration   1: 3.318 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.145 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  16.186 ms/op
                 createUser·p0.9999: 19.741 ms/op
                 createUser·p1.00:   20.644 ms/op

Iteration   2: 3.333 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.339 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  18.550 ms/op
                 createUser·p0.9999: 22.623 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   3: 3.317 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.642 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.065 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  14.821 ms/op
                 createUser·p0.9999: 22.646 ms/op
                 createUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288703
  mean =      3.323 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12221 
    [ 2.500,  5.000) = 271003 
    [ 5.000,  7.500) = 4451 
    [ 7.500, 10.000) = 466 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     22.197 ms/op
     p(99.9990) =     23.695 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 7.452 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.359 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.008 ms/op
Iteration   1: 3.213 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  12.387 ms/op
                 existUser·p0.9999: 19.597 ms/op
                 existUser·p1.00:   20.349 ms/op

Iteration   2: 3.271 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.276 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   6.791 ms/op
                 existUser·p0.999:  8.471 ms/op
                 existUser·p0.9999: 22.617 ms/op
                 existUser·p1.00:   23.822 ms/op

Iteration   3: 3.203 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.599 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  12.338 ms/op
                 existUser·p0.9999: 24.873 ms/op
                 existUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297108
  mean =      3.229 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14350 
    [ 2.500,  5.000) = 277512 
    [ 5.000,  7.500) = 4505 
    [ 7.500, 10.000) = 315 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     11.354 ms/op
     p(99.9900) =     23.251 ms/op
     p(99.9990) =     25.823 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 8.426 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.009 ms/op
Iteration   1: 3.333 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   6.283 ms/op
                 getUser·p0.999:  19.005 ms/op
                 getUser·p0.9999: 24.996 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   2: 3.217 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.321 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  12.632 ms/op
                 getUser·p0.9999: 22.741 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   3: 3.220 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   3.140 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   5.592 ms/op
                 getUser·p0.999:  8.744 ms/op
                 getUser·p0.9999: 21.280 ms/op
                 getUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294778
  mean =      3.256 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8017 
    [ 2.500,  5.000) = 281593 
    [ 5.000,  7.500) = 4248 
    [ 7.500, 10.000) = 402 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     25.592 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 8.663 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.070 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.011 ms/op
Iteration   1: 3.885 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.585 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  13.063 ms/op
                 listUser·p0.9999: 19.882 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   2: 3.863 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.798 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  14.419 ms/op
                 listUser·p0.9999: 23.896 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   3: 3.838 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  13.212 ms/op
                 listUser·p0.9999: 14.664 ms/op
                 listUser·p1.00:   15.647 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248575
  mean =      3.862 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 241304 
    [ 5.000,  7.500) = 5929 
    [ 7.500, 10.000) = 580 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 373 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.585 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.239 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     13.468 ms/op
     p(99.9900) =     22.586 ms/op
     p(99.9990) =     25.466 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.604 ± 0.574  ops/ms
ClientPb.existUser                       thrpt       3  10.249 ± 1.860  ops/ms
ClientPb.getUser                         thrpt       3   9.679 ± 2.864  ops/ms
ClientPb.listUser                        thrpt       3   8.362 ± 3.648  ops/ms
ClientPb.createUser                       avgt       3   3.260 ± 0.248   ms/op
ClientPb.existUser                        avgt       3   3.121 ± 0.691   ms/op
ClientPb.getUser                          avgt       3   3.273 ± 1.212   ms/op
ClientPb.listUser                         avgt       3   3.844 ± 0.968   ms/op
ClientPb.createUser                     sample  288703   3.323 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.145           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.890           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.745           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.197           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.888           ms/op
ClientPb.existUser                      sample  297108   3.229 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.932           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.920           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.890           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.354           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.251           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.919           ms/op
ClientPb.getUser                        sample  294778   3.256 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.967           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.775           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.170           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.970           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.657           ms/op
ClientPb.listUser                       sample  248575   3.862 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.585           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.748           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.239           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.726           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.468           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.586           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.182           ms/op
