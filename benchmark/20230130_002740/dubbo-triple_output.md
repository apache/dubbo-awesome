# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.661 ops/ms
# Warmup Iteration   2: 6.375 ops/ms
# Warmup Iteration   3: 9.177 ops/ms
Iteration   1: 9.612 ops/ms
Iteration   2: 10.122 ops/ms
Iteration   3: 10.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.061 ±(99.9%) 7.700 ops/ms [Average]
  (min, avg, max) = (9.612, 10.061, 10.450), stdev = 0.422
  CI (99.9%): [2.361, 17.762] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.295 ops/ms
# Warmup Iteration   2: 9.129 ops/ms
# Warmup Iteration   3: 10.176 ops/ms
Iteration   1: 10.433 ops/ms
Iteration   2: 10.737 ops/ms
Iteration   3: 10.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.515 ±(99.9%) 3.553 ops/ms [Average]
  (min, avg, max) = (10.375, 10.515, 10.737), stdev = 0.195
  CI (99.9%): [6.962, 14.068] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.401 ops/ms
# Warmup Iteration   2: 8.830 ops/ms
# Warmup Iteration   3: 9.487 ops/ms
Iteration   1: 9.820 ops/ms
Iteration   2: 10.248 ops/ms
Iteration   3: 9.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.981 ±(99.9%) 4.246 ops/ms [Average]
  (min, avg, max) = (9.820, 9.981, 10.248), stdev = 0.233
  CI (99.9%): [5.735, 14.227] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.209 ops/ms
# Warmup Iteration   2: 7.856 ops/ms
# Warmup Iteration   3: 8.362 ops/ms
Iteration   1: 8.570 ops/ms
Iteration   2: 8.556 ops/ms
Iteration   3: 8.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.525 ±(99.9%) 1.214 ops/ms [Average]
  (min, avg, max) = (8.448, 8.525, 8.570), stdev = 0.067
  CI (99.9%): [7.311, 9.739] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.551 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.005 ms/op
Iteration   1: 3.239 ±(99.9%) 0.003 ms/op
Iteration   2: 3.133 ±(99.9%) 0.004 ms/op
Iteration   3: 3.206 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.193 ±(99.9%) 0.995 ms/op [Average]
  (min, avg, max) = (3.133, 3.193, 3.239), stdev = 0.055
  CI (99.9%): [2.197, 4.188] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.752 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.307 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.002 ms/op
Iteration   1: 3.070 ±(99.9%) 0.005 ms/op
Iteration   2: 3.242 ±(99.9%) 0.006 ms/op
Iteration   3: 3.219 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.177 ±(99.9%) 1.708 ms/op [Average]
  (min, avg, max) = (3.070, 3.177, 3.242), stdev = 0.094
  CI (99.9%): [1.469, 4.885] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.360 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.415 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.005 ms/op
Iteration   1: 3.279 ±(99.9%) 0.005 ms/op
Iteration   2: 3.168 ±(99.9%) 0.006 ms/op
Iteration   3: 3.214 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.220 ±(99.9%) 1.018 ms/op [Average]
  (min, avg, max) = (3.168, 3.220, 3.279), stdev = 0.056
  CI (99.9%): [2.202, 4.239] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.621 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.254 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.784 ±(99.9%) 0.008 ms/op
Iteration   1: 3.775 ±(99.9%) 0.009 ms/op
Iteration   2: 3.853 ±(99.9%) 0.008 ms/op
Iteration   3: 3.830 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.819 ±(99.9%) 0.731 ms/op [Average]
  (min, avg, max) = (3.775, 3.819, 3.853), stdev = 0.040
  CI (99.9%): [3.088, 4.550] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.483 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.589 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.009 ms/op
Iteration   1: 3.241 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  11.738 ms/op
                 createUser·p0.9999: 19.788 ms/op
                 createUser·p1.00:   20.644 ms/op

Iteration   2: 3.161 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.372 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.305 ms/op
                 createUser·p0.95:   3.391 ms/op
                 createUser·p0.99:   5.211 ms/op
                 createUser·p0.999:  10.633 ms/op
                 createUser·p0.9999: 35.455 ms/op
                 createUser·p1.00:   35.521 ms/op

Iteration   3: 3.115 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.270 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.833 ms/op
                 createUser·p0.999:  11.353 ms/op
                 createUser·p0.9999: 31.949 ms/op
                 createUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302226
  mean =      3.172 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19837 
    [ 2.500,  5.000) = 276451 
    [ 5.000,  7.500) = 4997 
    [ 7.500, 10.000) = 543 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     11.600 ms/op
     p(99.9900) =     34.865 ms/op
     p(99.9990) =     35.455 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.855 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.471 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.008 ms/op
Iteration   1: 3.163 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  11.137 ms/op
                 existUser·p0.9999: 23.706 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   2: 3.119 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.776 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   5.054 ms/op
                 existUser·p0.999:  18.487 ms/op
                 existUser·p0.9999: 22.774 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   3: 3.221 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  9.989 ms/op
                 existUser·p0.9999: 22.783 ms/op
                 existUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302848
  mean =      3.167 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33799 
    [ 2.500,  5.000) = 264637 
    [ 5.000,  7.500) = 3651 
    [ 7.500, 10.000) = 379 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      5.218 ms/op
     p(99.9000) =     11.930 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     24.083 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.358 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.554 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.011 ms/op
Iteration   1: 3.175 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   6.676 ms/op
                 getUser·p0.999:  17.378 ms/op
                 getUser·p0.9999: 20.541 ms/op
                 getUser·p1.00:   21.561 ms/op

Iteration   2: 3.109 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.346 ms/op
                 getUser·p0.95:   3.539 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  11.538 ms/op
                 getUser·p0.9999: 22.526 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   3: 3.387 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.530 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   4.092 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  16.122 ms/op
                 getUser·p0.9999: 21.268 ms/op
                 getUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297960
  mean =      3.220 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11797 
    [ 2.500,  5.000) = 278378 
    [ 5.000,  7.500) = 6709 
    [ 7.500, 10.000) = 599 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 146 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     16.550 ms/op
     p(99.9900) =     21.922 ms/op
     p(99.9990) =     24.668 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.997 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.012 ms/op
Iteration   1: 3.822 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.902 ms/op
                 listUser·p0.999:  16.077 ms/op
                 listUser·p0.9999: 22.811 ms/op
                 listUser·p1.00:   23.757 ms/op

Iteration   2: 3.755 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  14.835 ms/op
                 listUser·p0.9999: 19.544 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   3: 3.743 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  13.608 ms/op
                 listUser·p0.9999: 18.026 ms/op
                 listUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254342
  mean =      3.773 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 245231 
    [ 5.000,  7.500) = 6677 
    [ 7.500, 10.000) = 1639 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      7.386 ms/op
     p(99.9000) =     14.631 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     23.391 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.061 ± 7.700  ops/ms
ClientPb.existUser                       thrpt       3  10.515 ± 3.553  ops/ms
ClientPb.getUser                         thrpt       3   9.981 ± 4.246  ops/ms
ClientPb.listUser                        thrpt       3   8.525 ± 1.214  ops/ms
ClientPb.createUser                       avgt       3   3.193 ± 0.995   ms/op
ClientPb.existUser                        avgt       3   3.177 ± 1.708   ms/op
ClientPb.getUser                          avgt       3   3.220 ± 1.018   ms/op
ClientPb.listUser                         avgt       3   3.819 ± 0.731   ms/op
ClientPb.createUser                     sample  302226   3.172 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.270           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.494           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.579           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.600           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.865           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.521           ms/op
ClientPb.existUser                      sample  302848   3.167 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.846           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.412           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.218           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.930           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.872           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.248           ms/op
ClientPb.getUser                        sample  297960   3.220 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.053           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.670           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.201           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.550           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.922           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.214           ms/op
ClientPb.listUser                       sample  254342   3.773 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.167           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.625           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.116           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.386           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.631           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.561           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.757           ms/op
