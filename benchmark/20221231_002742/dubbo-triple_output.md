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
# Warmup Iteration   1: 2.318 ops/ms
# Warmup Iteration   2: 6.466 ops/ms
# Warmup Iteration   3: 8.677 ops/ms
Iteration   1: 9.323 ops/ms
Iteration   2: 8.978 ops/ms
Iteration   3: 9.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.153 ±(99.9%) 3.145 ops/ms [Average]
  (min, avg, max) = (8.978, 9.153, 9.323), stdev = 0.172
  CI (99.9%): [6.008, 12.298] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.920 ops/ms
# Warmup Iteration   2: 9.212 ops/ms
# Warmup Iteration   3: 9.430 ops/ms
Iteration   1: 10.294 ops/ms
Iteration   2: 10.296 ops/ms
Iteration   3: 9.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.147 ±(99.9%) 4.682 ops/ms [Average]
  (min, avg, max) = (9.851, 10.147, 10.296), stdev = 0.257
  CI (99.9%): [5.465, 14.829] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.413 ops/ms
# Warmup Iteration   2: 8.701 ops/ms
# Warmup Iteration   3: 9.083 ops/ms
Iteration   1: 9.491 ops/ms
Iteration   2: 9.375 ops/ms
Iteration   3: 8.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.277 ±(99.9%) 5.046 ops/ms [Average]
  (min, avg, max) = (8.965, 9.277, 9.491), stdev = 0.277
  CI (99.9%): [4.231, 14.323] (assumes normal distribution)


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
# Warmup Iteration   1: 2.696 ops/ms
# Warmup Iteration   2: 7.148 ops/ms
# Warmup Iteration   3: 8.030 ops/ms
Iteration   1: 8.080 ops/ms
Iteration   2: 8.207 ops/ms
Iteration   3: 8.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.142 ±(99.9%) 1.162 ops/ms [Average]
  (min, avg, max) = (8.080, 8.142, 8.207), stdev = 0.064
  CI (99.9%): [6.980, 9.304] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.710 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.863 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.007 ms/op
Iteration   1: 3.326 ±(99.9%) 0.011 ms/op
Iteration   2: 3.370 ±(99.9%) 0.007 ms/op
Iteration   3: 3.319 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.338 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (3.319, 3.338, 3.370), stdev = 0.028
  CI (99.9%): [2.835, 3.842] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.600 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.412 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.267 ±(99.9%) 0.006 ms/op
Iteration   1: 3.182 ±(99.9%) 0.006 ms/op
Iteration   2: 3.173 ±(99.9%) 0.012 ms/op
Iteration   3: 3.070 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.142 ±(99.9%) 1.131 ms/op [Average]
  (min, avg, max) = (3.070, 3.142, 3.182), stdev = 0.062
  CI (99.9%): [2.011, 4.273] (assumes normal distribution)


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
# Warmup Iteration   1: 8.830 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.633 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.005 ms/op
Iteration   1: 3.453 ±(99.9%) 0.007 ms/op
Iteration   2: 3.369 ±(99.9%) 0.010 ms/op
Iteration   3: 3.298 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.373 ±(99.9%) 1.415 ms/op [Average]
  (min, avg, max) = (3.298, 3.373, 3.453), stdev = 0.078
  CI (99.9%): [1.959, 4.788] (assumes normal distribution)


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
# Warmup Iteration   1: 9.297 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.010 ms/op
Iteration   1: 3.997 ±(99.9%) 0.010 ms/op
Iteration   2: 3.847 ±(99.9%) 0.018 ms/op
Iteration   3: 3.880 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.908 ±(99.9%) 1.445 ms/op [Average]
  (min, avg, max) = (3.847, 3.908, 3.997), stdev = 0.079
  CI (99.9%): [2.463, 5.353] (assumes normal distribution)


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
# Warmup Iteration   1: 9.696 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.010 ms/op
Iteration   1: 3.385 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  19.968 ms/op
                 createUser·p0.9999: 23.593 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   2: 3.376 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  21.243 ms/op
                 createUser·p0.9999: 24.578 ms/op
                 createUser·p1.00:   25.133 ms/op

Iteration   3: 3.481 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.782 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  19.245 ms/op
                 createUser·p0.9999: 34.669 ms/op
                 createUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281179
  mean =      3.414 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11135 
    [ 2.500,  5.000) = 263683 
    [ 5.000,  7.500) = 5175 
    [ 7.500, 10.000) = 680 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     19.327 ms/op
     p(99.9900) =     34.464 ms/op
     p(99.9990) =     34.734 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 7.792 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.008 ms/op
Iteration   1: 3.285 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  11.093 ms/op
                 existUser·p0.9999: 23.520 ms/op
                 existUser·p1.00:   25.264 ms/op

Iteration   2: 3.163 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.626 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  18.200 ms/op
                 existUser·p0.9999: 24.900 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   3: 3.177 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.673 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  9.978 ms/op
                 existUser·p0.9999: 22.704 ms/op
                 existUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299136
  mean =      3.207 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10006 
    [ 2.500,  5.000) = 285097 
    [ 5.000,  7.500) = 3371 
    [ 7.500, 10.000) = 318 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     12.321 ms/op
     p(99.9900) =     23.923 ms/op
     p(99.9990) =     25.264 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 8.930 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.010 ms/op
Iteration   1: 3.496 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.423 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   5.123 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  20.254 ms/op
                 getUser·p0.9999: 23.738 ms/op
                 getUser·p1.00:   24.609 ms/op

Iteration   2: 3.432 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   4.018 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  11.846 ms/op
                 getUser·p0.9999: 26.335 ms/op
                 getUser·p1.00:   28.967 ms/op

Iteration   3: 3.397 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.550 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  19.813 ms/op
                 getUser·p0.9999: 27.053 ms/op
                 getUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278868
  mean =      3.441 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4810 
    [ 2.500,  5.000) = 262673 
    [ 5.000,  7.500) = 9941 
    [ 7.500, 10.000) = 907 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 70 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     26.382 ms/op
     p(99.9990) =     29.229 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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
# Warmup Iteration   1: 10.665 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.305 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.016 ms/op
Iteration   1: 3.946 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.481 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  21.627 ms/op
                 listUser·p0.9999: 24.376 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   2: 3.963 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.032 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  15.450 ms/op
                 listUser·p0.9999: 19.790 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   3: 3.934 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   6.561 ms/op
                 listUser·p0.999:  14.647 ms/op
                 listUser·p0.9999: 20.148 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243145
  mean =      3.948 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 235834 
    [ 5.000,  7.500) = 5655 
    [ 7.500, 10.000) = 870 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.481 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     15.794 ms/op
     p(99.9900) =     23.583 ms/op
     p(99.9990) =     25.582 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.153 ± 3.145  ops/ms
ClientPb.existUser                       thrpt       3  10.147 ± 4.682  ops/ms
ClientPb.getUser                         thrpt       3   9.277 ± 5.046  ops/ms
ClientPb.listUser                        thrpt       3   8.142 ± 1.162  ops/ms
ClientPb.createUser                       avgt       3   3.338 ± 0.503   ms/op
ClientPb.existUser                        avgt       3   3.142 ± 1.131   ms/op
ClientPb.getUser                          avgt       3   3.373 ± 1.415   ms/op
ClientPb.listUser                         avgt       3   3.908 ± 1.445   ms/op
ClientPb.createUser                     sample  281179   3.414 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.286           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.923           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.327           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.464           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.800           ms/op
ClientPb.existUser                      sample  299136   3.207 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.239           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.399           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.321           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.923           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.362           ms/op
ClientPb.getUser                        sample  278868   3.441 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.081           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.792           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.595           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.219           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.382           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.491           ms/op
ClientPb.listUser                       sample  243145   3.948 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.481           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.767           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.794           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.583           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.821           ms/op
