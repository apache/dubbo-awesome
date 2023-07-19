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
# Warmup Iteration   1: 2.061 ops/ms
# Warmup Iteration   2: 5.174 ops/ms
# Warmup Iteration   3: 8.636 ops/ms
Iteration   1: 9.324 ops/ms
Iteration   2: 9.368 ops/ms
Iteration   3: 9.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.333 ±(99.9%) 0.581 ops/ms [Average]
  (min, avg, max) = (9.306, 9.333, 9.368), stdev = 0.032
  CI (99.9%): [8.752, 9.914] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.977 ops/ms
# Warmup Iteration   2: 8.326 ops/ms
# Warmup Iteration   3: 9.375 ops/ms
Iteration   1: 9.588 ops/ms
Iteration   2: 9.553 ops/ms
Iteration   3: 9.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.613 ±(99.9%) 1.394 ops/ms [Average]
  (min, avg, max) = (9.553, 9.613, 9.699), stdev = 0.076
  CI (99.9%): [8.220, 11.007] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.039 ops/ms
# Warmup Iteration   2: 8.079 ops/ms
# Warmup Iteration   3: 9.172 ops/ms
Iteration   1: 9.035 ops/ms
Iteration   2: 9.299 ops/ms
Iteration   3: 9.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.220 ±(99.9%) 2.928 ops/ms [Average]
  (min, avg, max) = (9.035, 9.220, 9.325), stdev = 0.160
  CI (99.9%): [6.292, 12.148] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.898 ops/ms
# Warmup Iteration   2: 7.311 ops/ms
# Warmup Iteration   3: 7.892 ops/ms
Iteration   1: 7.988 ops/ms
Iteration   2: 8.180 ops/ms
Iteration   3: 7.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.999 ±(99.9%) 3.216 ops/ms [Average]
  (min, avg, max) = (7.828, 7.999, 8.180), stdev = 0.176
  CI (99.9%): [4.783, 11.215] (assumes normal distribution)


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
# Warmup Iteration   1: 9.257 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.007 ms/op
Iteration   1: 3.365 ±(99.9%) 0.008 ms/op
Iteration   2: 3.430 ±(99.9%) 0.009 ms/op
Iteration   3: 3.330 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.375 ±(99.9%) 0.925 ms/op [Average]
  (min, avg, max) = (3.330, 3.375, 3.430), stdev = 0.051
  CI (99.9%): [2.450, 4.300] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.057 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.490 ±(99.9%) 0.003 ms/op
Iteration   1: 3.350 ±(99.9%) 0.011 ms/op
Iteration   2: 3.290 ±(99.9%) 0.006 ms/op
Iteration   3: 3.309 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.316 ±(99.9%) 0.562 ms/op [Average]
  (min, avg, max) = (3.290, 3.316, 3.350), stdev = 0.031
  CI (99.9%): [2.754, 3.879] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.076 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.465 ±(99.9%) 0.004 ms/op
Iteration   1: 3.410 ±(99.9%) 0.004 ms/op
Iteration   2: 3.290 ±(99.9%) 0.008 ms/op
Iteration   3: 3.391 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.363 ±(99.9%) 1.175 ms/op [Average]
  (min, avg, max) = (3.290, 3.363, 3.410), stdev = 0.064
  CI (99.9%): [2.189, 4.538] (assumes normal distribution)


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
# Warmup Iteration   1: 10.685 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.429 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.010 ms/op
Iteration   1: 4.020 ±(99.9%) 0.007 ms/op
Iteration   2: 4.007 ±(99.9%) 0.013 ms/op
Iteration   3: 3.966 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.998 ±(99.9%) 0.519 ms/op [Average]
  (min, avg, max) = (3.966, 3.998, 4.020), stdev = 0.028
  CI (99.9%): [3.479, 4.516] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.762 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.905 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.688 ±(99.9%) 0.012 ms/op
Iteration   1: 3.383 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  19.653 ms/op
                 createUser·p0.9999: 25.035 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   2: 3.420 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.479 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.218 ms/op
                 createUser·p0.999:  23.512 ms/op
                 createUser·p0.9999: 25.810 ms/op
                 createUser·p1.00:   26.477 ms/op

Iteration   3: 3.355 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.406 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   5.108 ms/op
                 createUser·p0.999:  16.548 ms/op
                 createUser·p0.9999: 24.773 ms/op
                 createUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283438
  mean =      3.386 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7783 
    [ 2.500,  5.000) = 270030 
    [ 5.000,  7.500) = 4646 
    [ 7.500, 10.000) = 581 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      0.406 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     16.581 ms/op
     p(99.9900) =     25.559 ms/op
     p(99.9990) =     26.192 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.201 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.009 ms/op
Iteration   1: 3.369 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.409 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  9.781 ms/op
                 existUser·p0.9999: 22.004 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   2: 3.318 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  16.789 ms/op
                 existUser·p0.9999: 23.550 ms/op
                 existUser·p1.00:   24.936 ms/op

Iteration   3: 3.296 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  15.112 ms/op
                 existUser·p0.9999: 27.207 ms/op
                 existUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288436
  mean =      3.327 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8440 
    [ 2.500,  5.000) = 275565 
    [ 5.000,  7.500) = 3449 
    [ 7.500, 10.000) = 573 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     13.395 ms/op
     p(99.9900) =     25.935 ms/op
     p(99.9990) =     27.598 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 10.086 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.671 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.011 ms/op
Iteration   1: 3.480 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.851 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   6.816 ms/op
                 getUser·p0.999:  19.825 ms/op
                 getUser·p0.9999: 27.499 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   2: 3.503 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.665 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  20.824 ms/op
                 getUser·p0.9999: 26.444 ms/op
                 getUser·p1.00:   29.884 ms/op

Iteration   3: 3.349 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   2.025 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   5.816 ms/op
                 getUser·p0.999:  21.791 ms/op
                 getUser·p0.9999: 26.048 ms/op
                 getUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278687
  mean =      3.443 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6080 
    [ 2.500,  5.000) = 263900 
    [ 5.000,  7.500) = 7454 
    [ 7.500, 10.000) = 886 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      1.665 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     28.229 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 9.834 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.475 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.146 ±(99.9%) 0.012 ms/op
Iteration   1: 4.154 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.624 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   6.130 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  19.432 ms/op
                 listUser·p0.9999: 22.984 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   2: 4.035 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  15.512 ms/op
                 listUser·p0.9999: 19.431 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 3.970 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.929 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  15.389 ms/op
                 listUser·p0.9999: 18.676 ms/op
                 listUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236601
  mean =      4.052 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 225666 
    [ 5.000,  7.500) = 8162 
    [ 7.500, 10.000) = 1862 
    [10.000, 12.500) = 381 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.624 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     21.344 ms/op
     p(99.9990) =     24.361 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.333 ± 0.581  ops/ms
ClientPb.existUser                       thrpt       3   9.613 ± 1.394  ops/ms
ClientPb.getUser                         thrpt       3   9.220 ± 2.928  ops/ms
ClientPb.listUser                        thrpt       3   7.999 ± 3.216  ops/ms
ClientPb.createUser                       avgt       3   3.375 ± 0.925   ms/op
ClientPb.existUser                        avgt       3   3.316 ± 0.562   ms/op
ClientPb.getUser                          avgt       3   3.363 ± 1.175   ms/op
ClientPb.listUser                         avgt       3   3.998 ± 0.519   ms/op
ClientPb.createUser                     sample  283438   3.386 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.406           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.281           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.149           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.702           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.581           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.559           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.477           ms/op
ClientPb.existUser                      sample  288436   3.327 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.106           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.018           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.513           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.395           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.935           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.820           ms/op
ClientPb.getUser                        sample  278687   3.443 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.665           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.293           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.481           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.447           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.923           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.640           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.884           ms/op
ClientPb.listUser                       sample  236601   4.052 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.624           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.899           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.832           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.122           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.344           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.510           ms/op
