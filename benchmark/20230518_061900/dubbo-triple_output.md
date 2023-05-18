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
# Warmup Iteration   1: 2.549 ops/ms
# Warmup Iteration   2: 6.140 ops/ms
# Warmup Iteration   3: 8.941 ops/ms
Iteration   1: 10.038 ops/ms
Iteration   2: 9.887 ops/ms
Iteration   3: 9.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.894 ±(99.9%) 2.576 ops/ms [Average]
  (min, avg, max) = (9.756, 9.894, 10.038), stdev = 0.141
  CI (99.9%): [7.318, 12.470] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.678 ops/ms
# Warmup Iteration   2: 9.807 ops/ms
# Warmup Iteration   3: 10.015 ops/ms
Iteration   1: 10.009 ops/ms
Iteration   2: 10.440 ops/ms
Iteration   3: 10.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.315 ±(99.9%) 4.856 ops/ms [Average]
  (min, avg, max) = (10.009, 10.315, 10.496), stdev = 0.266
  CI (99.9%): [5.459, 15.171] (assumes normal distribution)


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
# Warmup Iteration   1: 3.347 ops/ms
# Warmup Iteration   2: 8.852 ops/ms
# Warmup Iteration   3: 9.817 ops/ms
Iteration   1: 9.766 ops/ms
Iteration   2: 10.436 ops/ms
Iteration   3: 10.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.077 ±(99.9%) 6.159 ops/ms [Average]
  (min, avg, max) = (9.766, 10.077, 10.436), stdev = 0.338
  CI (99.9%): [3.918, 16.236] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.371 ops/ms
# Warmup Iteration   2: 7.881 ops/ms
# Warmup Iteration   3: 8.355 ops/ms
Iteration   1: 8.344 ops/ms
Iteration   2: 8.610 ops/ms
Iteration   3: 8.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.562 ±(99.9%) 3.627 ops/ms [Average]
  (min, avg, max) = (8.344, 8.562, 8.733), stdev = 0.199
  CI (99.9%): [4.936, 12.189] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.759 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.504 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.365 ±(99.9%) 0.004 ms/op
Iteration   1: 3.140 ±(99.9%) 0.006 ms/op
Iteration   2: 3.080 ±(99.9%) 0.008 ms/op
Iteration   3: 3.103 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.108 ±(99.9%) 0.559 ms/op [Average]
  (min, avg, max) = (3.080, 3.108, 3.140), stdev = 0.031
  CI (99.9%): [2.549, 3.667] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 6.573 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
Iteration   1: 3.022 ±(99.9%) 0.007 ms/op
Iteration   2: 3.005 ±(99.9%) 0.008 ms/op
Iteration   3: 3.143 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.056 ±(99.9%) 1.374 ms/op [Average]
  (min, avg, max) = (3.005, 3.056, 3.143), stdev = 0.075
  CI (99.9%): [1.683, 4.430] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.130 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.522 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.003 ms/op
Iteration   1: 3.115 ±(99.9%) 0.007 ms/op
Iteration   2: 3.214 ±(99.9%) 0.007 ms/op
Iteration   3: 3.197 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.176 ±(99.9%) 0.972 ms/op [Average]
  (min, avg, max) = (3.115, 3.176, 3.214), stdev = 0.053
  CI (99.9%): [2.203, 4.148] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.763 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.983 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.006 ms/op
Iteration   1: 3.645 ±(99.9%) 0.013 ms/op
Iteration   2: 3.669 ±(99.9%) 0.011 ms/op
Iteration   3: 3.807 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.707 ±(99.9%) 1.595 ms/op [Average]
  (min, avg, max) = (3.645, 3.707, 3.807), stdev = 0.087
  CI (99.9%): [2.112, 5.301] (assumes normal distribution)


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
# Warmup Iteration   1: 7.364 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.899 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.011 ms/op
Iteration   1: 3.172 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.305 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  17.324 ms/op
                 createUser·p0.9999: 23.656 ms/op
                 createUser·p1.00:   25.002 ms/op

Iteration   2: 3.230 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  12.178 ms/op
                 createUser·p0.9999: 21.398 ms/op
                 createUser·p1.00:   22.184 ms/op

Iteration   3: 3.195 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.194 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  17.957 ms/op
                 createUser·p0.9999: 28.901 ms/op
                 createUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299693
  mean =      3.199 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26548 
    [ 2.500,  5.000) = 268402 
    [ 5.000,  7.500) = 3876 
    [ 7.500, 10.000) = 389 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     17.443 ms/op
     p(99.9900) =     27.297 ms/op
     p(99.9990) =     29.459 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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
# Warmup Iteration   1: 6.961 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.311 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
Iteration   1: 3.251 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.041 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  15.729 ms/op
                 existUser·p0.9999: 20.120 ms/op
                 existUser·p1.00:   20.775 ms/op

Iteration   2: 3.148 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  15.073 ms/op
                 existUser·p0.9999: 23.391 ms/op
                 existUser·p1.00:   23.921 ms/op

Iteration   3: 3.194 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.212 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   6.390 ms/op
                 existUser·p0.999:  14.336 ms/op
                 existUser·p0.9999: 23.230 ms/op
                 existUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300096
  mean =      3.197 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17730 
    [ 2.500,  5.000) = 275373 
    [ 5.000,  7.500) = 6004 
    [ 7.500, 10.000) = 465 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     14.369 ms/op
     p(99.9900) =     22.903 ms/op
     p(99.9990) =     23.888 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 7.231 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.403 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.008 ms/op
Iteration   1: 3.238 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.147 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  17.367 ms/op
                 getUser·p0.9999: 32.244 ms/op
                 getUser·p1.00:   33.194 ms/op

Iteration   2: 3.199 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.249 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  10.573 ms/op
                 getUser·p0.9999: 27.100 ms/op
                 getUser·p1.00:   29.852 ms/op

Iteration   3: 3.389 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.708 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  14.257 ms/op
                 getUser·p0.9999: 19.483 ms/op
                 getUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293012
  mean =      3.273 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15659 
    [ 2.500,  5.000) = 268207 
    [ 5.000,  7.500) = 8138 
    [ 7.500, 10.000) = 541 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     15.532 ms/op
     p(99.9900) =     30.900 ms/op
     p(99.9990) =     33.002 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


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
# Warmup Iteration   1: 9.309 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.740 ±(99.9%) 0.012 ms/op
Iteration   1: 3.719 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.765 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  14.778 ms/op
                 listUser·p0.9999: 17.839 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   2: 3.749 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.522 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  12.563 ms/op
                 listUser·p0.9999: 16.646 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   3: 3.811 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.453 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.329 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  13.435 ms/op
                 listUser·p0.9999: 17.289 ms/op
                 listUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255097
  mean =      3.759 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 58 
    [ 2.500,  3.750) = 180890 
    [ 3.750,  5.000) = 66787 
    [ 5.000,  6.250) = 2581 
    [ 6.250,  7.500) = 2881 
    [ 7.500,  8.750) = 866 
    [ 8.750, 10.000) = 329 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 206 
    [12.500, 13.750) = 159 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 123 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.453 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     12.927 ms/op
     p(99.9900) =     17.367 ms/op
     p(99.9990) =     18.640 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.894 ± 2.576  ops/ms
ClientPb.existUser                       thrpt       3  10.315 ± 4.856  ops/ms
ClientPb.getUser                         thrpt       3  10.077 ± 6.159  ops/ms
ClientPb.listUser                        thrpt       3   8.562 ± 3.627  ops/ms
ClientPb.createUser                       avgt       3   3.108 ± 0.559   ms/op
ClientPb.existUser                        avgt       3   3.056 ± 1.374   ms/op
ClientPb.getUser                          avgt       3   3.176 ± 0.972   ms/op
ClientPb.listUser                         avgt       3   3.707 ± 1.595   ms/op
ClientPb.createUser                     sample  299693   3.199 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.108           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.445           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.341           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.443           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.297           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.557           ms/op
ClientPb.existUser                      sample  300096   3.197 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.664           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.912           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.369           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.903           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.216           ms/op
ClientPb.getUser                        sample  293012   3.273 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.147           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.707           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.136           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.532           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.900           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.194           ms/op
ClientPb.listUser                       sample  255097   3.759 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.453           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.021           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.927           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.367           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.268           ms/op
