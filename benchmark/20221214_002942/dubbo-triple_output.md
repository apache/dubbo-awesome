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
# Warmup Iteration   1: 2.038 ops/ms
# Warmup Iteration   2: 5.325 ops/ms
# Warmup Iteration   3: 8.739 ops/ms
Iteration   1: 9.230 ops/ms
Iteration   2: 9.336 ops/ms
Iteration   3: 9.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.283 ±(99.9%) 0.966 ops/ms [Average]
  (min, avg, max) = (9.230, 9.283, 9.336), stdev = 0.053
  CI (99.9%): [8.316, 10.249] (assumes normal distribution)


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
# Warmup Iteration   1: 2.828 ops/ms
# Warmup Iteration   2: 8.733 ops/ms
# Warmup Iteration   3: 9.349 ops/ms
Iteration   1: 9.601 ops/ms
Iteration   2: 9.559 ops/ms
Iteration   3: 9.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.576 ±(99.9%) 0.402 ops/ms [Average]
  (min, avg, max) = (9.559, 9.576, 9.601), stdev = 0.022
  CI (99.9%): [9.173, 9.978] (assumes normal distribution)


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
# Warmup Iteration   1: 2.811 ops/ms
# Warmup Iteration   2: 8.207 ops/ms
# Warmup Iteration   3: 8.999 ops/ms
Iteration   1: 9.445 ops/ms
Iteration   2: 9.394 ops/ms
Iteration   3: 9.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.311 ±(99.9%) 3.469 ops/ms [Average]
  (min, avg, max) = (9.093, 9.311, 9.445), stdev = 0.190
  CI (99.9%): [5.842, 12.779] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.660 ops/ms
# Warmup Iteration   2: 7.315 ops/ms
# Warmup Iteration   3: 7.823 ops/ms
Iteration   1: 7.841 ops/ms
Iteration   2: 7.884 ops/ms
Iteration   3: 7.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.903 ±(99.9%) 1.331 ops/ms [Average]
  (min, avg, max) = (7.841, 7.903, 7.983), stdev = 0.073
  CI (99.9%): [6.572, 9.233] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.519 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.710 ±(99.9%) 0.004 ms/op
Iteration   1: 3.398 ±(99.9%) 0.009 ms/op
Iteration   2: 3.427 ±(99.9%) 0.005 ms/op
Iteration   3: 3.421 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.415 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (3.398, 3.415, 3.427), stdev = 0.016
  CI (99.9%): [3.129, 3.701] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.870 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.006 ms/op
Iteration   1: 3.332 ±(99.9%) 0.007 ms/op
Iteration   2: 3.283 ±(99.9%) 0.004 ms/op
Iteration   3: 3.313 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.309 ±(99.9%) 0.446 ms/op [Average]
  (min, avg, max) = (3.283, 3.309, 3.332), stdev = 0.024
  CI (99.9%): [2.863, 3.755] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.165 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.841 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.005 ms/op
Iteration   1: 3.574 ±(99.9%) 0.007 ms/op
Iteration   2: 3.443 ±(99.9%) 0.007 ms/op
Iteration   3: 3.323 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.447 ±(99.9%) 2.282 ms/op [Average]
  (min, avg, max) = (3.323, 3.447, 3.574), stdev = 0.125
  CI (99.9%): [1.165, 5.728] (assumes normal distribution)


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
# Warmup Iteration   1: 10.440 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.288 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.010 ms/op
Iteration   1: 4.028 ±(99.9%) 0.012 ms/op
Iteration   2: 3.935 ±(99.9%) 0.010 ms/op
Iteration   3: 3.888 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.950 ±(99.9%) 1.298 ms/op [Average]
  (min, avg, max) = (3.888, 3.950, 4.028), stdev = 0.071
  CI (99.9%): [2.652, 5.248] (assumes normal distribution)


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
# Warmup Iteration   1: 10.340 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.709 ±(99.9%) 0.014 ms/op
Iteration   1: 3.341 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   6.087 ms/op
                 createUser·p0.999:  23.364 ms/op
                 createUser·p0.9999: 25.690 ms/op
                 createUser·p1.00:   26.903 ms/op

Iteration   2: 3.497 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.880 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.153 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  9.260 ms/op
                 createUser·p0.9999: 26.931 ms/op
                 createUser·p1.00:   28.803 ms/op

Iteration   3: 3.435 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.413 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  24.707 ms/op
                 createUser·p0.9999: 31.709 ms/op
                 createUser·p1.00:   32.702 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280141
  mean =      3.423 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7020 
    [ 2.500,  5.000) = 267590 
    [ 5.000,  7.500) = 4463 
    [ 7.500, 10.000) = 598 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     22.179 ms/op
     p(99.9900) =     29.688 ms/op
     p(99.9990) =     32.014 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


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
# Warmup Iteration   1: 10.129 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.686 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.010 ms/op
Iteration   1: 3.470 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.041 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  20.890 ms/op
                 existUser·p0.9999: 23.119 ms/op
                 existUser·p1.00:   23.986 ms/op

Iteration   2: 3.301 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  14.829 ms/op
                 existUser·p0.9999: 27.470 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   3: 3.366 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   6.332 ms/op
                 existUser·p0.999:  20.843 ms/op
                 existUser·p0.9999: 31.233 ms/op
                 existUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284080
  mean =      3.378 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10399 
    [ 2.500,  5.000) = 267002 
    [ 5.000,  7.500) = 5304 
    [ 7.500, 10.000) = 696 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     20.838 ms/op
     p(99.9900) =     30.212 ms/op
     p(99.9990) =     31.697 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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
# Warmup Iteration   1: 9.166 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.011 ms/op
Iteration   1: 3.403 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.624 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  20.579 ms/op
                 getUser·p0.9999: 23.750 ms/op
                 getUser·p1.00:   25.494 ms/op

Iteration   2: 3.326 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.245 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  19.292 ms/op
                 getUser·p0.9999: 26.116 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   3: 3.377 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  19.988 ms/op
                 getUser·p0.9999: 27.790 ms/op
                 getUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284837
  mean =      3.368 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2649 
    [ 2.500,  5.000) = 275135 
    [ 5.000,  7.500) = 6230 
    [ 7.500, 10.000) = 428 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.245 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     20.092 ms/op
     p(99.9900) =     26.625 ms/op
     p(99.9990) =     28.480 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


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
# Warmup Iteration   1: 11.122 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.545 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.014 ms/op
Iteration   1: 4.049 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.880 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  21.135 ms/op
                 listUser·p0.9999: 27.165 ms/op
                 listUser·p1.00:   27.886 ms/op

Iteration   2: 4.178 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  16.204 ms/op
                 listUser·p0.9999: 19.366 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   3: 4.036 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 21.540 ms/op
                 listUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234806
  mean =      4.087 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 225414 
    [ 5.000,  7.500) = 6800 
    [ 7.500, 10.000) = 1687 
    [10.000, 12.500) = 366 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.880 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.651 ms/op
     p(99.9000) =     16.986 ms/op
     p(99.9900) =     26.019 ms/op
     p(99.9990) =     27.622 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.283 ± 0.966  ops/ms
ClientPb.existUser                       thrpt       3   9.576 ± 0.402  ops/ms
ClientPb.getUser                         thrpt       3   9.311 ± 3.469  ops/ms
ClientPb.listUser                        thrpt       3   7.903 ± 1.331  ops/ms
ClientPb.createUser                       avgt       3   3.415 ± 0.286   ms/op
ClientPb.existUser                        avgt       3   3.309 ± 0.446   ms/op
ClientPb.getUser                          avgt       3   3.447 ± 2.282   ms/op
ClientPb.listUser                         avgt       3   3.950 ± 1.298   ms/op
ClientPb.createUser                     sample  280141   3.423 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.413           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.784           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.179           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.688           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.702           ms/op
ClientPb.existUser                      sample  284080   3.378 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.041           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.972           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.838           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.212           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.047           ms/op
ClientPb.getUser                        sample  284837   3.368 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.245           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.026           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.947           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.092           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.625           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.738           ms/op
ClientPb.listUser                       sample  234806   4.087 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.880           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.651           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.986           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.019           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.886           ms/op
