# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.058 ops/ms
# Warmup Iteration   2: 5.592 ops/ms
# Warmup Iteration   3: 8.561 ops/ms
Iteration   1: 9.020 ops/ms
Iteration   2: 8.968 ops/ms
Iteration   3: 9.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.029 ±(99.9%) 1.192 ops/ms [Average]
  (min, avg, max) = (8.968, 9.029, 9.098), stdev = 0.065
  CI (99.9%): [7.837, 10.220] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.268 ops/ms
# Warmup Iteration   2: 8.749 ops/ms
# Warmup Iteration   3: 9.279 ops/ms
Iteration   1: 9.649 ops/ms
Iteration   2: 9.487 ops/ms
Iteration   3: 9.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.523 ±(99.9%) 2.043 ops/ms [Average]
  (min, avg, max) = (9.434, 9.523, 9.649), stdev = 0.112
  CI (99.9%): [7.480, 11.566] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.889 ops/ms
# Warmup Iteration   2: 8.459 ops/ms
# Warmup Iteration   3: 8.994 ops/ms
Iteration   1: 9.186 ops/ms
Iteration   2: 9.199 ops/ms
Iteration   3: 9.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.215 ±(99.9%) 0.713 ops/ms [Average]
  (min, avg, max) = (9.186, 9.215, 9.259), stdev = 0.039
  CI (99.9%): [8.502, 9.927] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.560 ops/ms
# Warmup Iteration   2: 6.820 ops/ms
# Warmup Iteration   3: 7.723 ops/ms
Iteration   1: 7.602 ops/ms
Iteration   2: 7.742 ops/ms
Iteration   3: 7.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.716 ±(99.9%) 1.883 ops/ms [Average]
  (min, avg, max) = (7.602, 7.716, 7.803), stdev = 0.103
  CI (99.9%): [5.833, 9.598] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.428 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.893 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.654 ±(99.9%) 0.003 ms/op
Iteration   1: 3.481 ±(99.9%) 0.005 ms/op
Iteration   2: 3.444 ±(99.9%) 0.008 ms/op
Iteration   3: 3.416 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.447 ±(99.9%) 0.603 ms/op [Average]
  (min, avg, max) = (3.416, 3.447, 3.481), stdev = 0.033
  CI (99.9%): [2.844, 4.050] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.229 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.002 ms/op
Iteration   1: 3.337 ±(99.9%) 0.005 ms/op
Iteration   2: 3.407 ±(99.9%) 0.002 ms/op
Iteration   3: 3.382 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.376 ±(99.9%) 0.648 ms/op [Average]
  (min, avg, max) = (3.337, 3.376, 3.407), stdev = 0.036
  CI (99.9%): [2.728, 4.023] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.269 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.004 ms/op
Iteration   1: 3.477 ±(99.9%) 0.005 ms/op
Iteration   2: 3.482 ±(99.9%) 0.007 ms/op
Iteration   3: 3.461 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.473 ±(99.9%) 0.202 ms/op [Average]
  (min, avg, max) = (3.461, 3.473, 3.482), stdev = 0.011
  CI (99.9%): [3.272, 3.675] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.817 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.356 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.194 ±(99.9%) 0.006 ms/op
Iteration   1: 4.062 ±(99.9%) 0.011 ms/op
Iteration   2: 4.152 ±(99.9%) 0.006 ms/op
Iteration   3: 4.032 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.082 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (4.032, 4.082, 4.152), stdev = 0.062
  CI (99.9%): [2.947, 5.217] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.911 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.486 ±(99.9%) 0.010 ms/op
Iteration   1: 3.537 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.677 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  19.516 ms/op
                 createUser·p0.9999: 22.839 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   2: 3.522 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.642 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  20.100 ms/op
                 createUser·p0.9999: 24.410 ms/op
                 createUser·p1.00:   25.035 ms/op

Iteration   3: 3.553 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  18.448 ms/op
                 createUser·p0.9999: 26.508 ms/op
                 createUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271255
  mean =      3.537 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6336 
    [ 2.500,  5.000) = 258933 
    [ 5.000,  7.500) = 4746 
    [ 7.500, 10.000) = 630 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     25.485 ms/op
     p(99.9990) =     27.230 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 10.434 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.413 ±(99.9%) 0.008 ms/op
Iteration   1: 3.335 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  20.164 ms/op
                 existUser·p0.9999: 22.768 ms/op
                 existUser·p1.00:   24.281 ms/op

Iteration   2: 3.447 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.343 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  22.030 ms/op
                 existUser·p0.9999: 24.745 ms/op
                 existUser·p1.00:   24.969 ms/op

Iteration   3: 3.376 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.554 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  12.290 ms/op
                 existUser·p0.9999: 26.493 ms/op
                 existUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283614
  mean =      3.385 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7579 
    [ 2.500,  5.000) = 270248 
    [ 5.000,  7.500) = 4621 
    [ 7.500, 10.000) = 474 
    [10.000, 12.500) = 342 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     18.015 ms/op
     p(99.9900) =     24.805 ms/op
     p(99.9990) =     26.880 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.317 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.013 ms/op
Iteration   1: 3.555 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.403 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  17.271 ms/op
                 getUser·p0.9999: 21.660 ms/op
                 getUser·p1.00:   22.217 ms/op

Iteration   2: 3.471 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.532 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   5.569 ms/op
                 getUser·p0.999:  7.922 ms/op
                 getUser·p0.9999: 22.931 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   3: 3.578 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.489 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  18.632 ms/op
                 getUser·p0.9999: 27.768 ms/op
                 getUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271475
  mean =      3.534 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2196 
    [ 2.500,  5.000) = 263100 
    [ 5.000,  7.500) = 4999 
    [ 7.500, 10.000) = 578 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.489 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.130 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     25.872 ms/op
     p(99.9990) =     28.176 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.854 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.520 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.012 ms/op
Iteration   1: 4.207 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.915 ms/op
                 listUser·p0.50:   4.092 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   7.936 ms/op
                 listUser·p0.999:  17.753 ms/op
                 listUser·p0.9999: 25.520 ms/op
                 listUser·p1.00:   25.756 ms/op

Iteration   2: 4.132 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  15.991 ms/op
                 listUser·p0.9999: 18.514 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   3: 4.081 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   6.909 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 16.422 ms/op
                 listUser·p1.00:   16.499 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231741
  mean =      4.139 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 221946 
    [ 5.000,  7.500) = 7801 
    [ 7.500, 10.000) = 1337 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 213 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.915 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     15.892 ms/op
     p(99.9900) =     24.570 ms/op
     p(99.9990) =     25.723 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.029 ± 1.192  ops/ms
ClientPb.existUser                       thrpt       3   9.523 ± 2.043  ops/ms
ClientPb.getUser                         thrpt       3   9.215 ± 0.713  ops/ms
ClientPb.listUser                        thrpt       3   7.716 ± 1.883  ops/ms
ClientPb.createUser                       avgt       3   3.447 ± 0.603   ms/op
ClientPb.existUser                        avgt       3   3.376 ± 0.648   ms/op
ClientPb.getUser                          avgt       3   3.473 ± 0.202   ms/op
ClientPb.listUser                         avgt       3   4.082 ± 1.135   ms/op
ClientPb.createUser                     sample  271255   3.537 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.264           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.026           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.169           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.268           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.485           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.787           ms/op
ClientPb.existUser                      sample  283614   3.385 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.188           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.071           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.825           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.015           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.805           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.165           ms/op
ClientPb.getUser                        sample  271475   3.534 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.489           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.404           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.130           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.138           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.872           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.312           ms/op
ClientPb.listUser                       sample  231741   4.139 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.915           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.882           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.193           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.892           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.570           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.756           ms/op
