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
# Warmup Iteration   1: 2.668 ops/ms
# Warmup Iteration   2: 6.487 ops/ms
# Warmup Iteration   3: 9.331 ops/ms
Iteration   1: 9.876 ops/ms
Iteration   2: 9.872 ops/ms
Iteration   3: 9.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.865 ±(99.9%) 0.272 ops/ms [Average]
  (min, avg, max) = (9.848, 9.865, 9.876), stdev = 0.015
  CI (99.9%): [9.593, 10.137] (assumes normal distribution)


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
# Warmup Iteration   1: 3.780 ops/ms
# Warmup Iteration   2: 9.240 ops/ms
# Warmup Iteration   3: 10.443 ops/ms
Iteration   1: 10.266 ops/ms
Iteration   2: 10.362 ops/ms
Iteration   3: 10.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.244 ±(99.9%) 2.393 ops/ms [Average]
  (min, avg, max) = (10.103, 10.244, 10.362), stdev = 0.131
  CI (99.9%): [7.851, 12.636] (assumes normal distribution)


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
# Warmup Iteration   1: 3.673 ops/ms
# Warmup Iteration   2: 9.513 ops/ms
# Warmup Iteration   3: 9.952 ops/ms
Iteration   1: 10.316 ops/ms
Iteration   2: 10.265 ops/ms
Iteration   3: 10.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.235 ±(99.9%) 1.815 ops/ms [Average]
  (min, avg, max) = (10.124, 10.235, 10.316), stdev = 0.099
  CI (99.9%): [8.421, 12.050] (assumes normal distribution)


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
# Warmup Iteration   1: 3.360 ops/ms
# Warmup Iteration   2: 7.427 ops/ms
# Warmup Iteration   3: 8.138 ops/ms
Iteration   1: 8.801 ops/ms
Iteration   2: 8.550 ops/ms
Iteration   3: 8.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.673 ±(99.9%) 2.295 ops/ms [Average]
  (min, avg, max) = (8.550, 8.673, 8.801), stdev = 0.126
  CI (99.9%): [6.377, 10.968] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.147 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.004 ms/op
Iteration   1: 3.223 ±(99.9%) 0.001 ms/op
Iteration   2: 3.120 ±(99.9%) 0.005 ms/op
Iteration   3: 3.085 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.142 ±(99.9%) 1.310 ms/op [Average]
  (min, avg, max) = (3.085, 3.142, 3.223), stdev = 0.072
  CI (99.9%): [1.833, 4.452] (assumes normal distribution)


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
# Warmup Iteration   1: 7.181 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.367 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.002 ms/op
Iteration   1: 3.115 ±(99.9%) 0.003 ms/op
Iteration   2: 3.167 ±(99.9%) 0.006 ms/op
Iteration   3: 2.932 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.071 ±(99.9%) 2.252 ms/op [Average]
  (min, avg, max) = (2.932, 3.071, 3.167), stdev = 0.123
  CI (99.9%): [0.820, 5.323] (assumes normal distribution)


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
# Warmup Iteration   1: 7.957 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.004 ms/op
Iteration   1: 3.191 ±(99.9%) 0.006 ms/op
Iteration   2: 3.206 ±(99.9%) 0.004 ms/op
Iteration   3: 3.107 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.168 ±(99.9%) 0.976 ms/op [Average]
  (min, avg, max) = (3.107, 3.168, 3.206), stdev = 0.054
  CI (99.9%): [2.192, 4.144] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.392 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.007 ms/op
Iteration   1: 3.692 ±(99.9%) 0.009 ms/op
Iteration   2: 3.792 ±(99.9%) 0.009 ms/op
Iteration   3: 3.727 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.737 ±(99.9%) 0.926 ms/op [Average]
  (min, avg, max) = (3.692, 3.737, 3.792), stdev = 0.051
  CI (99.9%): [2.810, 4.663] (assumes normal distribution)


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
# Warmup Iteration   1: 8.043 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.693 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.008 ms/op
Iteration   1: 3.202 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  18.022 ms/op
                 createUser·p0.9999: 22.545 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   2: 3.050 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.318 ms/op
                 createUser·p0.95:   3.535 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  9.180 ms/op
                 createUser·p0.9999: 25.117 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   3: 3.125 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  9.732 ms/op
                 createUser·p0.9999: 22.987 ms/op
                 createUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 307146
  mean =      3.124 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10220 
    [ 2.500,  5.000) = 292815 
    [ 5.000,  7.500) = 3358 
    [ 7.500, 10.000) = 407 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =     14.598 ms/op
     p(99.9900) =     24.159 ms/op
     p(99.9990) =     25.882 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 7.159 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.334 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.009 ms/op
Iteration   1: 3.127 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  13.332 ms/op
                 existUser·p0.9999: 19.621 ms/op
                 existUser·p1.00:   20.251 ms/op

Iteration   2: 3.150 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  8.864 ms/op
                 existUser·p0.9999: 26.696 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   3: 3.015 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.262 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  8.847 ms/op
                 existUser·p0.9999: 23.061 ms/op
                 existUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309841
  mean =      3.096 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19203 
    [ 2.500,  5.000) = 286423 
    [ 5.000,  7.500) = 3608 
    [ 7.500, 10.000) = 287 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     12.604 ms/op
     p(99.9900) =     25.724 ms/op
     p(99.9990) =     26.932 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 7.967 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.010 ms/op
Iteration   1: 3.203 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.448 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  17.072 ms/op
                 getUser·p0.9999: 20.088 ms/op
                 getUser·p1.00:   22.544 ms/op

Iteration   2: 3.245 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  8.792 ms/op
                 getUser·p0.9999: 26.083 ms/op
                 getUser·p1.00:   26.542 ms/op

Iteration   3: 3.152 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.427 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.210 ms/op
                 getUser·p0.999:  10.381 ms/op
                 getUser·p0.9999: 22.381 ms/op
                 getUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299910
  mean =      3.200 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26273 
    [ 2.500,  5.000) = 267116 
    [ 5.000,  7.500) = 5846 
    [ 7.500, 10.000) = 297 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     15.519 ms/op
     p(99.9900) =     25.560 ms/op
     p(99.9990) =     26.509 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 8.650 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.163 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.774 ±(99.9%) 0.011 ms/op
Iteration   1: 3.840 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  14.692 ms/op
                 listUser·p0.9999: 25.450 ms/op
                 listUser·p1.00:   26.575 ms/op

Iteration   2: 3.639 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.620 ms/op
                 listUser·p0.50:   3.527 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.112 ms/op
                 listUser·p0.99:   6.575 ms/op
                 listUser·p0.999:  13.502 ms/op
                 listUser·p0.9999: 14.696 ms/op
                 listUser·p1.00:   15.172 ms/op

Iteration   3: 3.624 ±(99.9%) 0.006 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   3.744 ms/op
                 listUser·p0.95:   3.903 ms/op
                 listUser·p0.99:   5.186 ms/op
                 listUser·p0.999:  12.698 ms/op
                 listUser·p0.9999: 13.926 ms/op
                 listUser·p1.00:   13.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259376
  mean =      3.698 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74 
    [ 2.500,  5.000) = 252347 
    [ 5.000,  7.500) = 5208 
    [ 7.500, 10.000) = 1100 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 320 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.614 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     24.685 ms/op
     p(99.9990) =     25.769 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.865 ± 0.272  ops/ms
ClientPb.existUser                       thrpt       3  10.244 ± 2.393  ops/ms
ClientPb.getUser                         thrpt       3  10.235 ± 1.815  ops/ms
ClientPb.listUser                        thrpt       3   8.673 ± 2.295  ops/ms
ClientPb.createUser                       avgt       3   3.142 ± 1.310   ms/op
ClientPb.existUser                        avgt       3   3.071 ± 2.252   ms/op
ClientPb.getUser                          avgt       3   3.168 ± 0.976   ms/op
ClientPb.listUser                         avgt       3   3.737 ± 0.926   ms/op
ClientPb.createUser                     sample  307146   3.124 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.974           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.998           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.498           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.276           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.598           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.159           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.149           ms/op
ClientPb.existUser                      sample  309841   3.096 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.937           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.334           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.292           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.604           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.724           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.968           ms/op
ClientPb.getUser                        sample  299910   3.200 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.118           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.613           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.051           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.546           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.519           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.560           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.542           ms/op
ClientPb.listUser                       sample  259376   3.698 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.614           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.617           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.182           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.898           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.337           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.685           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.575           ms/op
