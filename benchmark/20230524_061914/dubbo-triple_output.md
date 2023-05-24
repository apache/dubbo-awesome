# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.157 ops/ms
# Warmup Iteration   2: 2.538 ops/ms
# Warmup Iteration   3: 4.937 ops/ms
Iteration   1: 5.306 ops/ms
Iteration   2: 5.762 ops/ms
Iteration   3: 5.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.622 ±(99.9%) 5.007 ops/ms [Average]
  (min, avg, max) = (5.306, 5.622, 5.797), stdev = 0.274
  CI (99.9%): [0.615, 10.628] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.937 ops/ms
# Warmup Iteration   2: 4.939 ops/ms
# Warmup Iteration   3: 5.714 ops/ms
Iteration   1: 5.923 ops/ms
Iteration   2: 6.029 ops/ms
Iteration   3: 6.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.054 ±(99.9%) 2.628 ops/ms [Average]
  (min, avg, max) = (5.923, 6.054, 6.208), stdev = 0.144
  CI (99.9%): [3.425, 8.682] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.657 ops/ms
# Warmup Iteration   2: 4.704 ops/ms
# Warmup Iteration   3: 6.049 ops/ms
Iteration   1: 5.721 ops/ms
Iteration   2: 5.955 ops/ms
Iteration   3: 6.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.897 ±(99.9%) 2.833 ops/ms [Average]
  (min, avg, max) = (5.721, 5.897, 6.015), stdev = 0.155
  CI (99.9%): [3.064, 8.730] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.583 ops/ms
# Warmup Iteration   2: 3.712 ops/ms
# Warmup Iteration   3: 4.949 ops/ms
Iteration   1: 5.227 ops/ms
Iteration   2: 5.207 ops/ms
Iteration   3: 5.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.177 ±(99.9%) 1.276 ops/ms [Average]
  (min, avg, max) = (5.097, 5.177, 5.227), stdev = 0.070
  CI (99.9%): [3.901, 6.452] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 16.599 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 6.161 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.639 ±(99.9%) 0.010 ms/op
Iteration   1: 5.351 ±(99.9%) 0.014 ms/op
Iteration   2: 5.342 ±(99.9%) 0.009 ms/op
Iteration   3: 5.359 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.351 ±(99.9%) 0.155 ms/op [Average]
  (min, avg, max) = (5.342, 5.351, 5.359), stdev = 0.008
  CI (99.9%): [5.196, 5.505] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 15.666 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.063 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.159 ±(99.9%) 0.019 ms/op
Iteration   1: 5.390 ±(99.9%) 0.011 ms/op
Iteration   2: 5.423 ±(99.9%) 0.013 ms/op
Iteration   3: 5.590 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.467 ±(99.9%) 1.952 ms/op [Average]
  (min, avg, max) = (5.390, 5.467, 5.590), stdev = 0.107
  CI (99.9%): [3.515, 7.419] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 17.816 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 6.676 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.642 ±(99.9%) 0.015 ms/op
Iteration   1: 5.680 ±(99.9%) 0.015 ms/op
Iteration   2: 5.783 ±(99.9%) 0.010 ms/op
Iteration   3: 5.319 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.594 ±(99.9%) 4.449 ms/op [Average]
  (min, avg, max) = (5.319, 5.594, 5.783), stdev = 0.244
  CI (99.9%): [1.145, 10.043] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 17.655 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 7.964 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.251 ±(99.9%) 0.022 ms/op
Iteration   1: 6.008 ±(99.9%) 0.020 ms/op
Iteration   2: 6.553 ±(99.9%) 0.013 ms/op
Iteration   3: 6.305 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.289 ±(99.9%) 4.973 ms/op [Average]
  (min, avg, max) = (6.008, 6.289, 6.553), stdev = 0.273
  CI (99.9%): [1.315, 11.262] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 19.082 ±(99.9%) 0.341 ms/op
# Warmup Iteration   2: 7.036 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.164 ±(99.9%) 0.030 ms/op
Iteration   1: 5.721 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   1.548 ms/op
                 createUser·p0.50:   5.325 ms/op
                 createUser·p0.90:   7.389 ms/op
                 createUser·p0.95:   8.749 ms/op
                 createUser·p0.99:   12.340 ms/op
                 createUser·p0.999:  24.791 ms/op
                 createUser·p0.9999: 37.055 ms/op
                 createUser·p1.00:   38.470 ms/op

Iteration   2: 5.568 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.048 ms/op
                 createUser·p0.50:   5.300 ms/op
                 createUser·p0.90:   6.947 ms/op
                 createUser·p0.95:   7.766 ms/op
                 createUser·p0.99:   10.563 ms/op
                 createUser·p0.999:  25.625 ms/op
                 createUser·p0.9999: 36.013 ms/op
                 createUser·p1.00:   37.290 ms/op

Iteration   3: 5.453 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   5.210 ms/op
                 createUser·p0.90:   6.767 ms/op
                 createUser·p0.95:   7.676 ms/op
                 createUser·p0.99:   10.745 ms/op
                 createUser·p0.999:  17.614 ms/op
                 createUser·p0.9999: 31.782 ms/op
                 createUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171926
  mean =      5.579 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 62264 
    [ 5.000,  7.500) = 97483 
    [ 7.500, 10.000) = 9042 
    [10.000, 12.500) = 2066 
    [12.500, 15.000) = 510 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      5.284 ms/op
     p(90.0000) =      7.012 ms/op
     p(95.0000) =      8.077 ms/op
     p(99.0000) =     11.305 ms/op
     p(99.9000) =     22.610 ms/op
     p(99.9900) =     36.032 ms/op
     p(99.9990) =     38.422 ms/op
     p(99.9999) =     38.470 ms/op
    p(100.0000) =     38.470 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 15.941 ±(99.9%) 0.235 ms/op
# Warmup Iteration   2: 6.186 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.604 ±(99.9%) 0.023 ms/op
Iteration   1: 5.736 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   5.276 ms/op
                 existUser·p0.90:   7.725 ms/op
                 existUser·p0.95:   8.847 ms/op
                 existUser·p0.99:   11.895 ms/op
                 existUser·p0.999:  24.838 ms/op
                 existUser·p0.9999: 33.610 ms/op
                 existUser·p1.00:   34.669 ms/op

Iteration   2: 5.522 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.359 ms/op
                 existUser·p0.50:   5.136 ms/op
                 existUser·p0.90:   7.053 ms/op
                 existUser·p0.95:   8.266 ms/op
                 existUser·p0.99:   11.862 ms/op
                 existUser·p0.999:  18.949 ms/op
                 existUser·p0.9999: 32.552 ms/op
                 existUser·p1.00:   38.207 ms/op

Iteration   3: 5.332 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.937 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   6.595 ms/op
                 existUser·p0.95:   7.766 ms/op
                 existUser·p0.99:   10.813 ms/op
                 existUser·p0.999:  31.326 ms/op
                 existUser·p0.9999: 34.603 ms/op
                 existUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 173685
  mean =      5.525 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 75342 
    [ 5.000,  7.500) = 84101 
    [ 7.500, 10.000) = 10662 
    [10.000, 12.500) = 2440 
    [12.500, 15.000) = 663 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 60 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      7.143 ms/op
     p(95.0000) =      8.348 ms/op
     p(99.0000) =     11.600 ms/op
     p(99.9000) =     19.573 ms/op
     p(99.9900) =     34.227 ms/op
     p(99.9990) =     38.111 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.485 ±(99.9%) 0.359 ms/op
# Warmup Iteration   2: 7.261 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.075 ±(99.9%) 0.028 ms/op
Iteration   1: 5.897 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.630 ms/op
                 getUser·p0.50:   5.456 ms/op
                 getUser·p0.90:   7.455 ms/op
                 getUser·p0.95:   9.372 ms/op
                 getUser·p0.99:   13.664 ms/op
                 getUser·p0.999:  24.297 ms/op
                 getUser·p0.9999: 29.084 ms/op
                 getUser·p1.00:   30.212 ms/op

Iteration   2: 5.580 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.122 ms/op
                 getUser·p0.50:   5.210 ms/op
                 getUser·p0.90:   7.102 ms/op
                 getUser·p0.95:   8.405 ms/op
                 getUser·p0.99:   11.518 ms/op
                 getUser·p0.999:  28.299 ms/op
                 getUser·p0.9999: 38.652 ms/op
                 getUser·p1.00:   41.943 ms/op

Iteration   3: 5.621 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.028 ms/op
                 getUser·p0.50:   5.276 ms/op
                 getUser·p0.90:   7.086 ms/op
                 getUser·p0.95:   8.233 ms/op
                 getUser·p0.99:   11.190 ms/op
                 getUser·p0.999:  28.229 ms/op
                 getUser·p0.9999: 33.882 ms/op
                 getUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 168577
  mean =      5.696 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 54975 
    [ 5.000, 10.000) = 109440 
    [10.000, 15.000) = 3590 
    [15.000, 20.000) = 348 
    [20.000, 25.000) = 47 
    [25.000, 30.000) = 91 
    [30.000, 35.000) = 73 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      5.317 ms/op
     p(90.0000) =      7.193 ms/op
     p(95.0000) =      8.585 ms/op
     p(99.0000) =     12.255 ms/op
     p(99.9000) =     25.464 ms/op
     p(99.9900) =     34.537 ms/op
     p(99.9990) =     40.100 ms/op
     p(99.9999) =     41.943 ms/op
    p(100.0000) =     41.943 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.568 ±(99.9%) 0.354 ms/op
# Warmup Iteration   2: 8.823 ±(99.9%) 0.065 ms/op
# Warmup Iteration   3: 7.100 ±(99.9%) 0.031 ms/op
Iteration   1: 6.731 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.052 ms/op
                 listUser·p0.50:   6.308 ms/op
                 listUser·p0.90:   8.421 ms/op
                 listUser·p0.95:   9.798 ms/op
                 listUser·p0.99:   13.074 ms/op
                 listUser·p0.999:  26.247 ms/op
                 listUser·p0.9999: 29.753 ms/op
                 listUser·p1.00:   30.900 ms/op

Iteration   2: 6.446 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.105 ms/op
                 listUser·p0.50:   6.136 ms/op
                 listUser·p0.90:   7.594 ms/op
                 listUser·p0.95:   8.782 ms/op
                 listUser·p0.99:   12.548 ms/op
                 listUser·p0.999:  31.011 ms/op
                 listUser·p0.9999: 33.165 ms/op
                 listUser·p1.00:   34.013 ms/op

Iteration   3: 6.456 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.314 ms/op
                 listUser·p0.50:   6.013 ms/op
                 listUser·p0.90:   8.061 ms/op
                 listUser·p0.95:   9.765 ms/op
                 listUser·p0.99:   12.927 ms/op
                 listUser·p0.999:  28.273 ms/op
                 listUser·p0.9999: 31.855 ms/op
                 listUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 146694
  mean =      6.542 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 6749 
    [ 5.000,  7.500) = 118506 
    [ 7.500, 10.000) = 15575 
    [10.000, 12.500) = 4202 
    [12.500, 15.000) = 966 
    [15.000, 17.500) = 253 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 89 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.052 ms/op
     p(50.0000) =      6.144 ms/op
     p(90.0000) =      8.036 ms/op
     p(95.0000) =      9.454 ms/op
     p(99.0000) =     12.911 ms/op
     p(99.9000) =     28.538 ms/op
     p(99.9900) =     32.517 ms/op
     p(99.9990) =     33.753 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.622 ± 5.007  ops/ms
ClientPb.existUser                       thrpt       3   6.054 ± 2.628  ops/ms
ClientPb.getUser                         thrpt       3   5.897 ± 2.833  ops/ms
ClientPb.listUser                        thrpt       3   5.177 ± 1.276  ops/ms
ClientPb.createUser                       avgt       3   5.351 ± 0.155   ms/op
ClientPb.existUser                        avgt       3   5.467 ± 1.952   ms/op
ClientPb.getUser                          avgt       3   5.594 ± 4.449   ms/op
ClientPb.listUser                         avgt       3   6.289 ± 4.973   ms/op
ClientPb.createUser                     sample  171926   5.579 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.962           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.284           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.012           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.077           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.305           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.610           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.032           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.470           ms/op
ClientPb.existUser                      sample  173685   5.525 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.270           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.120           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.143           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.348           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.600           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.573           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.227           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.207           ms/op
ClientPb.getUser                        sample  168577   5.696 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.122           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.317           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.193           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.585           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.255           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.464           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.537           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.943           ms/op
ClientPb.listUser                       sample  146694   6.542 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           3.052           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.144           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.036           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.454           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.911           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.538           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.517           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.013           ms/op
