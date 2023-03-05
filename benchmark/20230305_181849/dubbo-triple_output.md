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
# Warmup Iteration   1: 1.232 ops/ms
# Warmup Iteration   2: 2.721 ops/ms
# Warmup Iteration   3: 5.467 ops/ms
Iteration   1: 5.605 ops/ms
Iteration   2: 5.989 ops/ms
Iteration   3: 6.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.873 ±(99.9%) 4.237 ops/ms [Average]
  (min, avg, max) = (5.605, 5.873, 6.024), stdev = 0.232
  CI (99.9%): [1.636, 10.109] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.662 ops/ms
# Warmup Iteration   2: 4.771 ops/ms
# Warmup Iteration   3: 6.230 ops/ms
Iteration   1: 6.285 ops/ms
Iteration   2: 6.414 ops/ms
Iteration   3: 6.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.310 ±(99.9%) 1.709 ops/ms [Average]
  (min, avg, max) = (6.232, 6.310, 6.414), stdev = 0.094
  CI (99.9%): [4.602, 8.019] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.731 ops/ms
# Warmup Iteration   2: 5.196 ops/ms
# Warmup Iteration   3: 5.782 ops/ms
Iteration   1: 6.130 ops/ms
Iteration   2: 6.141 ops/ms
Iteration   3: 6.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.105 ±(99.9%) 0.991 ops/ms [Average]
  (min, avg, max) = (6.042, 6.105, 6.141), stdev = 0.054
  CI (99.9%): [5.113, 7.096] (assumes normal distribution)


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
# Warmup Iteration   1: 1.628 ops/ms
# Warmup Iteration   2: 4.085 ops/ms
# Warmup Iteration   3: 5.212 ops/ms
Iteration   1: 5.169 ops/ms
Iteration   2: 5.071 ops/ms
Iteration   3: 5.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.144 ±(99.9%) 1.164 ops/ms [Average]
  (min, avg, max) = (5.071, 5.144, 5.191), stdev = 0.064
  CI (99.9%): [3.980, 6.308] (assumes normal distribution)


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
# Warmup Iteration   1: 20.284 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 6.715 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.623 ±(99.9%) 0.010 ms/op
Iteration   1: 5.293 ±(99.9%) 0.010 ms/op
Iteration   2: 5.284 ±(99.9%) 0.014 ms/op
Iteration   3: 5.435 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.337 ±(99.9%) 1.551 ms/op [Average]
  (min, avg, max) = (5.284, 5.337, 5.435), stdev = 0.085
  CI (99.9%): [3.786, 6.889] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.275 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 6.006 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.163 ±(99.9%) 0.009 ms/op
Iteration   1: 5.124 ±(99.9%) 0.006 ms/op
Iteration   2: 5.065 ±(99.9%) 0.015 ms/op
Iteration   3: 5.161 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.116 ±(99.9%) 0.885 ms/op [Average]
  (min, avg, max) = (5.065, 5.116, 5.161), stdev = 0.049
  CI (99.9%): [4.231, 6.002] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.406 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 6.177 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.494 ±(99.9%) 0.008 ms/op
Iteration   1: 5.387 ±(99.9%) 0.008 ms/op
Iteration   2: 5.438 ±(99.9%) 0.011 ms/op
Iteration   3: 5.200 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.342 ±(99.9%) 2.291 ms/op [Average]
  (min, avg, max) = (5.200, 5.342, 5.438), stdev = 0.126
  CI (99.9%): [3.050, 7.633] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.463 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 7.479 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.354 ±(99.9%) 0.013 ms/op
Iteration   1: 6.273 ±(99.9%) 0.014 ms/op
Iteration   2: 6.299 ±(99.9%) 0.011 ms/op
Iteration   3: 6.443 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.339 ±(99.9%) 1.669 ms/op [Average]
  (min, avg, max) = (6.273, 6.339, 6.443), stdev = 0.092
  CI (99.9%): [4.669, 8.008] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.868 ±(99.9%) 0.296 ms/op
# Warmup Iteration   2: 6.553 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.835 ±(99.9%) 0.027 ms/op
Iteration   1: 5.396 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.478 ms/op
                 createUser·p0.50:   5.095 ms/op
                 createUser·p0.90:   6.619 ms/op
                 createUser·p0.95:   7.602 ms/op
                 createUser·p0.99:   9.931 ms/op
                 createUser·p0.999:  26.664 ms/op
                 createUser·p0.9999: 36.780 ms/op
                 createUser·p1.00:   37.814 ms/op

Iteration   2: 5.601 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.392 ms/op
                 createUser·p0.50:   5.276 ms/op
                 createUser·p0.90:   7.168 ms/op
                 createUser·p0.95:   7.897 ms/op
                 createUser·p0.99:   10.535 ms/op
                 createUser·p0.999:  26.295 ms/op
                 createUser·p0.9999: 30.265 ms/op
                 createUser·p1.00:   31.261 ms/op

Iteration   3: 5.090 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.363 ms/op
                 createUser·p0.50:   4.858 ms/op
                 createUser·p0.90:   6.062 ms/op
                 createUser·p0.95:   6.734 ms/op
                 createUser·p0.99:   9.157 ms/op
                 createUser·p0.999:  27.451 ms/op
                 createUser·p0.9999: 33.522 ms/op
                 createUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 179169
  mean =      5.354 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 86126 
    [ 5.000,  7.500) = 83720 
    [ 7.500, 10.000) = 7601 
    [10.000, 12.500) = 1076 
    [12.500, 15.000) = 252 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.363 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      6.668 ms/op
     p(95.0000) =      7.553 ms/op
     p(99.0000) =      9.896 ms/op
     p(99.9000) =     26.668 ms/op
     p(99.9900) =     35.067 ms/op
     p(99.9990) =     37.814 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.264 ±(99.9%) 0.247 ms/op
# Warmup Iteration   2: 5.752 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.388 ±(99.9%) 0.019 ms/op
Iteration   1: 5.322 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.241 ms/op
                 existUser·p0.50:   5.038 ms/op
                 existUser·p0.90:   6.578 ms/op
                 existUser·p0.95:   7.660 ms/op
                 existUser·p0.99:   9.650 ms/op
                 existUser·p0.999:  20.148 ms/op
                 existUser·p0.9999: 24.016 ms/op
                 existUser·p1.00:   25.068 ms/op

Iteration   2: 5.110 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.413 ms/op
                 existUser·p0.50:   4.850 ms/op
                 existUser·p0.90:   6.054 ms/op
                 existUser·p0.95:   6.865 ms/op
                 existUser·p0.99:   9.716 ms/op
                 existUser·p0.999:  24.295 ms/op
                 existUser·p0.9999: 27.229 ms/op
                 existUser·p1.00:   27.886 ms/op

Iteration   3: 5.135 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.122 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   6.119 ms/op
                 existUser·p0.95:   6.840 ms/op
                 existUser·p0.99:   9.011 ms/op
                 existUser·p0.999:  13.304 ms/op
                 existUser·p0.9999: 26.913 ms/op
                 existUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 184937
  mean =      5.187 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 99923 
    [ 5.000,  7.500) = 77487 
    [ 7.500, 10.000) = 6173 
    [10.000, 12.500) = 907 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 68 

  Percentiles, ms/op:
      p(0.0000) =      2.122 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.250 ms/op
     p(95.0000) =      7.152 ms/op
     p(99.0000) =      9.388 ms/op
     p(99.9000) =     18.885 ms/op
     p(99.9900) =     26.854 ms/op
     p(99.9990) =     28.747 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.150 ±(99.9%) 0.271 ms/op
# Warmup Iteration   2: 6.598 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.626 ±(99.9%) 0.022 ms/op
Iteration   1: 5.562 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.677 ms/op
                 getUser·p0.50:   5.202 ms/op
                 getUser·p0.90:   6.619 ms/op
                 getUser·p0.95:   8.200 ms/op
                 getUser·p0.99:   13.599 ms/op
                 getUser·p0.999:  24.919 ms/op
                 getUser·p0.9999: 28.688 ms/op
                 getUser·p1.00:   31.654 ms/op

Iteration   2: 5.357 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.523 ms/op
                 getUser·p0.50:   5.136 ms/op
                 getUser·p0.90:   6.578 ms/op
                 getUser·p0.95:   7.438 ms/op
                 getUser·p0.99:   9.798 ms/op
                 getUser·p0.999:  13.812 ms/op
                 getUser·p0.9999: 29.755 ms/op
                 getUser·p1.00:   34.537 ms/op

Iteration   3: 5.448 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.535 ms/op
                 getUser·p0.50:   5.210 ms/op
                 getUser·p0.90:   6.423 ms/op
                 getUser·p0.95:   7.127 ms/op
                 getUser·p0.99:   10.486 ms/op
                 getUser·p0.999:  27.340 ms/op
                 getUser·p0.9999: 30.962 ms/op
                 getUser·p1.00:   32.702 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 175816
  mean =      5.454 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 67041 
    [ 5.000,  7.500) = 100046 
    [ 7.500, 10.000) = 6012 
    [10.000, 12.500) = 1612 
    [12.500, 15.000) = 629 
    [15.000, 17.500) = 236 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.677 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      6.529 ms/op
     p(95.0000) =      7.487 ms/op
     p(99.0000) =     11.076 ms/op
     p(99.9000) =     20.152 ms/op
     p(99.9900) =     30.245 ms/op
     p(99.9990) =     33.146 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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
# Warmup Iteration   1: 20.912 ±(99.9%) 0.341 ms/op
# Warmup Iteration   2: 7.389 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.547 ±(99.9%) 0.027 ms/op
Iteration   1: 6.371 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.248 ms/op
                 listUser·p0.50:   6.021 ms/op
                 listUser·p0.90:   7.684 ms/op
                 listUser·p0.95:   9.130 ms/op
                 listUser·p0.99:   12.042 ms/op
                 listUser·p0.999:  27.886 ms/op
                 listUser·p0.9999: 30.342 ms/op
                 listUser·p1.00:   31.359 ms/op

Iteration   2: 6.391 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.019 ms/op
                 listUser·p0.50:   6.119 ms/op
                 listUser·p0.90:   7.463 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   11.502 ms/op
                 listUser·p0.999:  29.567 ms/op
                 listUser·p0.9999: 32.833 ms/op
                 listUser·p1.00:   34.341 ms/op

Iteration   3: 6.121 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   3.117 ms/op
                 listUser·p0.50:   5.792 ms/op
                 listUser·p0.90:   7.209 ms/op
                 listUser·p0.95:   8.339 ms/op
                 listUser·p0.99:   11.321 ms/op
                 listUser·p0.999:  24.363 ms/op
                 listUser·p0.9999: 28.126 ms/op
                 listUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 152580
  mean =      6.292 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 6484 
    [ 5.000,  7.500) = 131344 
    [ 7.500, 10.000) = 10972 
    [10.000, 12.500) = 2780 
    [12.500, 15.000) = 558 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 92 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.019 ms/op
     p(50.0000) =      5.980 ms/op
     p(90.0000) =      7.455 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     11.600 ms/op
     p(99.9000) =     27.230 ms/op
     p(99.9900) =     32.398 ms/op
     p(99.9990) =     34.065 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.873 ± 4.237  ops/ms
ClientPb.existUser                       thrpt       3   6.310 ± 1.709  ops/ms
ClientPb.getUser                         thrpt       3   6.105 ± 0.991  ops/ms
ClientPb.listUser                        thrpt       3   5.144 ± 1.164  ops/ms
ClientPb.createUser                       avgt       3   5.337 ± 1.551   ms/op
ClientPb.existUser                        avgt       3   5.116 ± 0.885   ms/op
ClientPb.getUser                          avgt       3   5.342 ± 2.291   ms/op
ClientPb.listUser                         avgt       3   6.339 ± 1.669   ms/op
ClientPb.createUser                     sample  179169   5.354 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.363           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.038           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.668           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.553           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.896           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.668           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.067           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.814           ms/op
ClientPb.existUser                      sample  184937   5.187 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.122           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.940           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.250           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.152           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.388           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.885           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.854           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.803           ms/op
ClientPb.getUser                        sample  175816   5.454 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.677           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.177           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.529           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.487           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.076           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.152           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.245           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.537           ms/op
ClientPb.listUser                       sample  152580   6.292 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           3.019           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.980           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.455           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.600           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.230           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.398           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.341           ms/op
