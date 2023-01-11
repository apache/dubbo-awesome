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
# Warmup Iteration   1: 2.137 ops/ms
# Warmup Iteration   2: 5.056 ops/ms
# Warmup Iteration   3: 8.738 ops/ms
Iteration   1: 9.380 ops/ms
Iteration   2: 9.248 ops/ms
Iteration   3: 9.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.299 ±(99.9%) 1.290 ops/ms [Average]
  (min, avg, max) = (9.248, 9.299, 9.380), stdev = 0.071
  CI (99.9%): [8.009, 10.589] (assumes normal distribution)


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
# Warmup Iteration   1: 3.639 ops/ms
# Warmup Iteration   2: 9.070 ops/ms
# Warmup Iteration   3: 9.438 ops/ms
Iteration   1: 9.104 ops/ms
Iteration   2: 9.700 ops/ms
Iteration   3: 9.770 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.525 ±(99.9%) 6.672 ops/ms [Average]
  (min, avg, max) = (9.104, 9.525, 9.770), stdev = 0.366
  CI (99.9%): [2.853, 16.197] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.444 ops/ms
# Warmup Iteration   2: 8.822 ops/ms
# Warmup Iteration   3: 8.934 ops/ms
Iteration   1: 9.100 ops/ms
Iteration   2: 9.471 ops/ms
Iteration   3: 9.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.201 ±(99.9%) 4.319 ops/ms [Average]
  (min, avg, max) = (9.031, 9.201, 9.471), stdev = 0.237
  CI (99.9%): [4.882, 13.520] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.916 ops/ms
# Warmup Iteration   2: 7.312 ops/ms
# Warmup Iteration   3: 8.074 ops/ms
Iteration   1: 8.094 ops/ms
Iteration   2: 8.224 ops/ms
Iteration   3: 8.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.169 ±(99.9%) 1.233 ops/ms [Average]
  (min, avg, max) = (8.094, 8.169, 8.224), stdev = 0.068
  CI (99.9%): [6.936, 9.402] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.320 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.765 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.008 ms/op
Iteration   1: 3.439 ±(99.9%) 0.003 ms/op
Iteration   2: 3.200 ±(99.9%) 0.012 ms/op
Iteration   3: 3.396 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.345 ±(99.9%) 2.328 ms/op [Average]
  (min, avg, max) = (3.200, 3.345, 3.439), stdev = 0.128
  CI (99.9%): [1.017, 5.673] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.601 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.543 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.005 ms/op
Iteration   1: 3.298 ±(99.9%) 0.006 ms/op
Iteration   2: 3.192 ±(99.9%) 0.003 ms/op
Iteration   3: 3.285 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.258 ±(99.9%) 1.057 ms/op [Average]
  (min, avg, max) = (3.192, 3.258, 3.298), stdev = 0.058
  CI (99.9%): [2.201, 4.315] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.943 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.457 ±(99.9%) 0.005 ms/op
Iteration   1: 3.352 ±(99.9%) 0.010 ms/op
Iteration   2: 3.485 ±(99.9%) 0.004 ms/op
Iteration   3: 3.369 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.402 ±(99.9%) 1.321 ms/op [Average]
  (min, avg, max) = (3.352, 3.402, 3.485), stdev = 0.072
  CI (99.9%): [2.081, 4.723] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.194 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.297 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.008 ms/op
Iteration   1: 3.975 ±(99.9%) 0.012 ms/op
Iteration   2: 3.870 ±(99.9%) 0.014 ms/op
Iteration   3: 3.928 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.924 ±(99.9%) 0.954 ms/op [Average]
  (min, avg, max) = (3.870, 3.924, 3.975), stdev = 0.052
  CI (99.9%): [2.970, 4.878] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.923 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.649 ±(99.9%) 0.013 ms/op
Iteration   1: 3.332 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  20.383 ms/op
                 createUser·p0.9999: 23.717 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   2: 3.508 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.339 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   7.059 ms/op
                 createUser·p0.999:  22.053 ms/op
                 createUser·p0.9999: 30.110 ms/op
                 createUser·p1.00:   31.162 ms/op

Iteration   3: 3.319 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.817 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  18.049 ms/op
                 createUser·p0.9999: 26.947 ms/op
                 createUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283562
  mean =      3.384 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9133 
    [ 2.500,  5.000) = 268297 
    [ 5.000,  7.500) = 4715 
    [ 7.500, 10.000) = 836 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     19.405 ms/op
     p(99.9900) =     28.724 ms/op
     p(99.9990) =     31.102 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


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
# Warmup Iteration   1: 7.636 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.584 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.007 ms/op
Iteration   1: 3.260 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.454 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  8.682 ms/op
                 existUser·p0.9999: 26.909 ms/op
                 existUser·p1.00:   28.508 ms/op

Iteration   2: 3.195 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.243 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.768 ms/op
                 existUser·p0.999:  12.366 ms/op
                 existUser·p0.9999: 28.341 ms/op
                 existUser·p1.00:   28.967 ms/op

Iteration   3: 3.349 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.485 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   6.349 ms/op
                 existUser·p0.999:  20.285 ms/op
                 existUser·p0.9999: 26.426 ms/op
                 existUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293743
  mean =      3.267 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14305 
    [ 2.500,  5.000) = 274077 
    [ 5.000,  7.500) = 4394 
    [ 7.500, 10.000) = 516 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 122 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     11.321 ms/op
     p(99.9900) =     27.361 ms/op
     p(99.9990) =     28.967 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 8.510 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.742 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.009 ms/op
Iteration   1: 3.335 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.561 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  20.597 ms/op
                 getUser·p0.9999: 29.164 ms/op
                 getUser·p1.00:   30.114 ms/op

Iteration   2: 3.423 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  24.606 ms/op
                 getUser·p0.9999: 34.931 ms/op
                 getUser·p1.00:   35.389 ms/op

Iteration   3: 3.466 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  16.415 ms/op
                 getUser·p0.9999: 26.174 ms/op
                 getUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281772
  mean =      3.407 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16952 
    [ 2.500,  5.000) = 257937 
    [ 5.000,  7.500) = 5609 
    [ 7.500, 10.000) = 830 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     33.423 ms/op
     p(99.9990) =     35.270 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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
# Warmup Iteration   1: 9.822 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.357 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.014 ms/op
Iteration   1: 3.993 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.761 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  19.065 ms/op
                 listUser·p0.9999: 24.150 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   2: 3.976 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.759 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.977 ms/op
                 listUser·p0.999:  15.909 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.859 ms/op

Iteration   3: 3.985 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  14.828 ms/op
                 listUser·p0.9999: 16.597 ms/op
                 listUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240807
  mean =      3.985 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 233023 
    [ 5.000,  7.500) = 5559 
    [ 7.500, 10.000) = 1328 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 242 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.759 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     16.128 ms/op
     p(99.9900) =     23.686 ms/op
     p(99.9990) =     24.347 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.299 ± 1.290  ops/ms
ClientPb.existUser                       thrpt       3   9.525 ± 6.672  ops/ms
ClientPb.getUser                         thrpt       3   9.201 ± 4.319  ops/ms
ClientPb.listUser                        thrpt       3   8.169 ± 1.233  ops/ms
ClientPb.createUser                       avgt       3   3.345 ± 2.328   ms/op
ClientPb.existUser                        avgt       3   3.258 ± 1.057   ms/op
ClientPb.getUser                          avgt       3   3.402 ± 1.321   ms/op
ClientPb.listUser                         avgt       3   3.924 ± 0.954   ms/op
ClientPb.createUser                     sample  283562   3.384 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.339           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.281           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.808           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.405           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.724           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.162           ms/op
ClientPb.existUser                      sample  293743   3.267 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.243           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.858           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.321           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.361           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.967           ms/op
ClientPb.getUser                        sample  281772   3.407 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.966           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.013           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.007           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.423           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.389           ms/op
ClientPb.listUser                       sample  240807   3.985 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.759           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.184           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.128           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.686           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.510           ms/op
