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
# Warmup Iteration   1: 1.151 ops/ms
# Warmup Iteration   2: 2.535 ops/ms
# Warmup Iteration   3: 5.220 ops/ms
Iteration   1: 5.997 ops/ms
Iteration   2: 5.879 ops/ms
Iteration   3: 6.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.039 ±(99.9%) 3.379 ops/ms [Average]
  (min, avg, max) = (5.879, 6.039, 6.242), stdev = 0.185
  CI (99.9%): [2.660, 9.419] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.605 ops/ms
# Warmup Iteration   2: 5.245 ops/ms
# Warmup Iteration   3: 6.084 ops/ms
Iteration   1: 6.323 ops/ms
Iteration   2: 6.074 ops/ms
Iteration   3: 5.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.116 ±(99.9%) 3.468 ops/ms [Average]
  (min, avg, max) = (5.950, 6.116, 6.323), stdev = 0.190
  CI (99.9%): [2.648, 9.583] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.679 ops/ms
# Warmup Iteration   2: 4.807 ops/ms
# Warmup Iteration   3: 6.019 ops/ms
Iteration   1: 5.998 ops/ms
Iteration   2: 6.204 ops/ms
Iteration   3: 6.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.074 ±(99.9%) 2.068 ops/ms [Average]
  (min, avg, max) = (5.998, 6.074, 6.204), stdev = 0.113
  CI (99.9%): [4.006, 8.142] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.526 ops/ms
# Warmup Iteration   2: 4.234 ops/ms
# Warmup Iteration   3: 4.993 ops/ms
Iteration   1: 5.068 ops/ms
Iteration   2: 5.031 ops/ms
Iteration   3: 5.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.061 ±(99.9%) 0.505 ops/ms [Average]
  (min, avg, max) = (5.031, 5.061, 5.085), stdev = 0.028
  CI (99.9%): [4.556, 5.566] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 16.746 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 6.454 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.694 ±(99.9%) 0.005 ms/op
Iteration   1: 5.396 ±(99.9%) 0.009 ms/op
Iteration   2: 5.241 ±(99.9%) 0.008 ms/op
Iteration   3: 5.028 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.221 ±(99.9%) 3.373 ms/op [Average]
  (min, avg, max) = (5.028, 5.221, 5.396), stdev = 0.185
  CI (99.9%): [1.849, 8.594] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 15.257 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.635 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.256 ±(99.9%) 0.007 ms/op
Iteration   1: 5.138 ±(99.9%) 0.010 ms/op
Iteration   2: 5.265 ±(99.9%) 0.008 ms/op
Iteration   3: 5.136 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.180 ±(99.9%) 1.350 ms/op [Average]
  (min, avg, max) = (5.136, 5.180, 5.265), stdev = 0.074
  CI (99.9%): [3.830, 6.530] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 15.325 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 6.119 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.264 ±(99.9%) 0.006 ms/op
Iteration   1: 5.363 ±(99.9%) 0.008 ms/op
Iteration   2: 5.729 ±(99.9%) 0.010 ms/op
Iteration   3: 5.402 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.498 ±(99.9%) 3.664 ms/op [Average]
  (min, avg, max) = (5.363, 5.498, 5.729), stdev = 0.201
  CI (99.9%): [1.834, 9.162] (assumes normal distribution)


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
# Warmup Iteration   1: 16.902 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 8.565 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 7.010 ±(99.9%) 0.010 ms/op
Iteration   1: 6.243 ±(99.9%) 0.009 ms/op
Iteration   2: 6.351 ±(99.9%) 0.014 ms/op
Iteration   3: 6.559 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.384 ±(99.9%) 2.930 ms/op [Average]
  (min, avg, max) = (6.243, 6.384, 6.559), stdev = 0.161
  CI (99.9%): [3.455, 9.314] (assumes normal distribution)


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
# Warmup Iteration   1: 16.947 ±(99.9%) 0.299 ms/op
# Warmup Iteration   2: 6.596 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.788 ±(99.9%) 0.029 ms/op
Iteration   1: 5.303 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.573 ms/op
                 createUser·p0.50:   5.054 ms/op
                 createUser·p0.90:   6.487 ms/op
                 createUser·p0.95:   7.250 ms/op
                 createUser·p0.99:   11.197 ms/op
                 createUser·p0.999:  24.347 ms/op
                 createUser·p0.9999: 31.842 ms/op
                 createUser·p1.00:   32.702 ms/op

Iteration   2: 5.241 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.310 ms/op
                 createUser·p0.50:   4.981 ms/op
                 createUser·p0.90:   6.406 ms/op
                 createUser·p0.95:   7.184 ms/op
                 createUser·p0.99:   9.896 ms/op
                 createUser·p0.999:  25.560 ms/op
                 createUser·p0.9999: 30.199 ms/op
                 createUser·p1.00:   32.178 ms/op

Iteration   3: 5.397 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.290 ms/op
                 createUser·p0.50:   5.054 ms/op
                 createUser·p0.90:   6.578 ms/op
                 createUser·p0.95:   7.397 ms/op
                 createUser·p0.99:   11.528 ms/op
                 createUser·p0.999:  34.456 ms/op
                 createUser·p0.9999: 54.728 ms/op
                 createUser·p1.00:   55.247 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 180579
  mean =      5.313 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 87589 
    [ 5.000, 10.000) = 90651 
    [10.000, 15.000) = 1903 
    [15.000, 20.000) = 132 
    [20.000, 25.000) = 43 
    [25.000, 30.000) = 125 
    [30.000, 35.000) = 81 
    [35.000, 40.000) = 22 
    [40.000, 45.000) = 14 
    [45.000, 50.000) = 7 
    [50.000, 55.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.573 ms/op
     p(50.0000) =      5.030 ms/op
     p(90.0000) =      6.488 ms/op
     p(95.0000) =      7.274 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     27.547 ms/op
     p(99.9900) =     49.403 ms/op
     p(99.9990) =     55.194 ms/op
     p(99.9999) =     55.247 ms/op
    p(100.0000) =     55.247 ms/op


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
# Warmup Iteration   1: 16.892 ±(99.9%) 0.260 ms/op
# Warmup Iteration   2: 5.942 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.306 ±(99.9%) 0.020 ms/op
Iteration   1: 5.251 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.142 ms/op
                 existUser·p0.50:   4.989 ms/op
                 existUser·p0.90:   6.365 ms/op
                 existUser·p0.95:   7.455 ms/op
                 existUser·p0.99:   10.502 ms/op
                 existUser·p0.999:  25.530 ms/op
                 existUser·p0.9999: 36.236 ms/op
                 existUser·p1.00:   37.159 ms/op

Iteration   2: 5.355 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.101 ms/op
                 existUser·p0.50:   4.973 ms/op
                 existUser·p0.90:   6.799 ms/op
                 existUser·p0.95:   8.135 ms/op
                 existUser·p0.99:   11.518 ms/op
                 existUser·p0.999:  25.133 ms/op
                 existUser·p0.9999: 28.051 ms/op
                 existUser·p1.00:   28.606 ms/op

Iteration   3: 5.119 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.034 ms/op
                 existUser·p0.50:   4.899 ms/op
                 existUser·p0.90:   6.136 ms/op
                 existUser·p0.95:   6.863 ms/op
                 existUser·p0.99:   10.486 ms/op
                 existUser·p0.999:  17.711 ms/op
                 existUser·p0.9999: 29.024 ms/op
                 existUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 183077
  mean =      5.240 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 96395 
    [ 5.000,  7.500) = 77546 
    [ 7.500, 10.000) = 6310 
    [10.000, 12.500) = 1994 
    [12.500, 15.000) = 438 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      2.034 ms/op
     p(50.0000) =      4.956 ms/op
     p(90.0000) =      6.439 ms/op
     p(95.0000) =      7.487 ms/op
     p(99.0000) =     10.830 ms/op
     p(99.9000) =     20.346 ms/op
     p(99.9900) =     34.386 ms/op
     p(99.9990) =     37.050 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


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
# Warmup Iteration   1: 18.011 ±(99.9%) 0.263 ms/op
# Warmup Iteration   2: 6.994 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 5.657 ±(99.9%) 0.024 ms/op
Iteration   1: 5.478 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.253 ms/op
                 getUser·p0.50:   5.128 ms/op
                 getUser·p0.90:   6.709 ms/op
                 getUser·p0.95:   8.012 ms/op
                 getUser·p0.99:   12.239 ms/op
                 getUser·p0.999:  24.084 ms/op
                 getUser·p0.9999: 41.079 ms/op
                 getUser·p1.00:   42.598 ms/op

Iteration   2: 5.415 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.450 ms/op
                 getUser·p0.50:   5.079 ms/op
                 getUser·p0.90:   6.627 ms/op
                 getUser·p0.95:   8.176 ms/op
                 getUser·p0.99:   11.207 ms/op
                 getUser·p0.999:  27.162 ms/op
                 getUser·p0.9999: 35.604 ms/op
                 getUser·p1.00:   35.979 ms/op

Iteration   3: 5.362 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.585 ms/op
                 getUser·p0.50:   5.120 ms/op
                 getUser·p0.90:   6.570 ms/op
                 getUser·p0.95:   7.332 ms/op
                 getUser·p0.99:   10.961 ms/op
                 getUser·p0.999:  16.243 ms/op
                 getUser·p0.9999: 29.199 ms/op
                 getUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177101
  mean =      5.418 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 78126 
    [ 5.000, 10.000) = 95774 
    [10.000, 15.000) = 2702 
    [15.000, 20.000) = 269 
    [20.000, 25.000) = 92 
    [25.000, 30.000) = 79 
    [30.000, 35.000) = 29 
    [35.000, 40.000) = 21 
    [40.000, 45.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.450 ms/op
     p(50.0000) =      5.112 ms/op
     p(90.0000) =      6.619 ms/op
     p(95.0000) =      7.782 ms/op
     p(99.0000) =     11.551 ms/op
     p(99.9000) =     23.327 ms/op
     p(99.9900) =     35.933 ms/op
     p(99.9990) =     42.396 ms/op
     p(99.9999) =     42.598 ms/op
    p(100.0000) =     42.598 ms/op


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
# Warmup Iteration   1: 18.372 ±(99.9%) 0.311 ms/op
# Warmup Iteration   2: 7.814 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.481 ±(99.9%) 0.027 ms/op
Iteration   1: 6.276 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.454 ms/op
                 listUser·p0.50:   5.915 ms/op
                 listUser·p0.90:   7.610 ms/op
                 listUser·p0.95:   8.978 ms/op
                 listUser·p0.99:   12.780 ms/op
                 listUser·p0.999:  26.214 ms/op
                 listUser·p0.9999: 30.330 ms/op
                 listUser·p1.00:   30.835 ms/op

Iteration   2: 6.316 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.060 ms/op
                 listUser·p0.50:   6.013 ms/op
                 listUser·p0.90:   7.528 ms/op
                 listUser·p0.95:   8.716 ms/op
                 listUser·p0.99:   12.288 ms/op
                 listUser·p0.999:  28.639 ms/op
                 listUser·p0.9999: 31.607 ms/op
                 listUser·p1.00:   32.637 ms/op

Iteration   3: 6.411 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.503 ms/op
                 listUser·p0.50:   6.038 ms/op
                 listUser·p0.90:   7.987 ms/op
                 listUser·p0.95:   9.044 ms/op
                 listUser·p0.99:   12.108 ms/op
                 listUser·p0.999:  24.613 ms/op
                 listUser·p0.9999: 26.776 ms/op
                 listUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151553
  mean =      6.334 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 11078 
    [ 5.000,  7.500) = 122579 
    [ 7.500, 10.000) = 13400 
    [10.000, 12.500) = 3023 
    [12.500, 15.000) = 745 
    [15.000, 17.500) = 277 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 135 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.454 ms/op
     p(50.0000) =      5.988 ms/op
     p(90.0000) =      7.733 ms/op
     p(95.0000) =      8.929 ms/op
     p(99.0000) =     12.419 ms/op
     p(99.9000) =     26.247 ms/op
     p(99.9900) =     30.830 ms/op
     p(99.9990) =     32.451 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.039 ± 3.379  ops/ms
ClientPb.existUser                       thrpt       3   6.116 ± 3.468  ops/ms
ClientPb.getUser                         thrpt       3   6.074 ± 2.068  ops/ms
ClientPb.listUser                        thrpt       3   5.061 ± 0.505  ops/ms
ClientPb.createUser                       avgt       3   5.221 ± 3.373   ms/op
ClientPb.existUser                        avgt       3   5.180 ± 1.350   ms/op
ClientPb.getUser                          avgt       3   5.498 ± 3.664   ms/op
ClientPb.listUser                         avgt       3   6.384 ± 2.930   ms/op
ClientPb.createUser                     sample  180579   5.313 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.573           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.030           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.488           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.274           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.748           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.547           ms/op
ClientPb.createUser:createUser·p0.9999  sample          49.403           ms/op
ClientPb.createUser:createUser·p1.00    sample          55.247           ms/op
ClientPb.existUser                      sample  183077   5.240 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.034           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.956           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.439           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.487           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.830           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.346           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.386           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.159           ms/op
ClientPb.getUser                        sample  177101   5.418 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.450           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.112           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.619           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.782           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.551           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.327           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.933           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.598           ms/op
ClientPb.listUser                       sample  151553   6.334 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.454           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.988           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.733           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.929           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.419           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.247           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.830           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.637           ms/op
