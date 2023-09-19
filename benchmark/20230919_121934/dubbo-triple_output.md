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
# Warmup Iteration   1: 2.023 ops/ms
# Warmup Iteration   2: 5.570 ops/ms
# Warmup Iteration   3: 8.618 ops/ms
Iteration   1: 9.229 ops/ms
Iteration   2: 9.355 ops/ms
Iteration   3: 9.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.318 ±(99.9%) 1.419 ops/ms [Average]
  (min, avg, max) = (9.229, 9.318, 9.371), stdev = 0.078
  CI (99.9%): [7.899, 10.738] (assumes normal distribution)


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
# Warmup Iteration   1: 2.706 ops/ms
# Warmup Iteration   2: 8.470 ops/ms
# Warmup Iteration   3: 9.528 ops/ms
Iteration   1: 9.720 ops/ms
Iteration   2: 9.633 ops/ms
Iteration   3: 9.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.633 ±(99.9%) 1.585 ops/ms [Average]
  (min, avg, max) = (9.546, 9.633, 9.720), stdev = 0.087
  CI (99.9%): [8.047, 11.218] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.861 ops/ms
# Warmup Iteration   2: 8.440 ops/ms
# Warmup Iteration   3: 9.239 ops/ms
Iteration   1: 9.270 ops/ms
Iteration   2: 9.293 ops/ms
Iteration   3: 9.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.200 ±(99.9%) 2.602 ops/ms [Average]
  (min, avg, max) = (9.035, 9.200, 9.293), stdev = 0.143
  CI (99.9%): [6.598, 11.802] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.914 ops/ms
# Warmup Iteration   2: 6.928 ops/ms
# Warmup Iteration   3: 7.504 ops/ms
Iteration   1: 7.676 ops/ms
Iteration   2: 7.704 ops/ms
Iteration   3: 7.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.642 ±(99.9%) 1.522 ops/ms [Average]
  (min, avg, max) = (7.548, 7.642, 7.704), stdev = 0.083
  CI (99.9%): [6.121, 9.164] (assumes normal distribution)


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
# Warmup Iteration   1: 11.936 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.660 ±(99.9%) 0.004 ms/op
Iteration   1: 3.555 ±(99.9%) 0.005 ms/op
Iteration   2: 3.520 ±(99.9%) 0.003 ms/op
Iteration   3: 3.465 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.513 ±(99.9%) 0.828 ms/op [Average]
  (min, avg, max) = (3.465, 3.513, 3.555), stdev = 0.045
  CI (99.9%): [2.685, 4.341] (assumes normal distribution)


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
# Warmup Iteration   1: 8.478 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.412 ±(99.9%) 0.003 ms/op
Iteration   1: 3.361 ±(99.9%) 0.008 ms/op
Iteration   2: 3.355 ±(99.9%) 0.006 ms/op
Iteration   3: 3.413 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.376 ±(99.9%) 0.586 ms/op [Average]
  (min, avg, max) = (3.355, 3.376, 3.413), stdev = 0.032
  CI (99.9%): [2.790, 3.963] (assumes normal distribution)


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
# Warmup Iteration   1: 9.750 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.544 ±(99.9%) 0.004 ms/op
Iteration   1: 3.454 ±(99.9%) 0.004 ms/op
Iteration   2: 3.381 ±(99.9%) 0.007 ms/op
Iteration   3: 3.554 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.463 ±(99.9%) 1.591 ms/op [Average]
  (min, avg, max) = (3.381, 3.463, 3.554), stdev = 0.087
  CI (99.9%): [1.872, 5.054] (assumes normal distribution)


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
# Warmup Iteration   1: 9.931 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.519 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.008 ms/op
Iteration   1: 4.113 ±(99.9%) 0.007 ms/op
Iteration   2: 4.014 ±(99.9%) 0.010 ms/op
Iteration   3: 4.080 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.069 ±(99.9%) 0.917 ms/op [Average]
  (min, avg, max) = (4.014, 4.069, 4.113), stdev = 0.050
  CI (99.9%): [3.153, 4.986] (assumes normal distribution)


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
# Warmup Iteration   1: 10.909 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.157 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.812 ±(99.9%) 0.013 ms/op
Iteration   1: 3.439 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.354 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   6.177 ms/op
                 createUser·p0.999:  21.002 ms/op
                 createUser·p0.9999: 25.844 ms/op
                 createUser·p1.00:   26.640 ms/op

Iteration   2: 3.543 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.540 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   6.898 ms/op
                 createUser·p0.999:  22.807 ms/op
                 createUser·p0.9999: 25.984 ms/op
                 createUser·p1.00:   26.903 ms/op

Iteration   3: 3.511 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.612 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  21.163 ms/op
                 createUser·p0.9999: 27.220 ms/op
                 createUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274402
  mean =      3.497 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4757 
    [ 2.500,  5.000) = 262786 
    [ 5.000,  7.500) = 5626 
    [ 7.500, 10.000) = 550 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 96 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     21.253 ms/op
     p(99.9900) =     26.386 ms/op
     p(99.9990) =     27.684 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.114 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.560 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.009 ms/op
Iteration   1: 3.405 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.462 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.178 ms/op
                 existUser·p0.99:   6.554 ms/op
                 existUser·p0.999:  20.841 ms/op
                 existUser·p0.9999: 24.006 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   2: 3.348 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.544 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  22.364 ms/op
                 existUser·p0.9999: 25.588 ms/op
                 existUser·p1.00:   27.034 ms/op

Iteration   3: 3.415 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.996 ms/op
                 existUser·p0.999:  19.562 ms/op
                 existUser·p0.9999: 29.152 ms/op
                 existUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283107
  mean =      3.389 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6746 
    [ 2.500,  5.000) = 269617 
    [ 5.000,  7.500) = 5235 
    [ 7.500, 10.000) = 780 
    [10.000, 12.500) = 300 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 149 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     19.595 ms/op
     p(99.9900) =     28.066 ms/op
     p(99.9990) =     29.726 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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
# Warmup Iteration   1: 10.158 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.012 ms/op
Iteration   1: 3.520 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.751 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  19.859 ms/op
                 getUser·p0.9999: 22.345 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   2: 3.524 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.645 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  22.682 ms/op
                 getUser·p0.9999: 28.503 ms/op
                 getUser·p1.00:   29.884 ms/op

Iteration   3: 3.466 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.550 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  18.258 ms/op
                 getUser·p0.9999: 25.340 ms/op
                 getUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274007
  mean =      3.503 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4801 
    [ 2.500,  5.000) = 261604 
    [ 5.000,  7.500) = 6363 
    [ 7.500, 10.000) = 740 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.550 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     26.975 ms/op
     p(99.9990) =     28.984 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 11.020 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.427 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.268 ±(99.9%) 0.013 ms/op
Iteration   1: 4.145 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  20.110 ms/op
                 listUser·p0.9999: 23.515 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   2: 4.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  15.745 ms/op
                 listUser·p0.9999: 17.072 ms/op
                 listUser·p1.00:   17.596 ms/op

Iteration   3: 4.183 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   4.071 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  14.926 ms/op
                 listUser·p0.9999: 17.608 ms/op
                 listUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233775
  mean =      4.108 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 226157 
    [ 5.000,  7.500) = 5866 
    [ 7.500, 10.000) = 990 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.118 ms/op
     p(50.0000) =      3.965 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     16.318 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     24.095 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.318 ± 1.419  ops/ms
ClientPb.existUser                       thrpt       3   9.633 ± 1.585  ops/ms
ClientPb.getUser                         thrpt       3   9.200 ± 2.602  ops/ms
ClientPb.listUser                        thrpt       3   7.642 ± 1.522  ops/ms
ClientPb.createUser                       avgt       3   3.513 ± 0.828   ms/op
ClientPb.existUser                        avgt       3   3.376 ± 0.586   ms/op
ClientPb.getUser                          avgt       3   3.463 ± 1.591   ms/op
ClientPb.listUser                         avgt       3   4.069 ± 0.917   ms/op
ClientPb.createUser                     sample  274402   3.497 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.354           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.375           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.382           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.253           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.386           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.246           ms/op
ClientPb.existUser                      sample  283107   3.389 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.260           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.112           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.595           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.066           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.819           ms/op
ClientPb.getUser                        sample  274007   3.503 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.550           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.283           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.481           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.975           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.884           ms/op
ClientPb.listUser                       sample  233775   4.108 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.118           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.965           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.318           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.970           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.510           ms/op
