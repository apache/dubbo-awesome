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
# Warmup Iteration   1: 2.486 ops/ms
# Warmup Iteration   2: 6.018 ops/ms
# Warmup Iteration   3: 8.975 ops/ms
Iteration   1: 9.479 ops/ms
Iteration   2: 10.054 ops/ms
Iteration   3: 9.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.829 ±(99.9%) 5.606 ops/ms [Average]
  (min, avg, max) = (9.479, 9.829, 10.054), stdev = 0.307
  CI (99.9%): [4.223, 15.436] (assumes normal distribution)


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
# Warmup Iteration   1: 3.606 ops/ms
# Warmup Iteration   2: 9.305 ops/ms
# Warmup Iteration   3: 10.632 ops/ms
Iteration   1: 10.446 ops/ms
Iteration   2: 10.355 ops/ms
Iteration   3: 10.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.382 ±(99.9%) 1.014 ops/ms [Average]
  (min, avg, max) = (10.346, 10.382, 10.446), stdev = 0.056
  CI (99.9%): [9.369, 11.396] (assumes normal distribution)


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
# Warmup Iteration   1: 3.476 ops/ms
# Warmup Iteration   2: 9.044 ops/ms
# Warmup Iteration   3: 9.273 ops/ms
Iteration   1: 9.978 ops/ms
Iteration   2: 9.950 ops/ms
Iteration   3: 10.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.061 ±(99.9%) 3.079 ops/ms [Average]
  (min, avg, max) = (9.950, 10.061, 10.256), stdev = 0.169
  CI (99.9%): [6.982, 13.141] (assumes normal distribution)


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
# Warmup Iteration   1: 3.698 ops/ms
# Warmup Iteration   2: 7.833 ops/ms
# Warmup Iteration   3: 8.088 ops/ms
Iteration   1: 8.593 ops/ms
Iteration   2: 8.575 ops/ms
Iteration   3: 8.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.513 ±(99.9%) 2.253 ops/ms [Average]
  (min, avg, max) = (8.371, 8.513, 8.593), stdev = 0.124
  CI (99.9%): [6.260, 10.766] (assumes normal distribution)


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
# Warmup Iteration   1: 8.574 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.413 ±(99.9%) 0.007 ms/op
Iteration   1: 3.353 ±(99.9%) 0.006 ms/op
Iteration   2: 3.182 ±(99.9%) 0.006 ms/op
Iteration   3: 3.210 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.248 ±(99.9%) 1.668 ms/op [Average]
  (min, avg, max) = (3.182, 3.248, 3.353), stdev = 0.091
  CI (99.9%): [1.580, 4.917] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.975 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.350 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.007 ms/op
Iteration   1: 3.005 ±(99.9%) 0.005 ms/op
Iteration   2: 3.239 ±(99.9%) 0.005 ms/op
Iteration   3: 3.132 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.125 ±(99.9%) 2.139 ms/op [Average]
  (min, avg, max) = (3.005, 3.125, 3.239), stdev = 0.117
  CI (99.9%): [0.987, 5.264] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.223 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.373 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.004 ms/op
Iteration   1: 3.361 ±(99.9%) 0.006 ms/op
Iteration   2: 3.244 ±(99.9%) 0.004 ms/op
Iteration   3: 3.189 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.265 ±(99.9%) 1.608 ms/op [Average]
  (min, avg, max) = (3.189, 3.265, 3.361), stdev = 0.088
  CI (99.9%): [1.657, 4.873] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.805 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.294 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.781 ±(99.9%) 0.005 ms/op
Iteration   1: 3.716 ±(99.9%) 0.008 ms/op
Iteration   2: 3.728 ±(99.9%) 0.007 ms/op
Iteration   3: 3.697 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.714 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (3.697, 3.714, 3.728), stdev = 0.016
  CI (99.9%): [3.425, 4.002] (assumes normal distribution)


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
# Warmup Iteration   1: 8.119 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.008 ms/op
Iteration   1: 3.186 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.597 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  14.964 ms/op
                 createUser·p0.9999: 26.013 ms/op
                 createUser·p1.00:   26.673 ms/op

Iteration   2: 3.171 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.292 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.445 ms/op
                 createUser·p0.99:   5.022 ms/op
                 createUser·p0.999:  19.504 ms/op
                 createUser·p0.9999: 21.955 ms/op
                 createUser·p1.00:   22.118 ms/op

Iteration   3: 3.229 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.511 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  15.270 ms/op
                 createUser·p0.9999: 22.450 ms/op
                 createUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300145
  mean =      3.195 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17620 
    [ 2.500,  5.000) = 277325 
    [ 5.000,  7.500) = 4186 
    [ 7.500, 10.000) = 481 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     15.375 ms/op
     p(99.9900) =     25.231 ms/op
     p(99.9990) =     26.509 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.976 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.006 ms/op
Iteration   1: 3.095 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  9.765 ms/op
                 existUser·p0.9999: 19.792 ms/op
                 existUser·p1.00:   20.939 ms/op

Iteration   2: 3.044 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  13.069 ms/op
                 existUser·p0.9999: 20.004 ms/op
                 existUser·p1.00:   20.840 ms/op

Iteration   3: 3.089 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.444 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.330 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  9.372 ms/op
                 existUser·p0.9999: 16.839 ms/op
                 existUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311965
  mean =      3.076 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17888 
    [ 2.500,  5.000) = 289154 
    [ 5.000,  7.500) = 4141 
    [ 7.500, 10.000) = 419 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 165 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.494 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     12.763 ms/op
     p(99.9900) =     19.687 ms/op
     p(99.9990) =     20.829 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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
# Warmup Iteration   1: 8.928 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.499 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.011 ms/op
Iteration   1: 3.280 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  9.507 ms/op
                 getUser·p0.9999: 20.815 ms/op
                 getUser·p1.00:   22.675 ms/op

Iteration   2: 3.244 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  14.402 ms/op
                 getUser·p0.9999: 22.188 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   3: 3.261 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  8.467 ms/op
                 getUser·p0.9999: 25.461 ms/op
                 getUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294338
  mean =      3.262 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20315 
    [ 2.500,  5.000) = 265037 
    [ 5.000,  7.500) = 8249 
    [ 7.500, 10.000) = 393 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     13.718 ms/op
     p(99.9900) =     24.216 ms/op
     p(99.9990) =     25.660 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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
# Warmup Iteration   1: 8.835 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.727 ±(99.9%) 0.011 ms/op
Iteration   1: 3.806 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 25.757 ms/op
                 listUser·p1.00:   26.706 ms/op

Iteration   2: 3.803 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.617 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  15.221 ms/op
                 listUser·p0.9999: 17.288 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   3: 3.619 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.058 ms/op
                 listUser·p0.50:   3.518 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.129 ms/op
                 listUser·p0.99:   5.833 ms/op
                 listUser·p0.999:  14.172 ms/op
                 listUser·p0.9999: 20.644 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256546
  mean =      3.741 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 248356 
    [ 5.000,  7.500) = 6354 
    [ 7.500, 10.000) = 1189 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 264 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     14.671 ms/op
     p(99.9900) =     23.911 ms/op
     p(99.9990) =     26.206 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.829 ± 5.606  ops/ms
ClientPb.existUser                       thrpt       3  10.382 ± 1.014  ops/ms
ClientPb.getUser                         thrpt       3  10.061 ± 3.079  ops/ms
ClientPb.listUser                        thrpt       3   8.513 ± 2.253  ops/ms
ClientPb.createUser                       avgt       3   3.248 ± 1.668   ms/op
ClientPb.existUser                        avgt       3   3.125 ± 2.139   ms/op
ClientPb.getUser                          avgt       3   3.265 ± 1.608   ms/op
ClientPb.listUser                         avgt       3   3.714 ± 0.288   ms/op
ClientPb.createUser                     sample  300145   3.195 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.292           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.494           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.375           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.231           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.673           ms/op
ClientPb.existUser                      sample  311965   3.076 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.887           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.494           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.267           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.763           ms/op
ClientPb.existUser:existUser·p0.9999    sample          19.687           ms/op
ClientPb.existUser:existUser·p1.00      sample          20.939           ms/op
ClientPb.getUser                        sample  294338   3.262 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.155           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.695           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.718           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.216           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.066           ms/op
ClientPb.listUser                       sample  256546   3.741 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.617           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.898           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.671           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.911           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.706           ms/op
