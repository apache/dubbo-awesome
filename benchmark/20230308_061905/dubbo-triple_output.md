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
# Warmup Iteration   1: 2.678 ops/ms
# Warmup Iteration   2: 6.431 ops/ms
# Warmup Iteration   3: 9.385 ops/ms
Iteration   1: 9.556 ops/ms
Iteration   2: 9.644 ops/ms
Iteration   3: 10.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.783 ±(99.9%) 5.832 ops/ms [Average]
  (min, avg, max) = (9.556, 9.783, 10.149), stdev = 0.320
  CI (99.9%): [3.950, 15.615] (assumes normal distribution)


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
# Warmup Iteration   1: 3.788 ops/ms
# Warmup Iteration   2: 9.595 ops/ms
# Warmup Iteration   3: 10.048 ops/ms
Iteration   1: 10.216 ops/ms
Iteration   2: 10.411 ops/ms
Iteration   3: 10.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.411 ±(99.9%) 3.561 ops/ms [Average]
  (min, avg, max) = (10.216, 10.411, 10.606), stdev = 0.195
  CI (99.9%): [6.850, 13.972] (assumes normal distribution)


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
# Warmup Iteration   1: 3.523 ops/ms
# Warmup Iteration   2: 9.193 ops/ms
# Warmup Iteration   3: 9.464 ops/ms
Iteration   1: 9.752 ops/ms
Iteration   2: 10.224 ops/ms
Iteration   3: 10.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.099 ±(99.9%) 5.570 ops/ms [Average]
  (min, avg, max) = (9.752, 10.099, 10.323), stdev = 0.305
  CI (99.9%): [4.529, 15.670] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.466 ops/ms
# Warmup Iteration   2: 7.448 ops/ms
# Warmup Iteration   3: 8.289 ops/ms
Iteration   1: 8.304 ops/ms
Iteration   2: 8.717 ops/ms
Iteration   3: 8.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.521 ±(99.9%) 3.783 ops/ms [Average]
  (min, avg, max) = (8.304, 8.521, 8.717), stdev = 0.207
  CI (99.9%): [4.737, 12.304] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.031 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.551 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.005 ms/op
Iteration   1: 3.174 ±(99.9%) 0.003 ms/op
Iteration   2: 3.140 ±(99.9%) 0.005 ms/op
Iteration   3: 3.101 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.138 ±(99.9%) 0.658 ms/op [Average]
  (min, avg, max) = (3.101, 3.138, 3.174), stdev = 0.036
  CI (99.9%): [2.480, 3.796] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.134 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.508 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.007 ms/op
Iteration   1: 3.215 ±(99.9%) 0.003 ms/op
Iteration   2: 2.983 ±(99.9%) 0.007 ms/op
Iteration   3: 3.066 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.088 ±(99.9%) 2.152 ms/op [Average]
  (min, avg, max) = (2.983, 3.088, 3.215), stdev = 0.118
  CI (99.9%): [0.937, 5.240] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.865 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.003 ms/op
Iteration   1: 3.249 ±(99.9%) 0.002 ms/op
Iteration   2: 3.292 ±(99.9%) 0.005 ms/op
Iteration   3: 3.195 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.245 ±(99.9%) 0.886 ms/op [Average]
  (min, avg, max) = (3.195, 3.245, 3.292), stdev = 0.049
  CI (99.9%): [2.359, 4.132] (assumes normal distribution)


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
# Warmup Iteration   1: 9.181 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.221 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.771 ±(99.9%) 0.006 ms/op
Iteration   1: 3.688 ±(99.9%) 0.009 ms/op
Iteration   2: 3.794 ±(99.9%) 0.007 ms/op
Iteration   3: 3.806 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.763 ±(99.9%) 1.183 ms/op [Average]
  (min, avg, max) = (3.688, 3.763, 3.806), stdev = 0.065
  CI (99.9%): [2.580, 4.945] (assumes normal distribution)


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
# Warmup Iteration   1: 7.938 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.010 ms/op
Iteration   1: 3.150 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.685 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  19.857 ms/op
                 createUser·p0.9999: 21.971 ms/op
                 createUser·p1.00:   22.774 ms/op

Iteration   2: 3.292 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.274 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  15.630 ms/op
                 createUser·p0.9999: 21.842 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   3: 3.227 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.380 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  16.187 ms/op
                 createUser·p0.9999: 21.004 ms/op
                 createUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297798
  mean =      3.222 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20209 
    [ 2.500,  5.000) = 271550 
    [ 5.000,  7.500) = 5030 
    [ 7.500, 10.000) = 497 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 171 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.274 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     21.798 ms/op
     p(99.9990) =     23.889 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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
# Warmup Iteration   1: 6.769 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.401 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.007 ms/op
Iteration   1: 3.074 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.366 ms/op
                 existUser·p0.50:   2.976 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   5.502 ms/op
                 existUser·p0.999:  12.403 ms/op
                 existUser·p0.9999: 22.315 ms/op
                 existUser·p1.00:   23.658 ms/op

Iteration   2: 3.121 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.590 ms/op
                 existUser·p0.999:  14.700 ms/op
                 existUser·p0.9999: 21.569 ms/op
                 existUser·p1.00:   22.249 ms/op

Iteration   3: 3.018 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.516 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  11.321 ms/op
                 existUser·p0.9999: 20.977 ms/op
                 existUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312721
  mean =      3.070 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7688 
    [ 2.500,  5.000) = 299834 
    [ 5.000,  7.500) = 4437 
    [ 7.500, 10.000) = 360 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     13.764 ms/op
     p(99.9900) =     21.675 ms/op
     p(99.9990) =     23.613 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 7.751 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.009 ms/op
Iteration   1: 3.235 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  19.054 ms/op
                 getUser·p0.9999: 25.530 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   5.317 ms/op
                 getUser·p0.999:  9.298 ms/op
                 getUser·p0.9999: 24.904 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   3: 3.331 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  16.614 ms/op
                 getUser·p0.9999: 25.376 ms/op
                 getUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295297
  mean =      3.249 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14253 
    [ 2.500,  5.000) = 273454 
    [ 5.000,  7.500) = 6601 
    [ 7.500, 10.000) = 531 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     18.111 ms/op
     p(99.9900) =     25.214 ms/op
     p(99.9990) =     25.859 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.851 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.179 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.012 ms/op
Iteration   1: 3.791 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  13.943 ms/op
                 listUser·p0.9999: 27.922 ms/op
                 listUser·p1.00:   28.377 ms/op

Iteration   2: 3.684 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.931 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.267 ms/op
                 listUser·p0.999:  12.998 ms/op
                 listUser·p0.9999: 15.925 ms/op
                 listUser·p1.00:   15.925 ms/op

Iteration   3: 3.829 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   5.127 ms/op
                 listUser·p0.99:   7.774 ms/op
                 listUser·p0.999:  13.025 ms/op
                 listUser·p0.9999: 16.908 ms/op
                 listUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254892
  mean =      3.767 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 245250 
    [ 5.000,  7.500) = 7279 
    [ 7.500, 10.000) = 1618 
    [10.000, 12.500) = 290 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     13.584 ms/op
     p(99.9900) =     25.920 ms/op
     p(99.9990) =     28.240 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.783 ± 5.832  ops/ms
ClientPb.existUser                       thrpt       3  10.411 ± 3.561  ops/ms
ClientPb.getUser                         thrpt       3  10.099 ± 5.570  ops/ms
ClientPb.listUser                        thrpt       3   8.521 ± 3.783  ops/ms
ClientPb.createUser                       avgt       3   3.138 ± 0.658   ms/op
ClientPb.existUser                        avgt       3   3.088 ± 2.152   ms/op
ClientPb.getUser                          avgt       3   3.245 ± 0.886   ms/op
ClientPb.listUser                         avgt       3   3.763 ± 1.183   ms/op
ClientPb.createUser                     sample  297798   3.222 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.274           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.609           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.236           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.798           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.921           ms/op
ClientPb.existUser                      sample  312721   3.070 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.102           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.415           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.764           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.675           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.838           ms/op
ClientPb.getUser                        sample  295297   3.249 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.997           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.666           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.775           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.111           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.214           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.018           ms/op
ClientPb.listUser                       sample  254892   3.767 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.878           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.604           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.348           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.584           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.920           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.377           ms/op
