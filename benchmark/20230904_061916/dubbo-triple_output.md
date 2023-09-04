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
# Warmup Iteration   1: 2.441 ops/ms
# Warmup Iteration   2: 5.657 ops/ms
# Warmup Iteration   3: 9.042 ops/ms
Iteration   1: 9.790 ops/ms
Iteration   2: 9.558 ops/ms
Iteration   3: 9.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.742 ±(99.9%) 3.016 ops/ms [Average]
  (min, avg, max) = (9.558, 9.742, 9.878), stdev = 0.165
  CI (99.9%): [6.726, 12.758] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.088 ops/ms
# Warmup Iteration   2: 9.117 ops/ms
# Warmup Iteration   3: 10.317 ops/ms
Iteration   1: 9.965 ops/ms
Iteration   2: 9.970 ops/ms
Iteration   3: 10.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.979 ±(99.9%) 0.354 ops/ms [Average]
  (min, avg, max) = (9.965, 9.979, 10.001), stdev = 0.019
  CI (99.9%): [9.625, 10.332] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.598 ops/ms
# Warmup Iteration   2: 9.031 ops/ms
# Warmup Iteration   3: 9.772 ops/ms
Iteration   1: 10.221 ops/ms
Iteration   2: 9.896 ops/ms
Iteration   3: 10.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.100 ±(99.9%) 3.244 ops/ms [Average]
  (min, avg, max) = (9.896, 10.100, 10.221), stdev = 0.178
  CI (99.9%): [6.856, 13.344] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.338 ops/ms
# Warmup Iteration   2: 7.746 ops/ms
# Warmup Iteration   3: 8.065 ops/ms
Iteration   1: 8.316 ops/ms
Iteration   2: 8.323 ops/ms
Iteration   3: 8.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.344 ±(99.9%) 0.793 ops/ms [Average]
  (min, avg, max) = (8.316, 8.344, 8.394), stdev = 0.043
  CI (99.9%): [7.551, 9.137] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.286 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.694 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.004 ms/op
Iteration   1: 3.157 ±(99.9%) 0.003 ms/op
Iteration   2: 3.111 ±(99.9%) 0.003 ms/op
Iteration   3: 3.195 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.154 ±(99.9%) 0.762 ms/op [Average]
  (min, avg, max) = (3.111, 3.154, 3.195), stdev = 0.042
  CI (99.9%): [2.392, 3.917] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.686 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.365 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.003 ms/op
Iteration   1: 3.195 ±(99.9%) 0.002 ms/op
Iteration   2: 3.025 ±(99.9%) 0.002 ms/op
Iteration   3: 3.082 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.101 ±(99.9%) 1.582 ms/op [Average]
  (min, avg, max) = (3.025, 3.101, 3.195), stdev = 0.087
  CI (99.9%): [1.519, 4.683] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.476 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.438 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.002 ms/op
Iteration   1: 3.129 ±(99.9%) 0.004 ms/op
Iteration   2: 3.228 ±(99.9%) 0.007 ms/op
Iteration   3: 3.378 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.245 ±(99.9%) 2.295 ms/op [Average]
  (min, avg, max) = (3.129, 3.245, 3.378), stdev = 0.126
  CI (99.9%): [0.949, 5.540] (assumes normal distribution)


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
# Warmup Iteration   1: 9.562 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.828 ±(99.9%) 0.008 ms/op
Iteration   1: 3.779 ±(99.9%) 0.009 ms/op
Iteration   2: 3.766 ±(99.9%) 0.004 ms/op
Iteration   3: 3.801 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.782 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (3.766, 3.782, 3.801), stdev = 0.018
  CI (99.9%): [3.459, 4.104] (assumes normal distribution)


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
# Warmup Iteration   1: 7.809 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.396 ±(99.9%) 0.010 ms/op
Iteration   1: 3.302 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.294 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  10.724 ms/op
                 createUser·p0.9999: 25.032 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   2: 3.222 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  20.611 ms/op
                 createUser·p0.9999: 24.607 ms/op
                 createUser·p1.00:   26.313 ms/op

Iteration   3: 3.295 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  17.592 ms/op
                 createUser·p0.9999: 37.899 ms/op
                 createUser·p1.00:   38.011 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293242
  mean =      3.273 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27336 
    [ 2.500,  5.000) = 258715 
    [ 5.000,  7.500) = 5967 
    [ 7.500, 10.000) = 785 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     19.235 ms/op
     p(99.9900) =     36.897 ms/op
     p(99.9990) =     38.011 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


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
# Warmup Iteration   1: 7.852 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.355 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.009 ms/op
Iteration   1: 3.136 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.206 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  10.011 ms/op
                 existUser·p0.9999: 24.832 ms/op
                 existUser·p1.00:   25.625 ms/op

Iteration   2: 3.074 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  12.173 ms/op
                 existUser·p0.9999: 23.383 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.489 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  9.647 ms/op
                 existUser·p0.9999: 20.775 ms/op
                 existUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309071
  mean =      3.104 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17664 
    [ 2.500,  5.000) = 284990 
    [ 5.000,  7.500) = 5203 
    [ 7.500, 10.000) = 844 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     11.861 ms/op
     p(99.9900) =     23.632 ms/op
     p(99.9990) =     25.362 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


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
# Warmup Iteration   1: 8.048 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.490 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.010 ms/op
Iteration   1: 3.207 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.208 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  14.578 ms/op
                 getUser·p0.9999: 20.972 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   2: 3.293 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.573 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  9.482 ms/op
                 getUser·p0.9999: 25.651 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   3: 3.291 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.179 ms/op
                 getUser·p0.999:  11.450 ms/op
                 getUser·p0.9999: 22.292 ms/op
                 getUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294183
  mean =      3.263 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22141 
    [ 2.500,  5.000) = 263915 
    [ 5.000,  7.500) = 6421 
    [ 7.500, 10.000) = 1300 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     12.124 ms/op
     p(99.9900) =     24.778 ms/op
     p(99.9990) =     26.052 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


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
# Warmup Iteration   1: 9.258 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.285 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.013 ms/op
Iteration   1: 3.915 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   8.167 ms/op
                 listUser·p0.999:  16.776 ms/op
                 listUser·p0.9999: 21.228 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   2: 3.888 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.724 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  14.064 ms/op
                 listUser·p0.9999: 17.629 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   3: 3.862 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  13.928 ms/op
                 listUser·p0.9999: 18.158 ms/op
                 listUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246847
  mean =      3.888 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 236485 
    [ 5.000,  7.500) = 7592 
    [ 7.500, 10.000) = 1931 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.639 ms/op
     p(99.9000) =     14.486 ms/op
     p(99.9900) =     20.423 ms/op
     p(99.9990) =     21.843 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.742 ± 3.016  ops/ms
ClientPb.existUser                       thrpt       3   9.979 ± 0.354  ops/ms
ClientPb.getUser                         thrpt       3  10.100 ± 3.244  ops/ms
ClientPb.listUser                        thrpt       3   8.344 ± 0.793  ops/ms
ClientPb.createUser                       avgt       3   3.154 ± 0.762   ms/op
ClientPb.existUser                        avgt       3   3.101 ± 1.582   ms/op
ClientPb.getUser                          avgt       3   3.245 ± 2.295   ms/op
ClientPb.listUser                         avgt       3   3.782 ± 0.323   ms/op
ClientPb.createUser                     sample  293242   3.273 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.272           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.592           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.051           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.767           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.235           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.897           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.011           ms/op
ClientPb.existUser                      sample  309071   3.104 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.206           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.342           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.861           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.632           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.625           ms/op
ClientPb.getUser                        sample  294183   3.263 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.190           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.137           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.095           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.124           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.778           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.280           ms/op
ClientPb.listUser                       sample  246847   3.888 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.317           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.744           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.639           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.486           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.423           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.217           ms/op
