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
# Warmup Iteration   1: 1.874 ops/ms
# Warmup Iteration   2: 4.691 ops/ms
# Warmup Iteration   3: 8.316 ops/ms
Iteration   1: 8.842 ops/ms
Iteration   2: 9.092 ops/ms
Iteration   3: 9.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.066 ±(99.9%) 3.871 ops/ms [Average]
  (min, avg, max) = (8.842, 9.066, 9.264), stdev = 0.212
  CI (99.9%): [5.195, 12.937] (assumes normal distribution)


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
# Warmup Iteration   1: 2.735 ops/ms
# Warmup Iteration   2: 8.178 ops/ms
# Warmup Iteration   3: 9.165 ops/ms
Iteration   1: 9.326 ops/ms
Iteration   2: 9.668 ops/ms
Iteration   3: 9.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.518 ±(99.9%) 3.189 ops/ms [Average]
  (min, avg, max) = (9.326, 9.518, 9.668), stdev = 0.175
  CI (99.9%): [6.329, 12.707] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.689 ops/ms
# Warmup Iteration   2: 7.858 ops/ms
# Warmup Iteration   3: 9.115 ops/ms
Iteration   1: 9.225 ops/ms
Iteration   2: 9.387 ops/ms
Iteration   3: 9.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.329 ±(99.9%) 1.654 ops/ms [Average]
  (min, avg, max) = (9.225, 9.329, 9.387), stdev = 0.091
  CI (99.9%): [7.676, 10.983] (assumes normal distribution)


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
# Warmup Iteration   1: 2.712 ops/ms
# Warmup Iteration   2: 6.919 ops/ms
# Warmup Iteration   3: 7.714 ops/ms
Iteration   1: 7.657 ops/ms
Iteration   2: 7.824 ops/ms
Iteration   3: 8.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.901 ±(99.9%) 5.304 ops/ms [Average]
  (min, avg, max) = (7.657, 7.901, 8.223), stdev = 0.291
  CI (99.9%): [2.597, 13.205] (assumes normal distribution)


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
# Warmup Iteration   1: 9.387 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.010 ms/op
Iteration   1: 3.492 ±(99.9%) 0.009 ms/op
Iteration   2: 3.592 ±(99.9%) 0.004 ms/op
Iteration   3: 3.589 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.558 ±(99.9%) 1.044 ms/op [Average]
  (min, avg, max) = (3.492, 3.558, 3.592), stdev = 0.057
  CI (99.9%): [2.513, 4.602] (assumes normal distribution)


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
# Warmup Iteration   1: 7.740 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.004 ms/op
Iteration   1: 3.351 ±(99.9%) 0.006 ms/op
Iteration   2: 3.389 ±(99.9%) 0.009 ms/op
Iteration   3: 3.398 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.379 ±(99.9%) 0.451 ms/op [Average]
  (min, avg, max) = (3.351, 3.379, 3.398), stdev = 0.025
  CI (99.9%): [2.929, 3.830] (assumes normal distribution)


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
# Warmup Iteration   1: 10.022 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.863 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.006 ms/op
Iteration   1: 3.572 ±(99.9%) 0.005 ms/op
Iteration   2: 3.571 ±(99.9%) 0.004 ms/op
Iteration   3: 3.435 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.526 ±(99.9%) 1.435 ms/op [Average]
  (min, avg, max) = (3.435, 3.526, 3.572), stdev = 0.079
  CI (99.9%): [2.092, 4.961] (assumes normal distribution)


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
# Warmup Iteration   1: 10.644 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.481 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.152 ±(99.9%) 0.008 ms/op
Iteration   1: 4.064 ±(99.9%) 0.012 ms/op
Iteration   2: 4.115 ±(99.9%) 0.008 ms/op
Iteration   3: 4.074 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.084 ±(99.9%) 0.493 ms/op [Average]
  (min, avg, max) = (4.064, 4.084, 4.115), stdev = 0.027
  CI (99.9%): [3.591, 4.577] (assumes normal distribution)


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
# Warmup Iteration   1: 10.070 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 3.995 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.548 ±(99.9%) 0.010 ms/op
Iteration   1: 3.422 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.087 ms/op
                 createUser·p0.999:  9.978 ms/op
                 createUser·p0.9999: 24.039 ms/op
                 createUser·p1.00:   26.935 ms/op

Iteration   2: 3.543 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.405 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.845 ms/op
                 createUser·p0.99:   6.816 ms/op
                 createUser·p0.999:  22.610 ms/op
                 createUser·p0.9999: 25.690 ms/op
                 createUser·p1.00:   26.345 ms/op

Iteration   3: 3.527 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.742 ms/op
                 createUser·p0.999:  19.115 ms/op
                 createUser·p0.9999: 33.419 ms/op
                 createUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274291
  mean =      3.496 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4536 
    [ 2.500,  5.000) = 259925 
    [ 5.000,  7.500) = 8219 
    [ 7.500, 10.000) = 1141 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     14.008 ms/op
     p(99.9900) =     31.902 ms/op
     p(99.9990) =     33.998 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 9.938 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 3.717 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.009 ms/op
Iteration   1: 3.340 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  17.392 ms/op
                 existUser·p0.9999: 20.953 ms/op
                 existUser·p1.00:   22.118 ms/op

Iteration   2: 3.389 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.589 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.144 ms/op
                 existUser·p0.999:  18.341 ms/op
                 existUser·p0.9999: 23.841 ms/op
                 existUser·p1.00:   24.314 ms/op

Iteration   3: 3.445 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   6.546 ms/op
                 existUser·p0.999:  12.752 ms/op
                 existUser·p0.9999: 21.327 ms/op
                 existUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282776
  mean =      3.391 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12761 
    [ 2.500,  5.000) = 261637 
    [ 5.000,  7.500) = 7176 
    [ 7.500, 10.000) = 858 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      6.291 ms/op
     p(99.9000) =     12.780 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     24.254 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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
# Warmup Iteration   1: 11.619 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.590 ±(99.9%) 0.011 ms/op
Iteration   1: 3.605 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.438 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.963 ms/op
                 getUser·p0.99:   7.242 ms/op
                 getUser·p0.999:  21.587 ms/op
                 getUser·p0.9999: 29.275 ms/op
                 getUser·p1.00:   31.097 ms/op

Iteration   2: 3.468 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  21.751 ms/op
                 getUser·p0.9999: 29.149 ms/op
                 getUser·p1.00:   30.179 ms/op

Iteration   3: 3.583 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.450 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   7.406 ms/op
                 getUser·p0.999:  19.522 ms/op
                 getUser·p0.9999: 26.446 ms/op
                 getUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270157
  mean =      3.551 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4633 
    [ 2.500,  5.000) = 254663 
    [ 5.000,  7.500) = 8864 
    [ 7.500, 10.000) = 1351 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     21.430 ms/op
     p(99.9900) =     28.473 ms/op
     p(99.9990) =     30.133 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


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
# Warmup Iteration   1: 11.920 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.656 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.307 ±(99.9%) 0.015 ms/op
Iteration   1: 4.330 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   6.332 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  22.741 ms/op
                 listUser·p0.9999: 30.232 ms/op
                 listUser·p1.00:   30.835 ms/op

Iteration   2: 4.112 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.778 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   8.184 ms/op
                 listUser·p0.999:  15.909 ms/op
                 listUser·p0.9999: 21.536 ms/op
                 listUser·p1.00:   22.643 ms/op

Iteration   3: 3.999 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   7.617 ms/op
                 listUser·p0.999:  16.531 ms/op
                 listUser·p0.9999: 18.285 ms/op
                 listUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231705
  mean =      4.142 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 217251 
    [ 5.000,  7.500) = 11157 
    [ 7.500, 10.000) = 2005 
    [10.000, 12.500) = 694 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      8.323 ms/op
     p(99.9000) =     17.377 ms/op
     p(99.9900) =     28.693 ms/op
     p(99.9990) =     30.576 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.066 ± 3.871  ops/ms
ClientPb.existUser                       thrpt       3   9.518 ± 3.189  ops/ms
ClientPb.getUser                         thrpt       3   9.329 ± 1.654  ops/ms
ClientPb.listUser                        thrpt       3   7.901 ± 5.304  ops/ms
ClientPb.createUser                       avgt       3   3.558 ± 1.044   ms/op
ClientPb.existUser                        avgt       3   3.379 ± 0.451   ms/op
ClientPb.getUser                          avgt       3   3.526 ± 1.435   ms/op
ClientPb.listUser                         avgt       3   4.084 ± 0.493   ms/op
ClientPb.createUser                     sample  274291   3.496 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.051           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.010           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.801           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.562           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.008           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.902           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.144           ms/op
ClientPb.existUser                      sample  282776   3.391 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.972           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.153           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.291           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.780           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.741           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.314           ms/op
ClientPb.getUser                        sample  270157   3.551 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.264           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.547           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.922           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.430           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.473           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.097           ms/op
ClientPb.listUser                       sample  231705   4.142 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.290           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.210           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.323           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.377           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.693           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.835           ms/op
