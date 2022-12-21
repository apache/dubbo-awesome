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
# Warmup Iteration   1: 2.213 ops/ms
# Warmup Iteration   2: 6.023 ops/ms
# Warmup Iteration   3: 8.630 ops/ms
Iteration   1: 9.416 ops/ms
Iteration   2: 9.393 ops/ms
Iteration   3: 9.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.466 ±(99.9%) 1.971 ops/ms [Average]
  (min, avg, max) = (9.393, 9.466, 9.590), stdev = 0.108
  CI (99.9%): [7.495, 11.438] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.571 ops/ms
# Warmup Iteration   2: 9.045 ops/ms
# Warmup Iteration   3: 9.608 ops/ms
Iteration   1: 10.134 ops/ms
Iteration   2: 9.664 ops/ms
Iteration   3: 9.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.891 ±(99.9%) 4.295 ops/ms [Average]
  (min, avg, max) = (9.664, 9.891, 10.134), stdev = 0.235
  CI (99.9%): [5.596, 14.186] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.366 ops/ms
# Warmup Iteration   2: 8.650 ops/ms
# Warmup Iteration   3: 8.965 ops/ms
Iteration   1: 9.505 ops/ms
Iteration   2: 9.822 ops/ms
Iteration   3: 9.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.546 ±(99.9%) 4.716 ops/ms [Average]
  (min, avg, max) = (9.310, 9.546, 9.822), stdev = 0.258
  CI (99.9%): [4.830, 14.262] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.197 ops/ms
# Warmup Iteration   2: 7.218 ops/ms
# Warmup Iteration   3: 7.638 ops/ms
Iteration   1: 7.724 ops/ms
Iteration   2: 7.956 ops/ms
Iteration   3: 7.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.879 ±(99.9%) 2.440 ops/ms [Average]
  (min, avg, max) = (7.724, 7.879, 7.956), stdev = 0.134
  CI (99.9%): [5.439, 10.319] (assumes normal distribution)


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
# Warmup Iteration   1: 8.914 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.876 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.007 ms/op
Iteration   1: 3.362 ±(99.9%) 0.010 ms/op
Iteration   2: 3.402 ±(99.9%) 0.009 ms/op
Iteration   3: 3.354 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.372 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (3.354, 3.372, 3.402), stdev = 0.026
  CI (99.9%): [2.901, 3.844] (assumes normal distribution)


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
# Warmup Iteration   1: 9.499 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.315 ±(99.9%) 0.009 ms/op
Iteration   1: 3.346 ±(99.9%) 0.009 ms/op
Iteration   2: 3.306 ±(99.9%) 0.005 ms/op
Iteration   3: 3.409 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.354 ±(99.9%) 0.948 ms/op [Average]
  (min, avg, max) = (3.306, 3.354, 3.409), stdev = 0.052
  CI (99.9%): [2.406, 4.302] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.493 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.003 ms/op
Iteration   1: 3.340 ±(99.9%) 0.010 ms/op
Iteration   2: 3.368 ±(99.9%) 0.007 ms/op
Iteration   3: 3.493 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.400 ±(99.9%) 1.484 ms/op [Average]
  (min, avg, max) = (3.340, 3.400, 3.493), stdev = 0.081
  CI (99.9%): [1.916, 4.885] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.652 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.422 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.255 ±(99.9%) 0.006 ms/op
Iteration   1: 3.973 ±(99.9%) 0.012 ms/op
Iteration   2: 4.034 ±(99.9%) 0.013 ms/op
Iteration   3: 4.043 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.017 ±(99.9%) 0.691 ms/op [Average]
  (min, avg, max) = (3.973, 4.017, 4.043), stdev = 0.038
  CI (99.9%): [3.326, 4.708] (assumes normal distribution)


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
# Warmup Iteration   1: 9.876 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.035 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.010 ms/op
Iteration   1: 3.339 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.391 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.560 ms/op
                 createUser·p0.999:  22.151 ms/op
                 createUser·p0.9999: 25.325 ms/op
                 createUser·p1.00:   26.673 ms/op

Iteration   2: 3.564 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.233 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  22.888 ms/op
                 createUser·p0.9999: 25.461 ms/op
                 createUser·p1.00:   25.985 ms/op

Iteration   3: 3.503 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  18.612 ms/op
                 createUser·p0.9999: 26.570 ms/op
                 createUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276913
  mean =      3.466 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8947 
    [ 2.500,  5.000) = 260802 
    [ 5.000,  7.500) = 6294 
    [ 7.500, 10.000) = 442 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 145 
    [25.000, 27.500) = 68 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     20.709 ms/op
     p(99.9900) =     25.962 ms/op
     p(99.9990) =     27.205 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.948 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.565 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.350 ±(99.9%) 0.010 ms/op
Iteration   1: 3.295 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  11.253 ms/op
                 existUser·p0.9999: 27.076 ms/op
                 existUser·p1.00:   27.918 ms/op

Iteration   2: 3.314 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.577 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  12.214 ms/op
                 existUser·p0.9999: 28.869 ms/op
                 existUser·p1.00:   29.819 ms/op

Iteration   3: 3.241 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.307 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  10.034 ms/op
                 existUser·p0.9999: 30.053 ms/op
                 existUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292141
  mean =      3.283 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14279 
    [ 2.500,  5.000) = 273606 
    [ 5.000,  7.500) = 3335 
    [ 7.500, 10.000) = 525 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 85 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     12.105 ms/op
     p(99.9900) =     29.189 ms/op
     p(99.9990) =     30.628 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 8.822 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.009 ms/op
Iteration   1: 3.504 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  20.529 ms/op
                 getUser·p0.9999: 22.802 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   2: 3.430 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.567 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.942 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  21.785 ms/op
                 getUser·p0.9999: 25.996 ms/op
                 getUser·p1.00:   27.460 ms/op

Iteration   3: 3.428 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  19.272 ms/op
                 getUser·p0.9999: 27.602 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277828
  mean =      3.454 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9353 
    [ 2.500,  5.000) = 256942 
    [ 5.000,  7.500) = 10293 
    [ 7.500, 10.000) = 727 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     26.662 ms/op
     p(99.9990) =     28.268 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 9.468 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.379 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.170 ±(99.9%) 0.014 ms/op
Iteration   1: 4.118 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.886 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  18.326 ms/op
                 listUser·p0.9999: 24.190 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   2: 3.953 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 19.530 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   3: 3.927 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.731 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  16.744 ms/op
                 listUser·p0.9999: 22.830 ms/op
                 listUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240164
  mean =      3.998 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 230035 
    [ 5.000,  7.500) = 8037 
    [ 7.500, 10.000) = 1232 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 186 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.236 ms/op
     p(99.9000) =     16.450 ms/op
     p(99.9900) =     23.099 ms/op
     p(99.9990) =     24.596 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.466 ± 1.971  ops/ms
ClientPb.existUser                       thrpt       3   9.891 ± 4.295  ops/ms
ClientPb.getUser                         thrpt       3   9.546 ± 4.716  ops/ms
ClientPb.listUser                        thrpt       3   7.879 ± 2.440  ops/ms
ClientPb.createUser                       avgt       3   3.372 ± 0.472   ms/op
ClientPb.existUser                        avgt       3   3.354 ± 0.948   ms/op
ClientPb.getUser                          avgt       3   3.400 ± 1.484   ms/op
ClientPb.listUser                         avgt       3   4.017 ± 0.691   ms/op
ClientPb.createUser                     sample  276913   3.466 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.114           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.100           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.522           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.709           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.962           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.951           ms/op
ClientPb.existUser                      sample  292141   3.283 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.990           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.920           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.513           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.105           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.189           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.752           ms/op
ClientPb.getUser                        sample  277828   3.454 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.051           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.314           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.760           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.275           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.054           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.662           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.574           ms/op
ClientPb.listUser                       sample  240164   3.998 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.049           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.813           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.236           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.450           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.099           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.773           ms/op
