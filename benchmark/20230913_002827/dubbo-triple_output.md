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
# Warmup Iteration   1: 2.540 ops/ms
# Warmup Iteration   2: 6.026 ops/ms
# Warmup Iteration   3: 8.867 ops/ms
Iteration   1: 9.846 ops/ms
Iteration   2: 9.651 ops/ms
Iteration   3: 9.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.621 ±(99.9%) 4.409 ops/ms [Average]
  (min, avg, max) = (9.365, 9.621, 9.846), stdev = 0.242
  CI (99.9%): [5.212, 14.029] (assumes normal distribution)


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
# Warmup Iteration   1: 3.198 ops/ms
# Warmup Iteration   2: 8.795 ops/ms
# Warmup Iteration   3: 9.560 ops/ms
Iteration   1: 10.158 ops/ms
Iteration   2: 10.076 ops/ms
Iteration   3: 9.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.060 ±(99.9%) 1.944 ops/ms [Average]
  (min, avg, max) = (9.946, 10.060, 10.158), stdev = 0.107
  CI (99.9%): [8.116, 12.004] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.343 ops/ms
# Warmup Iteration   2: 8.353 ops/ms
# Warmup Iteration   3: 9.217 ops/ms
Iteration   1: 9.814 ops/ms
Iteration   2: 10.061 ops/ms
Iteration   3: 9.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.802 ±(99.9%) 4.860 ops/ms [Average]
  (min, avg, max) = (9.529, 9.802, 10.061), stdev = 0.266
  CI (99.9%): [4.941, 14.662] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.127 ops/ms
# Warmup Iteration   2: 7.601 ops/ms
# Warmup Iteration   3: 8.133 ops/ms
Iteration   1: 8.220 ops/ms
Iteration   2: 8.022 ops/ms
Iteration   3: 8.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.138 ±(99.9%) 1.885 ops/ms [Average]
  (min, avg, max) = (8.022, 8.138, 8.220), stdev = 0.103
  CI (99.9%): [6.253, 10.023] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.885 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.525 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.405 ±(99.9%) 0.005 ms/op
Iteration   1: 3.317 ±(99.9%) 0.002 ms/op
Iteration   2: 3.271 ±(99.9%) 0.003 ms/op
Iteration   3: 3.265 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.284 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (3.265, 3.284, 3.317), stdev = 0.028
  CI (99.9%): [2.764, 3.804] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.318 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.361 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.005 ms/op
Iteration   1: 3.093 ±(99.9%) 0.004 ms/op
Iteration   2: 3.119 ±(99.9%) 0.005 ms/op
Iteration   3: 3.080 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.097 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (3.080, 3.097, 3.119), stdev = 0.020
  CI (99.9%): [2.731, 3.464] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 7.946 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.004 ms/op
Iteration   1: 3.401 ±(99.9%) 0.003 ms/op
Iteration   2: 3.252 ±(99.9%) 0.003 ms/op
Iteration   3: 3.300 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.318 ±(99.9%) 1.393 ms/op [Average]
  (min, avg, max) = (3.252, 3.318, 3.401), stdev = 0.076
  CI (99.9%): [1.924, 4.711] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 9.255 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.203 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.928 ±(99.9%) 0.005 ms/op
Iteration   1: 3.801 ±(99.9%) 0.007 ms/op
Iteration   2: 3.768 ±(99.9%) 0.006 ms/op
Iteration   3: 3.846 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.805 ±(99.9%) 0.712 ms/op [Average]
  (min, avg, max) = (3.768, 3.805, 3.846), stdev = 0.039
  CI (99.9%): [3.093, 4.516] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.026 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.010 ms/op
Iteration   1: 3.234 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   7.266 ms/op
                 createUser·p0.999:  16.688 ms/op
                 createUser·p0.9999: 20.713 ms/op
                 createUser·p1.00:   21.561 ms/op

Iteration   2: 3.263 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.319 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  12.741 ms/op
                 createUser·p0.9999: 22.512 ms/op
                 createUser·p1.00:   23.298 ms/op

Iteration   3: 3.212 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.368 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  18.252 ms/op
                 createUser·p0.9999: 24.199 ms/op
                 createUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296194
  mean =      3.236 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22728 
    [ 2.500,  5.000) = 266172 
    [ 5.000,  7.500) = 5649 
    [ 7.500, 10.000) = 1115 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 150 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     18.082 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     25.036 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.201 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.410 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.009 ms/op
Iteration   1: 3.302 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   6.431 ms/op
                 existUser·p0.999:  13.714 ms/op
                 existUser·p0.9999: 20.697 ms/op
                 existUser·p1.00:   21.955 ms/op

Iteration   2: 3.137 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.587 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  12.403 ms/op
                 existUser·p0.9999: 26.601 ms/op
                 existUser·p1.00:   29.360 ms/op

Iteration   3: 3.312 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.256 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  13.699 ms/op
                 existUser·p0.9999: 23.190 ms/op
                 existUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295371
  mean =      3.248 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19459 
    [ 2.500,  5.000) = 265957 
    [ 5.000,  7.500) = 8488 
    [ 7.500, 10.000) = 1028 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 160 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     12.501 ms/op
     p(99.9900) =     25.000 ms/op
     p(99.9990) =     27.309 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 8.468 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.613 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.447 ±(99.9%) 0.012 ms/op
Iteration   1: 3.380 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.476 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   7.045 ms/op
                 getUser·p0.999:  19.104 ms/op
                 getUser·p0.9999: 27.248 ms/op
                 getUser·p1.00:   27.984 ms/op

Iteration   2: 3.425 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  19.308 ms/op
                 getUser·p0.9999: 28.388 ms/op
                 getUser·p1.00:   29.393 ms/op

Iteration   3: 3.235 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.046 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.673 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  10.866 ms/op
                 getUser·p0.9999: 35.725 ms/op
                 getUser·p1.00:   38.339 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 286771
  mean =      3.345 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8421 
    [ 2.500,  5.000) = 268826 
    [ 5.000,  7.500) = 7661 
    [ 7.500, 10.000) = 1371 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.476 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     16.650 ms/op
     p(99.9900) =     34.339 ms/op
     p(99.9990) =     38.339 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


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
# Warmup Iteration   1: 8.491 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.876 ±(99.9%) 0.013 ms/op
Iteration   1: 3.760 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.321 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  15.270 ms/op
                 listUser·p0.9999: 22.134 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   2: 3.690 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.006 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  15.172 ms/op
                 listUser·p0.9999: 19.137 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   3: 3.816 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  14.877 ms/op
                 listUser·p0.9999: 16.904 ms/op
                 listUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255614
  mean =      3.755 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 248109 
    [ 5.000,  7.500) = 5299 
    [ 7.500, 10.000) = 1491 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.608 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     14.916 ms/op
     p(99.9900) =     20.593 ms/op
     p(99.9990) =     22.198 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.621 ± 4.409  ops/ms
ClientPb.existUser                       thrpt       3  10.060 ± 1.944  ops/ms
ClientPb.getUser                         thrpt       3   9.802 ± 4.860  ops/ms
ClientPb.listUser                        thrpt       3   8.138 ± 1.885  ops/ms
ClientPb.createUser                       avgt       3   3.284 ± 0.520   ms/op
ClientPb.existUser                        avgt       3   3.097 ± 0.367   ms/op
ClientPb.getUser                          avgt       3   3.318 ± 1.393   ms/op
ClientPb.listUser                         avgt       3   3.805 ± 0.712   ms/op
ClientPb.createUser                     sample  296194   3.236 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.083           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.514           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.095           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.082           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.872           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.952           ms/op
ClientPb.existUser                      sample  295371   3.248 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.964           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.365           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.501           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.000           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.360           ms/op
ClientPb.getUser                        sample  286771   3.345 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.476           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.707           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.849           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.650           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.339           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.339           ms/op
ClientPb.listUser                       sample  255614   3.755 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.608           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.143           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.916           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.593           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.217           ms/op
