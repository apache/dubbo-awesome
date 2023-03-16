# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.643 ops/ms
# Warmup Iteration   2: 6.435 ops/ms
# Warmup Iteration   3: 8.871 ops/ms
Iteration   1: 10.200 ops/ms
Iteration   2: 9.743 ops/ms
Iteration   3: 10.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.006 ±(99.9%) 4.311 ops/ms [Average]
  (min, avg, max) = (9.743, 10.006, 10.200), stdev = 0.236
  CI (99.9%): [5.695, 14.317] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.610 ops/ms
# Warmup Iteration   2: 9.135 ops/ms
# Warmup Iteration   3: 9.594 ops/ms
Iteration   1: 10.220 ops/ms
Iteration   2: 10.024 ops/ms
Iteration   3: 10.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.125 ±(99.9%) 1.795 ops/ms [Average]
  (min, avg, max) = (10.024, 10.125, 10.220), stdev = 0.098
  CI (99.9%): [8.330, 11.919] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.579 ops/ms
# Warmup Iteration   2: 9.276 ops/ms
# Warmup Iteration   3: 9.518 ops/ms
Iteration   1: 10.056 ops/ms
Iteration   2: 10.259 ops/ms
Iteration   3: 10.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.208 ±(99.9%) 2.441 ops/ms [Average]
  (min, avg, max) = (10.056, 10.208, 10.309), stdev = 0.134
  CI (99.9%): [7.767, 12.650] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.190 ops/ms
# Warmup Iteration   2: 7.971 ops/ms
# Warmup Iteration   3: 8.405 ops/ms
Iteration   1: 8.500 ops/ms
Iteration   2: 8.722 ops/ms
Iteration   3: 8.397 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.540 ±(99.9%) 3.035 ops/ms [Average]
  (min, avg, max) = (8.397, 8.540, 8.722), stdev = 0.166
  CI (99.9%): [5.505, 11.575] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.926 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.580 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.386 ±(99.9%) 0.005 ms/op
Iteration   1: 3.342 ±(99.9%) 0.005 ms/op
Iteration   2: 3.231 ±(99.9%) 0.004 ms/op
Iteration   3: 3.112 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.228 ±(99.9%) 2.095 ms/op [Average]
  (min, avg, max) = (3.112, 3.228, 3.342), stdev = 0.115
  CI (99.9%): [1.134, 5.323] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.745 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.003 ms/op
Iteration   1: 3.080 ±(99.9%) 0.003 ms/op
Iteration   2: 3.104 ±(99.9%) 0.004 ms/op
Iteration   3: 3.010 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.064 ±(99.9%) 0.889 ms/op [Average]
  (min, avg, max) = (3.010, 3.064, 3.104), stdev = 0.049
  CI (99.9%): [2.175, 3.954] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.085 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.480 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.003 ms/op
Iteration   1: 3.239 ±(99.9%) 0.005 ms/op
Iteration   2: 3.121 ±(99.9%) 0.004 ms/op
Iteration   3: 3.295 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.218 ±(99.9%) 1.625 ms/op [Average]
  (min, avg, max) = (3.121, 3.218, 3.295), stdev = 0.089
  CI (99.9%): [1.593, 4.844] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.523 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.005 ms/op
Iteration   1: 3.785 ±(99.9%) 0.007 ms/op
Iteration   2: 3.629 ±(99.9%) 0.010 ms/op
Iteration   3: 3.767 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.727 ±(99.9%) 1.558 ms/op [Average]
  (min, avg, max) = (3.629, 3.727, 3.785), stdev = 0.085
  CI (99.9%): [2.169, 5.285] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.116 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.748 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.315 ±(99.9%) 0.009 ms/op
Iteration   1: 3.219 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  9.038 ms/op
                 createUser·p0.9999: 21.143 ms/op
                 createUser·p1.00:   21.922 ms/op

Iteration   2: 3.245 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.278 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   5.274 ms/op
                 createUser·p0.999:  8.618 ms/op
                 createUser·p0.9999: 26.345 ms/op
                 createUser·p1.00:   26.968 ms/op

Iteration   3: 3.320 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.641 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   4.123 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  20.243 ms/op
                 createUser·p0.9999: 24.883 ms/op
                 createUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294210
  mean =      3.261 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23407 
    [ 2.500,  5.000) = 263792 
    [ 5.000,  7.500) = 6342 
    [ 7.500, 10.000) = 341 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     19.162 ms/op
     p(99.9900) =     25.119 ms/op
     p(99.9990) =     26.579 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.526 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.501 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.008 ms/op
Iteration   1: 3.164 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  8.117 ms/op
                 existUser·p0.9999: 19.784 ms/op
                 existUser·p1.00:   20.873 ms/op

Iteration   2: 3.129 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  13.443 ms/op
                 existUser·p0.9999: 28.461 ms/op
                 existUser·p1.00:   29.655 ms/op

Iteration   3: 3.241 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  12.255 ms/op
                 existUser·p0.9999: 22.938 ms/op
                 existUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302145
  mean =      3.177 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18095 
    [ 2.500,  5.000) = 278172 
    [ 5.000,  7.500) = 5137 
    [ 7.500, 10.000) = 362 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     11.942 ms/op
     p(99.9900) =     27.347 ms/op
     p(99.9990) =     28.901 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.190 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.462 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.011 ms/op
Iteration   1: 3.307 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   4.157 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  20.377 ms/op
                 getUser·p0.9999: 29.469 ms/op
                 getUser·p1.00:   30.081 ms/op

Iteration   2: 3.149 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.430 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   5.358 ms/op
                 getUser·p0.999:  9.185 ms/op
                 getUser·p0.9999: 24.079 ms/op
                 getUser·p1.00:   24.609 ms/op

Iteration   3: 3.249 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  16.646 ms/op
                 getUser·p0.9999: 20.223 ms/op
                 getUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296761
  mean =      3.234 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8115 
    [ 2.500,  5.000) = 280288 
    [ 5.000,  7.500) = 7486 
    [ 7.500, 10.000) = 473 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     17.244 ms/op
     p(99.9900) =     26.585 ms/op
     p(99.9990) =     29.786 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.147 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.352 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.761 ±(99.9%) 0.011 ms/op
Iteration   1: 3.947 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.784 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  17.233 ms/op
                 listUser·p0.9999: 19.264 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   2: 3.719 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.825 ms/op
                 listUser·p0.999:  14.320 ms/op
                 listUser·p0.9999: 16.384 ms/op
                 listUser·p1.00:   16.450 ms/op

Iteration   3: 3.784 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 19.595 ms/op
                 listUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251560
  mean =      3.814 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 242315 
    [ 5.000,  7.500) = 6883 
    [ 7.500, 10.000) = 1601 
    [10.000, 12.500) = 298 
    [12.500, 15.000) = 219 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.784 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     14.287 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     19.724 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.006 ± 4.311  ops/ms
ClientPb.existUser                       thrpt       3  10.125 ± 1.795  ops/ms
ClientPb.getUser                         thrpt       3  10.208 ± 2.441  ops/ms
ClientPb.listUser                        thrpt       3   8.540 ± 3.035  ops/ms
ClientPb.createUser                       avgt       3   3.228 ± 2.095   ms/op
ClientPb.existUser                        avgt       3   3.064 ± 0.889   ms/op
ClientPb.getUser                          avgt       3   3.218 ± 1.625   ms/op
ClientPb.listUser                         avgt       3   3.727 ± 1.558   ms/op
ClientPb.createUser                     sample  294210   3.261 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.641           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.587           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.162           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.119           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.968           ms/op
ClientPb.existUser                      sample  302145   3.177 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.779           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.026           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.538           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.942           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.347           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.655           ms/op
ClientPb.getUser                        sample  296761   3.234 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.843           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.568           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.029           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.244           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.585           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.081           ms/op
ClientPb.listUser                       sample  251560   3.814 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.784           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.711           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.389           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.287           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.235           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.218           ms/op
