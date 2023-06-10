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
# Warmup Iteration   1: 2.074 ops/ms
# Warmup Iteration   2: 5.360 ops/ms
# Warmup Iteration   3: 8.076 ops/ms
Iteration   1: 8.988 ops/ms
Iteration   2: 9.249 ops/ms
Iteration   3: 9.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.238 ±(99.9%) 4.452 ops/ms [Average]
  (min, avg, max) = (8.988, 9.238, 9.476), stdev = 0.244
  CI (99.9%): [4.785, 13.690] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.769 ops/ms
# Warmup Iteration   2: 8.418 ops/ms
# Warmup Iteration   3: 9.675 ops/ms
Iteration   1: 9.226 ops/ms
Iteration   2: 9.836 ops/ms
Iteration   3: 9.929 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.663 ±(99.9%) 6.963 ops/ms [Average]
  (min, avg, max) = (9.226, 9.663, 9.929), stdev = 0.382
  CI (99.9%): [2.700, 16.627] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.712 ops/ms
# Warmup Iteration   2: 7.537 ops/ms
# Warmup Iteration   3: 8.973 ops/ms
Iteration   1: 9.140 ops/ms
Iteration   2: 9.475 ops/ms
Iteration   3: 9.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.373 ±(99.9%) 3.695 ops/ms [Average]
  (min, avg, max) = (9.140, 9.373, 9.505), stdev = 0.203
  CI (99.9%): [5.678, 13.069] (assumes normal distribution)


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
# Warmup Iteration   1: 2.667 ops/ms
# Warmup Iteration   2: 7.295 ops/ms
# Warmup Iteration   3: 7.845 ops/ms
Iteration   1: 7.754 ops/ms
Iteration   2: 7.927 ops/ms
Iteration   3: 8.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.912 ±(99.9%) 2.746 ops/ms [Average]
  (min, avg, max) = (7.754, 7.912, 8.054), stdev = 0.151
  CI (99.9%): [5.166, 10.658] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.162 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.759 ±(99.9%) 0.005 ms/op
Iteration   1: 3.320 ±(99.9%) 0.011 ms/op
Iteration   2: 3.442 ±(99.9%) 0.008 ms/op
Iteration   3: 3.450 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.404 ±(99.9%) 1.323 ms/op [Average]
  (min, avg, max) = (3.320, 3.404, 3.450), stdev = 0.073
  CI (99.9%): [2.081, 4.727] (assumes normal distribution)


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
# Warmup Iteration   1: 10.722 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.007 ms/op
Iteration   1: 3.313 ±(99.9%) 0.004 ms/op
Iteration   2: 3.299 ±(99.9%) 0.008 ms/op
Iteration   3: 3.375 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.329 ±(99.9%) 0.734 ms/op [Average]
  (min, avg, max) = (3.299, 3.329, 3.375), stdev = 0.040
  CI (99.9%): [2.595, 4.063] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.691 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.005 ms/op
Iteration   1: 3.398 ±(99.9%) 0.011 ms/op
Iteration   2: 3.443 ±(99.9%) 0.011 ms/op
Iteration   3: 3.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.437 ±(99.9%) 0.671 ms/op [Average]
  (min, avg, max) = (3.398, 3.437, 3.471), stdev = 0.037
  CI (99.9%): [2.766, 4.108] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.130 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.654 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.014 ms/op
Iteration   1: 4.017 ±(99.9%) 0.010 ms/op
Iteration   2: 3.935 ±(99.9%) 0.017 ms/op
Iteration   3: 4.141 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.031 ±(99.9%) 1.893 ms/op [Average]
  (min, avg, max) = (3.935, 4.031, 4.141), stdev = 0.104
  CI (99.9%): [2.139, 5.924] (assumes normal distribution)


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
# Warmup Iteration   1: 9.565 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.136 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.553 ±(99.9%) 0.011 ms/op
Iteration   1: 3.467 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  21.110 ms/op
                 createUser·p0.9999: 27.197 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   2: 3.432 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  22.245 ms/op
                 createUser·p0.9999: 31.263 ms/op
                 createUser·p1.00:   32.702 ms/op

Iteration   3: 3.520 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.659 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   6.947 ms/op
                 createUser·p0.999:  20.003 ms/op
                 createUser·p0.9999: 34.865 ms/op
                 createUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276210
  mean =      3.473 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7173 
    [ 2.500,  5.000) = 260866 
    [ 5.000,  7.500) = 6905 
    [ 7.500, 10.000) = 665 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     20.932 ms/op
     p(99.9900) =     32.408 ms/op
     p(99.9990) =     35.274 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.433 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.582 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.008 ms/op
Iteration   1: 3.356 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.972 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  8.159 ms/op
                 existUser·p0.9999: 25.951 ms/op
                 existUser·p1.00:   26.247 ms/op

Iteration   2: 3.412 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.559 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.145 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  21.048 ms/op
                 existUser·p0.9999: 24.960 ms/op
                 existUser·p1.00:   27.165 ms/op

Iteration   3: 3.324 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  16.387 ms/op
                 existUser·p0.9999: 24.096 ms/op
                 existUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285115
  mean =      3.364 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7833 
    [ 2.500,  5.000) = 272550 
    [ 5.000,  7.500) = 3781 
    [ 7.500, 10.000) = 342 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.470 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     13.400 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     26.191 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 9.857 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.843 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.634 ±(99.9%) 0.012 ms/op
Iteration   1: 3.543 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.809 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.186 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.341 ms/op
                 getUser·p0.999:  20.535 ms/op
                 getUser·p0.9999: 27.295 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   2: 3.410 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.765 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   5.783 ms/op
                 getUser·p0.999:  21.898 ms/op
                 getUser·p0.9999: 25.592 ms/op
                 getUser·p1.00:   26.542 ms/op

Iteration   3: 3.478 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  19.036 ms/op
                 getUser·p0.9999: 41.746 ms/op
                 getUser·p1.00:   42.992 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276258
  mean =      3.476 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 269351 
    [ 5.000, 10.000) = 6377 
    [10.000, 15.000) = 208 
    [15.000, 20.000) = 52 
    [20.000, 25.000) = 180 
    [25.000, 30.000) = 58 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     40.632 ms/op
     p(99.9990) =     42.876 ms/op
     p(99.9999) =     42.992 ms/op
    p(100.0000) =     42.992 ms/op


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
# Warmup Iteration   1: 11.037 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.407 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.243 ±(99.9%) 0.013 ms/op
Iteration   1: 4.128 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.255 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  20.429 ms/op
                 listUser·p0.9999: 25.681 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   2: 4.159 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.661 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.913 ms/op
                 listUser·p0.999:  15.303 ms/op
                 listUser·p0.9999: 23.668 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   3: 4.085 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.272 ms/op
                 listUser·p0.999:  16.631 ms/op
                 listUser·p0.9999: 18.285 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232739
  mean =      4.124 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 223536 
    [ 5.000,  7.500) = 6794 
    [ 7.500, 10.000) = 1569 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 201 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     17.081 ms/op
     p(99.9900) =     23.781 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.238 ± 4.452  ops/ms
ClientPb.existUser                       thrpt       3   9.663 ± 6.963  ops/ms
ClientPb.getUser                         thrpt       3   9.373 ± 3.695  ops/ms
ClientPb.listUser                        thrpt       3   7.912 ± 2.746  ops/ms
ClientPb.createUser                       avgt       3   3.404 ± 1.323   ms/op
ClientPb.existUser                        avgt       3   3.329 ± 0.734   ms/op
ClientPb.getUser                          avgt       3   3.437 ± 0.671   ms/op
ClientPb.listUser                         avgt       3   4.031 ± 1.893   ms/op
ClientPb.createUser                     sample  276210   3.473 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.362           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.473           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.283           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.932           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.408           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.652           ms/op
ClientPb.existUser                      sample  285115   3.364 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.470           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.751           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.400           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.428           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.165           ms/op
ClientPb.getUser                        sample  276258   3.476 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.809           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.226           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.923           ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.632           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.992           ms/op
ClientPb.listUser                       sample  232739   4.124 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.255           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.520           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.081           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.781           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.116           ms/op
