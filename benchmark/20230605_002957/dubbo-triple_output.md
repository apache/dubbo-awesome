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
# Warmup Iteration   1: 2.206 ops/ms
# Warmup Iteration   2: 5.338 ops/ms
# Warmup Iteration   3: 8.883 ops/ms
Iteration   1: 9.500 ops/ms
Iteration   2: 9.056 ops/ms
Iteration   3: 9.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.261 ±(99.9%) 4.083 ops/ms [Average]
  (min, avg, max) = (9.056, 9.261, 9.500), stdev = 0.224
  CI (99.9%): [5.178, 13.344] (assumes normal distribution)


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
# Warmup Iteration   1: 2.884 ops/ms
# Warmup Iteration   2: 9.058 ops/ms
# Warmup Iteration   3: 9.243 ops/ms
Iteration   1: 9.596 ops/ms
Iteration   2: 9.921 ops/ms
Iteration   3: 9.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.823 ±(99.9%) 3.605 ops/ms [Average]
  (min, avg, max) = (9.596, 9.823, 9.953), stdev = 0.198
  CI (99.9%): [6.218, 13.429] (assumes normal distribution)


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
# Warmup Iteration   1: 3.197 ops/ms
# Warmup Iteration   2: 8.483 ops/ms
# Warmup Iteration   3: 9.114 ops/ms
Iteration   1: 9.477 ops/ms
Iteration   2: 9.520 ops/ms
Iteration   3: 9.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.405 ±(99.9%) 2.979 ops/ms [Average]
  (min, avg, max) = (9.218, 9.405, 9.520), stdev = 0.163
  CI (99.9%): [6.426, 12.384] (assumes normal distribution)


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
# Warmup Iteration   1: 2.867 ops/ms
# Warmup Iteration   2: 7.174 ops/ms
# Warmup Iteration   3: 7.681 ops/ms
Iteration   1: 7.950 ops/ms
Iteration   2: 8.124 ops/ms
Iteration   3: 8.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.092 ±(99.9%) 2.354 ops/ms [Average]
  (min, avg, max) = (7.950, 8.092, 8.202), stdev = 0.129
  CI (99.9%): [5.738, 10.446] (assumes normal distribution)


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
# Warmup Iteration   1: 9.692 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.811 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.496 ±(99.9%) 0.006 ms/op
Iteration   1: 3.337 ±(99.9%) 0.007 ms/op
Iteration   2: 3.339 ±(99.9%) 0.007 ms/op
Iteration   3: 3.402 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.359 ±(99.9%) 0.669 ms/op [Average]
  (min, avg, max) = (3.337, 3.359, 3.402), stdev = 0.037
  CI (99.9%): [2.691, 4.028] (assumes normal distribution)


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
# Warmup Iteration   1: 9.171 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.005 ms/op
Iteration   1: 3.193 ±(99.9%) 0.007 ms/op
Iteration   2: 3.297 ±(99.9%) 0.004 ms/op
Iteration   3: 3.287 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.259 ±(99.9%) 1.043 ms/op [Average]
  (min, avg, max) = (3.193, 3.259, 3.297), stdev = 0.057
  CI (99.9%): [2.216, 4.302] (assumes normal distribution)


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
# Warmup Iteration   1: 9.574 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.896 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.002 ms/op
Iteration   1: 3.456 ±(99.9%) 0.006 ms/op
Iteration   2: 3.448 ±(99.9%) 0.008 ms/op
Iteration   3: 3.383 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.429 ±(99.9%) 0.735 ms/op [Average]
  (min, avg, max) = (3.383, 3.429, 3.456), stdev = 0.040
  CI (99.9%): [2.694, 4.164] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.859 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.364 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.010 ms/op
Iteration   1: 3.827 ±(99.9%) 0.013 ms/op
Iteration   2: 3.961 ±(99.9%) 0.012 ms/op
Iteration   3: 3.936 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.908 ±(99.9%) 1.301 ms/op [Average]
  (min, avg, max) = (3.827, 3.908, 3.961), stdev = 0.071
  CI (99.9%): [2.607, 5.208] (assumes normal distribution)


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
# Warmup Iteration   1: 9.143 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.417 ±(99.9%) 0.010 ms/op
Iteration   1: 3.496 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.292 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   6.685 ms/op
                 createUser·p0.999:  20.138 ms/op
                 createUser·p0.9999: 23.100 ms/op
                 createUser·p1.00:   24.052 ms/op

Iteration   2: 3.463 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.507 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  21.447 ms/op
                 createUser·p0.9999: 24.995 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   3: 3.533 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.554 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   6.767 ms/op
                 createUser·p0.999:  17.895 ms/op
                 createUser·p0.9999: 25.887 ms/op
                 createUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274160
  mean =      3.497 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3009 
    [ 2.500,  5.000) = 261960 
    [ 5.000,  7.500) = 7513 
    [ 7.500, 10.000) = 1040 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     25.283 ms/op
     p(99.9990) =     26.616 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.947 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.609 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.355 ±(99.9%) 0.009 ms/op
Iteration   1: 3.380 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.518 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  12.681 ms/op
                 existUser·p0.9999: 20.873 ms/op
                 existUser·p1.00:   21.594 ms/op

Iteration   2: 3.265 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.157 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   6.029 ms/op
                 existUser·p0.999:  11.338 ms/op
                 existUser·p0.9999: 21.535 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   3: 3.332 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.380 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  20.235 ms/op
                 existUser·p0.9999: 26.949 ms/op
                 existUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288441
  mean =      3.325 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11926 
    [ 2.500,  5.000) = 269897 
    [ 5.000,  7.500) = 5693 
    [ 7.500, 10.000) = 541 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 139 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     12.681 ms/op
     p(99.9900) =     25.526 ms/op
     p(99.9990) =     27.172 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.918 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.834 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.011 ms/op
Iteration   1: 3.463 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  19.925 ms/op
                 getUser·p0.9999: 23.847 ms/op
                 getUser·p1.00:   24.609 ms/op

Iteration   2: 3.295 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.319 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  10.453 ms/op
                 getUser·p0.9999: 24.773 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   3: 3.574 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.493 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.125 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.529 ms/op
                 getUser·p0.999:  19.594 ms/op
                 getUser·p0.9999: 26.642 ms/op
                 getUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279178
  mean =      3.440 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4420 
    [ 2.500,  5.000) = 267501 
    [ 5.000,  7.500) = 6284 
    [ 7.500, 10.000) = 618 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     19.774 ms/op
     p(99.9900) =     25.657 ms/op
     p(99.9990) =     27.375 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.906 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.619 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.013 ms/op
Iteration   1: 4.024 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.415 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.668 ms/op
                 listUser·p0.999:  20.042 ms/op
                 listUser·p0.9999: 29.442 ms/op
                 listUser·p1.00:   30.474 ms/op

Iteration   2: 4.024 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  15.583 ms/op
                 listUser·p0.9999: 18.973 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   3: 4.017 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.470 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  14.965 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238430
  mean =      4.022 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 227739 
    [ 5.000,  7.500) = 7819 
    [ 7.500, 10.000) = 1738 
    [10.000, 12.500) = 547 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.856 ms/op
     p(99.9000) =     15.860 ms/op
     p(99.9900) =     27.634 ms/op
     p(99.9990) =     30.058 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.261 ± 4.083  ops/ms
ClientPb.existUser                       thrpt       3   9.823 ± 3.605  ops/ms
ClientPb.getUser                         thrpt       3   9.405 ± 2.979  ops/ms
ClientPb.listUser                        thrpt       3   8.092 ± 2.354  ops/ms
ClientPb.createUser                       avgt       3   3.359 ± 0.669   ms/op
ClientPb.existUser                        avgt       3   3.259 ± 1.043   ms/op
ClientPb.getUser                          avgt       3   3.429 ± 0.735   ms/op
ClientPb.listUser                         avgt       3   3.908 ± 1.301   ms/op
ClientPb.createUser                     sample  274160   3.497 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.292           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.100           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.628           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.488           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.907           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.283           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.771           ms/op
ClientPb.existUser                      sample  288441   3.325 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.157           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.865           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.681           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.526           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.754           ms/op
ClientPb.getUser                        sample  279178   3.440 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.816           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.095           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.774           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.657           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.558           ms/op
ClientPb.listUser                       sample  238430   4.022 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.415           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.856           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.860           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.634           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.474           ms/op
