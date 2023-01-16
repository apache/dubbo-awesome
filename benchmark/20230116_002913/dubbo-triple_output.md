# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.758 ops/ms
# Warmup Iteration   2: 6.454 ops/ms
# Warmup Iteration   3: 9.253 ops/ms
Iteration   1: 10.015 ops/ms
Iteration   2: 9.725 ops/ms
Iteration   3: 9.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.749 ±(99.9%) 4.645 ops/ms [Average]
  (min, avg, max) = (9.507, 9.749, 10.015), stdev = 0.255
  CI (99.9%): [5.104, 14.394] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.634 ops/ms
# Warmup Iteration   2: 9.509 ops/ms
# Warmup Iteration   3: 10.241 ops/ms
Iteration   1: 10.525 ops/ms
Iteration   2: 9.977 ops/ms
Iteration   3: 10.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.461 ±(99.9%) 8.306 ops/ms [Average]
  (min, avg, max) = (9.977, 10.461, 10.881), stdev = 0.455
  CI (99.9%): [2.155, 18.766] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.534 ops/ms
# Warmup Iteration   2: 9.182 ops/ms
# Warmup Iteration   3: 10.085 ops/ms
Iteration   1: 9.760 ops/ms
Iteration   2: 10.082 ops/ms
Iteration   3: 10.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.997 ±(99.9%) 3.777 ops/ms [Average]
  (min, avg, max) = (9.760, 9.997, 10.147), stdev = 0.207
  CI (99.9%): [6.220, 13.773] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.559 ops/ms
# Warmup Iteration   2: 8.144 ops/ms
# Warmup Iteration   3: 8.454 ops/ms
Iteration   1: 8.787 ops/ms
Iteration   2: 8.502 ops/ms
Iteration   3: 8.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.681 ±(99.9%) 2.855 ops/ms [Average]
  (min, avg, max) = (8.502, 8.681, 8.787), stdev = 0.156
  CI (99.9%): [5.827, 11.536] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.628 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.530 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.004 ms/op
Iteration   1: 3.171 ±(99.9%) 0.007 ms/op
Iteration   2: 3.157 ±(99.9%) 0.009 ms/op
Iteration   3: 3.058 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.129 ±(99.9%) 1.118 ms/op [Average]
  (min, avg, max) = (3.058, 3.129, 3.171), stdev = 0.061
  CI (99.9%): [2.011, 4.247] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.398 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.007 ms/op
Iteration   1: 3.069 ±(99.9%) 0.008 ms/op
Iteration   2: 3.119 ±(99.9%) 0.004 ms/op
Iteration   3: 3.103 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.097 ±(99.9%) 0.465 ms/op [Average]
  (min, avg, max) = (3.069, 3.097, 3.119), stdev = 0.025
  CI (99.9%): [2.632, 3.562] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.576 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.003 ms/op
Iteration   1: 3.102 ±(99.9%) 0.004 ms/op
Iteration   2: 3.155 ±(99.9%) 0.005 ms/op
Iteration   3: 3.110 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.122 ±(99.9%) 0.523 ms/op [Average]
  (min, avg, max) = (3.102, 3.122, 3.155), stdev = 0.029
  CI (99.9%): [2.599, 3.645] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.649 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.101 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.007 ms/op
Iteration   1: 3.809 ±(99.9%) 0.007 ms/op
Iteration   2: 3.748 ±(99.9%) 0.005 ms/op
Iteration   3: 3.738 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.765 ±(99.9%) 0.703 ms/op [Average]
  (min, avg, max) = (3.738, 3.765, 3.809), stdev = 0.039
  CI (99.9%): [3.062, 4.468] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.972 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.630 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.008 ms/op
Iteration   1: 3.156 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  18.570 ms/op
                 createUser·p0.9999: 24.314 ms/op
                 createUser·p1.00:   25.002 ms/op

Iteration   2: 3.175 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  9.410 ms/op
                 createUser·p0.9999: 21.004 ms/op
                 createUser·p1.00:   21.823 ms/op

Iteration   3: 3.309 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.466 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  13.829 ms/op
                 createUser·p0.9999: 18.043 ms/op
                 createUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298875
  mean =      3.212 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21968 
    [ 2.500,  5.000) = 269923 
    [ 5.000,  7.500) = 6153 
    [ 7.500, 10.000) = 309 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 164 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     15.155 ms/op
     p(99.9900) =     23.022 ms/op
     p(99.9990) =     24.807 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.905 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.007 ms/op
Iteration   1: 3.076 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  10.600 ms/op
                 existUser·p0.9999: 25.488 ms/op
                 existUser·p1.00:   26.739 ms/op

Iteration   2: 3.106 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.559 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  11.437 ms/op
                 existUser·p0.9999: 22.043 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   3: 3.287 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  8.769 ms/op
                 existUser·p0.9999: 24.556 ms/op
                 existUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304252
  mean =      3.154 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20155 
    [ 2.500,  5.000) = 279148 
    [ 5.000,  7.500) = 4239 
    [ 7.500, 10.000) = 339 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     11.038 ms/op
     p(99.9900) =     24.745 ms/op
     p(99.9990) =     26.411 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.925 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.590 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.011 ms/op
Iteration   1: 3.056 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.380 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.310 ms/op
                 getUser·p0.95:   3.510 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  9.847 ms/op
                 getUser·p0.9999: 20.876 ms/op
                 getUser·p1.00:   21.561 ms/op

Iteration   2: 3.130 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  11.158 ms/op
                 getUser·p0.9999: 25.716 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   3: 3.160 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.253 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  12.632 ms/op
                 getUser·p0.9999: 18.641 ms/op
                 getUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 308065
  mean =      3.115 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11282 
    [ 2.500,  5.000) = 291263 
    [ 5.000,  7.500) = 4745 
    [ 7.500, 10.000) = 404 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     12.452 ms/op
     p(99.9900) =     24.681 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.966 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.152 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.743 ±(99.9%) 0.011 ms/op
Iteration   1: 3.697 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  14.926 ms/op
                 listUser·p0.9999: 22.219 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   2: 3.729 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  14.844 ms/op
                 listUser·p0.9999: 18.004 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   3: 3.815 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.490 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.040 ms/op
                 listUser·p0.999:  14.631 ms/op
                 listUser·p0.9999: 18.055 ms/op
                 listUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256128
  mean =      3.746 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 248596 
    [ 5.000,  7.500) = 5832 
    [ 7.500, 10.000) = 1001 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 295 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.530 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     14.858 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     24.244 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.749 ± 4.645  ops/ms
ClientPb.existUser                       thrpt       3  10.461 ± 8.306  ops/ms
ClientPb.getUser                         thrpt       3   9.997 ± 3.777  ops/ms
ClientPb.listUser                        thrpt       3   8.681 ± 2.855  ops/ms
ClientPb.createUser                       avgt       3   3.129 ± 1.118   ms/op
ClientPb.existUser                        avgt       3   3.097 ± 0.465   ms/op
ClientPb.getUser                          avgt       3   3.122 ± 0.523   ms/op
ClientPb.listUser                         avgt       3   3.765 ± 0.703   ms/op
ClientPb.createUser                     sample  298875   3.212 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.957           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.596           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.084           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.521           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.155           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.022           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.002           ms/op
ClientPb.existUser                      sample  304252   3.154 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.987           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.341           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.038           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.745           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.739           ms/op
ClientPb.getUser                        sample  308065   3.115 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.953           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.408           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.666           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.538           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.452           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.681           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.837           ms/op
ClientPb.listUser                       sample  256128   3.746 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.530           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.043           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.832           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.858           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.087           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.347           ms/op
