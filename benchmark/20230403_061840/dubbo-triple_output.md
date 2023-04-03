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
# Warmup Iteration   1: 2.759 ops/ms
# Warmup Iteration   2: 7.054 ops/ms
# Warmup Iteration   3: 9.216 ops/ms
Iteration   1: 9.715 ops/ms
Iteration   2: 9.775 ops/ms
Iteration   3: 10.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.890 ±(99.9%) 4.619 ops/ms [Average]
  (min, avg, max) = (9.715, 9.890, 10.181), stdev = 0.253
  CI (99.9%): [5.271, 14.510] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.482 ops/ms
# Warmup Iteration   2: 9.524 ops/ms
# Warmup Iteration   3: 9.980 ops/ms
Iteration   1: 10.355 ops/ms
Iteration   2: 10.017 ops/ms
Iteration   3: 10.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.146 ±(99.9%) 3.335 ops/ms [Average]
  (min, avg, max) = (10.017, 10.146, 10.355), stdev = 0.183
  CI (99.9%): [6.811, 13.481] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.538 ops/ms
# Warmup Iteration   2: 8.685 ops/ms
# Warmup Iteration   3: 9.963 ops/ms
Iteration   1: 10.434 ops/ms
Iteration   2: 10.319 ops/ms
Iteration   3: 9.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.187 ±(99.9%) 6.070 ops/ms [Average]
  (min, avg, max) = (9.809, 10.187, 10.434), stdev = 0.333
  CI (99.9%): [4.118, 16.257] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.285 ops/ms
# Warmup Iteration   2: 7.626 ops/ms
# Warmup Iteration   3: 8.278 ops/ms
Iteration   1: 8.593 ops/ms
Iteration   2: 8.566 ops/ms
Iteration   3: 8.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.630 ±(99.9%) 1.606 ops/ms [Average]
  (min, avg, max) = (8.566, 8.630, 8.730), stdev = 0.088
  CI (99.9%): [7.024, 10.235] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.424 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.511 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.001 ms/op
Iteration   1: 3.401 ±(99.9%) 0.007 ms/op
Iteration   2: 3.329 ±(99.9%) 0.005 ms/op
Iteration   3: 3.148 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.293 ±(99.9%) 2.385 ms/op [Average]
  (min, avg, max) = (3.148, 3.293, 3.401), stdev = 0.131
  CI (99.9%): [0.908, 5.677] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.199 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.283 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.006 ms/op
Iteration   1: 3.048 ±(99.9%) 0.003 ms/op
Iteration   2: 3.138 ±(99.9%) 0.004 ms/op
Iteration   3: 3.027 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.071 ±(99.9%) 1.073 ms/op [Average]
  (min, avg, max) = (3.027, 3.071, 3.138), stdev = 0.059
  CI (99.9%): [1.997, 4.144] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.568 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.429 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.004 ms/op
Iteration   1: 3.266 ±(99.9%) 0.005 ms/op
Iteration   2: 3.242 ±(99.9%) 0.008 ms/op
Iteration   3: 3.055 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.188 ±(99.9%) 2.108 ms/op [Average]
  (min, avg, max) = (3.055, 3.188, 3.266), stdev = 0.116
  CI (99.9%): [1.080, 5.295] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.261 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.068 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.875 ±(99.9%) 0.006 ms/op
Iteration   1: 3.746 ±(99.9%) 0.009 ms/op
Iteration   2: 3.721 ±(99.9%) 0.006 ms/op
Iteration   3: 3.691 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.719 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (3.691, 3.719, 3.746), stdev = 0.028
  CI (99.9%): [3.218, 4.221] (assumes normal distribution)


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
# Warmup Iteration   1: 8.065 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.910 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
Iteration   1: 3.142 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  16.912 ms/op
                 createUser·p0.9999: 21.772 ms/op
                 createUser·p1.00:   22.217 ms/op

Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.153 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.252 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  11.150 ms/op
                 createUser·p0.9999: 20.546 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   3: 3.147 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  9.627 ms/op
                 createUser·p0.9999: 16.487 ms/op
                 createUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305084
  mean =      3.145 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27013 
    [ 2.500,  5.000) = 271338 
    [ 5.000,  7.500) = 5844 
    [ 7.500, 10.000) = 499 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     14.087 ms/op
     p(99.9900) =     20.988 ms/op
     p(99.9990) =     21.955 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.823 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.009 ms/op
Iteration   1: 3.236 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  8.536 ms/op
                 existUser·p0.9999: 20.917 ms/op
                 existUser·p1.00:   21.463 ms/op

Iteration   2: 3.023 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.186 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.359 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  8.667 ms/op
                 existUser·p0.9999: 27.886 ms/op
                 existUser·p1.00:   28.148 ms/op

Iteration   3: 3.180 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.266 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.694 ms/op
                 existUser·p0.999:  14.656 ms/op
                 existUser·p0.9999: 21.847 ms/op
                 existUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305239
  mean =      3.144 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23173 
    [ 2.500,  5.000) = 276252 
    [ 5.000,  7.500) = 5174 
    [ 7.500, 10.000) = 265 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     14.223 ms/op
     p(99.9900) =     26.314 ms/op
     p(99.9990) =     28.079 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 8.239 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.010 ms/op
Iteration   1: 3.252 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.327 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  16.562 ms/op
                 getUser·p0.9999: 19.977 ms/op
                 getUser·p1.00:   21.365 ms/op

Iteration   2: 3.233 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.153 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  11.896 ms/op
                 getUser·p0.9999: 22.810 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   3: 3.163 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  11.232 ms/op
                 getUser·p0.9999: 28.054 ms/op
                 getUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298365
  mean =      3.215 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13847 
    [ 2.500,  5.000) = 277423 
    [ 5.000,  7.500) = 6325 
    [ 7.500, 10.000) = 399 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.778 ms/op
     p(99.9000) =     13.194 ms/op
     p(99.9900) =     25.040 ms/op
     p(99.9990) =     28.312 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 8.968 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.249 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.786 ±(99.9%) 0.011 ms/op
Iteration   1: 3.704 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.935 ms/op
                 listUser·p0.999:  15.149 ms/op
                 listUser·p0.9999: 23.015 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   2: 3.805 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.107 ms/op
                 listUser·p0.9999: 17.780 ms/op
                 listUser·p1.00:   17.891 ms/op

Iteration   3: 3.845 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  13.120 ms/op
                 listUser·p0.9999: 16.728 ms/op
                 listUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253687
  mean =      3.784 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 244923 
    [ 5.000,  7.500) = 7017 
    [ 7.500, 10.000) = 938 
    [10.000, 12.500) = 295 
    [12.500, 15.000) = 286 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     22.291 ms/op
     p(99.9990) =     23.904 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.890 ± 4.619  ops/ms
ClientPb.existUser                       thrpt       3  10.146 ± 3.335  ops/ms
ClientPb.getUser                         thrpt       3  10.187 ± 6.070  ops/ms
ClientPb.listUser                        thrpt       3   8.630 ± 1.606  ops/ms
ClientPb.createUser                       avgt       3   3.293 ± 2.385   ms/op
ClientPb.existUser                        avgt       3   3.071 ± 1.073   ms/op
ClientPb.getUser                          avgt       3   3.188 ± 2.108   ms/op
ClientPb.listUser                         avgt       3   3.719 ± 0.502   ms/op
ClientPb.createUser                     sample  305084   3.145 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.083           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.087           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.988           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.217           ms/op
ClientPb.existUser                      sample  305239   3.144 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.928           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.527           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.439           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.223           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.314           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.148           ms/op
ClientPb.getUser                        sample  298365   3.215 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.153           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.621           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.778           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.194           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.040           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.410           ms/op
ClientPb.listUser                       sample  253687   3.784 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.270           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.703           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.100           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.906           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.959           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.291           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.281           ms/op
