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
# Warmup Iteration   1: 2.102 ops/ms
# Warmup Iteration   2: 5.343 ops/ms
# Warmup Iteration   3: 8.648 ops/ms
Iteration   1: 8.803 ops/ms
Iteration   2: 9.280 ops/ms
Iteration   3: 9.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.140 ±(99.9%) 5.350 ops/ms [Average]
  (min, avg, max) = (8.803, 9.140, 9.338), stdev = 0.293
  CI (99.9%): [3.790, 14.491] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.110 ops/ms
# Warmup Iteration   2: 9.003 ops/ms
# Warmup Iteration   3: 9.188 ops/ms
Iteration   1: 9.707 ops/ms
Iteration   2: 9.573 ops/ms
Iteration   3: 9.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.575 ±(99.9%) 2.390 ops/ms [Average]
  (min, avg, max) = (9.445, 9.575, 9.707), stdev = 0.131
  CI (99.9%): [7.186, 11.965] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.046 ops/ms
# Warmup Iteration   2: 8.311 ops/ms
# Warmup Iteration   3: 8.859 ops/ms
Iteration   1: 9.535 ops/ms
Iteration   2: 9.361 ops/ms
Iteration   3: 9.235 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.377 ±(99.9%) 2.744 ops/ms [Average]
  (min, avg, max) = (9.235, 9.377, 9.535), stdev = 0.150
  CI (99.9%): [6.633, 12.121] (assumes normal distribution)


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
# Warmup Iteration   1: 2.631 ops/ms
# Warmup Iteration   2: 6.586 ops/ms
# Warmup Iteration   3: 7.417 ops/ms
Iteration   1: 7.689 ops/ms
Iteration   2: 8.159 ops/ms
Iteration   3: 8.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.968 ±(99.9%) 4.513 ops/ms [Average]
  (min, avg, max) = (7.689, 7.968, 8.159), stdev = 0.247
  CI (99.9%): [3.456, 12.481] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 10.347 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.005 ms/op
Iteration   1: 3.525 ±(99.9%) 0.007 ms/op
Iteration   2: 3.432 ±(99.9%) 0.009 ms/op
Iteration   3: 3.429 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.462 ±(99.9%) 0.997 ms/op [Average]
  (min, avg, max) = (3.429, 3.462, 3.525), stdev = 0.055
  CI (99.9%): [2.465, 4.459] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.978 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.619 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.005 ms/op
Iteration   1: 3.288 ±(99.9%) 0.008 ms/op
Iteration   2: 3.281 ±(99.9%) 0.002 ms/op
Iteration   3: 3.402 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.324 ±(99.9%) 1.234 ms/op [Average]
  (min, avg, max) = (3.281, 3.324, 3.402), stdev = 0.068
  CI (99.9%): [2.090, 4.557] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.201 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.003 ms/op
Iteration   1: 3.458 ±(99.9%) 0.006 ms/op
Iteration   2: 3.338 ±(99.9%) 0.009 ms/op
Iteration   3: 3.408 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.401 ±(99.9%) 1.100 ms/op [Average]
  (min, avg, max) = (3.338, 3.401, 3.458), stdev = 0.060
  CI (99.9%): [2.302, 4.501] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.071 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.805 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.014 ms/op
Iteration   1: 4.047 ±(99.9%) 0.013 ms/op
Iteration   2: 4.036 ±(99.9%) 0.010 ms/op
Iteration   3: 4.072 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.052 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (4.036, 4.052, 4.072), stdev = 0.018
  CI (99.9%): [3.717, 4.387] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.853 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.448 ±(99.9%) 0.010 ms/op
Iteration   1: 3.407 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.210 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  19.440 ms/op
                 createUser·p0.9999: 22.643 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   2: 3.529 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.260 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  21.856 ms/op
                 createUser·p0.9999: 26.596 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   3: 3.392 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.395 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  18.612 ms/op
                 createUser·p0.9999: 25.053 ms/op
                 createUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278803
  mean =      3.442 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9593 
    [ 2.500,  5.000) = 262613 
    [ 5.000,  7.500) = 5468 
    [ 7.500, 10.000) = 672 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     18.730 ms/op
     p(99.9900) =     25.264 ms/op
     p(99.9990) =     27.041 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.869 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.720 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.355 ±(99.9%) 0.009 ms/op
Iteration   1: 3.263 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.245 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  9.174 ms/op
                 existUser·p0.9999: 33.751 ms/op
                 existUser·p1.00:   34.406 ms/op

Iteration   2: 3.573 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.374 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   6.349 ms/op
                 existUser·p0.999:  21.908 ms/op
                 existUser·p0.9999: 27.987 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   3: 3.538 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.714 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  20.513 ms/op
                 existUser·p0.9999: 27.555 ms/op
                 existUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278058
  mean =      3.452 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9272 
    [ 2.500,  5.000) = 261308 
    [ 5.000,  7.500) = 6472 
    [ 7.500, 10.000) = 714 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     10.911 ms/op
     p(99.9900) =     32.400 ms/op
     p(99.9990) =     34.341 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.382 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.948 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.008 ms/op
Iteration   1: 3.506 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   7.102 ms/op
                 getUser·p0.999:  19.458 ms/op
                 getUser·p0.9999: 25.100 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   2: 3.380 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.624 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  21.166 ms/op
                 getUser·p0.9999: 26.365 ms/op
                 getUser·p1.00:   28.148 ms/op

Iteration   3: 3.381 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.655 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  20.474 ms/op
                 getUser·p0.9999: 26.625 ms/op
                 getUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280473
  mean =      3.421 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5246 
    [ 2.500,  5.000) = 268066 
    [ 5.000,  7.500) = 5856 
    [ 7.500, 10.000) = 800 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 94 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     19.580 ms/op
     p(99.9900) =     26.310 ms/op
     p(99.9990) =     27.171 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 12.343 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.523 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.283 ±(99.9%) 0.015 ms/op
Iteration   1: 4.122 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.927 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  21.266 ms/op
                 listUser·p0.9999: 23.879 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   2: 3.980 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.872 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  16.049 ms/op
                 listUser·p0.9999: 21.197 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   3: 4.077 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   7.742 ms/op
                 listUser·p0.999:  15.028 ms/op
                 listUser·p0.9999: 16.597 ms/op
                 listUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236367
  mean =      4.059 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 227845 
    [ 5.000,  7.500) = 6090 
    [ 7.500, 10.000) = 1467 
    [10.000, 12.500) = 347 
    [12.500, 15.000) = 202 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.872 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     15.821 ms/op
     p(99.9900) =     22.875 ms/op
     p(99.9990) =     24.618 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.140 ± 5.350  ops/ms
ClientPb.existUser                       thrpt       3   9.575 ± 2.390  ops/ms
ClientPb.getUser                         thrpt       3   9.377 ± 2.744  ops/ms
ClientPb.listUser                        thrpt       3   7.968 ± 4.513  ops/ms
ClientPb.createUser                       avgt       3   3.462 ± 0.997   ms/op
ClientPb.existUser                        avgt       3   3.324 ± 1.234   ms/op
ClientPb.getUser                          avgt       3   3.401 ± 1.100   ms/op
ClientPb.listUser                         avgt       3   4.052 ± 0.335   ms/op
ClientPb.createUser                     sample  278803   3.442 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.210           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.005           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.730           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.264           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.165           ms/op
ClientPb.existUser                      sample  278058   3.452 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.219           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.322           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.112           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.481           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.185           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.911           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.400           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.406           ms/op
ClientPb.getUser                        sample  280473   3.421 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.092           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.611           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.580           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.310           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.148           ms/op
ClientPb.listUser                       sample  236367   4.059 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.872           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.537           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.821           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.875           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.642           ms/op
