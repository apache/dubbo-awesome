# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.110 ops/ms
# Warmup Iteration   2: 5.547 ops/ms
# Warmup Iteration   3: 8.343 ops/ms
Iteration   1: 9.403 ops/ms
Iteration   2: 9.008 ops/ms
Iteration   3: 9.090 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.167 ±(99.9%) 3.807 ops/ms [Average]
  (min, avg, max) = (9.008, 9.167, 9.403), stdev = 0.209
  CI (99.9%): [5.360, 12.974] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.316 ops/ms
# Warmup Iteration   2: 8.224 ops/ms
# Warmup Iteration   3: 9.336 ops/ms
Iteration   1: 9.874 ops/ms
Iteration   2: 9.769 ops/ms
Iteration   3: 9.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.828 ±(99.9%) 0.973 ops/ms [Average]
  (min, avg, max) = (9.769, 9.828, 9.874), stdev = 0.053
  CI (99.9%): [8.855, 10.801] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.306 ops/ms
# Warmup Iteration   2: 8.449 ops/ms
# Warmup Iteration   3: 8.990 ops/ms
Iteration   1: 9.194 ops/ms
Iteration   2: 9.661 ops/ms
Iteration   3: 9.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.452 ±(99.9%) 4.330 ops/ms [Average]
  (min, avg, max) = (9.194, 9.452, 9.661), stdev = 0.237
  CI (99.9%): [5.122, 13.783] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.841 ops/ms
# Warmup Iteration   2: 7.029 ops/ms
# Warmup Iteration   3: 7.874 ops/ms
Iteration   1: 8.018 ops/ms
Iteration   2: 7.858 ops/ms
Iteration   3: 8.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.994 ±(99.9%) 2.308 ops/ms [Average]
  (min, avg, max) = (7.858, 7.994, 8.108), stdev = 0.127
  CI (99.9%): [5.686, 10.302] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.615 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.081 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.582 ±(99.9%) 0.008 ms/op
Iteration   1: 3.581 ±(99.9%) 0.008 ms/op
Iteration   2: 3.374 ±(99.9%) 0.008 ms/op
Iteration   3: 3.531 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.496 ±(99.9%) 1.968 ms/op [Average]
  (min, avg, max) = (3.374, 3.496, 3.581), stdev = 0.108
  CI (99.9%): [1.528, 5.463] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.955 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.694 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.432 ±(99.9%) 0.011 ms/op
Iteration   1: 3.391 ±(99.9%) 0.005 ms/op
Iteration   2: 3.335 ±(99.9%) 0.003 ms/op
Iteration   3: 3.274 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.333 ±(99.9%) 1.075 ms/op [Average]
  (min, avg, max) = (3.274, 3.333, 3.391), stdev = 0.059
  CI (99.9%): [2.258, 4.408] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.330 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.004 ms/op
Iteration   1: 3.598 ±(99.9%) 0.005 ms/op
Iteration   2: 3.503 ±(99.9%) 0.003 ms/op
Iteration   3: 3.408 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.503 ±(99.9%) 1.729 ms/op [Average]
  (min, avg, max) = (3.408, 3.503, 3.598), stdev = 0.095
  CI (99.9%): [1.774, 5.232] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.258 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.408 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.008 ms/op
Iteration   1: 4.022 ±(99.9%) 0.012 ms/op
Iteration   2: 3.989 ±(99.9%) 0.011 ms/op
Iteration   3: 4.034 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.015 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (3.989, 4.015, 4.034), stdev = 0.023
  CI (99.9%): [3.589, 4.441] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.373 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.813 ±(99.9%) 0.014 ms/op
Iteration   1: 3.514 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.714 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  21.070 ms/op
                 createUser·p0.9999: 23.187 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   2: 3.552 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   6.218 ms/op
                 createUser·p0.999:  21.880 ms/op
                 createUser·p0.9999: 25.068 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   3: 3.530 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.700 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   6.431 ms/op
                 createUser·p0.999:  19.607 ms/op
                 createUser·p0.9999: 31.618 ms/op
                 createUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271683
  mean =      3.532 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6818 
    [ 2.500,  5.000) = 256680 
    [ 5.000,  7.500) = 6709 
    [ 7.500, 10.000) = 967 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     20.185 ms/op
     p(99.9900) =     30.806 ms/op
     p(99.9990) =     32.042 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.945 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.008 ms/op
Iteration   1: 3.324 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.021 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  17.038 ms/op
                 existUser·p0.9999: 22.213 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   2: 3.294 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.642 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  10.663 ms/op
                 existUser·p0.9999: 26.051 ms/op
                 existUser·p1.00:   27.263 ms/op

Iteration   3: 3.363 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.651 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  20.708 ms/op
                 existUser·p0.9999: 26.919 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288476
  mean =      3.327 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10362 
    [ 2.500,  5.000) = 271627 
    [ 5.000,  7.500) = 5203 
    [ 7.500, 10.000) = 880 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.021 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.286 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     26.018 ms/op
     p(99.9990) =     27.147 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.540 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.010 ms/op
Iteration   1: 3.424 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  18.874 ms/op
                 getUser·p0.9999: 23.615 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   2: 3.557 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.223 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.162 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  11.813 ms/op
                 getUser·p0.9999: 22.086 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   3: 3.503 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   6.925 ms/op
                 getUser·p0.999:  17.491 ms/op
                 getUser·p0.9999: 26.267 ms/op
                 getUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274614
  mean =      3.494 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9481 
    [ 2.500,  5.000) = 255420 
    [ 5.000,  7.500) = 7908 
    [ 7.500, 10.000) = 1312 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     14.696 ms/op
     p(99.9900) =     24.921 ms/op
     p(99.9990) =     26.419 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.512 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.580 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.224 ±(99.9%) 0.014 ms/op
Iteration   1: 4.051 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   7.905 ms/op
                 listUser·p0.999:  20.812 ms/op
                 listUser·p0.9999: 24.543 ms/op
                 listUser·p1.00:   26.771 ms/op

Iteration   2: 4.112 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   8.203 ms/op
                 listUser·p0.999:  15.434 ms/op
                 listUser·p0.9999: 20.029 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   3: 4.077 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   8.020 ms/op
                 listUser·p0.999:  16.138 ms/op
                 listUser·p0.9999: 20.593 ms/op
                 listUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235168
  mean =      4.080 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 223575 
    [ 5.000,  7.500) = 8426 
    [ 7.500, 10.000) = 2277 
    [10.000, 12.500) = 273 
    [12.500, 15.000) = 236 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      8.023 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     23.428 ms/op
     p(99.9990) =     25.105 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.167 ± 3.807  ops/ms
ClientPb.existUser                       thrpt       3   9.828 ± 0.973  ops/ms
ClientPb.getUser                         thrpt       3   9.452 ± 4.330  ops/ms
ClientPb.listUser                        thrpt       3   7.994 ± 2.308  ops/ms
ClientPb.createUser                       avgt       3   3.496 ± 1.968   ms/op
ClientPb.existUser                        avgt       3   3.333 ± 1.075   ms/op
ClientPb.getUser                          avgt       3   3.503 ± 1.729   ms/op
ClientPb.listUser                         avgt       3   4.015 ± 0.426   ms/op
ClientPb.createUser                     sample  271683   3.532 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.374           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.412           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.063           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.473           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.414           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.185           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.806           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.768           ms/op
ClientPb.existUser                      sample  288476   3.327 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.021           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.286           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.103           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.974           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.018           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.361           ms/op
ClientPb.getUser                        sample  274614   3.494 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.695           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.415           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.750           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.696           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.921           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.771           ms/op
ClientPb.listUser                       sample  235168   4.080 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.151           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.981           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.023           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.941           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.428           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.771           ms/op
