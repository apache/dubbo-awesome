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
# Warmup Iteration   1: 1.557 ops/ms
# Warmup Iteration   2: 3.676 ops/ms
# Warmup Iteration   3: 6.741 ops/ms
Iteration   1: 6.862 ops/ms
Iteration   2: 7.419 ops/ms
Iteration   3: 7.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.198 ±(99.9%) 5.397 ops/ms [Average]
  (min, avg, max) = (6.862, 7.198, 7.419), stdev = 0.296
  CI (99.9%): [1.801, 12.595] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.215 ops/ms
# Warmup Iteration   2: 5.879 ops/ms
# Warmup Iteration   3: 7.386 ops/ms
Iteration   1: 7.607 ops/ms
Iteration   2: 7.347 ops/ms
Iteration   3: 7.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.626 ±(99.9%) 5.277 ops/ms [Average]
  (min, avg, max) = (7.347, 7.626, 7.924), stdev = 0.289
  CI (99.9%): [2.349, 12.904] (assumes normal distribution)


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
# Warmup Iteration   1: 2.077 ops/ms
# Warmup Iteration   2: 6.121 ops/ms
# Warmup Iteration   3: 6.870 ops/ms
Iteration   1: 7.173 ops/ms
Iteration   2: 7.679 ops/ms
Iteration   3: 7.638 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.497 ±(99.9%) 5.131 ops/ms [Average]
  (min, avg, max) = (7.173, 7.497, 7.679), stdev = 0.281
  CI (99.9%): [2.365, 12.628] (assumes normal distribution)


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
# Warmup Iteration   1: 2.006 ops/ms
# Warmup Iteration   2: 5.177 ops/ms
# Warmup Iteration   3: 5.733 ops/ms
Iteration   1: 5.896 ops/ms
Iteration   2: 6.140 ops/ms
Iteration   3: 6.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.033 ±(99.9%) 2.277 ops/ms [Average]
  (min, avg, max) = (5.896, 6.033, 6.140), stdev = 0.125
  CI (99.9%): [3.756, 8.310] (assumes normal distribution)


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
# Warmup Iteration   1: 13.717 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.683 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.631 ±(99.9%) 0.005 ms/op
Iteration   1: 4.348 ±(99.9%) 0.009 ms/op
Iteration   2: 4.438 ±(99.9%) 0.010 ms/op
Iteration   3: 4.394 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.393 ±(99.9%) 0.819 ms/op [Average]
  (min, avg, max) = (4.348, 4.393, 4.438), stdev = 0.045
  CI (99.9%): [3.574, 5.212] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 13.740 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.884 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.087 ±(99.9%) 0.006 ms/op
Iteration   1: 4.321 ±(99.9%) 0.004 ms/op
Iteration   2: 4.262 ±(99.9%) 0.006 ms/op
Iteration   3: 4.004 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.196 ±(99.9%) 3.077 ms/op [Average]
  (min, avg, max) = (4.004, 4.196, 4.321), stdev = 0.169
  CI (99.9%): [1.119, 7.273] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 14.138 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.360 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.453 ±(99.9%) 0.004 ms/op
Iteration   1: 4.058 ±(99.9%) 0.006 ms/op
Iteration   2: 4.361 ±(99.9%) 0.004 ms/op
Iteration   3: 4.439 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.286 ±(99.9%) 3.668 ms/op [Average]
  (min, avg, max) = (4.058, 4.286, 4.439), stdev = 0.201
  CI (99.9%): [0.618, 7.954] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 16.056 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 6.200 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.254 ±(99.9%) 0.012 ms/op
Iteration   1: 5.219 ±(99.9%) 0.013 ms/op
Iteration   2: 5.149 ±(99.9%) 0.009 ms/op
Iteration   3: 5.042 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.137 ±(99.9%) 1.628 ms/op [Average]
  (min, avg, max) = (5.042, 5.137, 5.219), stdev = 0.089
  CI (99.9%): [3.508, 6.765] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.951 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 5.279 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.728 ±(99.9%) 0.021 ms/op
Iteration   1: 4.350 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.802 ms/op
                 createUser·p0.50:   4.051 ms/op
                 createUser·p0.90:   5.300 ms/op
                 createUser·p0.95:   6.005 ms/op
                 createUser·p0.99:   8.471 ms/op
                 createUser·p0.999:  25.149 ms/op
                 createUser·p0.9999: 29.458 ms/op
                 createUser·p1.00:   31.097 ms/op

Iteration   2: 4.412 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.015 ms/op
                 createUser·p0.50:   4.055 ms/op
                 createUser·p0.90:   5.489 ms/op
                 createUser·p0.95:   6.439 ms/op
                 createUser·p0.99:   8.765 ms/op
                 createUser·p0.999:  27.380 ms/op
                 createUser·p0.9999: 31.073 ms/op
                 createUser·p1.00:   32.932 ms/op

Iteration   3: 4.552 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.066 ms/op
                 createUser·p0.50:   4.194 ms/op
                 createUser·p0.90:   5.693 ms/op
                 createUser·p0.95:   6.477 ms/op
                 createUser·p0.99:   8.585 ms/op
                 createUser·p0.999:  16.346 ms/op
                 createUser·p0.9999: 34.011 ms/op
                 createUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 216194
  mean =      4.436 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 251 
    [ 2.500,  5.000) = 176130 
    [ 5.000,  7.500) = 35215 
    [ 7.500, 10.000) = 3399 
    [10.000, 12.500) = 610 
    [12.500, 15.000) = 233 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 102 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.802 ms/op
     p(50.0000) =      4.096 ms/op
     p(90.0000) =      5.521 ms/op
     p(95.0000) =      6.324 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     25.592 ms/op
     p(99.9900) =     32.178 ms/op
     p(99.9990) =     34.396 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.933 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 4.972 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.320 ±(99.9%) 0.016 ms/op
Iteration   1: 4.225 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.974 ms/op
                 existUser·p0.50:   3.949 ms/op
                 existUser·p0.90:   5.202 ms/op
                 existUser·p0.95:   5.931 ms/op
                 existUser·p0.99:   7.856 ms/op
                 existUser·p0.999:  13.550 ms/op
                 existUser·p0.9999: 30.802 ms/op
                 existUser·p1.00:   32.080 ms/op

Iteration   2: 4.218 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.837 ms/op
                 existUser·p0.50:   3.895 ms/op
                 existUser·p0.90:   5.177 ms/op
                 existUser·p0.95:   6.218 ms/op
                 existUser·p0.99:   8.765 ms/op
                 existUser·p0.999:  14.486 ms/op
                 existUser·p0.9999: 32.290 ms/op
                 existUser·p1.00:   33.423 ms/op

Iteration   3: 4.351 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.247 ms/op
                 existUser·p0.50:   3.887 ms/op
                 existUser·p0.90:   5.530 ms/op
                 existUser·p0.95:   6.554 ms/op
                 existUser·p0.99:   10.158 ms/op
                 existUser·p0.999:  18.711 ms/op
                 existUser·p0.9999: 39.995 ms/op
                 existUser·p1.00:   41.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 225230
  mean =      4.264 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 194355 
    [ 5.000, 10.000) = 29350 
    [10.000, 15.000) = 1240 
    [15.000, 20.000) = 86 
    [20.000, 25.000) = 27 
    [25.000, 30.000) = 60 
    [30.000, 35.000) = 80 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      6.242 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     18.249 ms/op
     p(99.9900) =     39.191 ms/op
     p(99.9990) =     40.272 ms/op
     p(99.9999) =     41.878 ms/op
    p(100.0000) =     41.878 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.808 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 5.141 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.352 ±(99.9%) 0.016 ms/op
Iteration   1: 4.577 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.118 ms/op
                 getUser·p0.50:   4.202 ms/op
                 getUser·p0.90:   6.005 ms/op
                 getUser·p0.95:   6.906 ms/op
                 getUser·p0.99:   9.404 ms/op
                 getUser·p0.999:  23.337 ms/op
                 getUser·p0.9999: 38.011 ms/op
                 getUser·p1.00:   38.339 ms/op

Iteration   2: 4.379 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.962 ms/op
                 getUser·p0.50:   4.071 ms/op
                 getUser·p0.90:   5.423 ms/op
                 getUser·p0.95:   6.259 ms/op
                 getUser·p0.99:   8.798 ms/op
                 getUser·p0.999:  15.104 ms/op
                 getUser·p0.9999: 29.219 ms/op
                 getUser·p1.00:   30.147 ms/op

Iteration   3: 4.443 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.956 ms/op
                 getUser·p0.50:   4.112 ms/op
                 getUser·p0.90:   5.415 ms/op
                 getUser·p0.95:   6.275 ms/op
                 getUser·p0.99:   9.110 ms/op
                 getUser·p0.999:  29.196 ms/op
                 getUser·p0.9999: 33.423 ms/op
                 getUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 214835
  mean =      4.465 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 174234 
    [ 5.000,  7.500) = 35176 
    [ 7.500, 10.000) = 3959 
    [10.000, 12.500) = 951 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 102 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.956 ms/op
     p(50.0000) =      4.125 ms/op
     p(90.0000) =      5.603 ms/op
     p(95.0000) =      6.578 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     25.630 ms/op
     p(99.9900) =     36.440 ms/op
     p(99.9990) =     38.329 ms/op
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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.644 ±(99.9%) 0.225 ms/op
# Warmup Iteration   2: 6.271 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.703 ±(99.9%) 0.028 ms/op
Iteration   1: 5.410 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   4.964 ms/op
                 listUser·p0.90:   6.947 ms/op
                 listUser·p0.95:   8.020 ms/op
                 listUser·p0.99:   10.975 ms/op
                 listUser·p0.999:  33.048 ms/op
                 listUser·p0.9999: 35.216 ms/op
                 listUser·p1.00:   36.045 ms/op

Iteration   2: 5.283 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.909 ms/op
                 listUser·p0.50:   4.915 ms/op
                 listUser·p0.90:   6.513 ms/op
                 listUser·p0.95:   7.619 ms/op
                 listUser·p0.99:   10.437 ms/op
                 listUser·p0.999:  23.263 ms/op
                 listUser·p0.9999: 28.291 ms/op
                 listUser·p1.00:   28.738 ms/op

Iteration   3: 5.037 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   6.324 ms/op
                 listUser·p0.95:   7.856 ms/op
                 listUser·p0.99:   10.469 ms/op
                 listUser·p0.999:  19.742 ms/op
                 listUser·p0.9999: 22.793 ms/op
                 listUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 183167
  mean =      5.239 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 109363 
    [ 5.000,  7.500) = 62504 
    [ 7.500, 10.000) = 8762 
    [10.000, 12.500) = 1594 
    [12.500, 15.000) = 471 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 56 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.909 ms/op
     p(50.0000) =      4.817 ms/op
     p(90.0000) =      6.611 ms/op
     p(95.0000) =      7.864 ms/op
     p(99.0000) =     10.568 ms/op
     p(99.9000) =     23.069 ms/op
     p(99.9900) =     34.648 ms/op
     p(99.9990) =     35.827 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.198 ± 5.397  ops/ms
ClientPb.existUser                       thrpt       3   7.626 ± 5.277  ops/ms
ClientPb.getUser                         thrpt       3   7.497 ± 5.131  ops/ms
ClientPb.listUser                        thrpt       3   6.033 ± 2.277  ops/ms
ClientPb.createUser                       avgt       3   4.393 ± 0.819   ms/op
ClientPb.existUser                        avgt       3   4.196 ± 3.077   ms/op
ClientPb.getUser                          avgt       3   4.286 ± 3.668   ms/op
ClientPb.listUser                         avgt       3   5.137 ± 1.628   ms/op
ClientPb.createUser                     sample  216194   4.436 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.802           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.096           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.521           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.324           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.585           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.592           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.178           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.472           ms/op
ClientPb.existUser                      sample  225230   4.264 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.247           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.242           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.897           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.249           ms/op
ClientPb.existUser:existUser·p0.9999    sample          39.191           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.878           ms/op
ClientPb.getUser                        sample  214835   4.465 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.956           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.603           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.578           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.044           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.630           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.440           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.339           ms/op
ClientPb.listUser                       sample  183167   5.239 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.909           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.611           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.864           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.568           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.069           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.648           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.045           ms/op
