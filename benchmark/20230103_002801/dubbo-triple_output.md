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
# Warmup Iteration   1: 2.698 ops/ms
# Warmup Iteration   2: 6.595 ops/ms
# Warmup Iteration   3: 9.152 ops/ms
Iteration   1: 10.207 ops/ms
Iteration   2: 9.984 ops/ms
Iteration   3: 9.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.000 ±(99.9%) 3.632 ops/ms [Average]
  (min, avg, max) = (9.810, 10.000, 10.207), stdev = 0.199
  CI (99.9%): [6.368, 13.633] (assumes normal distribution)


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
# Warmup Iteration   1: 3.935 ops/ms
# Warmup Iteration   2: 9.523 ops/ms
# Warmup Iteration   3: 10.541 ops/ms
Iteration   1: 10.686 ops/ms
Iteration   2: 10.262 ops/ms
Iteration   3: 10.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.617 ±(99.9%) 5.944 ops/ms [Average]
  (min, avg, max) = (10.262, 10.617, 10.903), stdev = 0.326
  CI (99.9%): [4.673, 16.561] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.486 ops/ms
# Warmup Iteration   2: 9.150 ops/ms
# Warmup Iteration   3: 10.171 ops/ms
Iteration   1: 9.665 ops/ms
Iteration   2: 9.969 ops/ms
Iteration   3: 10.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.963 ±(99.9%) 5.392 ops/ms [Average]
  (min, avg, max) = (9.665, 9.963, 10.256), stdev = 0.296
  CI (99.9%): [4.571, 15.355] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.636 ops/ms
# Warmup Iteration   2: 7.604 ops/ms
# Warmup Iteration   3: 8.490 ops/ms
Iteration   1: 8.643 ops/ms
Iteration   2: 8.765 ops/ms
Iteration   3: 8.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.712 ±(99.9%) 1.144 ops/ms [Average]
  (min, avg, max) = (8.643, 8.712, 8.765), stdev = 0.063
  CI (99.9%): [7.568, 9.855] (assumes normal distribution)


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
# Warmup Iteration   1: 8.050 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.374 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.004 ms/op
Iteration   1: 3.133 ±(99.9%) 0.003 ms/op
Iteration   2: 3.081 ±(99.9%) 0.002 ms/op
Iteration   3: 3.065 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.093 ±(99.9%) 0.651 ms/op [Average]
  (min, avg, max) = (3.065, 3.093, 3.133), stdev = 0.036
  CI (99.9%): [2.442, 3.744] (assumes normal distribution)


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
# Warmup Iteration   1: 6.462 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.002 ms/op
Iteration   1: 2.925 ±(99.9%) 0.005 ms/op
Iteration   2: 3.186 ±(99.9%) 0.004 ms/op
Iteration   3: 3.153 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.088 ±(99.9%) 2.591 ms/op [Average]
  (min, avg, max) = (2.925, 3.088, 3.186), stdev = 0.142
  CI (99.9%): [0.497, 5.679] (assumes normal distribution)


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
# Warmup Iteration   1: 7.225 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.004 ms/op
Iteration   1: 3.103 ±(99.9%) 0.001 ms/op
Iteration   2: 3.122 ±(99.9%) 0.003 ms/op
Iteration   3: 3.222 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.149 ±(99.9%) 1.167 ms/op [Average]
  (min, avg, max) = (3.103, 3.149, 3.222), stdev = 0.064
  CI (99.9%): [1.982, 4.316] (assumes normal distribution)


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
# Warmup Iteration   1: 8.739 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.742 ±(99.9%) 0.006 ms/op
Iteration   1: 3.715 ±(99.9%) 0.008 ms/op
Iteration   2: 3.667 ±(99.9%) 0.004 ms/op
Iteration   3: 3.650 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.677 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (3.650, 3.677, 3.715), stdev = 0.034
  CI (99.9%): [3.060, 4.294] (assumes normal distribution)


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
# Warmup Iteration   1: 7.207 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.009 ms/op
Iteration   1: 3.223 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  9.121 ms/op
                 createUser·p0.9999: 23.200 ms/op
                 createUser·p1.00:   23.265 ms/op

Iteration   2: 3.254 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  17.916 ms/op
                 createUser·p0.9999: 21.960 ms/op
                 createUser·p1.00:   22.807 ms/op

Iteration   3: 3.203 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  14.519 ms/op
                 createUser·p0.9999: 18.744 ms/op
                 createUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297422
  mean =      3.226 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16876 
    [ 2.500,  5.000) = 274281 
    [ 5.000,  7.500) = 5434 
    [ 7.500, 10.000) = 409 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     15.823 ms/op
     p(99.9900) =     22.815 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 6.893 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
Iteration   1: 3.020 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.376 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.187 ms/op
                 existUser·p0.95:   3.351 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  9.191 ms/op
                 existUser·p0.9999: 22.735 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   2: 2.995 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.404 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  8.801 ms/op
                 existUser·p0.9999: 22.315 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.565 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  9.345 ms/op
                 existUser·p0.9999: 19.038 ms/op
                 existUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 319385
  mean =      3.004 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19780 
    [ 2.500,  5.000) = 294492 
    [ 5.000,  7.500) = 4633 
    [ 7.500, 10.000) = 191 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.215 ms/op
     p(95.0000) =      3.441 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     22.155 ms/op
     p(99.9990) =     23.056 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 7.231 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.382 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.009 ms/op
Iteration   1: 3.185 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.483 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   6.857 ms/op
                 getUser·p0.999:  16.608 ms/op
                 getUser·p0.9999: 19.037 ms/op
                 getUser·p1.00:   19.956 ms/op

Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.374 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.555 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  10.129 ms/op
                 getUser·p0.9999: 21.888 ms/op
                 getUser·p1.00:   22.774 ms/op

Iteration   3: 3.249 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   5.997 ms/op
                 getUser·p0.999:  11.184 ms/op
                 getUser·p0.9999: 24.357 ms/op
                 getUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302112
  mean =      3.175 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10773 
    [ 2.500,  5.000) = 282582 
    [ 5.000,  7.500) = 7671 
    [ 7.500, 10.000) = 667 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     16.225 ms/op
     p(99.9900) =     22.472 ms/op
     p(99.9990) =     24.837 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 8.150 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.788 ±(99.9%) 0.012 ms/op
Iteration   1: 3.720 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  13.713 ms/op
                 listUser·p0.9999: 19.431 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   2: 3.580 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.494 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   3.990 ms/op
                 listUser·p0.99:   6.103 ms/op
                 listUser·p0.999:  12.550 ms/op
                 listUser·p0.9999: 14.483 ms/op
                 listUser·p1.00:   16.777 ms/op

Iteration   3: 3.718 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  13.579 ms/op
                 listUser·p0.9999: 20.964 ms/op
                 listUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 261533
  mean =      3.672 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 254612 
    [ 5.000,  7.500) = 5280 
    [ 7.500, 10.000) = 935 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 251 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     12.960 ms/op
     p(99.9900) =     19.263 ms/op
     p(99.9990) =     21.140 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.000 ± 3.632  ops/ms
ClientPb.existUser                       thrpt       3  10.617 ± 5.944  ops/ms
ClientPb.getUser                         thrpt       3   9.963 ± 5.392  ops/ms
ClientPb.listUser                        thrpt       3   8.712 ± 1.144  ops/ms
ClientPb.createUser                       avgt       3   3.093 ± 0.651   ms/op
ClientPb.existUser                        avgt       3   3.088 ± 2.591   ms/op
ClientPb.getUser                          avgt       3   3.149 ± 1.167   ms/op
ClientPb.listUser                         avgt       3   3.677 ± 0.617   ms/op
ClientPb.createUser                     sample  297422   3.226 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.973           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.100           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.823           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.815           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.265           ms/op
ClientPb.existUser                      sample  319385   3.004 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.260           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.441           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.284           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.175           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.155           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.233           ms/op
ClientPb.getUser                        sample  302112   3.175 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.184           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.523           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.373           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.225           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.472           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.904           ms/op
ClientPb.listUser                       sample  261533   3.672 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.325           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.617           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.627           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.960           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.263           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.365           ms/op
