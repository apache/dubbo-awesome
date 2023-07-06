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
# Warmup Iteration   1: 2.369 ops/ms
# Warmup Iteration   2: 5.971 ops/ms
# Warmup Iteration   3: 8.855 ops/ms
Iteration   1: 9.484 ops/ms
Iteration   2: 9.995 ops/ms
Iteration   3: 9.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.734 ±(99.9%) 4.664 ops/ms [Average]
  (min, avg, max) = (9.484, 9.734, 9.995), stdev = 0.256
  CI (99.9%): [5.071, 14.398] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.955 ops/ms
# Warmup Iteration   2: 9.341 ops/ms
# Warmup Iteration   3: 10.158 ops/ms
Iteration   1: 9.976 ops/ms
Iteration   2: 10.272 ops/ms
Iteration   3: 10.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.109 ±(99.9%) 2.740 ops/ms [Average]
  (min, avg, max) = (9.976, 10.109, 10.272), stdev = 0.150
  CI (99.9%): [7.369, 12.849] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.304 ops/ms
# Warmup Iteration   2: 8.049 ops/ms
# Warmup Iteration   3: 9.716 ops/ms
Iteration   1: 9.941 ops/ms
Iteration   2: 10.017 ops/ms
Iteration   3: 9.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.938 ±(99.9%) 1.464 ops/ms [Average]
  (min, avg, max) = (9.856, 9.938, 10.017), stdev = 0.080
  CI (99.9%): [8.474, 11.402] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.313 ops/ms
# Warmup Iteration   2: 7.940 ops/ms
# Warmup Iteration   3: 8.327 ops/ms
Iteration   1: 8.600 ops/ms
Iteration   2: 8.351 ops/ms
Iteration   3: 8.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.515 ±(99.9%) 2.582 ops/ms [Average]
  (min, avg, max) = (8.351, 8.515, 8.600), stdev = 0.142
  CI (99.9%): [5.932, 11.097] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.016 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.402 ±(99.9%) 0.008 ms/op
Iteration   1: 3.416 ±(99.9%) 0.004 ms/op
Iteration   2: 3.222 ±(99.9%) 0.008 ms/op
Iteration   3: 3.277 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.305 ±(99.9%) 1.823 ms/op [Average]
  (min, avg, max) = (3.222, 3.305, 3.416), stdev = 0.100
  CI (99.9%): [1.481, 5.128] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.892 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.003 ms/op
Iteration   1: 3.156 ±(99.9%) 0.004 ms/op
Iteration   2: 3.125 ±(99.9%) 0.003 ms/op
Iteration   3: 3.061 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.114 ±(99.9%) 0.878 ms/op [Average]
  (min, avg, max) = (3.061, 3.114, 3.156), stdev = 0.048
  CI (99.9%): [2.236, 3.992] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.091 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.797 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.003 ms/op
Iteration   1: 3.357 ±(99.9%) 0.003 ms/op
Iteration   2: 3.298 ±(99.9%) 0.008 ms/op
Iteration   3: 3.428 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.361 ±(99.9%) 1.186 ms/op [Average]
  (min, avg, max) = (3.298, 3.361, 3.428), stdev = 0.065
  CI (99.9%): [2.175, 4.547] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.191 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.212 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.903 ±(99.9%) 0.007 ms/op
Iteration   1: 3.761 ±(99.9%) 0.011 ms/op
Iteration   2: 3.723 ±(99.9%) 0.011 ms/op
Iteration   3: 3.816 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.767 ±(99.9%) 0.854 ms/op [Average]
  (min, avg, max) = (3.723, 3.767, 3.816), stdev = 0.047
  CI (99.9%): [2.913, 4.621] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.569 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.010 ms/op
Iteration   1: 3.299 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  9.863 ms/op
                 createUser·p0.9999: 26.070 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   2: 3.212 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.442 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  20.330 ms/op
                 createUser·p0.9999: 27.494 ms/op
                 createUser·p1.00:   27.918 ms/op

Iteration   3: 3.271 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.001 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  15.417 ms/op
                 createUser·p0.9999: 20.651 ms/op
                 createUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294339
  mean =      3.260 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17665 
    [ 2.500,  5.000) = 270629 
    [ 5.000,  7.500) = 4973 
    [ 7.500, 10.000) = 567 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     17.312 ms/op
     p(99.9900) =     26.256 ms/op
     p(99.9990) =     27.887 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.831 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.009 ms/op
Iteration   1: 3.084 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.491 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  8.847 ms/op
                 existUser·p0.9999: 21.695 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   2: 3.153 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  9.550 ms/op
                 existUser·p0.9999: 22.234 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   3: 3.155 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.673 ms/op
                 existUser·p0.999:  9.355 ms/op
                 existUser·p0.9999: 20.447 ms/op
                 existUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306472
  mean =      3.131 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18864 
    [ 2.500,  5.000) = 282383 
    [ 5.000,  7.500) = 4663 
    [ 7.500, 10.000) = 272 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      9.340 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     23.032 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.323 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.010 ms/op
Iteration   1: 3.323 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  17.414 ms/op
                 getUser·p0.9999: 21.365 ms/op
                 getUser·p1.00:   22.315 ms/op

Iteration   2: 3.185 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.208 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  12.636 ms/op
                 getUser·p0.9999: 22.640 ms/op
                 getUser·p1.00:   23.364 ms/op

Iteration   3: 3.161 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.460 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   5.407 ms/op
                 getUser·p0.999:  14.336 ms/op
                 getUser·p0.9999: 22.049 ms/op
                 getUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297733
  mean =      3.222 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15352 
    [ 2.500,  5.000) = 275660 
    [ 5.000,  7.500) = 5523 
    [ 7.500, 10.000) = 657 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 161 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     15.497 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     23.075 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.448 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.061 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.817 ±(99.9%) 0.012 ms/op
Iteration   1: 3.817 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.618 ms/op
                 listUser·p0.999:  17.662 ms/op
                 listUser·p0.9999: 19.591 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   2: 3.776 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.083 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.287 ms/op
                 listUser·p0.9999: 19.580 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   3: 3.770 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.923 ms/op
                 listUser·p0.999:  12.967 ms/op
                 listUser·p0.9999: 14.345 ms/op
                 listUser·p1.00:   14.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253342
  mean =      3.788 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 96 
    [ 2.500,  5.000) = 245227 
    [ 5.000,  7.500) = 5912 
    [ 7.500, 10.000) = 1507 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 313 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     19.497 ms/op
     p(99.9990) =     21.236 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.734 ± 4.664  ops/ms
ClientPb.existUser                       thrpt       3  10.109 ± 2.740  ops/ms
ClientPb.getUser                         thrpt       3   9.938 ± 1.464  ops/ms
ClientPb.listUser                        thrpt       3   8.515 ± 2.582  ops/ms
ClientPb.createUser                       avgt       3   3.305 ± 1.823   ms/op
ClientPb.existUser                        avgt       3   3.114 ± 0.878   ms/op
ClientPb.getUser                          avgt       3   3.361 ± 1.186   ms/op
ClientPb.listUser                         avgt       3   3.767 ± 0.854   ms/op
ClientPb.createUser                     sample  294339   3.260 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.001           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.613           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.710           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.312           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.256           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.918           ms/op
ClientPb.existUser                      sample  306472   3.131 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.803           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.400           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.513           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.340           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.791           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.200           ms/op
ClientPb.getUser                        sample  297733   3.222 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.208           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.580           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.177           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.497           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.053           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.364           ms/op
ClientPb.listUser                       sample  253342   3.788 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.266           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.621           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.137           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.201           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.926           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.497           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.086           ms/op
