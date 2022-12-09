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
# Warmup Iteration   1: 2.740 ops/ms
# Warmup Iteration   2: 6.093 ops/ms
# Warmup Iteration   3: 9.302 ops/ms
Iteration   1: 10.032 ops/ms
Iteration   2: 10.041 ops/ms
Iteration   3: 9.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.727 ±(99.9%) 9.783 ops/ms [Average]
  (min, avg, max) = (9.108, 9.727, 10.041), stdev = 0.536
  CI (99.9%): [≈ 0, 19.510] (assumes normal distribution)


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
# Warmup Iteration   1: 3.528 ops/ms
# Warmup Iteration   2: 9.872 ops/ms
# Warmup Iteration   3: 10.249 ops/ms
Iteration   1: 10.477 ops/ms
Iteration   2: 10.889 ops/ms
Iteration   3: 10.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.591 ±(99.9%) 4.743 ops/ms [Average]
  (min, avg, max) = (10.408, 10.591, 10.889), stdev = 0.260
  CI (99.9%): [5.848, 15.334] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.481 ops/ms
# Warmup Iteration   2: 9.009 ops/ms
# Warmup Iteration   3: 9.875 ops/ms
Iteration   1: 10.145 ops/ms
Iteration   2: 10.242 ops/ms
Iteration   3: 10.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.137 ±(99.9%) 2.005 ops/ms [Average]
  (min, avg, max) = (10.023, 10.137, 10.242), stdev = 0.110
  CI (99.9%): [8.132, 12.142] (assumes normal distribution)


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
# Warmup Iteration   1: 3.174 ops/ms
# Warmup Iteration   2: 8.012 ops/ms
# Warmup Iteration   3: 8.413 ops/ms
Iteration   1: 8.596 ops/ms
Iteration   2: 8.418 ops/ms
Iteration   3: 8.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.506 ±(99.9%) 1.618 ops/ms [Average]
  (min, avg, max) = (8.418, 8.506, 8.596), stdev = 0.089
  CI (99.9%): [6.888, 10.124] (assumes normal distribution)


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
# Warmup Iteration   1: 8.366 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.379 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.004 ms/op
Iteration   1: 3.191 ±(99.9%) 0.010 ms/op
Iteration   2: 3.144 ±(99.9%) 0.008 ms/op
Iteration   3: 3.115 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.150 ±(99.9%) 0.701 ms/op [Average]
  (min, avg, max) = (3.115, 3.150, 3.191), stdev = 0.038
  CI (99.9%): [2.449, 3.851] (assumes normal distribution)


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
# Warmup Iteration   1: 7.866 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.297 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.004 ms/op
Iteration   1: 3.108 ±(99.9%) 0.002 ms/op
Iteration   2: 3.078 ±(99.9%) 0.007 ms/op
Iteration   3: 2.932 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.039 ±(99.9%) 1.722 ms/op [Average]
  (min, avg, max) = (2.932, 3.039, 3.108), stdev = 0.094
  CI (99.9%): [1.317, 4.762] (assumes normal distribution)


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
# Warmup Iteration   1: 7.675 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.472 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.002 ms/op
Iteration   1: 3.054 ±(99.9%) 0.007 ms/op
Iteration   2: 3.089 ±(99.9%) 0.002 ms/op
Iteration   3: 3.292 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.145 ±(99.9%) 2.345 ms/op [Average]
  (min, avg, max) = (3.054, 3.145, 3.292), stdev = 0.129
  CI (99.9%): [0.800, 5.490] (assumes normal distribution)


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
# Warmup Iteration   1: 8.222 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.020 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.705 ±(99.9%) 0.008 ms/op
Iteration   1: 3.759 ±(99.9%) 0.007 ms/op
Iteration   2: 3.622 ±(99.9%) 0.013 ms/op
Iteration   3: 3.657 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.680 ±(99.9%) 1.299 ms/op [Average]
  (min, avg, max) = (3.622, 3.680, 3.759), stdev = 0.071
  CI (99.9%): [2.381, 4.978] (assumes normal distribution)


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
# Warmup Iteration   1: 8.409 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.014 ms/op
Iteration   1: 3.209 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  12.421 ms/op
                 createUser·p0.9999: 21.633 ms/op
                 createUser·p1.00:   22.381 ms/op

Iteration   2: 3.236 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.243 ms/op
                 createUser·p0.999:  9.656 ms/op
                 createUser·p0.9999: 22.450 ms/op
                 createUser·p1.00:   23.560 ms/op

Iteration   3: 3.213 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  10.093 ms/op
                 createUser·p0.9999: 21.433 ms/op
                 createUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298103
  mean =      3.219 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18043 
    [ 2.500,  5.000) = 272835 
    [ 5.000,  7.500) = 6476 
    [ 7.500, 10.000) = 349 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     11.682 ms/op
     p(99.9900) =     22.059 ms/op
     p(99.9990) =     23.234 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 6.945 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.008 ms/op
Iteration   1: 3.073 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.417 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  12.124 ms/op
                 existUser·p0.9999: 19.877 ms/op
                 existUser·p1.00:   20.447 ms/op

Iteration   2: 3.047 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.143 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   5.104 ms/op
                 existUser·p0.999:  14.172 ms/op
                 existUser·p0.9999: 22.056 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   3: 3.068 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  8.962 ms/op
                 existUser·p0.9999: 19.825 ms/op
                 existUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313025
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27203 
    [ 2.500,  5.000) = 280799 
    [ 5.000,  7.500) = 4397 
    [ 7.500, 10.000) = 216 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     21.519 ms/op
     p(99.9990) =     22.737 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 7.689 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.541 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.249 ±(99.9%) 0.008 ms/op
Iteration   1: 3.185 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.669 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  16.992 ms/op
                 getUser·p0.9999: 30.999 ms/op
                 getUser·p1.00:   31.195 ms/op

Iteration   2: 3.085 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.355 ms/op
                 getUser·p0.95:   3.551 ms/op
                 getUser·p0.99:   5.161 ms/op
                 getUser·p0.999:  10.453 ms/op
                 getUser·p0.9999: 20.272 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   3: 3.270 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  9.867 ms/op
                 getUser·p0.9999: 23.338 ms/op
                 getUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301812
  mean =      3.178 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11659 
    [ 2.500,  5.000) = 284392 
    [ 5.000,  7.500) = 4982 
    [ 7.500, 10.000) = 420 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     16.482 ms/op
     p(99.9900) =     30.593 ms/op
     p(99.9990) =     31.129 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


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
# Warmup Iteration   1: 8.403 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.796 ±(99.9%) 0.012 ms/op
Iteration   1: 3.741 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.974 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  13.615 ms/op
                 listUser·p0.9999: 18.904 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   2: 3.737 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.077 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  13.688 ms/op
                 listUser·p0.9999: 15.958 ms/op
                 listUser·p1.00:   16.007 ms/op

Iteration   3: 3.729 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  12.354 ms/op
                 listUser·p0.9999: 13.746 ms/op
                 listUser·p1.00:   13.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256871
  mean =      3.736 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 249026 
    [ 5.000,  7.500) = 5654 
    [ 7.500, 10.000) = 1420 
    [10.000, 12.500) = 311 
    [12.500, 15.000) = 315 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.974 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     13.222 ms/op
     p(99.9900) =     17.420 ms/op
     p(99.9990) =     20.327 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.727 ± 9.783  ops/ms
ClientPb.existUser                       thrpt       3  10.591 ± 4.743  ops/ms
ClientPb.getUser                         thrpt       3  10.137 ± 2.005  ops/ms
ClientPb.listUser                        thrpt       3   8.506 ± 1.618  ops/ms
ClientPb.createUser                       avgt       3   3.150 ± 0.701   ms/op
ClientPb.existUser                        avgt       3   3.039 ± 1.722   ms/op
ClientPb.getUser                          avgt       3   3.145 ± 2.345   ms/op
ClientPb.listUser                         avgt       3   3.680 ± 1.299   ms/op
ClientPb.createUser                     sample  298103   3.219 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.953           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.415           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.682           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.059           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.560           ms/op
ClientPb.existUser                      sample  313025   3.063 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.085           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.267           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.058           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.519           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.298           ms/op
ClientPb.getUser                        sample  301812   3.178 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.934           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.527           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.734           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.482           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.593           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.195           ms/op
ClientPb.listUser                       sample  256871   3.736 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.974           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.641           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.084           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.258           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.222           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.420           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.856           ms/op
