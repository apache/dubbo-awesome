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
# Warmup Iteration   1: 2.706 ops/ms
# Warmup Iteration   2: 6.177 ops/ms
# Warmup Iteration   3: 9.374 ops/ms
Iteration   1: 9.886 ops/ms
Iteration   2: 10.309 ops/ms
Iteration   3: 9.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.055 ±(99.9%) 4.090 ops/ms [Average]
  (min, avg, max) = (9.886, 10.055, 10.309), stdev = 0.224
  CI (99.9%): [5.965, 14.145] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.686 ops/ms
# Warmup Iteration   2: 9.695 ops/ms
# Warmup Iteration   3: 9.951 ops/ms
Iteration   1: 9.972 ops/ms
Iteration   2: 10.006 ops/ms
Iteration   3: 10.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.009 ±(99.9%) 0.717 ops/ms [Average]
  (min, avg, max) = (9.972, 10.009, 10.050), stdev = 0.039
  CI (99.9%): [9.292, 10.726] (assumes normal distribution)


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
# Warmup Iteration   1: 3.570 ops/ms
# Warmup Iteration   2: 9.165 ops/ms
# Warmup Iteration   3: 9.629 ops/ms
Iteration   1: 10.331 ops/ms
Iteration   2: 9.871 ops/ms
Iteration   3: 9.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.065 ±(99.9%) 4.346 ops/ms [Average]
  (min, avg, max) = (9.871, 10.065, 10.331), stdev = 0.238
  CI (99.9%): [5.719, 14.412] (assumes normal distribution)


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
# Warmup Iteration   1: 3.384 ops/ms
# Warmup Iteration   2: 7.878 ops/ms
# Warmup Iteration   3: 8.545 ops/ms
Iteration   1: 8.479 ops/ms
Iteration   2: 8.803 ops/ms
Iteration   3: 8.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.712 ±(99.9%) 3.716 ops/ms [Average]
  (min, avg, max) = (8.479, 8.712, 8.855), stdev = 0.204
  CI (99.9%): [4.997, 12.428] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.784 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.008 ms/op
Iteration   1: 3.176 ±(99.9%) 0.003 ms/op
Iteration   2: 3.326 ±(99.9%) 0.004 ms/op
Iteration   3: 3.221 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.241 ±(99.9%) 1.403 ms/op [Average]
  (min, avg, max) = (3.176, 3.241, 3.326), stdev = 0.077
  CI (99.9%): [1.838, 4.644] (assumes normal distribution)


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
# Warmup Iteration   1: 7.449 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.006 ms/op
Iteration   1: 2.994 ±(99.9%) 0.007 ms/op
Iteration   2: 3.039 ±(99.9%) 0.007 ms/op
Iteration   3: 3.026 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.020 ±(99.9%) 0.421 ms/op [Average]
  (min, avg, max) = (2.994, 3.020, 3.039), stdev = 0.023
  CI (99.9%): [2.599, 3.440] (assumes normal distribution)


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
# Warmup Iteration   1: 7.845 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.408 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.003 ms/op
Iteration   1: 3.086 ±(99.9%) 0.002 ms/op
Iteration   2: 3.109 ±(99.9%) 0.006 ms/op
Iteration   3: 3.099 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.098 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (3.086, 3.098, 3.109), stdev = 0.011
  CI (99.9%): [2.891, 3.305] (assumes normal distribution)


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
# Warmup Iteration   1: 9.391 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.797 ±(99.9%) 0.007 ms/op
Iteration   1: 3.632 ±(99.9%) 0.007 ms/op
Iteration   2: 3.661 ±(99.9%) 0.008 ms/op
Iteration   3: 3.557 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.617 ±(99.9%) 0.978 ms/op [Average]
  (min, avg, max) = (3.557, 3.617, 3.661), stdev = 0.054
  CI (99.9%): [2.639, 4.594] (assumes normal distribution)


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
# Warmup Iteration   1: 8.107 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.009 ms/op
Iteration   1: 3.133 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.638 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  10.090 ms/op
                 createUser·p0.9999: 25.021 ms/op
                 createUser·p1.00:   26.640 ms/op

Iteration   2: 3.252 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  19.649 ms/op
                 createUser·p0.9999: 25.133 ms/op
                 createUser·p1.00:   25.788 ms/op

Iteration   3: 3.187 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.581 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  10.977 ms/op
                 createUser·p0.9999: 21.034 ms/op
                 createUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300738
  mean =      3.190 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22177 
    [ 2.500,  5.000) = 273241 
    [ 5.000,  7.500) = 4549 
    [ 7.500, 10.000) = 382 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.999 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     15.620 ms/op
     p(99.9900) =     24.824 ms/op
     p(99.9990) =     25.853 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 7.730 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.358 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.008 ms/op
Iteration   1: 3.147 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.516 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  9.585 ms/op
                 existUser·p0.9999: 26.602 ms/op
                 existUser·p1.00:   26.673 ms/op

Iteration   2: 3.184 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.161 ms/op
                 existUser·p0.999:  17.105 ms/op
                 existUser·p0.9999: 20.349 ms/op
                 existUser·p1.00:   21.299 ms/op

Iteration   3: 3.172 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  9.372 ms/op
                 existUser·p0.9999: 22.766 ms/op
                 existUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302981
  mean =      3.168 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26336 
    [ 2.500,  5.000) = 271001 
    [ 5.000,  7.500) = 5017 
    [ 7.500, 10.000) = 253 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     25.586 ms/op
     p(99.9990) =     26.640 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 8.003 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.377 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.394 ±(99.9%) 0.010 ms/op
Iteration   1: 3.172 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.675 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  11.614 ms/op
                 getUser·p0.9999: 20.770 ms/op
                 getUser·p1.00:   21.234 ms/op

Iteration   2: 3.270 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  14.438 ms/op
                 getUser·p0.9999: 22.512 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   3: 3.221 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.452 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  15.811 ms/op
                 getUser·p0.9999: 33.427 ms/op
                 getUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298192
  mean =      3.220 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13276 
    [ 2.500,  5.000) = 275215 
    [ 5.000,  7.500) = 8674 
    [ 7.500, 10.000) = 630 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     15.720 ms/op
     p(99.9900) =     32.178 ms/op
     p(99.9990) =     33.756 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 8.566 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.121 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.012 ms/op
Iteration   1: 3.764 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.452 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  17.110 ms/op
                 listUser·p0.9999: 24.446 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   2: 3.583 ±(99.9%) 0.006 ms/op
                 listUser·p0.00:   2.437 ms/op
                 listUser·p0.50:   3.502 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.018 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  12.878 ms/op
                 listUser·p0.9999: 14.828 ms/op
                 listUser·p1.00:   14.893 ms/op

Iteration   3: 3.640 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.923 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   3.756 ms/op
                 listUser·p0.95:   3.969 ms/op
                 listUser·p0.99:   6.250 ms/op
                 listUser·p0.999:  13.910 ms/op
                 listUser·p0.9999: 17.891 ms/op
                 listUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 261968
  mean =      3.661 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 256457 
    [ 5.000,  7.500) = 3919 
    [ 7.500, 10.000) = 875 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 331 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.452 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     13.796 ms/op
     p(99.9900) =     23.449 ms/op
     p(99.9990) =     25.060 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.055 ± 4.090  ops/ms
ClientPb.existUser                       thrpt       3  10.009 ± 0.717  ops/ms
ClientPb.getUser                         thrpt       3  10.065 ± 4.346  ops/ms
ClientPb.listUser                        thrpt       3   8.712 ± 3.716  ops/ms
ClientPb.createUser                       avgt       3   3.241 ± 1.403   ms/op
ClientPb.existUser                        avgt       3   3.020 ± 0.421   ms/op
ClientPb.getUser                          avgt       3   3.098 ± 0.207   ms/op
ClientPb.listUser                         avgt       3   3.617 ± 0.978   ms/op
ClientPb.createUser                     sample  300738   3.190 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.999           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.576           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.349           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.620           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.824           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.640           ms/op
ClientPb.existUser                      sample  302981   3.168 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.946           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.940           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.415           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.730           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.586           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.673           ms/op
ClientPb.getUser                        sample  298192   3.220 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.055           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.157           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.259           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.720           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.178           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.406           ms/op
ClientPb.listUser                       sample  261968   3.661 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.452           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.576           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.121           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.529           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.796           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.449           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.625           ms/op
