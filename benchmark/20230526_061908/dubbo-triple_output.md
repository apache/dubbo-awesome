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
# Warmup Iteration   1: 2.059 ops/ms
# Warmup Iteration   2: 5.955 ops/ms
# Warmup Iteration   3: 9.019 ops/ms
Iteration   1: 9.226 ops/ms
Iteration   2: 9.580 ops/ms
Iteration   3: 9.405 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.404 ±(99.9%) 3.233 ops/ms [Average]
  (min, avg, max) = (9.226, 9.404, 9.580), stdev = 0.177
  CI (99.9%): [6.171, 12.636] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.002 ops/ms
# Warmup Iteration   2: 8.293 ops/ms
# Warmup Iteration   3: 8.790 ops/ms
Iteration   1: 9.639 ops/ms
Iteration   2: 9.794 ops/ms
Iteration   3: 9.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.780 ±(99.9%) 2.441 ops/ms [Average]
  (min, avg, max) = (9.639, 9.780, 9.906), stdev = 0.134
  CI (99.9%): [7.339, 12.220] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.815 ops/ms
# Warmup Iteration   2: 8.371 ops/ms
# Warmup Iteration   3: 8.944 ops/ms
Iteration   1: 9.166 ops/ms
Iteration   2: 9.620 ops/ms
Iteration   3: 9.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.346 ±(99.9%) 4.400 ops/ms [Average]
  (min, avg, max) = (9.166, 9.346, 9.620), stdev = 0.241
  CI (99.9%): [4.946, 13.746] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.843 ops/ms
# Warmup Iteration   2: 6.815 ops/ms
# Warmup Iteration   3: 7.875 ops/ms
Iteration   1: 8.186 ops/ms
Iteration   2: 7.983 ops/ms
Iteration   3: 8.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.071 ±(99.9%) 1.898 ops/ms [Average]
  (min, avg, max) = (7.983, 8.071, 8.186), stdev = 0.104
  CI (99.9%): [6.173, 9.969] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.732 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.007 ms/op
Iteration   1: 3.405 ±(99.9%) 0.006 ms/op
Iteration   2: 3.327 ±(99.9%) 0.008 ms/op
Iteration   3: 3.439 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.390 ±(99.9%) 1.053 ms/op [Average]
  (min, avg, max) = (3.327, 3.390, 3.439), stdev = 0.058
  CI (99.9%): [2.337, 4.443] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.720 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.414 ±(99.9%) 0.006 ms/op
Iteration   1: 3.238 ±(99.9%) 0.012 ms/op
Iteration   2: 3.312 ±(99.9%) 0.011 ms/op
Iteration   3: 3.296 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.282 ±(99.9%) 0.704 ms/op [Average]
  (min, avg, max) = (3.238, 3.282, 3.312), stdev = 0.039
  CI (99.9%): [2.578, 3.986] (assumes normal distribution)


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
# Warmup Iteration   1: 8.965 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.006 ms/op
Iteration   1: 3.565 ±(99.9%) 0.006 ms/op
Iteration   2: 3.367 ±(99.9%) 0.011 ms/op
Iteration   3: 3.315 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.416 ±(99.9%) 2.404 ms/op [Average]
  (min, avg, max) = (3.315, 3.416, 3.565), stdev = 0.132
  CI (99.9%): [1.012, 5.820] (assumes normal distribution)


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
# Warmup Iteration   1: 10.325 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.009 ms/op
Iteration   1: 3.922 ±(99.9%) 0.013 ms/op
Iteration   2: 4.039 ±(99.9%) 0.019 ms/op
Iteration   3: 3.878 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.946 ±(99.9%) 1.517 ms/op [Average]
  (min, avg, max) = (3.878, 3.946, 4.039), stdev = 0.083
  CI (99.9%): [2.429, 5.464] (assumes normal distribution)


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
# Warmup Iteration   1: 8.685 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.011 ms/op
Iteration   1: 3.495 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.649 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.794 ms/op
                 createUser·p0.999:  19.628 ms/op
                 createUser·p0.9999: 22.086 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   2: 3.430 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.454 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   4.850 ms/op
                 createUser·p0.999:  21.856 ms/op
                 createUser·p0.9999: 27.394 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   3: 3.581 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  20.626 ms/op
                 createUser·p0.9999: 29.394 ms/op
                 createUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274225
  mean =      3.501 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12291 
    [ 2.500,  5.000) = 256247 
    [ 5.000,  7.500) = 4915 
    [ 7.500, 10.000) = 422 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 141 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     20.269 ms/op
     p(99.9900) =     27.511 ms/op
     p(99.9990) =     29.565 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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
# Warmup Iteration   1: 7.968 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.402 ±(99.9%) 0.009 ms/op
Iteration   1: 3.311 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.174 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  14.358 ms/op
                 existUser·p0.9999: 22.326 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   2: 3.350 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.380 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  21.447 ms/op
                 existUser·p0.9999: 24.268 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   3: 3.415 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   6.324 ms/op
                 existUser·p0.999:  16.565 ms/op
                 existUser·p0.9999: 25.556 ms/op
                 existUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285686
  mean =      3.358 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12987 
    [ 2.500,  5.000) = 267345 
    [ 5.000,  7.500) = 4743 
    [ 7.500, 10.000) = 285 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     16.562 ms/op
     p(99.9900) =     24.983 ms/op
     p(99.9990) =     25.760 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 9.442 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.008 ms/op
Iteration   1: 3.543 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.368 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  19.965 ms/op
                 getUser·p0.9999: 24.280 ms/op
                 getUser·p1.00:   24.838 ms/op

Iteration   2: 3.472 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.454 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  21.253 ms/op
                 getUser·p0.9999: 24.216 ms/op
                 getUser·p1.00:   25.035 ms/op

Iteration   3: 3.603 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.251 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   6.742 ms/op
                 getUser·p0.999:  17.612 ms/op
                 getUser·p0.9999: 24.191 ms/op
                 getUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271219
  mean =      3.539 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9486 
    [ 2.500,  5.000) = 253161 
    [ 5.000,  7.500) = 7232 
    [ 7.500, 10.000) = 919 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 134 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.368 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     18.864 ms/op
     p(99.9900) =     24.216 ms/op
     p(99.9990) =     25.241 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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
# Warmup Iteration   1: 9.834 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.284 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.011 ms/op
Iteration   1: 3.934 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.105 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  20.808 ms/op
                 listUser·p0.9999: 24.663 ms/op
                 listUser·p1.00:   25.952 ms/op

Iteration   2: 4.130 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  14.165 ms/op
                 listUser·p0.9999: 17.727 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   3: 4.079 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   8.126 ms/op
                 listUser·p0.999:  14.418 ms/op
                 listUser·p0.9999: 22.381 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237151
  mean =      4.046 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 225720 
    [ 5.000,  7.500) = 8948 
    [ 7.500, 10.000) = 1593 
    [10.000, 12.500) = 325 
    [12.500, 15.000) = 270 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.105 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     23.101 ms/op
     p(99.9990) =     25.772 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.404 ± 3.233  ops/ms
ClientPb.existUser                       thrpt       3   9.780 ± 2.441  ops/ms
ClientPb.getUser                         thrpt       3   9.346 ± 4.400  ops/ms
ClientPb.listUser                        thrpt       3   8.071 ± 1.898  ops/ms
ClientPb.createUser                       avgt       3   3.390 ± 1.053   ms/op
ClientPb.existUser                        avgt       3   3.282 ± 0.704   ms/op
ClientPb.getUser                          avgt       3   3.416 ± 2.404   ms/op
ClientPb.listUser                         avgt       3   3.946 ± 1.517   ms/op
ClientPb.createUser                     sample  274225   3.501 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.149           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.162           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.415           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.718           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.269           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.511           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.590           ms/op
ClientPb.existUser                      sample  285686   3.358 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.696           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.030           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.562           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.983           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.051           ms/op
ClientPb.getUser                        sample  271219   3.539 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.368           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.396           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.481           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.373           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.864           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.216           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.297           ms/op
ClientPb.listUser                       sample  237151   4.046 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.105           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.973           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.561           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.139           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.101           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.952           ms/op
