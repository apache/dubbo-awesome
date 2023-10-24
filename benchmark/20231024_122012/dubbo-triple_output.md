# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.097 ops/ms
# Warmup Iteration   2: 5.617 ops/ms
# Warmup Iteration   3: 8.267 ops/ms
Iteration   1: 9.022 ops/ms
Iteration   2: 9.120 ops/ms
Iteration   3: 9.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.147 ±(99.9%) 2.559 ops/ms [Average]
  (min, avg, max) = (9.022, 9.147, 9.299), stdev = 0.140
  CI (99.9%): [6.588, 11.706] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.169 ops/ms
# Warmup Iteration   2: 8.724 ops/ms
# Warmup Iteration   3: 9.251 ops/ms
Iteration   1: 9.317 ops/ms
Iteration   2: 9.374 ops/ms
Iteration   3: 9.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.391 ±(99.9%) 1.521 ops/ms [Average]
  (min, avg, max) = (9.317, 9.391, 9.481), stdev = 0.083
  CI (99.9%): [7.870, 10.912] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.898 ops/ms
# Warmup Iteration   2: 8.372 ops/ms
# Warmup Iteration   3: 8.954 ops/ms
Iteration   1: 9.067 ops/ms
Iteration   2: 9.034 ops/ms
Iteration   3: 9.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.137 ±(99.9%) 2.754 ops/ms [Average]
  (min, avg, max) = (9.034, 9.137, 9.311), stdev = 0.151
  CI (99.9%): [6.384, 11.891] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 2.616 ops/ms
# Warmup Iteration   2: 7.141 ops/ms
# Warmup Iteration   3: 7.551 ops/ms
Iteration   1: 7.580 ops/ms
Iteration   2: 7.556 ops/ms
Iteration   3: 7.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.631 ±(99.9%) 1.994 ops/ms [Average]
  (min, avg, max) = (7.556, 7.631, 7.756), stdev = 0.109
  CI (99.9%): [5.637, 9.625] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.280 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.752 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.633 ±(99.9%) 0.005 ms/op
Iteration   1: 3.597 ±(99.9%) 0.005 ms/op
Iteration   2: 3.512 ±(99.9%) 0.007 ms/op
Iteration   3: 3.490 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.533 ±(99.9%) 1.028 ms/op [Average]
  (min, avg, max) = (3.490, 3.533, 3.597), stdev = 0.056
  CI (99.9%): [2.505, 4.561] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.529 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.496 ±(99.9%) 0.005 ms/op
Iteration   1: 3.557 ±(99.9%) 0.003 ms/op
Iteration   2: 3.484 ±(99.9%) 0.003 ms/op
Iteration   3: 3.436 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.492 ±(99.9%) 1.105 ms/op [Average]
  (min, avg, max) = (3.436, 3.492, 3.557), stdev = 0.061
  CI (99.9%): [2.388, 4.597] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.292 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.786 ±(99.9%) 0.004 ms/op
Iteration   1: 3.634 ±(99.9%) 0.004 ms/op
Iteration   2: 3.605 ±(99.9%) 0.006 ms/op
Iteration   3: 3.570 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.603 ±(99.9%) 0.584 ms/op [Average]
  (min, avg, max) = (3.570, 3.603, 3.634), stdev = 0.032
  CI (99.9%): [3.019, 4.187] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.918 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.518 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.204 ±(99.9%) 0.007 ms/op
Iteration   1: 4.161 ±(99.9%) 0.007 ms/op
Iteration   2: 4.161 ±(99.9%) 0.008 ms/op
Iteration   3: 4.145 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.156 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (4.145, 4.156, 4.161), stdev = 0.010
  CI (99.9%): [3.982, 4.330] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.834 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.370 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.011 ms/op
Iteration   1: 3.574 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.339 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  19.349 ms/op
                 createUser·p0.9999: 22.972 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   2: 3.573 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.677 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  21.645 ms/op
                 createUser·p0.9999: 28.512 ms/op
                 createUser·p1.00:   28.869 ms/op

Iteration   3: 3.617 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.478 ms/op
                 createUser·p0.90:   4.166 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  23.174 ms/op
                 createUser·p0.9999: 25.963 ms/op
                 createUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267379
  mean =      3.588 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1699 
    [ 2.500,  5.000) = 260193 
    [ 5.000,  7.500) = 4405 
    [ 7.500, 10.000) = 522 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     20.500 ms/op
     p(99.9900) =     26.616 ms/op
     p(99.9990) =     28.726 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.932 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.008 ms/op
Iteration   1: 3.465 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.462 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.972 ms/op
                 existUser·p0.999:  20.349 ms/op
                 existUser·p0.9999: 23.028 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   2: 3.408 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.274 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  22.222 ms/op
                 existUser·p0.9999: 25.723 ms/op
                 existUser·p1.00:   26.739 ms/op

Iteration   3: 3.524 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   3.998 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.994 ms/op
                 existUser·p0.999:  13.239 ms/op
                 existUser·p0.9999: 25.559 ms/op
                 existUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 277014
  mean =      3.465 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3568 
    [ 2.500,  5.000) = 267984 
    [ 5.000,  7.500) = 4079 
    [ 7.500, 10.000) = 677 
    [10.000, 12.500) = 334 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     25.438 ms/op
     p(99.9990) =     26.630 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.060 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.009 ms/op
Iteration   1: 3.787 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.374 ms/op
                 getUser·p0.50:   3.514 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   6.095 ms/op
                 getUser·p0.99:   8.421 ms/op
                 getUser·p0.999:  21.452 ms/op
                 getUser·p0.9999: 24.445 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   2: 3.597 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.502 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  22.315 ms/op
                 getUser·p0.9999: 25.399 ms/op
                 getUser·p1.00:   25.821 ms/op

Iteration   3: 3.607 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   3.490 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  17.849 ms/op
                 getUser·p0.9999: 26.710 ms/op
                 getUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 261988
  mean =      3.662 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1968 
    [ 2.500,  5.000) = 250352 
    [ 5.000,  7.500) = 7477 
    [ 7.500, 10.000) = 1363 
    [10.000, 12.500) = 344 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 146 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     21.070 ms/op
     p(99.9900) =     25.454 ms/op
     p(99.9990) =     27.504 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.541 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.600 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.240 ±(99.9%) 0.014 ms/op
Iteration   1: 4.347 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.606 ms/op
                 listUser·p0.50:   4.252 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  22.427 ms/op
                 listUser·p0.9999: 25.446 ms/op
                 listUser·p1.00:   26.214 ms/op

Iteration   2: 4.204 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   7.254 ms/op
                 listUser·p0.999:  16.773 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   3: 4.247 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   8.156 ms/op
                 listUser·p0.999:  15.577 ms/op
                 listUser·p0.9999: 19.051 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 224879
  mean =      4.265 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 210955 
    [ 5.000,  7.500) = 11796 
    [ 7.500, 10.000) = 1128 
    [10.000, 12.500) = 310 
    [12.500, 15.000) = 266 
    [15.000, 17.500) = 219 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      4.100 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     24.560 ms/op
     p(99.9990) =     25.674 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.147 ± 2.559  ops/ms
ClientPb.existUser                       thrpt       3   9.391 ± 1.521  ops/ms
ClientPb.getUser                         thrpt       3   9.137 ± 2.754  ops/ms
ClientPb.listUser                        thrpt       3   7.631 ± 1.994  ops/ms
ClientPb.createUser                       avgt       3   3.533 ± 1.028   ms/op
ClientPb.existUser                        avgt       3   3.492 ± 1.105   ms/op
ClientPb.getUser                          avgt       3   3.603 ± 0.584   ms/op
ClientPb.listUser                         avgt       3   4.156 ± 0.174   ms/op
ClientPb.createUser                     sample  267379   3.588 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.331           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.457           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.116           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.939           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.500           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.616           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.869           ms/op
ClientPb.existUser                      sample  277014   3.465 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.075           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.351           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.194           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.038           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.730           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.438           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.739           ms/op
ClientPb.getUser                        sample  261988   3.662 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.757           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.502           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.440           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.348           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.070           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.454           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.984           ms/op
ClientPb.listUser                       sample  224879   4.265 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.606           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.100           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.784           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.112           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.332           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.876           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.560           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.214           ms/op
