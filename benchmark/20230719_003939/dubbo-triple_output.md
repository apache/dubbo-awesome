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
# Warmup Iteration   1: 2.151 ops/ms
# Warmup Iteration   2: 5.115 ops/ms
# Warmup Iteration   3: 8.378 ops/ms
Iteration   1: 8.974 ops/ms
Iteration   2: 8.932 ops/ms
Iteration   3: 9.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.974 ±(99.9%) 0.750 ops/ms [Average]
  (min, avg, max) = (8.932, 8.974, 9.015), stdev = 0.041
  CI (99.9%): [8.224, 9.723] (assumes normal distribution)


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
# Warmup Iteration   1: 3.404 ops/ms
# Warmup Iteration   2: 8.836 ops/ms
# Warmup Iteration   3: 9.297 ops/ms
Iteration   1: 9.763 ops/ms
Iteration   2: 9.736 ops/ms
Iteration   3: 9.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.637 ±(99.9%) 3.585 ops/ms [Average]
  (min, avg, max) = (9.410, 9.637, 9.763), stdev = 0.196
  CI (99.9%): [6.052, 13.221] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.377 ops/ms
# Warmup Iteration   2: 8.062 ops/ms
# Warmup Iteration   3: 8.871 ops/ms
Iteration   1: 9.003 ops/ms
Iteration   2: 9.252 ops/ms
Iteration   3: 9.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.125 ±(99.9%) 2.272 ops/ms [Average]
  (min, avg, max) = (9.003, 9.125, 9.252), stdev = 0.125
  CI (99.9%): [6.853, 11.396] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.994 ops/ms
# Warmup Iteration   2: 7.501 ops/ms
# Warmup Iteration   3: 7.760 ops/ms
Iteration   1: 7.936 ops/ms
Iteration   2: 7.860 ops/ms
Iteration   3: 8.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.950 ±(99.9%) 1.779 ops/ms [Average]
  (min, avg, max) = (7.860, 7.950, 8.054), stdev = 0.097
  CI (99.9%): [6.171, 9.728] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.095 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.857 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.533 ±(99.9%) 0.005 ms/op
Iteration   1: 3.385 ±(99.9%) 0.005 ms/op
Iteration   2: 3.412 ±(99.9%) 0.010 ms/op
Iteration   3: 3.344 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.381 ±(99.9%) 0.626 ms/op [Average]
  (min, avg, max) = (3.344, 3.381, 3.412), stdev = 0.034
  CI (99.9%): [2.755, 4.007] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.719 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.006 ms/op
Iteration   1: 3.368 ±(99.9%) 0.009 ms/op
Iteration   2: 3.212 ±(99.9%) 0.008 ms/op
Iteration   3: 3.189 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.256 ±(99.9%) 1.776 ms/op [Average]
  (min, avg, max) = (3.189, 3.256, 3.368), stdev = 0.097
  CI (99.9%): [1.480, 5.032] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 8.682 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.669 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.778 ±(99.9%) 0.004 ms/op
Iteration   1: 3.634 ±(99.9%) 0.003 ms/op
Iteration   2: 3.350 ±(99.9%) 0.006 ms/op
Iteration   3: 3.473 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.486 ±(99.9%) 2.599 ms/op [Average]
  (min, avg, max) = (3.350, 3.486, 3.634), stdev = 0.142
  CI (99.9%): [0.887, 6.085] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 10.131 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.008 ms/op
Iteration   1: 4.042 ±(99.9%) 0.007 ms/op
Iteration   2: 4.026 ±(99.9%) 0.008 ms/op
Iteration   3: 4.005 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.024 ±(99.9%) 0.341 ms/op [Average]
  (min, avg, max) = (4.005, 4.024, 4.042), stdev = 0.019
  CI (99.9%): [3.683, 4.366] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.982 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 4.006 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.010 ms/op
Iteration   1: 3.571 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   6.832 ms/op
                 createUser·p0.999:  20.620 ms/op
                 createUser·p0.9999: 25.366 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   2: 3.389 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  22.315 ms/op
                 createUser·p0.9999: 27.806 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   3: 3.390 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.339 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  21.223 ms/op
                 createUser·p0.9999: 28.836 ms/op
                 createUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278334
  mean =      3.448 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8174 
    [ 2.500,  5.000) = 262127 
    [ 5.000,  7.500) = 6914 
    [ 7.500, 10.000) = 635 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 71 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     21.201 ms/op
     p(99.9900) =     27.853 ms/op
     p(99.9990) =     29.557 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


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
# Warmup Iteration   1: 8.334 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.570 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.009 ms/op
Iteration   1: 3.314 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.040 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  13.972 ms/op
                 existUser·p0.9999: 21.836 ms/op
                 existUser·p1.00:   23.003 ms/op

Iteration   2: 3.228 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  19.002 ms/op
                 existUser·p0.9999: 25.202 ms/op
                 existUser·p1.00:   25.592 ms/op

Iteration   3: 3.267 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.386 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  8.897 ms/op
                 existUser·p0.9999: 32.604 ms/op
                 existUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293436
  mean =      3.269 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8350 
    [ 2.500,  5.000) = 280373 
    [ 5.000,  7.500) = 3885 
    [ 7.500, 10.000) = 377 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.040 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     14.405 ms/op
     p(99.9900) =     31.479 ms/op
     p(99.9990) =     33.296 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


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
# Warmup Iteration   1: 7.998 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.812 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.632 ±(99.9%) 0.012 ms/op
Iteration   1: 3.449 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.348 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.056 ms/op
                 getUser·p0.99:   6.575 ms/op
                 getUser·p0.999:  12.845 ms/op
                 getUser·p0.9999: 23.846 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   2: 3.444 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  23.008 ms/op
                 getUser·p0.9999: 26.345 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   3: 3.629 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.566 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   6.281 ms/op
                 getUser·p0.999:  19.624 ms/op
                 getUser·p0.9999: 27.924 ms/op
                 getUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273718
  mean =      3.505 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7154 
    [ 2.500,  5.000) = 258267 
    [ 5.000,  7.500) = 7226 
    [ 7.500, 10.000) = 652 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 69 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     13.009 ms/op
     p(99.9900) =     27.427 ms/op
     p(99.9990) =     28.630 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


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
# Warmup Iteration   1: 11.571 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.523 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.014 ms/op
Iteration   1: 4.157 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   8.110 ms/op
                 listUser·p0.999:  22.154 ms/op
                 listUser·p0.9999: 25.403 ms/op
                 listUser·p1.00:   26.444 ms/op

Iteration   2: 4.011 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  15.585 ms/op
                 listUser·p0.9999: 21.529 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   3: 4.038 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.034 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.961 ms/op
                 listUser·p0.999:  15.892 ms/op
                 listUser·p0.9999: 22.260 ms/op
                 listUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235909
  mean =      4.068 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 227388 
    [ 5.000,  7.500) = 5461 
    [ 7.500, 10.000) = 2145 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      2.034 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      7.930 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     24.557 ms/op
     p(99.9990) =     26.317 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.974 ± 0.750  ops/ms
ClientPb.existUser                       thrpt       3   9.637 ± 3.585  ops/ms
ClientPb.getUser                         thrpt       3   9.125 ± 2.272  ops/ms
ClientPb.listUser                        thrpt       3   7.950 ± 1.779  ops/ms
ClientPb.createUser                       avgt       3   3.381 ± 0.626   ms/op
ClientPb.existUser                        avgt       3   3.256 ± 1.776   ms/op
ClientPb.getUser                          avgt       3   3.486 ± 2.599   ms/op
ClientPb.listUser                         avgt       3   4.024 ± 0.341   ms/op
ClientPb.createUser                     sample  278334   3.448 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.023           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.309           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.193           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.201           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.853           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.917           ms/op
ClientPb.existUser                      sample  293436   3.269 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.040           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.227           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.579           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.405           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.479           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.341           ms/op
ClientPb.getUser                        sample  273718   3.505 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.566           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.604           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.009           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.427           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.262           ms/op
ClientPb.listUser                       sample  235909   4.068 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.034           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.930           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.334           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.557           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.444           ms/op
