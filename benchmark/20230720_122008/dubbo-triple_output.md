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
# Warmup Iteration   1: 2.551 ops/ms
# Warmup Iteration   2: 6.626 ops/ms
# Warmup Iteration   3: 8.975 ops/ms
Iteration   1: 9.849 ops/ms
Iteration   2: 9.922 ops/ms
Iteration   3: 9.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.839 ±(99.9%) 1.622 ops/ms [Average]
  (min, avg, max) = (9.745, 9.839, 9.922), stdev = 0.089
  CI (99.9%): [8.217, 11.461] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.735 ops/ms
# Warmup Iteration   2: 8.998 ops/ms
# Warmup Iteration   3: 9.699 ops/ms
Iteration   1: 10.472 ops/ms
Iteration   2: 10.293 ops/ms
Iteration   3: 10.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.282 ±(99.9%) 3.575 ops/ms [Average]
  (min, avg, max) = (10.081, 10.282, 10.472), stdev = 0.196
  CI (99.9%): [6.707, 13.857] (assumes normal distribution)


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
# Warmup Iteration   1: 3.625 ops/ms
# Warmup Iteration   2: 9.252 ops/ms
# Warmup Iteration   3: 9.587 ops/ms
Iteration   1: 9.983 ops/ms
Iteration   2: 10.048 ops/ms
Iteration   3: 9.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.912 ±(99.9%) 3.313 ops/ms [Average]
  (min, avg, max) = (9.706, 9.912, 10.048), stdev = 0.182
  CI (99.9%): [6.599, 13.225] (assumes normal distribution)


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
# Warmup Iteration   1: 3.285 ops/ms
# Warmup Iteration   2: 7.546 ops/ms
# Warmup Iteration   3: 8.144 ops/ms
Iteration   1: 8.574 ops/ms
Iteration   2: 8.383 ops/ms
Iteration   3: 8.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.478 ±(99.9%) 1.735 ops/ms [Average]
  (min, avg, max) = (8.383, 8.478, 8.574), stdev = 0.095
  CI (99.9%): [6.743, 10.213] (assumes normal distribution)


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
# Warmup Iteration   1: 8.930 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.003 ms/op
Iteration   1: 3.258 ±(99.9%) 0.006 ms/op
Iteration   2: 3.297 ±(99.9%) 0.006 ms/op
Iteration   3: 3.377 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.311 ±(99.9%) 1.108 ms/op [Average]
  (min, avg, max) = (3.258, 3.311, 3.377), stdev = 0.061
  CI (99.9%): [2.202, 4.419] (assumes normal distribution)


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
# Warmup Iteration   1: 6.730 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.351 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.004 ms/op
Iteration   1: 3.126 ±(99.9%) 0.011 ms/op
Iteration   2: 3.219 ±(99.9%) 0.007 ms/op
Iteration   3: 3.294 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.213 ±(99.9%) 1.538 ms/op [Average]
  (min, avg, max) = (3.126, 3.213, 3.294), stdev = 0.084
  CI (99.9%): [1.675, 4.751] (assumes normal distribution)


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
# Warmup Iteration   1: 8.824 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.296 ±(99.9%) 0.004 ms/op
Iteration   1: 3.287 ±(99.9%) 0.004 ms/op
Iteration   2: 3.279 ±(99.9%) 0.004 ms/op
Iteration   3: 3.294 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.287 ±(99.9%) 0.141 ms/op [Average]
  (min, avg, max) = (3.279, 3.287, 3.294), stdev = 0.008
  CI (99.9%): [3.146, 3.427] (assumes normal distribution)


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
# Warmup Iteration   1: 9.443 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.793 ±(99.9%) 0.005 ms/op
Iteration   1: 3.918 ±(99.9%) 0.006 ms/op
Iteration   2: 3.744 ±(99.9%) 0.005 ms/op
Iteration   3: 3.657 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.773 ±(99.9%) 2.422 ms/op [Average]
  (min, avg, max) = (3.657, 3.773, 3.918), stdev = 0.133
  CI (99.9%): [1.351, 6.195] (assumes normal distribution)


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
# Warmup Iteration   1: 8.304 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 4.073 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.010 ms/op
Iteration   1: 3.199 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.686 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  15.678 ms/op
                 createUser·p0.9999: 20.480 ms/op
                 createUser·p1.00:   20.972 ms/op

Iteration   2: 3.278 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.442 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  12.630 ms/op
                 createUser·p0.9999: 22.317 ms/op
                 createUser·p1.00:   23.167 ms/op

Iteration   3: 3.194 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.342 ms/op
                 createUser·p0.95:   3.510 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  15.270 ms/op
                 createUser·p0.9999: 21.036 ms/op
                 createUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297866
  mean =      3.223 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27861 
    [ 2.500,  5.000) = 264924 
    [ 5.000,  7.500) = 4377 
    [ 7.500, 10.000) = 293 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.442 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     15.516 ms/op
     p(99.9900) =     21.398 ms/op
     p(99.9990) =     22.874 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 7.751 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.424 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.008 ms/op
Iteration   1: 3.125 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  8.839 ms/op
                 existUser·p0.9999: 20.269 ms/op
                 existUser·p1.00:   21.070 ms/op

Iteration   2: 3.072 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.245 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.801 ms/op
                 existUser·p0.999:  11.715 ms/op
                 existUser·p0.9999: 34.615 ms/op
                 existUser·p1.00:   36.045 ms/op

Iteration   3: 3.297 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.288 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  13.434 ms/op
                 existUser·p0.9999: 24.858 ms/op
                 existUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303353
  mean =      3.162 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18636 
    [ 2.500,  5.000) = 279758 
    [ 5.000,  7.500) = 4205 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.288 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.320 ms/op
     p(99.9000) =     11.633 ms/op
     p(99.9900) =     32.429 ms/op
     p(99.9990) =     35.890 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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
# Warmup Iteration   1: 7.908 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.457 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.011 ms/op
Iteration   1: 3.250 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  10.840 ms/op
                 getUser·p0.9999: 21.342 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   2: 3.268 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.733 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.157 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  9.075 ms/op
                 getUser·p0.9999: 26.680 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   3: 3.272 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  9.917 ms/op
                 getUser·p0.9999: 29.237 ms/op
                 getUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294067
  mean =      3.264 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17408 
    [ 2.500,  5.000) = 269083 
    [ 5.000,  7.500) = 7002 
    [ 7.500, 10.000) = 261 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     10.784 ms/op
     p(99.9900) =     27.759 ms/op
     p(99.9990) =     29.470 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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
# Warmup Iteration   1: 9.650 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.876 ±(99.9%) 0.013 ms/op
Iteration   1: 3.694 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.481 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.178 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  13.637 ms/op
                 listUser·p0.9999: 20.611 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   2: 3.821 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.011 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  13.533 ms/op
                 listUser·p0.9999: 16.637 ms/op
                 listUser·p1.00:   16.843 ms/op

Iteration   3: 3.782 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  14.287 ms/op
                 listUser·p0.9999: 21.529 ms/op
                 listUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254845
  mean =      3.765 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 247955 
    [ 5.000,  7.500) = 5123 
    [ 7.500, 10.000) = 1042 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 280 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.481 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     20.629 ms/op
     p(99.9990) =     22.598 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.839 ± 1.622  ops/ms
ClientPb.existUser                       thrpt       3  10.282 ± 3.575  ops/ms
ClientPb.getUser                         thrpt       3   9.912 ± 3.313  ops/ms
ClientPb.listUser                        thrpt       3   8.478 ± 1.735  ops/ms
ClientPb.createUser                       avgt       3   3.311 ± 1.108   ms/op
ClientPb.existUser                        avgt       3   3.213 ± 1.538   ms/op
ClientPb.getUser                          avgt       3   3.287 ± 0.141   ms/op
ClientPb.listUser                         avgt       3   3.773 ± 2.422   ms/op
ClientPb.createUser                     sample  297866   3.223 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.442           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.502           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.415           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.516           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.398           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.167           ms/op
ClientPb.existUser                      sample  303353   3.162 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.288           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.006           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.320           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.633           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.429           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.045           ms/op
ClientPb.getUser                        sample  294067   3.264 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.882           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.711           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.710           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.784           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.759           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.081           ms/op
ClientPb.listUser                       sample  254845   3.765 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.481           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.808           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.599           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.629           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.691           ms/op
