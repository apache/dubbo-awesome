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
# Warmup Iteration   1: 2.735 ops/ms
# Warmup Iteration   2: 6.852 ops/ms
# Warmup Iteration   3: 9.492 ops/ms
Iteration   1: 9.840 ops/ms
Iteration   2: 9.752 ops/ms
Iteration   3: 10.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.897 ±(99.9%) 3.306 ops/ms [Average]
  (min, avg, max) = (9.752, 9.897, 10.100), stdev = 0.181
  CI (99.9%): [6.592, 13.203] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.459 ops/ms
# Warmup Iteration   2: 9.109 ops/ms
# Warmup Iteration   3: 10.315 ops/ms
Iteration   1: 10.375 ops/ms
Iteration   2: 10.480 ops/ms
Iteration   3: 10.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.526 ±(99.9%) 3.233 ops/ms [Average]
  (min, avg, max) = (10.375, 10.526, 10.721), stdev = 0.177
  CI (99.9%): [7.293, 13.758] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.357 ops/ms
# Warmup Iteration   2: 9.004 ops/ms
# Warmup Iteration   3: 9.726 ops/ms
Iteration   1: 9.913 ops/ms
Iteration   2: 9.704 ops/ms
Iteration   3: 9.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.745 ±(99.9%) 2.757 ops/ms [Average]
  (min, avg, max) = (9.619, 9.745, 9.913), stdev = 0.151
  CI (99.9%): [6.988, 12.502] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.701 ops/ms
# Warmup Iteration   2: 7.933 ops/ms
# Warmup Iteration   3: 8.332 ops/ms
Iteration   1: 8.420 ops/ms
Iteration   2: 8.625 ops/ms
Iteration   3: 8.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.457 ±(99.9%) 2.792 ops/ms [Average]
  (min, avg, max) = (8.326, 8.457, 8.625), stdev = 0.153
  CI (99.9%): [5.665, 11.249] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.634 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.343 ±(99.9%) 0.007 ms/op
Iteration   1: 3.109 ±(99.9%) 0.008 ms/op
Iteration   2: 3.275 ±(99.9%) 0.005 ms/op
Iteration   3: 3.106 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.163 ±(99.9%) 1.764 ms/op [Average]
  (min, avg, max) = (3.106, 3.163, 3.275), stdev = 0.097
  CI (99.9%): [1.399, 4.928] (assumes normal distribution)


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
# Warmup Iteration   1: 8.032 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
Iteration   1: 3.117 ±(99.9%) 0.007 ms/op
Iteration   2: 3.064 ±(99.9%) 0.008 ms/op
Iteration   3: 3.090 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.090 ±(99.9%) 0.487 ms/op [Average]
  (min, avg, max) = (3.064, 3.090, 3.117), stdev = 0.027
  CI (99.9%): [2.603, 3.577] (assumes normal distribution)


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
# Warmup Iteration   1: 7.599 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.322 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.006 ms/op
Iteration   1: 3.250 ±(99.9%) 0.004 ms/op
Iteration   2: 3.262 ±(99.9%) 0.004 ms/op
Iteration   3: 3.146 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.219 ±(99.9%) 1.162 ms/op [Average]
  (min, avg, max) = (3.146, 3.219, 3.262), stdev = 0.064
  CI (99.9%): [2.057, 4.381] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.311 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.819 ±(99.9%) 0.006 ms/op
Iteration   1: 3.704 ±(99.9%) 0.008 ms/op
Iteration   2: 3.631 ±(99.9%) 0.010 ms/op
Iteration   3: 3.717 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.684 ±(99.9%) 0.847 ms/op [Average]
  (min, avg, max) = (3.631, 3.684, 3.717), stdev = 0.046
  CI (99.9%): [2.837, 4.531] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.787 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.009 ms/op
Iteration   1: 3.240 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.319 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  11.763 ms/op
                 createUser·p0.9999: 26.247 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   2: 3.325 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.280 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  16.746 ms/op
                 createUser·p0.9999: 22.557 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.165 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.265 ms/op
                 createUser·p0.95:   3.318 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  11.174 ms/op
                 createUser·p0.9999: 21.201 ms/op
                 createUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297765
  mean =      3.222 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28334 
    [ 2.500,  5.000) = 263751 
    [ 5.000,  7.500) = 4922 
    [ 7.500, 10.000) = 381 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 166 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.280 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     11.354 ms/op
     p(99.9900) =     23.313 ms/op
     p(99.9990) =     26.971 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 7.107 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.324 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.008 ms/op
Iteration   1: 3.093 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.348 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  8.137 ms/op
                 existUser·p0.9999: 19.137 ms/op
                 existUser·p1.00:   19.759 ms/op

Iteration   2: 3.067 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.376 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  13.943 ms/op
                 existUser·p0.9999: 20.185 ms/op
                 existUser·p1.00:   20.972 ms/op

Iteration   3: 3.111 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  16.081 ms/op
                 existUser·p0.9999: 22.517 ms/op
                 existUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310693
  mean =      3.090 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24143 
    [ 2.500,  5.000) = 280960 
    [ 5.000,  7.500) = 4751 
    [ 7.500, 10.000) = 359 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 198 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     20.705 ms/op
     p(99.9990) =     22.963 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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
# Warmup Iteration   1: 8.306 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.010 ms/op
Iteration   1: 3.129 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   5.374 ms/op
                 getUser·p0.999:  17.111 ms/op
                 getUser·p0.9999: 22.148 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   2: 3.150 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  18.350 ms/op
                 getUser·p0.9999: 21.130 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   3: 3.110 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.363 ms/op
                 getUser·p0.95:   3.510 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  8.899 ms/op
                 getUser·p0.9999: 19.239 ms/op
                 getUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 306700
  mean =      3.129 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14269 
    [ 2.500,  5.000) = 287458 
    [ 5.000,  7.500) = 4122 
    [ 7.500, 10.000) = 398 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 204 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     16.361 ms/op
     p(99.9900) =     20.687 ms/op
     p(99.9990) =     22.959 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 8.402 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.010 ms/op
Iteration   1: 3.806 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.831 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.038 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 21.660 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   2: 3.717 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.460 ms/op
                 listUser·p0.50:   3.539 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 20.939 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 3.726 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.556 ms/op
                 listUser·p0.999:  13.582 ms/op
                 listUser·p0.9999: 17.807 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255822
  mean =      3.749 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 247671 
    [ 5.000,  7.500) = 6276 
    [ 7.500, 10.000) = 1185 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.460 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     14.167 ms/op
     p(99.9900) =     20.972 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.897 ± 3.306  ops/ms
ClientPb.existUser                       thrpt       3  10.526 ± 3.233  ops/ms
ClientPb.getUser                         thrpt       3   9.745 ± 2.757  ops/ms
ClientPb.listUser                        thrpt       3   8.457 ± 2.792  ops/ms
ClientPb.createUser                       avgt       3   3.163 ± 1.764   ms/op
ClientPb.existUser                        avgt       3   3.090 ± 0.487   ms/op
ClientPb.getUser                          avgt       3   3.219 ± 1.162   ms/op
ClientPb.listUser                         avgt       3   3.684 ± 0.847   ms/op
ClientPb.createUser                     sample  297765   3.222 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.280           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.666           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.562           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.354           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.313           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.165           ms/op
ClientPb.existUser                      sample  310693   3.090 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.075           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.449           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.423           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.926           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.705           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.691           ms/op
ClientPb.getUser                        sample  306700   3.129 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.075           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.424           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.686           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.448           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.361           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.687           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.003           ms/op
ClientPb.listUser                       sample  255822   3.749 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.460           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.654           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.067           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.947           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.167           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.972           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.117           ms/op
