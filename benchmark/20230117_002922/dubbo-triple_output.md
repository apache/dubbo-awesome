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
# Warmup Iteration   1: 2.136 ops/ms
# Warmup Iteration   2: 5.654 ops/ms
# Warmup Iteration   3: 8.405 ops/ms
Iteration   1: 9.053 ops/ms
Iteration   2: 9.101 ops/ms
Iteration   3: 9.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.193 ±(99.9%) 3.698 ops/ms [Average]
  (min, avg, max) = (9.053, 9.193, 9.426), stdev = 0.203
  CI (99.9%): [5.496, 12.891] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.092 ops/ms
# Warmup Iteration   2: 8.341 ops/ms
# Warmup Iteration   3: 9.809 ops/ms
Iteration   1: 9.688 ops/ms
Iteration   2: 9.678 ops/ms
Iteration   3: 9.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.772 ±(99.9%) 2.824 ops/ms [Average]
  (min, avg, max) = (9.678, 9.772, 9.951), stdev = 0.155
  CI (99.9%): [6.948, 12.596] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.798 ops/ms
# Warmup Iteration   2: 7.695 ops/ms
# Warmup Iteration   3: 9.245 ops/ms
Iteration   1: 9.581 ops/ms
Iteration   2: 9.500 ops/ms
Iteration   3: 9.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.582 ±(99.9%) 1.521 ops/ms [Average]
  (min, avg, max) = (9.500, 9.582, 9.666), stdev = 0.083
  CI (99.9%): [8.061, 11.103] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.547 ops/ms
# Warmup Iteration   2: 6.958 ops/ms
# Warmup Iteration   3: 7.893 ops/ms
Iteration   1: 8.075 ops/ms
Iteration   2: 7.941 ops/ms
Iteration   3: 8.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.060 ±(99.9%) 2.046 ops/ms [Average]
  (min, avg, max) = (7.941, 8.060, 8.164), stdev = 0.112
  CI (99.9%): [6.014, 10.105] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 8.617 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.715 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.008 ms/op
Iteration   1: 3.422 ±(99.9%) 0.009 ms/op
Iteration   2: 3.398 ±(99.9%) 0.008 ms/op
Iteration   3: 3.290 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.370 ±(99.9%) 1.275 ms/op [Average]
  (min, avg, max) = (3.290, 3.370, 3.422), stdev = 0.070
  CI (99.9%): [2.095, 4.644] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.132 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.006 ms/op
Iteration   1: 3.404 ±(99.9%) 0.004 ms/op
Iteration   2: 3.202 ±(99.9%) 0.012 ms/op
Iteration   3: 3.343 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.317 ±(99.9%) 1.893 ms/op [Average]
  (min, avg, max) = (3.202, 3.317, 3.404), stdev = 0.104
  CI (99.9%): [1.424, 5.209] (assumes normal distribution)


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
# Warmup Iteration   1: 8.396 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.664 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.006 ms/op
Iteration   1: 3.500 ±(99.9%) 0.009 ms/op
Iteration   2: 3.472 ±(99.9%) 0.004 ms/op
Iteration   3: 3.420 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.464 ±(99.9%) 0.741 ms/op [Average]
  (min, avg, max) = (3.420, 3.464, 3.500), stdev = 0.041
  CI (99.9%): [2.723, 4.205] (assumes normal distribution)


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
# Warmup Iteration   1: 11.161 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.335 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.150 ±(99.9%) 0.008 ms/op
Iteration   1: 3.912 ±(99.9%) 0.012 ms/op
Iteration   2: 4.069 ±(99.9%) 0.008 ms/op
Iteration   3: 3.890 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.957 ±(99.9%) 1.782 ms/op [Average]
  (min, avg, max) = (3.890, 3.957, 4.069), stdev = 0.098
  CI (99.9%): [2.175, 5.738] (assumes normal distribution)


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
# Warmup Iteration   1: 11.264 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 3.955 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.652 ±(99.9%) 0.012 ms/op
Iteration   1: 3.555 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.577 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  20.218 ms/op
                 createUser·p0.9999: 22.381 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   2: 3.634 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.667 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   6.611 ms/op
                 createUser·p0.999:  21.269 ms/op
                 createUser·p0.9999: 26.673 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   3: 3.589 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.478 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  18.469 ms/op
                 createUser·p0.9999: 31.630 ms/op
                 createUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 266944
  mean =      3.592 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5480 
    [ 2.500,  5.000) = 251561 
    [ 5.000,  7.500) = 8877 
    [ 7.500, 10.000) = 535 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 146 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     19.857 ms/op
     p(99.9900) =     28.982 ms/op
     p(99.9990) =     32.615 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


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
# Warmup Iteration   1: 8.605 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.396 ±(99.9%) 0.009 ms/op
Iteration   1: 3.340 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.372 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.105 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  20.322 ms/op
                 existUser·p0.9999: 23.672 ms/op
                 existUser·p1.00:   24.642 ms/op

Iteration   2: 3.288 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  10.895 ms/op
                 existUser·p0.9999: 27.835 ms/op
                 existUser·p1.00:   28.869 ms/op

Iteration   3: 3.350 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   6.146 ms/op
                 existUser·p0.999:  26.702 ms/op
                 existUser·p0.9999: 33.817 ms/op
                 existUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288594
  mean =      3.326 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7403 
    [ 2.500,  5.000) = 274954 
    [ 5.000,  7.500) = 5338 
    [ 7.500, 10.000) = 415 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     18.912 ms/op
     p(99.9900) =     32.936 ms/op
     p(99.9990) =     35.653 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


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
# Warmup Iteration   1: 9.810 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.012 ms/op
Iteration   1: 3.531 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   7.258 ms/op
                 getUser·p0.999:  20.512 ms/op
                 getUser·p0.9999: 24.312 ms/op
                 getUser·p1.00:   24.609 ms/op

Iteration   2: 3.504 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.665 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  10.838 ms/op
                 getUser·p0.9999: 29.016 ms/op
                 getUser·p1.00:   29.426 ms/op

Iteration   3: 3.490 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  10.715 ms/op
                 getUser·p0.9999: 27.492 ms/op
                 getUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273441
  mean =      3.508 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6185 
    [ 2.500,  5.000) = 258147 
    [ 5.000,  7.500) = 7664 
    [ 7.500, 10.000) = 922 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     12.232 ms/op
     p(99.9900) =     27.656 ms/op
     p(99.9990) =     29.402 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.963 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.405 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.211 ±(99.9%) 0.013 ms/op
Iteration   1: 4.153 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  20.283 ms/op
                 listUser·p0.9999: 25.100 ms/op
                 listUser·p1.00:   25.657 ms/op

Iteration   2: 4.156 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.378 ms/op
                 listUser·p0.99:   8.135 ms/op
                 listUser·p0.999:  16.006 ms/op
                 listUser·p0.9999: 19.567 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   3: 4.017 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  15.490 ms/op
                 listUser·p0.9999: 18.743 ms/op
                 listUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233625
  mean =      4.108 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 221244 
    [ 5.000,  7.500) = 9054 
    [ 7.500, 10.000) = 2482 
    [10.000, 12.500) = 268 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      7.938 ms/op
     p(99.9000) =     16.689 ms/op
     p(99.9900) =     24.368 ms/op
     p(99.9990) =     25.460 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.193 ± 3.698  ops/ms
ClientPb.existUser                       thrpt       3   9.772 ± 2.824  ops/ms
ClientPb.getUser                         thrpt       3   9.582 ± 1.521  ops/ms
ClientPb.listUser                        thrpt       3   8.060 ± 2.046  ops/ms
ClientPb.createUser                       avgt       3   3.370 ± 1.275   ms/op
ClientPb.existUser                        avgt       3   3.317 ± 1.893   ms/op
ClientPb.getUser                          avgt       3   3.464 ± 0.741   ms/op
ClientPb.listUser                         avgt       3   3.957 ± 1.782   ms/op
ClientPb.createUser                     sample  266944   3.592 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.851           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.445           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.162           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.563           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.095           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.857           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.982           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.063           ms/op
ClientPb.existUser                      sample  288594   3.326 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.057           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.166           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.751           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.912           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.936           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.241           ms/op
ClientPb.getUser                        sample  273441   3.508 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.421           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.375           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.857           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.232           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.656           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.426           ms/op
ClientPb.listUser                       sample  233625   4.108 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.335           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.063           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.938           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.689           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.368           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.657           ms/op
