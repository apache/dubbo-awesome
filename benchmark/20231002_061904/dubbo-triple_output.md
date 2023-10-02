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
# Warmup Iteration   1: 2.040 ops/ms
# Warmup Iteration   2: 5.339 ops/ms
# Warmup Iteration   3: 8.460 ops/ms
Iteration   1: 9.036 ops/ms
Iteration   2: 9.034 ops/ms
Iteration   3: 9.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.043 ±(99.9%) 0.244 ops/ms [Average]
  (min, avg, max) = (9.034, 9.043, 9.058), stdev = 0.013
  CI (99.9%): [8.799, 9.287] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.668 ops/ms
# Warmup Iteration   2: 8.563 ops/ms
# Warmup Iteration   3: 9.210 ops/ms
Iteration   1: 9.324 ops/ms
Iteration   2: 9.412 ops/ms
Iteration   3: 9.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.365 ±(99.9%) 0.803 ops/ms [Average]
  (min, avg, max) = (9.324, 9.365, 9.412), stdev = 0.044
  CI (99.9%): [8.562, 10.168] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.262 ops/ms
# Warmup Iteration   2: 8.571 ops/ms
# Warmup Iteration   3: 8.685 ops/ms
Iteration   1: 8.952 ops/ms
Iteration   2: 9.154 ops/ms
Iteration   3: 8.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.963 ±(99.9%) 3.408 ops/ms [Average]
  (min, avg, max) = (8.781, 8.963, 9.154), stdev = 0.187
  CI (99.9%): [5.555, 12.370] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.121 ops/ms
# Warmup Iteration   2: 7.056 ops/ms
# Warmup Iteration   3: 7.660 ops/ms
Iteration   1: 7.526 ops/ms
Iteration   2: 7.735 ops/ms
Iteration   3: 7.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.610 ±(99.9%) 2.019 ops/ms [Average]
  (min, avg, max) = (7.526, 7.610, 7.735), stdev = 0.111
  CI (99.9%): [5.591, 9.628] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.391 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.749 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.638 ±(99.9%) 0.006 ms/op
Iteration   1: 3.483 ±(99.9%) 0.006 ms/op
Iteration   2: 3.582 ±(99.9%) 0.004 ms/op
Iteration   3: 3.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.511 ±(99.9%) 1.133 ms/op [Average]
  (min, avg, max) = (3.467, 3.511, 3.582), stdev = 0.062
  CI (99.9%): [2.378, 4.644] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.904 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.536 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.004 ms/op
Iteration   1: 3.453 ±(99.9%) 0.003 ms/op
Iteration   2: 3.376 ±(99.9%) 0.004 ms/op
Iteration   3: 3.257 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.362 ±(99.9%) 1.806 ms/op [Average]
  (min, avg, max) = (3.257, 3.362, 3.453), stdev = 0.099
  CI (99.9%): [1.556, 5.168] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.262 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.653 ±(99.9%) 0.003 ms/op
Iteration   1: 3.571 ±(99.9%) 0.003 ms/op
Iteration   2: 3.600 ±(99.9%) 0.004 ms/op
Iteration   3: 3.529 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.567 ±(99.9%) 0.657 ms/op [Average]
  (min, avg, max) = (3.529, 3.567, 3.600), stdev = 0.036
  CI (99.9%): [2.910, 4.223] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.851 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.415 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.215 ±(99.9%) 0.006 ms/op
Iteration   1: 4.263 ±(99.9%) 0.007 ms/op
Iteration   2: 4.186 ±(99.9%) 0.006 ms/op
Iteration   3: 4.283 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.244 ±(99.9%) 0.935 ms/op [Average]
  (min, avg, max) = (4.186, 4.244, 4.283), stdev = 0.051
  CI (99.9%): [3.309, 5.179] (assumes normal distribution)


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
# Warmup Iteration   1: 8.923 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.608 ±(99.9%) 0.011 ms/op
Iteration   1: 3.496 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   7.029 ms/op
                 createUser·p0.999:  18.416 ms/op
                 createUser·p0.9999: 22.282 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   2: 3.488 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  20.283 ms/op
                 createUser·p0.9999: 23.221 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   3: 3.565 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   6.881 ms/op
                 createUser·p0.999:  13.320 ms/op
                 createUser·p0.9999: 25.986 ms/op
                 createUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272809
  mean =      3.516 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5105 
    [ 2.500,  5.000) = 259095 
    [ 5.000,  7.500) = 7047 
    [ 7.500, 10.000) = 839 
    [10.000, 12.500) = 298 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     17.924 ms/op
     p(99.9900) =     23.612 ms/op
     p(99.9990) =     26.387 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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
# Warmup Iteration   1: 9.318 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.451 ±(99.9%) 0.009 ms/op
Iteration   1: 3.418 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.495 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   6.435 ms/op
                 existUser·p0.999:  19.104 ms/op
                 existUser·p0.9999: 29.819 ms/op
                 existUser·p1.00:   33.817 ms/op

Iteration   2: 3.399 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.362 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   6.808 ms/op
                 existUser·p0.999:  20.578 ms/op
                 existUser·p0.9999: 23.907 ms/op
                 existUser·p1.00:   24.773 ms/op

Iteration   3: 3.525 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   7.205 ms/op
                 existUser·p0.999:  14.647 ms/op
                 existUser·p0.9999: 25.915 ms/op
                 existUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278427
  mean =      3.446 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5652 
    [ 2.500,  5.000) = 263796 
    [ 5.000,  7.500) = 7263 
    [ 7.500, 10.000) = 932 
    [10.000, 12.500) = 394 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     19.104 ms/op
     p(99.9900) =     28.841 ms/op
     p(99.9990) =     31.948 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 10.751 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 3.762 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.600 ±(99.9%) 0.010 ms/op
Iteration   1: 3.591 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.716 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   7.201 ms/op
                 getUser·p0.999:  14.598 ms/op
                 getUser·p0.9999: 22.067 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   2: 3.550 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  21.561 ms/op
                 getUser·p0.9999: 23.789 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   3: 3.458 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.071 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   6.603 ms/op
                 getUser·p0.999:  22.885 ms/op
                 getUser·p0.9999: 28.467 ms/op
                 getUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271753
  mean =      3.532 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3518 
    [ 2.500,  5.000) = 259793 
    [ 5.000,  7.500) = 6891 
    [ 7.500, 10.000) = 1034 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     27.672 ms/op
     p(99.9990) =     28.845 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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
# Warmup Iteration   1: 10.972 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.505 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.282 ±(99.9%) 0.015 ms/op
Iteration   1: 4.253 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   4.104 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   8.086 ms/op
                 listUser·p0.999:  20.897 ms/op
                 listUser·p0.9999: 23.740 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   2: 4.251 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.444 ms/op
                 listUser·p0.50:   4.121 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  16.102 ms/op
                 listUser·p0.9999: 19.021 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   3: 4.262 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   4.104 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   8.552 ms/op
                 listUser·p0.999:  14.697 ms/op
                 listUser·p0.9999: 17.269 ms/op
                 listUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 225454
  mean =      4.255 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 214188 
    [ 5.000,  7.500) = 7456 
    [ 7.500, 10.000) = 2608 
    [10.000, 12.500) = 555 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      4.108 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      8.421 ms/op
     p(99.9000) =     16.220 ms/op
     p(99.9900) =     22.643 ms/op
     p(99.9990) =     24.289 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.043 ± 0.244  ops/ms
ClientPb.existUser                       thrpt       3   9.365 ± 0.803  ops/ms
ClientPb.getUser                         thrpt       3   8.963 ± 3.408  ops/ms
ClientPb.listUser                        thrpt       3   7.610 ± 2.019  ops/ms
ClientPb.createUser                       avgt       3   3.511 ± 1.133   ms/op
ClientPb.existUser                        avgt       3   3.362 ± 1.806   ms/op
ClientPb.getUser                          avgt       3   3.567 ± 0.657   ms/op
ClientPb.listUser                         avgt       3   4.244 ± 0.935   ms/op
ClientPb.createUser                     sample  272809   3.516 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.087           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.947           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.924           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.612           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.444           ms/op
ClientPb.existUser                      sample  278427   3.446 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.362           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.817           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.243           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.889           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.104           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.841           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.817           ms/op
ClientPb.getUser                        sample  271753   3.532 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.818           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.832           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.054           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.672           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.901           ms/op
ClientPb.listUser                       sample  225454   4.255 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.444           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.997           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.421           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.220           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.643           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.379           ms/op
