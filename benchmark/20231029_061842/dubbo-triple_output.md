# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.018 ops/ms
# Warmup Iteration   2: 5.069 ops/ms
# Warmup Iteration   3: 8.299 ops/ms
Iteration   1: 8.829 ops/ms
Iteration   2: 8.912 ops/ms
Iteration   3: 8.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.901 ±(99.9%) 1.236 ops/ms [Average]
  (min, avg, max) = (8.829, 8.901, 8.963), stdev = 0.068
  CI (99.9%): [7.665, 10.137] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.070 ops/ms
# Warmup Iteration   2: 8.601 ops/ms
# Warmup Iteration   3: 9.086 ops/ms
Iteration   1: 9.315 ops/ms
Iteration   2: 9.652 ops/ms
Iteration   3: 9.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.523 ±(99.9%) 3.317 ops/ms [Average]
  (min, avg, max) = (9.315, 9.523, 9.652), stdev = 0.182
  CI (99.9%): [6.206, 12.839] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.972 ops/ms
# Warmup Iteration   2: 8.399 ops/ms
# Warmup Iteration   3: 8.986 ops/ms
Iteration   1: 9.055 ops/ms
Iteration   2: 9.102 ops/ms
Iteration   3: 9.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.193 ±(99.9%) 3.635 ops/ms [Average]
  (min, avg, max) = (9.055, 9.193, 9.421), stdev = 0.199
  CI (99.9%): [5.558, 12.828] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.111 ops/ms
# Warmup Iteration   2: 7.136 ops/ms
# Warmup Iteration   3: 7.596 ops/ms
Iteration   1: 7.709 ops/ms
Iteration   2: 7.710 ops/ms
Iteration   3: 7.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.694 ±(99.9%) 0.480 ops/ms [Average]
  (min, avg, max) = (7.664, 7.694, 7.710), stdev = 0.026
  CI (99.9%): [7.214, 8.174] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.844 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.833 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.650 ±(99.9%) 0.003 ms/op
Iteration   1: 3.727 ±(99.9%) 0.005 ms/op
Iteration   2: 3.577 ±(99.9%) 0.002 ms/op
Iteration   3: 3.492 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.599 ±(99.9%) 2.169 ms/op [Average]
  (min, avg, max) = (3.492, 3.599, 3.727), stdev = 0.119
  CI (99.9%): [1.430, 5.768] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.013 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.369 ±(99.9%) 0.003 ms/op
Iteration   1: 3.395 ±(99.9%) 0.005 ms/op
Iteration   2: 3.360 ±(99.9%) 0.005 ms/op
Iteration   3: 3.359 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.372 ±(99.9%) 0.376 ms/op [Average]
  (min, avg, max) = (3.359, 3.372, 3.395), stdev = 0.021
  CI (99.9%): [2.996, 3.747] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.472 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.802 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.003 ms/op
Iteration   1: 3.531 ±(99.9%) 0.005 ms/op
Iteration   2: 3.518 ±(99.9%) 0.005 ms/op
Iteration   3: 3.488 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.513 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (3.488, 3.513, 3.531), stdev = 0.022
  CI (99.9%): [3.106, 3.919] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.577 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.221 ±(99.9%) 0.009 ms/op
Iteration   1: 4.210 ±(99.9%) 0.005 ms/op
Iteration   2: 4.187 ±(99.9%) 0.008 ms/op
Iteration   3: 4.158 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.185 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (4.158, 4.185, 4.210), stdev = 0.026
  CI (99.9%): [3.712, 4.658] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.423 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.678 ±(99.9%) 0.011 ms/op
Iteration   1: 3.587 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  20.251 ms/op
                 createUser·p0.9999: 23.497 ms/op
                 createUser·p1.00:   25.133 ms/op

Iteration   2: 3.556 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.520 ms/op
                 createUser·p0.50:   3.461 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  10.915 ms/op
                 createUser·p0.9999: 24.053 ms/op
                 createUser·p1.00:   24.707 ms/op

Iteration   3: 3.545 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  19.262 ms/op
                 createUser·p0.9999: 35.716 ms/op
                 createUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269264
  mean =      3.562 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7101 
    [ 2.500,  5.000) = 257658 
    [ 5.000,  7.500) = 3638 
    [ 7.500, 10.000) = 383 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     16.801 ms/op
     p(99.9900) =     33.724 ms/op
     p(99.9990) =     35.934 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.823 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.760 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.008 ms/op
Iteration   1: 3.402 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.602 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  19.399 ms/op
                 existUser·p0.9999: 22.099 ms/op
                 existUser·p1.00:   23.036 ms/op

Iteration   2: 3.435 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  12.386 ms/op
                 existUser·p0.9999: 23.386 ms/op
                 existUser·p1.00:   23.658 ms/op

Iteration   3: 3.343 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.882 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  19.847 ms/op
                 existUser·p0.9999: 24.853 ms/op
                 existUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282660
  mean =      3.393 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5471 
    [ 2.500,  5.000) = 272765 
    [ 5.000,  7.500) = 3394 
    [ 7.500, 10.000) = 483 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 143 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     13.746 ms/op
     p(99.9900) =     23.551 ms/op
     p(99.9990) =     25.407 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.005 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.821 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.621 ±(99.9%) 0.010 ms/op
Iteration   1: 3.554 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.511 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.857 ms/op
                 getUser·p0.999:  10.142 ms/op
                 getUser·p0.9999: 22.184 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   2: 3.545 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.448 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   5.900 ms/op
                 getUser·p0.999:  20.939 ms/op
                 getUser·p0.9999: 23.461 ms/op
                 getUser·p1.00:   25.887 ms/op

Iteration   3: 3.490 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.378 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  21.823 ms/op
                 getUser·p0.9999: 24.543 ms/op
                 getUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271770
  mean =      3.529 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2097 
    [ 2.500,  5.000) = 263884 
    [ 5.000,  7.500) = 4786 
    [ 7.500, 10.000) = 444 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 142 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.378 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     15.347 ms/op
     p(99.9900) =     24.084 ms/op
     p(99.9990) =     24.913 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.288 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.440 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.203 ±(99.9%) 0.011 ms/op
Iteration   1: 4.092 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.681 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  17.821 ms/op
                 listUser·p0.9999: 25.866 ms/op
                 listUser·p1.00:   27.034 ms/op

Iteration   2: 4.132 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  16.122 ms/op
                 listUser·p0.9999: 18.186 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   3: 4.083 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  14.708 ms/op
                 listUser·p0.9999: 16.286 ms/op
                 listUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233903
  mean =      4.102 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 225341 
    [ 5.000,  7.500) = 6996 
    [ 7.500, 10.000) = 761 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.681 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     15.748 ms/op
     p(99.9900) =     24.268 ms/op
     p(99.9990) =     26.432 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.901 ± 1.236  ops/ms
ClientPb.existUser                       thrpt       3   9.523 ± 3.317  ops/ms
ClientPb.getUser                         thrpt       3   9.193 ± 3.635  ops/ms
ClientPb.listUser                        thrpt       3   7.694 ± 0.480  ops/ms
ClientPb.createUser                       avgt       3   3.599 ± 2.169   ms/op
ClientPb.existUser                        avgt       3   3.372 ± 0.376   ms/op
ClientPb.getUser                          avgt       3   3.513 ± 0.406   ms/op
ClientPb.listUser                         avgt       3   4.185 ± 0.473   ms/op
ClientPb.createUser                     sample  269264   3.562 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.190           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.449           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.125           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.825           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.801           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.724           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.241           ms/op
ClientPb.existUser                      sample  282660   3.393 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.958           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.973           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.746           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.551           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.625           ms/op
ClientPb.getUser                        sample  271770   3.529 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.378           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.420           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.084           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.242           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.347           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.084           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.887           ms/op
ClientPb.listUser                       sample  233903   4.102 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.681           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.825           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.988           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.748           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.268           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.034           ms/op
