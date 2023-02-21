# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.911 ops/ms
# Warmup Iteration   2: 5.182 ops/ms
# Warmup Iteration   3: 8.782 ops/ms
Iteration   1: 9.178 ops/ms
Iteration   2: 9.539 ops/ms
Iteration   3: 9.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.413 ±(99.9%) 3.719 ops/ms [Average]
  (min, avg, max) = (9.178, 9.413, 9.539), stdev = 0.204
  CI (99.9%): [5.694, 13.133] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.799 ops/ms
# Warmup Iteration   2: 8.544 ops/ms
# Warmup Iteration   3: 9.532 ops/ms
Iteration   1: 10.016 ops/ms
Iteration   2: 9.592 ops/ms
Iteration   3: 9.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.831 ±(99.9%) 3.956 ops/ms [Average]
  (min, avg, max) = (9.592, 9.831, 10.016), stdev = 0.217
  CI (99.9%): [5.875, 13.787] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.759 ops/ms
# Warmup Iteration   2: 8.017 ops/ms
# Warmup Iteration   3: 9.307 ops/ms
Iteration   1: 9.639 ops/ms
Iteration   2: 9.079 ops/ms
Iteration   3: 9.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.434 ±(99.9%) 5.630 ops/ms [Average]
  (min, avg, max) = (9.079, 9.434, 9.639), stdev = 0.309
  CI (99.9%): [3.804, 15.064] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.163 ops/ms
# Warmup Iteration   2: 7.666 ops/ms
# Warmup Iteration   3: 7.806 ops/ms
Iteration   1: 8.252 ops/ms
Iteration   2: 7.987 ops/ms
Iteration   3: 8.405 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.215 ±(99.9%) 3.863 ops/ms [Average]
  (min, avg, max) = (7.987, 8.215, 8.405), stdev = 0.212
  CI (99.9%): [4.351, 12.078] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.546 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.007 ms/op
Iteration   1: 3.402 ±(99.9%) 0.005 ms/op
Iteration   2: 3.384 ±(99.9%) 0.010 ms/op
Iteration   3: 3.295 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.360 ±(99.9%) 1.043 ms/op [Average]
  (min, avg, max) = (3.295, 3.360, 3.402), stdev = 0.057
  CI (99.9%): [2.317, 4.403] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.475 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.009 ms/op
Iteration   1: 3.300 ±(99.9%) 0.002 ms/op
Iteration   2: 3.311 ±(99.9%) 0.007 ms/op
Iteration   3: 3.218 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.276 ±(99.9%) 0.930 ms/op [Average]
  (min, avg, max) = (3.218, 3.276, 3.311), stdev = 0.051
  CI (99.9%): [2.346, 4.206] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.785 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.006 ms/op
Iteration   1: 3.494 ±(99.9%) 0.006 ms/op
Iteration   2: 3.302 ±(99.9%) 0.011 ms/op
Iteration   3: 3.303 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.366 ±(99.9%) 2.018 ms/op [Average]
  (min, avg, max) = (3.302, 3.366, 3.494), stdev = 0.111
  CI (99.9%): [1.349, 5.384] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.583 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.013 ms/op
Iteration   1: 3.990 ±(99.9%) 0.007 ms/op
Iteration   2: 4.046 ±(99.9%) 0.011 ms/op
Iteration   3: 3.892 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.976 ±(99.9%) 1.422 ms/op [Average]
  (min, avg, max) = (3.892, 3.976, 4.046), stdev = 0.078
  CI (99.9%): [2.553, 5.398] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.764 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.828 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.010 ms/op
Iteration   1: 3.414 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  20.737 ms/op
                 createUser·p0.9999: 24.082 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   2: 3.368 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.663 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  22.641 ms/op
                 createUser·p0.9999: 24.904 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   3: 3.588 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.661 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  16.056 ms/op
                 createUser·p0.9999: 26.258 ms/op
                 createUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277813
  mean =      3.454 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9205 
    [ 2.500,  5.000) = 263293 
    [ 5.000,  7.500) = 4523 
    [ 7.500, 10.000) = 363 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 138 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     24.878 ms/op
     p(99.9990) =     26.655 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.686 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.008 ms/op
Iteration   1: 3.368 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.442 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   6.122 ms/op
                 existUser·p0.999:  20.186 ms/op
                 existUser·p0.9999: 22.905 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   2: 3.347 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.679 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  11.452 ms/op
                 existUser·p0.9999: 23.724 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   3: 3.376 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.642 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  20.980 ms/op
                 existUser·p0.9999: 27.989 ms/op
                 existUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285345
  mean =      3.364 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6887 
    [ 2.500,  5.000) = 271864 
    [ 5.000,  7.500) = 5251 
    [ 7.500, 10.000) = 805 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.442 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     17.191 ms/op
     p(99.9900) =     27.180 ms/op
     p(99.9990) =     28.772 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.458 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.862 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.570 ±(99.9%) 0.011 ms/op
Iteration   1: 3.416 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.458 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  19.587 ms/op
                 getUser·p0.9999: 23.194 ms/op
                 getUser·p1.00:   24.674 ms/op

Iteration   2: 3.503 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  22.544 ms/op
                 getUser·p0.9999: 26.183 ms/op
                 getUser·p1.00:   26.903 ms/op

Iteration   3: 3.567 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.166 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  19.935 ms/op
                 getUser·p0.9999: 26.412 ms/op
                 getUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274486
  mean =      3.494 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5251 
    [ 2.500,  5.000) = 262868 
    [ 5.000,  7.500) = 5120 
    [ 7.500, 10.000) = 761 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     19.841 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     27.214 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.629 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.424 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.968 ±(99.9%) 0.013 ms/op
Iteration   1: 4.079 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  18.809 ms/op
                 listUser·p0.9999: 22.790 ms/op
                 listUser·p1.00:   24.084 ms/op

Iteration   2: 3.880 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  15.188 ms/op
                 listUser·p0.9999: 15.532 ms/op
                 listUser·p1.00:   15.712 ms/op

Iteration   3: 3.939 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  14.795 ms/op
                 listUser·p0.9999: 16.904 ms/op
                 listUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242149
  mean =      3.964 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 233998 
    [ 5.000,  7.500) = 5921 
    [ 7.500, 10.000) = 1270 
    [10.000, 12.500) = 406 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 237 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.269 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     15.300 ms/op
     p(99.9900) =     21.912 ms/op
     p(99.9990) =     23.569 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.413 ± 3.719  ops/ms
ClientPb.existUser                       thrpt       3   9.831 ± 3.956  ops/ms
ClientPb.getUser                         thrpt       3   9.434 ± 5.630  ops/ms
ClientPb.listUser                        thrpt       3   8.215 ± 3.863  ops/ms
ClientPb.createUser                       avgt       3   3.360 ± 1.043   ms/op
ClientPb.existUser                        avgt       3   3.276 ± 0.930   ms/op
ClientPb.getUser                          avgt       3   3.366 ± 2.018   ms/op
ClientPb.listUser                         avgt       3   3.976 ± 1.422   ms/op
ClientPb.createUser                     sample  277813   3.454 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.157           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.026           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.203           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.878           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.837           ms/op
ClientPb.existUser                      sample  285345   3.364 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.442           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.988           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.191           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.180           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.262           ms/op
ClientPb.getUser                        sample  274486   3.494 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.206           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.268           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.332           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.841           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.625           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.000           ms/op
ClientPb.listUser                       sample  242149   3.964 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.269           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.365           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.300           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.912           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.084           ms/op
