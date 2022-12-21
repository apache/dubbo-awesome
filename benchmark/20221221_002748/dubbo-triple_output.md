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
# Warmup Iteration   1: 2.491 ops/ms
# Warmup Iteration   2: 6.402 ops/ms
# Warmup Iteration   3: 9.198 ops/ms
Iteration   1: 10.260 ops/ms
Iteration   2: 9.887 ops/ms
Iteration   3: 9.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.046 ±(99.9%) 3.516 ops/ms [Average]
  (min, avg, max) = (9.887, 10.046, 10.260), stdev = 0.193
  CI (99.9%): [6.530, 13.563] (assumes normal distribution)


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
# Warmup Iteration   1: 3.412 ops/ms
# Warmup Iteration   2: 9.290 ops/ms
# Warmup Iteration   3: 10.402 ops/ms
Iteration   1: 10.655 ops/ms
Iteration   2: 10.686 ops/ms
Iteration   3: 10.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.663 ±(99.9%) 0.370 ops/ms [Average]
  (min, avg, max) = (10.647, 10.663, 10.686), stdev = 0.020
  CI (99.9%): [10.292, 11.033] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.761 ops/ms
# Warmup Iteration   2: 8.994 ops/ms
# Warmup Iteration   3: 9.740 ops/ms
Iteration   1: 10.073 ops/ms
Iteration   2: 9.989 ops/ms
Iteration   3: 10.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.084 ±(99.9%) 1.861 ops/ms [Average]
  (min, avg, max) = (9.989, 10.084, 10.192), stdev = 0.102
  CI (99.9%): [8.223, 11.945] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.527 ops/ms
# Warmup Iteration   2: 8.050 ops/ms
# Warmup Iteration   3: 8.336 ops/ms
Iteration   1: 8.429 ops/ms
Iteration   2: 8.709 ops/ms
Iteration   3: 8.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.519 ±(99.9%) 3.005 ops/ms [Average]
  (min, avg, max) = (8.419, 8.519, 8.709), stdev = 0.165
  CI (99.9%): [5.514, 11.524] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.750 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.593 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.006 ms/op
Iteration   1: 3.106 ±(99.9%) 0.001 ms/op
Iteration   2: 3.144 ±(99.9%) 0.002 ms/op
Iteration   3: 3.061 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.104 ±(99.9%) 0.757 ms/op [Average]
  (min, avg, max) = (3.061, 3.104, 3.144), stdev = 0.041
  CI (99.9%): [2.347, 3.860] (assumes normal distribution)


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
# Warmup Iteration   1: 6.512 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.441 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.005 ms/op
Iteration   1: 2.994 ±(99.9%) 0.004 ms/op
Iteration   2: 3.040 ±(99.9%) 0.004 ms/op
Iteration   3: 2.967 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.000 ±(99.9%) 0.682 ms/op [Average]
  (min, avg, max) = (2.967, 3.000, 3.040), stdev = 0.037
  CI (99.9%): [2.319, 3.682] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.499 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.366 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.366 ±(99.9%) 0.003 ms/op
Iteration   1: 3.116 ±(99.9%) 0.003 ms/op
Iteration   2: 3.186 ±(99.9%) 0.006 ms/op
Iteration   3: 3.223 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.175 ±(99.9%) 0.989 ms/op [Average]
  (min, avg, max) = (3.116, 3.175, 3.223), stdev = 0.054
  CI (99.9%): [2.186, 4.164] (assumes normal distribution)


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
# Warmup Iteration   1: 8.579 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.963 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.738 ±(99.9%) 0.007 ms/op
Iteration   1: 3.710 ±(99.9%) 0.010 ms/op
Iteration   2: 3.704 ±(99.9%) 0.007 ms/op
Iteration   3: 3.611 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.675 ±(99.9%) 1.009 ms/op [Average]
  (min, avg, max) = (3.611, 3.675, 3.710), stdev = 0.055
  CI (99.9%): [2.666, 4.683] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.179 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.008 ms/op
Iteration   1: 3.249 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.214 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  16.613 ms/op
                 createUser·p0.9999: 18.711 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   2: 3.127 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  16.088 ms/op
                 createUser·p0.9999: 21.441 ms/op
                 createUser·p1.00:   22.938 ms/op

Iteration   3: 3.130 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   5.104 ms/op
                 createUser·p0.999:  13.278 ms/op
                 createUser·p0.9999: 21.252 ms/op
                 createUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303001
  mean =      3.167 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23158 
    [ 2.500,  5.000) = 272772 
    [ 5.000,  7.500) = 6067 
    [ 7.500, 10.000) = 510 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     16.040 ms/op
     p(99.9900) =     20.962 ms/op
     p(99.9990) =     22.704 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.550 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.475 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.007 ms/op
Iteration   1: 3.004 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  11.387 ms/op
                 existUser·p0.9999: 19.952 ms/op
                 existUser·p1.00:   20.775 ms/op

Iteration   2: 3.078 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.579 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  12.632 ms/op
                 existUser·p0.9999: 21.831 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   3: 3.252 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   6.221 ms/op
                 existUser·p0.999:  12.011 ms/op
                 existUser·p0.9999: 22.156 ms/op
                 existUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308667
  mean =      3.108 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22636 
    [ 2.500,  5.000) = 280536 
    [ 5.000,  7.500) = 4627 
    [ 7.500, 10.000) = 414 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     12.282 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     22.435 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 7.599 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.358 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.184 ±(99.9%) 0.010 ms/op
Iteration   1: 3.129 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   5.465 ms/op
                 getUser·p0.999:  11.970 ms/op
                 getUser·p0.9999: 21.004 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   2: 3.059 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.520 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.318 ms/op
                 getUser·p0.95:   3.592 ms/op
                 getUser·p0.99:   5.251 ms/op
                 getUser·p0.999:  10.641 ms/op
                 getUser·p0.9999: 25.612 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  9.716 ms/op
                 getUser·p0.9999: 23.301 ms/op
                 getUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 309654
  mean =      3.096 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17589 
    [ 2.500,  5.000) = 286456 
    [ 5.000,  7.500) = 4916 
    [ 7.500, 10.000) = 345 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     11.076 ms/op
     p(99.9900) =     23.628 ms/op
     p(99.9990) =     26.113 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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
# Warmup Iteration   1: 9.159 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.999 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.010 ms/op
Iteration   1: 3.700 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.942 ms/op
                 listUser·p0.50:   3.518 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  16.065 ms/op
                 listUser·p0.9999: 20.843 ms/op
                 listUser·p1.00:   25.428 ms/op

Iteration   2: 3.643 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.182 ms/op
                 listUser·p0.99:   6.341 ms/op
                 listUser·p0.999:  13.189 ms/op
                 listUser·p0.9999: 14.582 ms/op
                 listUser·p1.00:   14.811 ms/op

Iteration   3: 3.731 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  13.369 ms/op
                 listUser·p0.9999: 15.478 ms/op
                 listUser·p1.00:   15.663 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 260039
  mean =      3.691 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 252813 
    [ 5.000,  7.500) = 5537 
    [ 7.500, 10.000) = 1025 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 332 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.942 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.845 ms/op
     p(99.9000) =     13.631 ms/op
     p(99.9900) =     19.071 ms/op
     p(99.9990) =     23.259 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.046 ± 3.516  ops/ms
ClientPb.existUser                       thrpt       3  10.663 ± 0.370  ops/ms
ClientPb.getUser                         thrpt       3  10.084 ± 1.861  ops/ms
ClientPb.listUser                        thrpt       3   8.519 ± 3.005  ops/ms
ClientPb.createUser                       avgt       3   3.104 ± 0.757   ms/op
ClientPb.existUser                        avgt       3   3.000 ± 0.682   ms/op
ClientPb.getUser                          avgt       3   3.175 ± 0.989   ms/op
ClientPb.listUser                         avgt       3   3.675 ± 1.009   ms/op
ClientPb.createUser                     sample  303001   3.167 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.055           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.584           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.040           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.962           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.938           ms/op
ClientPb.existUser                      sample  308667   3.108 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.791           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.396           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.282           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.725           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.708           ms/op
ClientPb.getUser                        sample  309654   3.096 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.920           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.400           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.674           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.423           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.076           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.628           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.313           ms/op
ClientPb.listUser                       sample  260039   3.691 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.942           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.625           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.845           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.631           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.071           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.428           ms/op
