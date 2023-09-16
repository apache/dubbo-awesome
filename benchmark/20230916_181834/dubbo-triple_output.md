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
# Warmup Iteration   1: 2.102 ops/ms
# Warmup Iteration   2: 5.540 ops/ms
# Warmup Iteration   3: 8.435 ops/ms
Iteration   1: 9.089 ops/ms
Iteration   2: 9.114 ops/ms
Iteration   3: 9.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.135 ±(99.9%) 1.088 ops/ms [Average]
  (min, avg, max) = (9.089, 9.135, 9.203), stdev = 0.060
  CI (99.9%): [8.047, 10.223] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.336 ops/ms
# Warmup Iteration   2: 8.902 ops/ms
# Warmup Iteration   3: 9.544 ops/ms
Iteration   1: 9.621 ops/ms
Iteration   2: 9.734 ops/ms
Iteration   3: 9.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.689 ±(99.9%) 1.089 ops/ms [Average]
  (min, avg, max) = (9.621, 9.689, 9.734), stdev = 0.060
  CI (99.9%): [8.600, 10.778] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.102 ops/ms
# Warmup Iteration   2: 8.659 ops/ms
# Warmup Iteration   3: 9.084 ops/ms
Iteration   1: 9.200 ops/ms
Iteration   2: 9.234 ops/ms
Iteration   3: 9.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.256 ±(99.9%) 1.288 ops/ms [Average]
  (min, avg, max) = (9.200, 9.256, 9.336), stdev = 0.071
  CI (99.9%): [7.968, 10.544] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.638 ops/ms
# Warmup Iteration   2: 6.635 ops/ms
# Warmup Iteration   3: 7.760 ops/ms
Iteration   1: 7.697 ops/ms
Iteration   2: 7.595 ops/ms
Iteration   3: 7.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.645 ±(99.9%) 0.930 ops/ms [Average]
  (min, avg, max) = (7.595, 7.645, 7.697), stdev = 0.051
  CI (99.9%): [6.715, 8.575] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 10.860 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.796 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.651 ±(99.9%) 0.005 ms/op
Iteration   1: 3.543 ±(99.9%) 0.004 ms/op
Iteration   2: 3.511 ±(99.9%) 0.004 ms/op
Iteration   3: 3.510 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.521 ±(99.9%) 0.341 ms/op [Average]
  (min, avg, max) = (3.510, 3.521, 3.543), stdev = 0.019
  CI (99.9%): [3.180, 3.862] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.624 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.523 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.003 ms/op
Iteration   1: 3.319 ±(99.9%) 0.004 ms/op
Iteration   2: 3.349 ±(99.9%) 0.004 ms/op
Iteration   3: 3.317 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.328 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (3.317, 3.328, 3.349), stdev = 0.018
  CI (99.9%): [2.994, 3.663] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.207 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.003 ms/op
Iteration   1: 3.499 ±(99.9%) 0.005 ms/op
Iteration   2: 3.538 ±(99.9%) 0.003 ms/op
Iteration   3: 3.476 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.504 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (3.476, 3.504, 3.538), stdev = 0.031
  CI (99.9%): [2.937, 4.072] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.981 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.407 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.167 ±(99.9%) 0.008 ms/op
Iteration   1: 4.114 ±(99.9%) 0.006 ms/op
Iteration   2: 4.113 ±(99.9%) 0.009 ms/op
Iteration   3: 4.075 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.101 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (4.075, 4.101, 4.114), stdev = 0.022
  CI (99.9%): [3.695, 4.507] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.752 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.902 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.589 ±(99.9%) 0.010 ms/op
Iteration   1: 3.585 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.802 ms/op
                 createUser·p0.999:  10.285 ms/op
                 createUser·p0.9999: 23.563 ms/op
                 createUser·p1.00:   24.936 ms/op

Iteration   2: 3.520 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.755 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  22.033 ms/op
                 createUser·p0.9999: 24.936 ms/op
                 createUser·p1.00:   26.477 ms/op

Iteration   3: 3.451 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.454 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   6.914 ms/op
                 createUser·p0.999:  20.742 ms/op
                 createUser·p0.9999: 26.889 ms/op
                 createUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273042
  mean =      3.518 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8001 
    [ 2.500,  5.000) = 259353 
    [ 5.000,  7.500) = 4529 
    [ 7.500, 10.000) = 473 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 132 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     27.427 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 8.068 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.656 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.009 ms/op
Iteration   1: 3.360 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.434 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  12.779 ms/op
                 existUser·p0.9999: 23.838 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   2: 3.375 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  22.853 ms/op
                 existUser·p0.9999: 25.526 ms/op
                 existUser·p1.00:   26.608 ms/op

Iteration   3: 3.447 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  19.190 ms/op
                 existUser·p0.9999: 27.212 ms/op
                 existUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282837
  mean =      3.394 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4761 
    [ 2.500,  5.000) = 272777 
    [ 5.000,  7.500) = 4019 
    [ 7.500, 10.000) = 760 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 143 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     14.090 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     28.121 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 9.169 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.600 ±(99.9%) 0.010 ms/op
Iteration   1: 3.585 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.489 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  20.933 ms/op
                 getUser·p0.9999: 23.462 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   2: 3.486 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.169 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  22.451 ms/op
                 getUser·p0.9999: 25.029 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   3: 3.520 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.655 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  9.404 ms/op
                 getUser·p0.9999: 26.383 ms/op
                 getUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271891
  mean =      3.530 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1799 
    [ 2.500,  5.000) = 264056 
    [ 5.000,  7.500) = 4911 
    [ 7.500, 10.000) = 535 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 157 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     16.155 ms/op
     p(99.9900) =     25.100 ms/op
     p(99.9990) =     26.916 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.623 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.345 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.249 ±(99.9%) 0.012 ms/op
Iteration   1: 4.174 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  19.975 ms/op
                 listUser·p0.9999: 24.729 ms/op
                 listUser·p1.00:   25.723 ms/op

Iteration   2: 4.217 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.544 ms/op
                 listUser·p0.50:   4.108 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  15.107 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   3: 4.185 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.046 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  17.786 ms/op
                 listUser·p0.9999: 21.466 ms/op
                 listUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228928
  mean =      4.192 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 218943 
    [ 5.000,  7.500) = 8044 
    [ 7.500, 10.000) = 1069 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 269 
    [15.000, 17.500) = 291 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     23.433 ms/op
     p(99.9990) =     25.221 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.135 ± 1.088  ops/ms
ClientPb.existUser                       thrpt       3   9.689 ± 1.089  ops/ms
ClientPb.getUser                         thrpt       3   9.256 ± 1.288  ops/ms
ClientPb.listUser                        thrpt       3   7.645 ± 0.930  ops/ms
ClientPb.createUser                       avgt       3   3.521 ± 0.341   ms/op
ClientPb.existUser                        avgt       3   3.328 ± 0.335   ms/op
ClientPb.getUser                          avgt       3   3.504 ± 0.568   ms/op
ClientPb.listUser                         avgt       3   4.101 ± 0.406   ms/op
ClientPb.createUser                     sample  273042   3.518 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.208           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.070           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.514           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.723           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.492           ms/op
ClientPb.existUser                      sample  282837   3.394 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.887           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.988           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.090           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.345           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.246           ms/op
ClientPb.getUser                        sample  271891   3.530 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.169           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.428           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.149           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.997           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.155           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.100           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.329           ms/op
ClientPb.listUser                       sample  228928   4.192 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.288           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.047           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.907           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.160           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.039           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.433           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.723           ms/op
