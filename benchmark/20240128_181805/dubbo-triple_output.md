# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.253 ops/ms
# Warmup Iteration   2: 11.488 ops/ms
# Warmup Iteration   3: 11.886 ops/ms
Iteration   1: 12.088 ops/ms
Iteration   2: 12.228 ops/ms
Iteration   3: 12.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.223 ±(99.9%) 2.407 ops/ms [Average]
  (min, avg, max) = (12.088, 12.223, 12.352), stdev = 0.132
  CI (99.9%): [9.816, 14.630] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.847 ops/ms
# Warmup Iteration   2: 12.534 ops/ms
# Warmup Iteration   3: 12.599 ops/ms
Iteration   1: 12.681 ops/ms
Iteration   2: 12.694 ops/ms
Iteration   3: 12.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.669 ±(99.9%) 0.579 ops/ms [Average]
  (min, avg, max) = (12.633, 12.669, 12.694), stdev = 0.032
  CI (99.9%): [12.090, 13.249] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.269 ops/ms
# Warmup Iteration   2: 12.250 ops/ms
# Warmup Iteration   3: 12.513 ops/ms
Iteration   1: 12.449 ops/ms
Iteration   2: 12.469 ops/ms
Iteration   3: 12.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.425 ±(99.9%) 1.088 ops/ms [Average]
  (min, avg, max) = (12.357, 12.425, 12.469), stdev = 0.060
  CI (99.9%): [11.337, 13.513] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.618 ops/ms
# Warmup Iteration   2: 10.531 ops/ms
# Warmup Iteration   3: 10.561 ops/ms
Iteration   1: 10.608 ops/ms
Iteration   2: 10.440 ops/ms
Iteration   3: 10.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.518 ±(99.9%) 1.546 ops/ms [Average]
  (min, avg, max) = (10.440, 10.518, 10.608), stdev = 0.085
  CI (99.9%): [8.972, 12.065] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.214 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.665 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.004 ms/op
Iteration   1: 2.563 ±(99.9%) 0.004 ms/op
Iteration   2: 2.581 ±(99.9%) 0.005 ms/op
Iteration   3: 2.570 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.572 ±(99.9%) 0.167 ms/op [Average]
  (min, avg, max) = (2.563, 2.572, 2.581), stdev = 0.009
  CI (99.9%): [2.404, 2.739] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.015 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.004 ms/op
Iteration   1: 2.530 ±(99.9%) 0.004 ms/op
Iteration   2: 2.503 ±(99.9%) 0.003 ms/op
Iteration   3: 2.479 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.504 ±(99.9%) 0.464 ms/op [Average]
  (min, avg, max) = (2.479, 2.504, 2.530), stdev = 0.025
  CI (99.9%): [2.040, 2.968] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.884 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.577 ±(99.9%) 0.005 ms/op
Iteration   1: 2.613 ±(99.9%) 0.005 ms/op
Iteration   2: 2.577 ±(99.9%) 0.005 ms/op
Iteration   3: 2.572 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.587 ±(99.9%) 0.401 ms/op [Average]
  (min, avg, max) = (2.572, 2.587, 2.613), stdev = 0.022
  CI (99.9%): [2.187, 2.988] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.897 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.006 ms/op
Iteration   1: 3.095 ±(99.9%) 0.006 ms/op
Iteration   2: 3.088 ±(99.9%) 0.007 ms/op
Iteration   3: 3.059 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.080 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (3.059, 3.080, 3.095), stdev = 0.019
  CI (99.9%): [2.730, 3.431] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.144 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.764 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.641 ±(99.9%) 0.006 ms/op
Iteration   1: 2.628 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.207 ms/op
                 createUser·p0.95:   3.355 ms/op
                 createUser·p0.99:   3.924 ms/op
                 createUser·p0.999:  11.824 ms/op
                 createUser·p0.9999: 14.115 ms/op
                 createUser·p1.00:   14.483 ms/op

Iteration   2: 2.636 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   2.712 ms/op
                 createUser·p0.90:   3.207 ms/op
                 createUser·p0.95:   3.314 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  9.978 ms/op
                 createUser·p0.9999: 13.795 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   3: 2.637 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.985 ms/op
                 createUser·p0.50:   2.679 ms/op
                 createUser·p0.90:   3.211 ms/op
                 createUser·p0.95:   3.334 ms/op
                 createUser·p0.99:   3.969 ms/op
                 createUser·p0.999:  8.125 ms/op
                 createUser·p0.9999: 11.074 ms/op
                 createUser·p1.00:   14.500 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 364127
  mean =      2.633 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 25 
    [ 1.250,  2.500) = 171338 
    [ 2.500,  3.750) = 188229 
    [ 3.750,  5.000) = 3685 
    [ 5.000,  6.250) = 438 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      2.679 ms/op
     p(90.0000) =      3.211 ms/op
     p(95.0000) =      3.330 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      8.322 ms/op
     p(99.9900) =     13.657 ms/op
     p(99.9990) =     14.600 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.050 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.005 ms/op
Iteration   1: 2.550 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   2.609 ms/op
                 existUser·p0.90:   3.113 ms/op
                 existUser·p0.95:   3.224 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  5.743 ms/op
                 existUser·p0.9999: 14.122 ms/op
                 existUser·p1.00:   14.828 ms/op

Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.955 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.084 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  5.829 ms/op
                 existUser·p0.9999: 12.747 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   3: 2.568 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   2.634 ms/op
                 existUser·p0.90:   3.133 ms/op
                 existUser·p0.95:   3.244 ms/op
                 existUser·p0.99:   3.764 ms/op
                 existUser·p0.999:  8.946 ms/op
                 existUser·p0.9999: 12.428 ms/op
                 existUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 376161
  mean =      2.549 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 181569 
    [ 2.500,  3.750) = 191333 
    [ 3.750,  5.000) = 2503 
    [ 5.000,  6.250) = 333 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 124 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      6.461 ms/op
     p(99.9900) =     13.528 ms/op
     p(99.9990) =     14.766 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.653 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.573 ±(99.9%) 0.006 ms/op
Iteration   1: 2.555 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   3.858 ms/op
                 getUser·p0.999:  12.007 ms/op
                 getUser·p0.9999: 14.369 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   2: 2.559 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.067 ms/op
                 getUser·p0.999:  10.420 ms/op
                 getUser·p0.9999: 14.180 ms/op
                 getUser·p1.00:   14.909 ms/op

Iteration   3: 2.546 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  10.306 ms/op
                 getUser·p0.9999: 56.354 ms/op
                 getUser·p1.00:   57.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375631
  mean =      2.553 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 374511 
    [ 5.000, 10.000) = 727 
    [10.000, 15.000) = 351 
    [15.000, 20.000) = 4 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 3 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =     10.322 ms/op
     p(99.9900) =     23.402 ms/op
     p(99.9990) =     56.770 ms/op
     p(99.9999) =     57.278 ms/op
    p(100.0000) =     57.278 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.852 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.009 ms/op
Iteration   1: 3.100 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.999 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.029 ms/op
                 listUser·p0.999:  9.648 ms/op
                 listUser·p0.9999: 11.423 ms/op
                 listUser·p1.00:   12.730 ms/op

Iteration   2: 3.065 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  10.219 ms/op
                 listUser·p0.9999: 12.765 ms/op
                 listUser·p1.00:   13.779 ms/op

Iteration   3: 3.060 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.971 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.004 ms/op
                 listUser·p0.9999: 10.306 ms/op
                 listUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311861
  mean =      3.075 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 80460 
    [ 2.500,  3.750) = 189150 
    [ 3.750,  5.000) = 34358 
    [ 5.000,  6.250) = 6206 
    [ 6.250,  7.500) = 925 
    [ 7.500,  8.750) = 208 
    [ 8.750, 10.000) = 228 
    [10.000, 11.250) = 202 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.738 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     11.502 ms/op
     p(99.9990) =     13.613 ms/op
     p(99.9999) =     13.779 ms/op
    p(100.0000) =     13.779 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.223 ± 2.407  ops/ms
ClientPb.existUser                       thrpt       3  12.669 ± 0.579  ops/ms
ClientPb.getUser                         thrpt       3  12.425 ± 1.088  ops/ms
ClientPb.listUser                        thrpt       3  10.518 ± 1.546  ops/ms
ClientPb.createUser                       avgt       3   2.572 ± 0.167   ms/op
ClientPb.existUser                        avgt       3   2.504 ± 0.464   ms/op
ClientPb.getUser                          avgt       3   2.587 ± 0.401   ms/op
ClientPb.listUser                         avgt       3   3.080 ± 0.351   ms/op
ClientPb.createUser                     sample  364127   2.633 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.952           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.679           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.322           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.657           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.041           ms/op
ClientPb.existUser                      sample  376161   2.549 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.896           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.605           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.461           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.528           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.828           ms/op
ClientPb.getUser                        sample  375631   2.553 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.808           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.593           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.322           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.402           ms/op
ClientPb.getUser:getUser·p1.00          sample          57.278           ms/op
ClientPb.listUser                       sample  311861   3.075 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.971           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.019           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.738           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.634           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.502           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.779           ms/op
