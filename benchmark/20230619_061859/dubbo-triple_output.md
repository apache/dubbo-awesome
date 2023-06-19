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
# Warmup Iteration   1: 2.160 ops/ms
# Warmup Iteration   2: 5.169 ops/ms
# Warmup Iteration   3: 9.298 ops/ms
Iteration   1: 9.475 ops/ms
Iteration   2: 9.680 ops/ms
Iteration   3: 9.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.507 ±(99.9%) 2.901 ops/ms [Average]
  (min, avg, max) = (9.367, 9.507, 9.680), stdev = 0.159
  CI (99.9%): [6.606, 12.408] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.551 ops/ms
# Warmup Iteration   2: 9.113 ops/ms
# Warmup Iteration   3: 10.076 ops/ms
Iteration   1: 10.221 ops/ms
Iteration   2: 9.984 ops/ms
Iteration   3: 10.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.138 ±(99.9%) 2.428 ops/ms [Average]
  (min, avg, max) = (9.984, 10.138, 10.221), stdev = 0.133
  CI (99.9%): [7.710, 12.566] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.875 ops/ms
# Warmup Iteration   2: 8.298 ops/ms
# Warmup Iteration   3: 9.017 ops/ms
Iteration   1: 9.948 ops/ms
Iteration   2: 10.011 ops/ms
Iteration   3: 9.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.943 ±(99.9%) 1.293 ops/ms [Average]
  (min, avg, max) = (9.870, 9.943, 10.011), stdev = 0.071
  CI (99.9%): [8.650, 11.236] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.916 ops/ms
# Warmup Iteration   2: 7.515 ops/ms
# Warmup Iteration   3: 8.129 ops/ms
Iteration   1: 8.474 ops/ms
Iteration   2: 8.348 ops/ms
Iteration   3: 8.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.462 ±(99.9%) 1.984 ops/ms [Average]
  (min, avg, max) = (8.348, 8.462, 8.564), stdev = 0.109
  CI (99.9%): [6.478, 10.445] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.666 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.350 ±(99.9%) 0.009 ms/op
Iteration   1: 3.345 ±(99.9%) 0.003 ms/op
Iteration   2: 3.196 ±(99.9%) 0.004 ms/op
Iteration   3: 3.235 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.259 ±(99.9%) 1.401 ms/op [Average]
  (min, avg, max) = (3.196, 3.259, 3.345), stdev = 0.077
  CI (99.9%): [1.858, 4.660] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.550 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.008 ms/op
Iteration   1: 3.078 ±(99.9%) 0.004 ms/op
Iteration   2: 3.057 ±(99.9%) 0.002 ms/op
Iteration   3: 3.045 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.060 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (3.045, 3.060, 3.078), stdev = 0.017
  CI (99.9%): [2.754, 3.366] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.335 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.380 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.355 ±(99.9%) 0.003 ms/op
Iteration   1: 3.141 ±(99.9%) 0.003 ms/op
Iteration   2: 3.128 ±(99.9%) 0.005 ms/op
Iteration   3: 3.308 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.192 ±(99.9%) 1.828 ms/op [Average]
  (min, avg, max) = (3.128, 3.192, 3.308), stdev = 0.100
  CI (99.9%): [1.364, 5.020] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.962 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.178 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.815 ±(99.9%) 0.006 ms/op
Iteration   1: 3.820 ±(99.9%) 0.006 ms/op
Iteration   2: 3.744 ±(99.9%) 0.009 ms/op
Iteration   3: 3.688 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.751 ±(99.9%) 1.214 ms/op [Average]
  (min, avg, max) = (3.688, 3.751, 3.820), stdev = 0.067
  CI (99.9%): [2.536, 4.965] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.148 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.009 ms/op
Iteration   1: 3.228 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.282 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  18.350 ms/op
                 createUser·p0.9999: 20.945 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.006 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.269 ms/op
                 createUser·p0.95:   3.437 ms/op
                 createUser·p0.99:   4.948 ms/op
                 createUser·p0.999:  8.968 ms/op
                 createUser·p0.9999: 23.298 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   3: 3.210 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   4.034 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  14.991 ms/op
                 createUser·p0.9999: 21.695 ms/op
                 createUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301197
  mean =      3.186 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16266 
    [ 2.500,  5.000) = 278821 
    [ 5.000,  7.500) = 5186 
    [ 7.500, 10.000) = 418 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     16.889 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     23.756 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.353 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.008 ms/op
Iteration   1: 3.081 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.411 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  16.646 ms/op
                 existUser·p0.9999: 30.019 ms/op
                 existUser·p1.00:   30.507 ms/op

Iteration   2: 3.095 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   5.248 ms/op
                 existUser·p0.999:  12.960 ms/op
                 existUser·p0.9999: 21.768 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   3: 2.988 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.166 ms/op
                 existUser·p0.95:   3.322 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  14.559 ms/op
                 existUser·p0.9999: 23.242 ms/op
                 existUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314263
  mean =      3.054 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19278 
    [ 2.500,  5.000) = 290677 
    [ 5.000,  7.500) = 3326 
    [ 7.500, 10.000) = 472 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.252 ms/op
     p(95.0000) =      3.473 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =     14.725 ms/op
     p(99.9900) =     25.686 ms/op
     p(99.9990) =     30.437 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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
# Warmup Iteration   1: 8.465 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.012 ms/op
Iteration   1: 3.232 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.366 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  11.434 ms/op
                 getUser·p0.9999: 26.018 ms/op
                 getUser·p1.00:   26.935 ms/op

Iteration   2: 3.110 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.543 ms/op
                 getUser·p0.99:   4.891 ms/op
                 getUser·p0.999:  9.640 ms/op
                 getUser·p0.9999: 25.812 ms/op
                 getUser·p1.00:   26.247 ms/op

Iteration   3: 3.180 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.382 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  8.668 ms/op
                 getUser·p0.9999: 21.430 ms/op
                 getUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302348
  mean =      3.173 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16188 
    [ 2.500,  5.000) = 281495 
    [ 5.000,  7.500) = 4044 
    [ 7.500, 10.000) = 327 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.667 ms/op
     p(99.9900) =     25.682 ms/op
     p(99.9990) =     26.804 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 9.204 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.014 ms/op
Iteration   1: 3.745 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   6.546 ms/op
                 listUser·p0.999:  14.746 ms/op
                 listUser·p0.9999: 19.676 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   2: 3.796 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  12.648 ms/op
                 listUser·p0.9999: 18.055 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   3: 3.685 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.047 ms/op
                 listUser·p0.99:   5.818 ms/op
                 listUser·p0.999:  12.765 ms/op
                 listUser·p0.9999: 19.930 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256536
  mean =      3.741 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 250098 
    [ 5.000,  7.500) = 4866 
    [ 7.500, 10.000) = 887 
    [10.000, 12.500) = 290 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.114 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     13.124 ms/op
     p(99.9900) =     19.344 ms/op
     p(99.9990) =     20.808 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.507 ± 2.901  ops/ms
ClientPb.existUser                       thrpt       3  10.138 ± 2.428  ops/ms
ClientPb.getUser                         thrpt       3   9.943 ± 1.293  ops/ms
ClientPb.listUser                        thrpt       3   8.462 ± 1.984  ops/ms
ClientPb.createUser                       avgt       3   3.259 ± 1.401   ms/op
ClientPb.existUser                        avgt       3   3.060 ± 0.306   ms/op
ClientPb.getUser                          avgt       3   3.192 ± 1.828   ms/op
ClientPb.listUser                         avgt       3   3.751 ± 1.214   ms/op
ClientPb.createUser                     sample  301197   3.186 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.006           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.502           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.620           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.889           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.741           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.543           ms/op
ClientPb.existUser                      sample  314263   3.054 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.912           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.276           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.725           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.686           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.507           ms/op
ClientPb.getUser                        sample  302348   3.173 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.075           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.543           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.571           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.667           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.682           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.935           ms/op
ClientPb.listUser                       sample  256536   3.741 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.114           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.693           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.124           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.344           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.906           ms/op
