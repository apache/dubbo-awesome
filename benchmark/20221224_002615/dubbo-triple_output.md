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
# Warmup Iteration   1: 2.526 ops/ms
# Warmup Iteration   2: 6.842 ops/ms
# Warmup Iteration   3: 9.294 ops/ms
Iteration   1: 10.123 ops/ms
Iteration   2: 9.696 ops/ms
Iteration   3: 9.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.845 ±(99.9%) 4.405 ops/ms [Average]
  (min, avg, max) = (9.696, 9.845, 10.123), stdev = 0.241
  CI (99.9%): [5.440, 14.250] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.804 ops/ms
# Warmup Iteration   2: 9.531 ops/ms
# Warmup Iteration   3: 10.396 ops/ms
Iteration   1: 10.531 ops/ms
Iteration   2: 10.413 ops/ms
Iteration   3: 10.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.550 ±(99.9%) 2.689 ops/ms [Average]
  (min, avg, max) = (10.413, 10.550, 10.706), stdev = 0.147
  CI (99.9%): [7.862, 13.239] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.601 ops/ms
# Warmup Iteration   2: 9.752 ops/ms
# Warmup Iteration   3: 9.711 ops/ms
Iteration   1: 10.249 ops/ms
Iteration   2: 10.552 ops/ms
Iteration   3: 10.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.296 ±(99.9%) 4.309 ops/ms [Average]
  (min, avg, max) = (10.087, 10.296, 10.552), stdev = 0.236
  CI (99.9%): [5.987, 14.605] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.555 ops/ms
# Warmup Iteration   2: 7.292 ops/ms
# Warmup Iteration   3: 8.487 ops/ms
Iteration   1: 8.572 ops/ms
Iteration   2: 8.448 ops/ms
Iteration   3: 8.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.542 ±(99.9%) 1.518 ops/ms [Average]
  (min, avg, max) = (8.448, 8.542, 8.606), stdev = 0.083
  CI (99.9%): [7.024, 10.060] (assumes normal distribution)


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
# Warmup Iteration   1: 7.900 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.400 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.006 ms/op
Iteration   1: 3.252 ±(99.9%) 0.008 ms/op
Iteration   2: 3.196 ±(99.9%) 0.005 ms/op
Iteration   3: 3.193 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.214 ±(99.9%) 0.610 ms/op [Average]
  (min, avg, max) = (3.193, 3.214, 3.252), stdev = 0.033
  CI (99.9%): [2.604, 3.823] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.945 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.005 ms/op
Iteration   1: 3.192 ±(99.9%) 0.002 ms/op
Iteration   2: 2.921 ±(99.9%) 0.005 ms/op
Iteration   3: 2.977 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.030 ±(99.9%) 2.613 ms/op [Average]
  (min, avg, max) = (2.921, 3.030, 3.192), stdev = 0.143
  CI (99.9%): [0.417, 5.643] (assumes normal distribution)


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
# Warmup Iteration   1: 7.183 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.333 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.002 ms/op
Iteration   1: 3.072 ±(99.9%) 0.004 ms/op
Iteration   2: 3.003 ±(99.9%) 0.002 ms/op
Iteration   3: 3.076 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.050 ±(99.9%) 0.744 ms/op [Average]
  (min, avg, max) = (3.003, 3.050, 3.076), stdev = 0.041
  CI (99.9%): [2.306, 3.795] (assumes normal distribution)


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
# Warmup Iteration   1: 8.668 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.015 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.699 ±(99.9%) 0.011 ms/op
Iteration   1: 3.699 ±(99.9%) 0.008 ms/op
Iteration   2: 3.682 ±(99.9%) 0.007 ms/op
Iteration   3: 3.593 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.658 ±(99.9%) 1.045 ms/op [Average]
  (min, avg, max) = (3.593, 3.658, 3.699), stdev = 0.057
  CI (99.9%): [2.613, 4.703] (assumes normal distribution)


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
# Warmup Iteration   1: 7.786 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.640 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.010 ms/op
Iteration   1: 3.212 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  15.978 ms/op
                 createUser·p0.9999: 20.744 ms/op
                 createUser·p1.00:   30.671 ms/op

Iteration   2: 3.252 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.266 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  16.966 ms/op
                 createUser·p0.9999: 24.942 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   3: 3.120 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.305 ms/op
                 createUser·p0.95:   3.543 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  16.515 ms/op
                 createUser·p0.9999: 20.808 ms/op
                 createUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300084
  mean =      3.194 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20737 
    [ 2.500,  5.000) = 274234 
    [ 5.000,  7.500) = 4214 
    [ 7.500, 10.000) = 344 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     16.515 ms/op
     p(99.9900) =     24.084 ms/op
     p(99.9990) =     27.818 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 6.713 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.007 ms/op
Iteration   1: 3.055 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.251 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  8.461 ms/op
                 existUser·p0.9999: 18.842 ms/op
                 existUser·p1.00:   19.235 ms/op

Iteration   2: 3.051 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   5.200 ms/op
                 existUser·p0.999:  13.631 ms/op
                 existUser·p0.9999: 22.349 ms/op
                 existUser·p1.00:   24.412 ms/op

Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.265 ms/op
                 existUser·p0.99:   4.899 ms/op
                 existUser·p0.999:  7.864 ms/op
                 existUser·p0.9999: 19.804 ms/op
                 existUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315809
  mean =      3.038 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31470 
    [ 2.500,  5.000) = 280636 
    [ 5.000,  7.500) = 3058 
    [ 7.500, 10.000) = 230 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 183 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.991 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.228 ms/op
     p(95.0000) =      3.437 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =     12.304 ms/op
     p(99.9900) =     20.808 ms/op
     p(99.9990) =     23.056 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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
# Warmup Iteration   1: 7.079 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.403 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.235 ±(99.9%) 0.009 ms/op
Iteration   1: 3.165 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  18.088 ms/op
                 getUser·p0.9999: 28.111 ms/op
                 getUser·p1.00:   29.131 ms/op

Iteration   2: 3.155 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.275 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.374 ms/op
                 getUser·p0.999:  9.154 ms/op
                 getUser·p0.9999: 24.432 ms/op
                 getUser·p1.00:   25.526 ms/op

Iteration   3: 3.239 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  14.363 ms/op
                 getUser·p0.9999: 18.822 ms/op
                 getUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301260
  mean =      3.186 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18863 
    [ 2.500,  5.000) = 273754 
    [ 5.000,  7.500) = 7728 
    [ 7.500, 10.000) = 454 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.275 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     14.991 ms/op
     p(99.9900) =     26.746 ms/op
     p(99.9990) =     28.474 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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
# Warmup Iteration   1: 8.154 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.013 ms/op
Iteration   1: 3.677 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   3.527 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 20.008 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   2: 3.730 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  12.846 ms/op
                 listUser·p0.9999: 14.451 ms/op
                 listUser·p1.00:   14.762 ms/op

Iteration   3: 3.593 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   3.719 ms/op
                 listUser·p0.95:   3.973 ms/op
                 listUser·p0.99:   6.275 ms/op
                 listUser·p0.999:  11.880 ms/op
                 listUser·p0.9999: 12.714 ms/op
                 listUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 261683
  mean =      3.666 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 253473 
    [ 5.000,  7.500) = 6520 
    [ 7.500, 10.000) = 1069 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     12.665 ms/op
     p(99.9900) =     18.809 ms/op
     p(99.9990) =     20.817 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.845 ± 4.405  ops/ms
ClientPb.existUser                       thrpt       3  10.550 ± 2.689  ops/ms
ClientPb.getUser                         thrpt       3  10.296 ± 4.309  ops/ms
ClientPb.listUser                        thrpt       3   8.542 ± 1.518  ops/ms
ClientPb.createUser                       avgt       3   3.214 ± 0.610   ms/op
ClientPb.existUser                        avgt       3   3.030 ± 2.613   ms/op
ClientPb.getUser                          avgt       3   3.050 ± 0.744   ms/op
ClientPb.listUser                         avgt       3   3.658 ± 1.045   ms/op
ClientPb.createUser                     sample  300084   3.194 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.722           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.658           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.515           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.084           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.671           ms/op
ClientPb.existUser                      sample  315809   3.038 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.991           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.437           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.128           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.304           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.808           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.412           ms/op
ClientPb.getUser                        sample  301260   3.186 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.275           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.186           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.136           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.991           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.746           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.131           ms/op
ClientPb.listUser                       sample  261683   3.666 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.235           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.576           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.742           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.665           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.809           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.594           ms/op
