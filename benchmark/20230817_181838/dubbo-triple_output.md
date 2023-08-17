# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.503 ops/ms
# Warmup Iteration   2: 5.808 ops/ms
# Warmup Iteration   3: 9.219 ops/ms
Iteration   1: 9.888 ops/ms
Iteration   2: 9.651 ops/ms
Iteration   3: 9.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.800 ±(99.9%) 2.367 ops/ms [Average]
  (min, avg, max) = (9.651, 9.800, 9.888), stdev = 0.130
  CI (99.9%): [7.433, 12.167] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.444 ops/ms
# Warmup Iteration   2: 8.863 ops/ms
# Warmup Iteration   3: 9.705 ops/ms
Iteration   1: 10.294 ops/ms
Iteration   2: 9.992 ops/ms
Iteration   3: 10.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.186 ±(99.9%) 3.079 ops/ms [Average]
  (min, avg, max) = (9.992, 10.186, 10.294), stdev = 0.169
  CI (99.9%): [7.107, 13.266] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.461 ops/ms
# Warmup Iteration   2: 8.630 ops/ms
# Warmup Iteration   3: 9.182 ops/ms
Iteration   1: 9.607 ops/ms
Iteration   2: 9.628 ops/ms
Iteration   3: 9.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.688 ±(99.9%) 2.217 ops/ms [Average]
  (min, avg, max) = (9.607, 9.688, 9.827), stdev = 0.122
  CI (99.9%): [7.470, 11.905] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 3.250 ops/ms
# Warmup Iteration   2: 7.567 ops/ms
# Warmup Iteration   3: 8.161 ops/ms
Iteration   1: 8.132 ops/ms
Iteration   2: 8.345 ops/ms
Iteration   3: 8.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.323 ±(99.9%) 3.314 ops/ms [Average]
  (min, avg, max) = (8.132, 8.323, 8.493), stdev = 0.182
  CI (99.9%): [5.009, 11.637] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.498 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.665 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.503 ±(99.9%) 0.004 ms/op
Iteration   1: 3.382 ±(99.9%) 0.005 ms/op
Iteration   2: 3.301 ±(99.9%) 0.004 ms/op
Iteration   3: 3.284 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.322 ±(99.9%) 0.954 ms/op [Average]
  (min, avg, max) = (3.284, 3.322, 3.382), stdev = 0.052
  CI (99.9%): [2.368, 4.276] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.630 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.459 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.003 ms/op
Iteration   1: 3.127 ±(99.9%) 0.004 ms/op
Iteration   2: 3.228 ±(99.9%) 0.006 ms/op
Iteration   3: 3.076 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.144 ±(99.9%) 1.416 ms/op [Average]
  (min, avg, max) = (3.076, 3.144, 3.228), stdev = 0.078
  CI (99.9%): [1.728, 4.560] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.647 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.487 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.487 ±(99.9%) 0.003 ms/op
Iteration   1: 3.309 ±(99.9%) 0.004 ms/op
Iteration   2: 3.221 ±(99.9%) 0.003 ms/op
Iteration   3: 3.331 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.287 ±(99.9%) 1.060 ms/op [Average]
  (min, avg, max) = (3.221, 3.287, 3.331), stdev = 0.058
  CI (99.9%): [2.227, 4.347] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.044 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.353 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.003 ms/op
Iteration   1: 3.835 ±(99.9%) 0.006 ms/op
Iteration   2: 3.802 ±(99.9%) 0.008 ms/op
Iteration   3: 3.945 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.861 ±(99.9%) 1.361 ms/op [Average]
  (min, avg, max) = (3.802, 3.861, 3.945), stdev = 0.075
  CI (99.9%): [2.500, 5.222] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.467 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.408 ±(99.9%) 0.010 ms/op
Iteration   1: 3.302 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.289 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  18.487 ms/op
                 createUser·p0.9999: 24.083 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   2: 3.237 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  11.312 ms/op
                 createUser·p0.9999: 24.117 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   3: 3.339 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  16.324 ms/op
                 createUser·p0.9999: 20.571 ms/op
                 createUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291365
  mean =      3.292 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16676 
    [ 2.500,  5.000) = 266843 
    [ 5.000,  7.500) = 6450 
    [ 7.500, 10.000) = 856 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     16.831 ms/op
     p(99.9900) =     23.986 ms/op
     p(99.9990) =     24.481 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.420 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.411 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.008 ms/op
Iteration   1: 3.078 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.458 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  12.960 ms/op
                 existUser·p0.9999: 21.745 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   2: 3.268 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.542 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  13.879 ms/op
                 existUser·p0.9999: 24.911 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   3: 3.288 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.120 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   6.423 ms/op
                 existUser·p0.999:  16.712 ms/op
                 existUser·p0.9999: 21.603 ms/op
                 existUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299133
  mean =      3.208 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18771 
    [ 2.500,  5.000) = 271617 
    [ 5.000,  7.500) = 7249 
    [ 7.500, 10.000) = 959 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     23.968 ms/op
     p(99.9990) =     25.330 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.081 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.011 ms/op
Iteration   1: 3.304 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  12.584 ms/op
                 getUser·p0.9999: 22.151 ms/op
                 getUser·p1.00:   22.643 ms/op

Iteration   2: 3.320 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  17.764 ms/op
                 getUser·p0.9999: 23.474 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   3: 3.308 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.285 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   4.190 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  11.876 ms/op
                 getUser·p0.9999: 25.176 ms/op
                 getUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290025
  mean =      3.311 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14684 
    [ 2.500,  5.000) = 266570 
    [ 5.000,  7.500) = 7349 
    [ 7.500, 10.000) = 1032 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.285 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     14.284 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     25.664 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.925 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.014 ms/op
Iteration   1: 3.797 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.876 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   7.503 ms/op
                 listUser·p0.999:  19.104 ms/op
                 listUser·p0.9999: 21.834 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   2: 3.835 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 16.706 ms/op
                 listUser·p1.00:   23.069 ms/op

Iteration   3: 3.813 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.087 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  12.824 ms/op
                 listUser·p0.9999: 18.743 ms/op
                 listUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251482
  mean =      3.815 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 241766 
    [ 5.000,  7.500) = 7038 
    [ 7.500, 10.000) = 1854 
    [10.000, 12.500) = 290 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.876 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     14.361 ms/op
     p(99.9900) =     21.229 ms/op
     p(99.9990) =     23.018 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.800 ± 2.367  ops/ms
ClientPb.existUser                       thrpt       3  10.186 ± 3.079  ops/ms
ClientPb.getUser                         thrpt       3   9.688 ± 2.217  ops/ms
ClientPb.listUser                        thrpt       3   8.323 ± 3.314  ops/ms
ClientPb.createUser                       avgt       3   3.322 ± 0.954   ms/op
ClientPb.existUser                        avgt       3   3.144 ± 1.416   ms/op
ClientPb.getUser                          avgt       3   3.287 ± 1.060   ms/op
ClientPb.listUser                         avgt       3   3.861 ± 1.361   ms/op
ClientPb.createUser                     sample  291365   3.292 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.990           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.160           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.831           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.986           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.510           ms/op
ClientPb.existUser                      sample  299133   3.208 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.120           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.998           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.062           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.122           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.968           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.494           ms/op
ClientPb.getUser                        sample  290025   3.311 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.285           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.707           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.488           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.284           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.970           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.821           ms/op
ClientPb.listUser                       sample  251482   3.815 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.876           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.170           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.569           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.361           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.229           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.069           ms/op
