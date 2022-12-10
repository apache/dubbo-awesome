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
# Warmup Iteration   1: 2.435 ops/ms
# Warmup Iteration   2: 5.773 ops/ms
# Warmup Iteration   3: 9.688 ops/ms
Iteration   1: 9.793 ops/ms
Iteration   2: 10.124 ops/ms
Iteration   3: 10.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.004 ±(99.9%) 3.344 ops/ms [Average]
  (min, avg, max) = (9.793, 10.004, 10.124), stdev = 0.183
  CI (99.9%): [6.660, 13.348] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.677 ops/ms
# Warmup Iteration   2: 9.522 ops/ms
# Warmup Iteration   3: 10.416 ops/ms
Iteration   1: 10.730 ops/ms
Iteration   2: 10.699 ops/ms
Iteration   3: 10.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.571 ±(99.9%) 4.546 ops/ms [Average]
  (min, avg, max) = (10.284, 10.571, 10.730), stdev = 0.249
  CI (99.9%): [6.025, 15.117] (assumes normal distribution)


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
# Warmup Iteration   1: 3.463 ops/ms
# Warmup Iteration   2: 8.974 ops/ms
# Warmup Iteration   3: 9.807 ops/ms
Iteration   1: 10.111 ops/ms
Iteration   2: 9.791 ops/ms
Iteration   3: 10.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.997 ±(99.9%) 3.249 ops/ms [Average]
  (min, avg, max) = (9.791, 9.997, 10.111), stdev = 0.178
  CI (99.9%): [6.748, 13.246] (assumes normal distribution)


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
# Warmup Iteration   1: 3.492 ops/ms
# Warmup Iteration   2: 7.809 ops/ms
# Warmup Iteration   3: 8.392 ops/ms
Iteration   1: 8.667 ops/ms
Iteration   2: 8.523 ops/ms
Iteration   3: 8.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.559 ±(99.9%) 1.743 ops/ms [Average]
  (min, avg, max) = (8.487, 8.559, 8.667), stdev = 0.096
  CI (99.9%): [6.816, 10.302] (assumes normal distribution)


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
# Warmup Iteration   1: 9.320 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.003 ms/op
Iteration   1: 3.154 ±(99.9%) 0.006 ms/op
Iteration   2: 3.115 ±(99.9%) 0.005 ms/op
Iteration   3: 3.065 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.111 ±(99.9%) 0.819 ms/op [Average]
  (min, avg, max) = (3.065, 3.111, 3.154), stdev = 0.045
  CI (99.9%): [2.293, 3.930] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.212 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.364 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.003 ms/op
Iteration   1: 2.994 ±(99.9%) 0.005 ms/op
Iteration   2: 3.047 ±(99.9%) 0.008 ms/op
Iteration   3: 3.105 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.049 ±(99.9%) 1.017 ms/op [Average]
  (min, avg, max) = (2.994, 3.049, 3.105), stdev = 0.056
  CI (99.9%): [2.031, 4.066] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.397 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.669 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.003 ms/op
Iteration   1: 3.143 ±(99.9%) 0.003 ms/op
Iteration   2: 3.131 ±(99.9%) 0.003 ms/op
Iteration   3: 3.097 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.124 ±(99.9%) 0.437 ms/op [Average]
  (min, avg, max) = (3.097, 3.124, 3.143), stdev = 0.024
  CI (99.9%): [2.686, 3.561] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.015 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.755 ±(99.9%) 0.005 ms/op
Iteration   1: 3.791 ±(99.9%) 0.008 ms/op
Iteration   2: 3.708 ±(99.9%) 0.007 ms/op
Iteration   3: 3.672 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.724 ±(99.9%) 1.110 ms/op [Average]
  (min, avg, max) = (3.672, 3.724, 3.791), stdev = 0.061
  CI (99.9%): [2.614, 4.833] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.321 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.830 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.009 ms/op
Iteration   1: 3.104 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.487 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  19.263 ms/op
                 createUser·p0.9999: 21.488 ms/op
                 createUser·p1.00:   22.184 ms/op

Iteration   2: 3.056 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.199 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  8.217 ms/op
                 createUser·p0.9999: 24.299 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   3: 3.130 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   5.207 ms/op
                 createUser·p0.999:  13.206 ms/op
                 createUser·p0.9999: 17.596 ms/op
                 createUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 309800
  mean =      3.096 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23511 
    [ 2.500,  5.000) = 282469 
    [ 5.000,  7.500) = 3095 
    [ 7.500, 10.000) = 333 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      5.235 ms/op
     p(99.9000) =     13.976 ms/op
     p(99.9900) =     23.692 ms/op
     p(99.9990) =     24.442 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.480 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.190 ±(99.9%) 0.009 ms/op
Iteration   1: 3.111 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.685 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  8.471 ms/op
                 existUser·p0.9999: 20.012 ms/op
                 existUser·p1.00:   20.677 ms/op

Iteration   2: 3.092 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  9.355 ms/op
                 existUser·p0.9999: 21.922 ms/op
                 existUser·p1.00:   22.807 ms/op

Iteration   3: 3.078 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.518 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.310 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  8.820 ms/op
                 existUser·p0.9999: 20.883 ms/op
                 existUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309937
  mean =      3.093 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22139 
    [ 2.500,  5.000) = 283601 
    [ 5.000,  7.500) = 3526 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     21.168 ms/op
     p(99.9990) =     22.345 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 7.433 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.183 ±(99.9%) 0.008 ms/op
Iteration   1: 3.188 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  13.381 ms/op
                 getUser·p0.9999: 27.356 ms/op
                 getUser·p1.00:   28.443 ms/op

Iteration   2: 3.227 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.346 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   5.577 ms/op
                 getUser·p0.999:  10.924 ms/op
                 getUser·p0.9999: 25.919 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   3: 3.284 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.744 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  13.500 ms/op
                 getUser·p0.9999: 20.432 ms/op
                 getUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296746
  mean =      3.233 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11578 
    [ 2.500,  5.000) = 278035 
    [ 5.000,  7.500) = 6061 
    [ 7.500, 10.000) = 649 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 69 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     13.455 ms/op
     p(99.9900) =     26.028 ms/op
     p(99.9990) =     28.443 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 8.469 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.088 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.012 ms/op
Iteration   1: 3.719 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.642 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  15.385 ms/op
                 listUser·p0.9999: 21.941 ms/op
                 listUser·p1.00:   24.936 ms/op

Iteration   2: 3.716 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.962 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  12.403 ms/op
                 listUser·p0.9999: 16.440 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   3: 3.822 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.942 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.602 ms/op
                 listUser·p0.999:  14.238 ms/op
                 listUser·p0.9999: 19.059 ms/op
                 listUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255702
  mean =      3.752 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 247772 
    [ 5.000,  7.500) = 5858 
    [ 7.500, 10.000) = 1252 
    [10.000, 12.500) = 292 
    [12.500, 15.000) = 278 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.642 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     14.128 ms/op
     p(99.9900) =     20.873 ms/op
     p(99.9990) =     24.885 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.004 ± 3.344  ops/ms
ClientPb.existUser                       thrpt       3  10.571 ± 4.546  ops/ms
ClientPb.getUser                         thrpt       3   9.997 ± 3.249  ops/ms
ClientPb.listUser                        thrpt       3   8.559 ± 1.743  ops/ms
ClientPb.createUser                       avgt       3   3.111 ± 0.819   ms/op
ClientPb.existUser                        avgt       3   3.049 ± 1.017   ms/op
ClientPb.getUser                          avgt       3   3.124 ± 0.437   ms/op
ClientPb.listUser                         avgt       3   3.724 ± 1.110   ms/op
ClientPb.createUser                     sample  309800   3.096 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.945           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.600           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.235           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.976           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.692           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.576           ms/op
ClientPb.existUser                      sample  309937   3.093 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.685           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.355           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.317           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.273           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.168           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.807           ms/op
ClientPb.getUser                        sample  296746   3.233 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.744           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.572           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.931           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.455           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.028           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.443           ms/op
ClientPb.listUser                       sample  255702   3.752 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.642           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.625           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.086           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.128           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.873           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.936           ms/op
