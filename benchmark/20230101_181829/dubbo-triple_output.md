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
# Warmup Iteration   1: 2.047 ops/ms
# Warmup Iteration   2: 5.464 ops/ms
# Warmup Iteration   3: 8.499 ops/ms
Iteration   1: 7.888 ops/ms
Iteration   2: 9.283 ops/ms
Iteration   3: 9.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.840 ±(99.9%) 15.049 ops/ms [Average]
  (min, avg, max) = (7.888, 8.840, 9.349), stdev = 0.825
  CI (99.9%): [≈ 0, 23.889] (assumes normal distribution)


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
# Warmup Iteration   1: 3.010 ops/ms
# Warmup Iteration   2: 8.466 ops/ms
# Warmup Iteration   3: 9.286 ops/ms
Iteration   1: 10.010 ops/ms
Iteration   2: 9.925 ops/ms
Iteration   3: 9.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.954 ±(99.9%) 0.882 ops/ms [Average]
  (min, avg, max) = (9.925, 9.954, 10.010), stdev = 0.048
  CI (99.9%): [9.072, 10.836] (assumes normal distribution)


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
# Warmup Iteration   1: 3.015 ops/ms
# Warmup Iteration   2: 8.451 ops/ms
# Warmup Iteration   3: 9.189 ops/ms
Iteration   1: 9.546 ops/ms
Iteration   2: 9.552 ops/ms
Iteration   3: 9.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.522 ±(99.9%) 0.850 ops/ms [Average]
  (min, avg, max) = (9.468, 9.522, 9.552), stdev = 0.047
  CI (99.9%): [8.672, 10.372] (assumes normal distribution)


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
# Warmup Iteration   1: 2.989 ops/ms
# Warmup Iteration   2: 7.298 ops/ms
# Warmup Iteration   3: 7.622 ops/ms
Iteration   1: 7.918 ops/ms
Iteration   2: 7.800 ops/ms
Iteration   3: 7.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.747 ±(99.9%) 3.691 ops/ms [Average]
  (min, avg, max) = (7.524, 7.747, 7.918), stdev = 0.202
  CI (99.9%): [4.056, 11.438] (assumes normal distribution)


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
# Warmup Iteration   1: 9.889 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.010 ms/op
Iteration   1: 3.433 ±(99.9%) 0.007 ms/op
Iteration   2: 3.432 ±(99.9%) 0.009 ms/op
Iteration   3: 3.364 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.410 ±(99.9%) 0.727 ms/op [Average]
  (min, avg, max) = (3.364, 3.410, 3.433), stdev = 0.040
  CI (99.9%): [2.682, 4.137] (assumes normal distribution)


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
# Warmup Iteration   1: 9.645 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.474 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.460 ±(99.9%) 0.004 ms/op
Iteration   1: 3.210 ±(99.9%) 0.007 ms/op
Iteration   2: 3.257 ±(99.9%) 0.009 ms/op
Iteration   3: 3.427 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.298 ±(99.9%) 2.081 ms/op [Average]
  (min, avg, max) = (3.210, 3.298, 3.427), stdev = 0.114
  CI (99.9%): [1.217, 5.379] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.594 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.007 ms/op
Iteration   1: 3.487 ±(99.9%) 0.007 ms/op
Iteration   2: 3.558 ±(99.9%) 0.005 ms/op
Iteration   3: 3.441 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.495 ±(99.9%) 1.083 ms/op [Average]
  (min, avg, max) = (3.441, 3.495, 3.558), stdev = 0.059
  CI (99.9%): [2.412, 4.579] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.323 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.314 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.159 ±(99.9%) 0.010 ms/op
Iteration   1: 3.991 ±(99.9%) 0.013 ms/op
Iteration   2: 4.056 ±(99.9%) 0.014 ms/op
Iteration   3: 4.152 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.067 ±(99.9%) 1.478 ms/op [Average]
  (min, avg, max) = (3.991, 4.067, 4.152), stdev = 0.081
  CI (99.9%): [2.588, 5.545] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.160 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.521 ±(99.9%) 0.011 ms/op
Iteration   1: 3.340 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.898 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.543 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  21.534 ms/op
                 createUser·p0.9999: 27.225 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   2: 3.429 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  22.829 ms/op
                 createUser·p0.9999: 25.548 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   3: 3.372 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.575 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   5.194 ms/op
                 createUser·p0.999:  18.126 ms/op
                 createUser·p0.9999: 30.393 ms/op
                 createUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283881
  mean =      3.380 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10865 
    [ 2.500,  5.000) = 268534 
    [ 5.000,  7.500) = 3566 
    [ 7.500, 10.000) = 451 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 149 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     18.288 ms/op
     p(99.9900) =     28.603 ms/op
     p(99.9990) =     31.080 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.302 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.379 ±(99.9%) 0.010 ms/op
Iteration   1: 3.422 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.973 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  11.740 ms/op
                 existUser·p0.9999: 24.434 ms/op
                 existUser·p1.00:   24.969 ms/op

Iteration   2: 3.427 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.155 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   6.496 ms/op
                 existUser·p0.999:  22.283 ms/op
                 existUser·p0.9999: 28.749 ms/op
                 existUser·p1.00:   29.491 ms/op

Iteration   3: 3.380 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  23.209 ms/op
                 existUser·p0.9999: 28.427 ms/op
                 existUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281498
  mean =      3.410 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17841 
    [ 2.500,  5.000) = 255166 
    [ 5.000,  7.500) = 7198 
    [ 7.500, 10.000) = 698 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 137 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     28.274 ms/op
     p(99.9990) =     29.333 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.956 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.885 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.012 ms/op
Iteration   1: 3.396 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.475 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  11.559 ms/op
                 getUser·p0.9999: 24.023 ms/op
                 getUser·p1.00:   24.773 ms/op

Iteration   2: 3.377 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.335 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  23.010 ms/op
                 getUser·p0.9999: 27.394 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   3: 3.450 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.675 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.603 ms/op
                 getUser·p0.999:  23.210 ms/op
                 getUser·p0.9999: 32.661 ms/op
                 getUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281852
  mean =      3.407 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6890 
    [ 2.500,  5.000) = 267868 
    [ 5.000,  7.500) = 6031 
    [ 7.500, 10.000) = 670 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     12.665 ms/op
     p(99.9900) =     31.752 ms/op
     p(99.9990) =     33.632 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 10.697 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.340 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.180 ±(99.9%) 0.014 ms/op
Iteration   1: 4.117 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.761 ms/op
                 listUser·p0.999:  18.591 ms/op
                 listUser·p0.9999: 25.411 ms/op
                 listUser·p1.00:   26.247 ms/op

Iteration   2: 4.066 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 21.070 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   3: 3.945 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.935 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.096 ms/op
                 listUser·p0.999:  16.663 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237317
  mean =      4.041 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 227656 
    [ 5.000,  7.500) = 7007 
    [ 7.500, 10.000) = 1890 
    [10.000, 12.500) = 277 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.399 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     16.690 ms/op
     p(99.9900) =     24.528 ms/op
     p(99.9990) =     25.993 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   8.840 ± 15.049  ops/ms
ClientPb.existUser                       thrpt       3   9.954 ±  0.882  ops/ms
ClientPb.getUser                         thrpt       3   9.522 ±  0.850  ops/ms
ClientPb.listUser                        thrpt       3   7.747 ±  3.691  ops/ms
ClientPb.createUser                       avgt       3   3.410 ±  0.727   ms/op
ClientPb.existUser                        avgt       3   3.298 ±  2.081   ms/op
ClientPb.getUser                          avgt       3   3.495 ±  1.083   ms/op
ClientPb.listUser                         avgt       3   4.067 ±  1.478   ms/op
ClientPb.createUser                     sample  283881   3.380 ±  0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.141            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314            ms/op
ClientPb.createUser:createUser·p0.90    sample           3.752            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.047            ms/op
ClientPb.createUser:createUser·p0.99    sample           5.530            ms/op
ClientPb.createUser:createUser·p0.999   sample          18.288            ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.603            ms/op
ClientPb.createUser:createUser·p1.00    sample          31.326            ms/op
ClientPb.existUser                      sample  281498   3.410 ±  0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.713            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.281            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.936            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.334            ms/op
ClientPb.existUser:existUser·p0.99      sample           6.177            ms/op
ClientPb.existUser:existUser·p0.999     sample          13.746            ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.274            ms/op
ClientPb.existUser:existUser·p1.00      sample          29.491            ms/op
ClientPb.getUser                        sample  281852   3.407 ±  0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.335            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.744            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.010            ms/op
ClientPb.getUser:getUser·p0.99          sample           6.005            ms/op
ClientPb.getUser:getUser·p0.999         sample          12.665            ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.752            ms/op
ClientPb.getUser:getUser·p1.00          sample          33.751            ms/op
ClientPb.listUser                       sample  237317   4.041 ±  0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.399            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.867            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.792            ms/op
ClientPb.listUser:listUser·p0.99        sample           7.684            ms/op
ClientPb.listUser:listUser·p0.999       sample          16.690            ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.528            ms/op
ClientPb.listUser:listUser·p1.00        sample          26.247            ms/op
