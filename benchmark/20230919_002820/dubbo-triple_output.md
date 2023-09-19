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
# Warmup Iteration   1: 2.482 ops/ms
# Warmup Iteration   2: 5.501 ops/ms
# Warmup Iteration   3: 8.993 ops/ms
Iteration   1: 9.695 ops/ms
Iteration   2: 9.897 ops/ms
Iteration   3: 9.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.850 ±(99.9%) 2.518 ops/ms [Average]
  (min, avg, max) = (9.695, 9.850, 9.960), stdev = 0.138
  CI (99.9%): [7.332, 12.369] (assumes normal distribution)


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
# Warmup Iteration   1: 3.596 ops/ms
# Warmup Iteration   2: 9.574 ops/ms
# Warmup Iteration   3: 9.618 ops/ms
Iteration   1: 9.906 ops/ms
Iteration   2: 10.274 ops/ms
Iteration   3: 9.997 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.059 ±(99.9%) 3.498 ops/ms [Average]
  (min, avg, max) = (9.906, 10.059, 10.274), stdev = 0.192
  CI (99.9%): [6.561, 13.557] (assumes normal distribution)


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
# Warmup Iteration   1: 3.324 ops/ms
# Warmup Iteration   2: 8.585 ops/ms
# Warmup Iteration   3: 9.367 ops/ms
Iteration   1: 9.714 ops/ms
Iteration   2: 10.041 ops/ms
Iteration   3: 9.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.836 ±(99.9%) 3.252 ops/ms [Average]
  (min, avg, max) = (9.714, 9.836, 10.041), stdev = 0.178
  CI (99.9%): [6.584, 13.089] (assumes normal distribution)


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
# Warmup Iteration   1: 3.206 ops/ms
# Warmup Iteration   2: 7.636 ops/ms
# Warmup Iteration   3: 8.170 ops/ms
Iteration   1: 8.361 ops/ms
Iteration   2: 8.081 ops/ms
Iteration   3: 8.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.243 ±(99.9%) 2.649 ops/ms [Average]
  (min, avg, max) = (8.081, 8.243, 8.361), stdev = 0.145
  CI (99.9%): [5.594, 10.892] (assumes normal distribution)


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
# Warmup Iteration   1: 8.039 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.416 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.403 ±(99.9%) 0.002 ms/op
Iteration   1: 3.309 ±(99.9%) 0.002 ms/op
Iteration   2: 3.283 ±(99.9%) 0.002 ms/op
Iteration   3: 3.366 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.319 ±(99.9%) 0.782 ms/op [Average]
  (min, avg, max) = (3.283, 3.319, 3.366), stdev = 0.043
  CI (99.9%): [2.537, 4.102] (assumes normal distribution)


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
# Warmup Iteration   1: 7.493 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.398 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.003 ms/op
Iteration   1: 3.176 ±(99.9%) 0.006 ms/op
Iteration   2: 3.119 ±(99.9%) 0.002 ms/op
Iteration   3: 3.060 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.118 ±(99.9%) 1.051 ms/op [Average]
  (min, avg, max) = (3.060, 3.118, 3.176), stdev = 0.058
  CI (99.9%): [2.068, 4.169] (assumes normal distribution)


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
# Warmup Iteration   1: 7.464 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.386 ±(99.9%) 0.004 ms/op
Iteration   1: 3.223 ±(99.9%) 0.003 ms/op
Iteration   2: 3.288 ±(99.9%) 0.002 ms/op
Iteration   3: 3.228 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.247 ±(99.9%) 0.652 ms/op [Average]
  (min, avg, max) = (3.223, 3.247, 3.288), stdev = 0.036
  CI (99.9%): [2.594, 3.899] (assumes normal distribution)


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
# Warmup Iteration   1: 9.390 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.195 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.004 ms/op
Iteration   1: 3.949 ±(99.9%) 0.004 ms/op
Iteration   2: 3.816 ±(99.9%) 0.005 ms/op
Iteration   3: 3.848 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.871 ±(99.9%) 1.266 ms/op [Average]
  (min, avg, max) = (3.816, 3.871, 3.949), stdev = 0.069
  CI (99.9%): [2.605, 5.137] (assumes normal distribution)


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
# Warmup Iteration   1: 8.915 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.369 ±(99.9%) 0.010 ms/op
Iteration   1: 3.253 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  12.430 ms/op
                 createUser·p0.9999: 22.053 ms/op
                 createUser·p1.00:   22.315 ms/op

Iteration   2: 3.335 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  17.302 ms/op
                 createUser·p0.9999: 21.019 ms/op
                 createUser·p1.00:   22.315 ms/op

Iteration   3: 3.345 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  16.259 ms/op
                 createUser·p0.9999: 20.654 ms/op
                 createUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289770
  mean =      3.310 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10061 
    [ 2.500,  5.000) = 275070 
    [ 5.000,  7.500) = 3585 
    [ 7.500, 10.000) = 449 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     16.158 ms/op
     p(99.9900) =     21.398 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 7.272 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.315 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.009 ms/op
Iteration   1: 3.234 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  14.647 ms/op
                 existUser·p0.9999: 22.151 ms/op
                 existUser·p1.00:   22.905 ms/op

Iteration   2: 3.211 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  10.690 ms/op
                 existUser·p0.9999: 22.579 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   3: 3.176 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.657 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  12.949 ms/op
                 existUser·p0.9999: 22.870 ms/op
                 existUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299201
  mean =      3.207 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23523 
    [ 2.500,  5.000) = 270670 
    [ 5.000,  7.500) = 4189 
    [ 7.500, 10.000) = 376 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     13.006 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     23.168 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 7.467 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.315 ±(99.9%) 0.009 ms/op
Iteration   1: 3.362 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.372 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  19.169 ms/op
                 getUser·p0.9999: 31.275 ms/op
                 getUser·p1.00:   31.425 ms/op

Iteration   2: 3.224 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   5.431 ms/op
                 getUser·p0.999:  18.210 ms/op
                 getUser·p0.9999: 23.364 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   3: 3.248 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.147 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  9.680 ms/op
                 getUser·p0.9999: 21.430 ms/op
                 getUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292827
  mean =      3.277 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13305 
    [ 2.500,  5.000) = 273126 
    [ 5.000,  7.500) = 5400 
    [ 7.500, 10.000) = 460 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 142 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     17.247 ms/op
     p(99.9900) =     28.054 ms/op
     p(99.9990) =     31.394 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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
# Warmup Iteration   1: 9.189 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.195 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.011 ms/op
Iteration   1: 3.852 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.868 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  16.495 ms/op
                 listUser·p0.9999: 23.749 ms/op
                 listUser·p1.00:   25.657 ms/op

Iteration   2: 3.795 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  14.025 ms/op
                 listUser·p0.9999: 18.027 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   3: 3.914 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  12.834 ms/op
                 listUser·p0.9999: 20.665 ms/op
                 listUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249072
  mean =      3.853 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 242461 
    [ 5.000,  7.500) = 4933 
    [ 7.500, 10.000) = 859 
    [10.000, 12.500) = 268 
    [12.500, 15.000) = 312 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.744 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     22.384 ms/op
     p(99.9990) =     25.641 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.850 ± 2.518  ops/ms
ClientPb.existUser                       thrpt       3  10.059 ± 3.498  ops/ms
ClientPb.getUser                         thrpt       3   9.836 ± 3.252  ops/ms
ClientPb.listUser                        thrpt       3   8.243 ± 2.649  ops/ms
ClientPb.createUser                       avgt       3   3.319 ± 0.782   ms/op
ClientPb.existUser                        avgt       3   3.118 ± 1.051   ms/op
ClientPb.getUser                          avgt       3   3.247 ± 0.652   ms/op
ClientPb.listUser                         avgt       3   3.871 ± 1.266   ms/op
ClientPb.createUser                     sample  289770   3.310 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.792           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.026           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.612           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.158           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.398           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.577           ms/op
ClientPb.existUser                      sample  299201   3.207 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.151           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.441           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.006           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.544           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.298           ms/op
ClientPb.getUser                        sample  292827   3.277 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.147           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.349           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.247           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.054           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.425           ms/op
ClientPb.listUser                       sample  249072   3.853 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.868           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.760           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.178           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.744           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.074           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.384           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.657           ms/op
