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
# Warmup Iteration   1: 2.670 ops/ms
# Warmup Iteration   2: 6.053 ops/ms
# Warmup Iteration   3: 9.322 ops/ms
Iteration   1: 9.618 ops/ms
Iteration   2: 9.615 ops/ms
Iteration   3: 10.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.764 ±(99.9%) 4.638 ops/ms [Average]
  (min, avg, max) = (9.615, 9.764, 10.057), stdev = 0.254
  CI (99.9%): [5.126, 14.402] (assumes normal distribution)


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
# Warmup Iteration   1: 3.470 ops/ms
# Warmup Iteration   2: 9.180 ops/ms
# Warmup Iteration   3: 9.940 ops/ms
Iteration   1: 9.858 ops/ms
Iteration   2: 10.365 ops/ms
Iteration   3: 10.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.292 ±(99.9%) 7.334 ops/ms [Average]
  (min, avg, max) = (9.858, 10.292, 10.652), stdev = 0.402
  CI (99.9%): [2.957, 17.626] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.580 ops/ms
# Warmup Iteration   2: 8.733 ops/ms
# Warmup Iteration   3: 10.084 ops/ms
Iteration   1: 9.601 ops/ms
Iteration   2: 9.755 ops/ms
Iteration   3: 9.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.735 ±(99.9%) 2.288 ops/ms [Average]
  (min, avg, max) = (9.601, 9.735, 9.849), stdev = 0.125
  CI (99.9%): [7.447, 12.023] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.240 ops/ms
# Warmup Iteration   2: 7.222 ops/ms
# Warmup Iteration   3: 8.167 ops/ms
Iteration   1: 8.371 ops/ms
Iteration   2: 8.323 ops/ms
Iteration   3: 8.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.420 ±(99.9%) 2.360 ops/ms [Average]
  (min, avg, max) = (8.323, 8.420, 8.567), stdev = 0.129
  CI (99.9%): [6.060, 10.780] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.688 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.004 ms/op
Iteration   1: 3.289 ±(99.9%) 0.005 ms/op
Iteration   2: 3.283 ±(99.9%) 0.008 ms/op
Iteration   3: 3.206 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.260 ±(99.9%) 0.842 ms/op [Average]
  (min, avg, max) = (3.206, 3.260, 3.289), stdev = 0.046
  CI (99.9%): [2.418, 4.102] (assumes normal distribution)


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
# Warmup Iteration   1: 7.279 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.436 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.005 ms/op
Iteration   1: 3.132 ±(99.9%) 0.006 ms/op
Iteration   2: 3.108 ±(99.9%) 0.005 ms/op
Iteration   3: 3.076 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.105 ±(99.9%) 0.514 ms/op [Average]
  (min, avg, max) = (3.076, 3.105, 3.132), stdev = 0.028
  CI (99.9%): [2.592, 3.619] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.146 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.445 ±(99.9%) 0.004 ms/op
Iteration   1: 3.115 ±(99.9%) 0.006 ms/op
Iteration   2: 3.152 ±(99.9%) 0.002 ms/op
Iteration   3: 3.102 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.123 ±(99.9%) 0.480 ms/op [Average]
  (min, avg, max) = (3.102, 3.123, 3.152), stdev = 0.026
  CI (99.9%): [2.643, 3.603] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.568 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.180 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.742 ±(99.9%) 0.008 ms/op
Iteration   1: 3.637 ±(99.9%) 0.010 ms/op
Iteration   2: 3.637 ±(99.9%) 0.010 ms/op
Iteration   3: 3.604 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.626 ±(99.9%) 0.354 ms/op [Average]
  (min, avg, max) = (3.604, 3.626, 3.637), stdev = 0.019
  CI (99.9%): [3.272, 3.980] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.264 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.008 ms/op
Iteration   1: 3.201 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  18.129 ms/op
                 createUser·p0.9999: 21.628 ms/op
                 createUser·p1.00:   23.462 ms/op

Iteration   2: 3.367 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.163 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  19.040 ms/op
                 createUser·p0.9999: 22.168 ms/op
                 createUser·p1.00:   23.069 ms/op

Iteration   3: 3.293 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.636 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  15.630 ms/op
                 createUser·p0.9999: 23.021 ms/op
                 createUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291993
  mean =      3.285 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19105 
    [ 2.500,  5.000) = 266047 
    [ 5.000,  7.500) = 5886 
    [ 7.500, 10.000) = 454 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 141 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     22.440 ms/op
     p(99.9990) =     23.251 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 7.168 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.549 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.008 ms/op
Iteration   1: 3.085 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.023 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   5.345 ms/op
                 existUser·p0.999:  12.485 ms/op
                 existUser·p0.9999: 21.779 ms/op
                 existUser·p1.00:   22.839 ms/op

Iteration   2: 3.136 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.434 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.956 ms/op
                 existUser·p0.999:  11.698 ms/op
                 existUser·p0.9999: 23.809 ms/op
                 existUser·p1.00:   24.576 ms/op

Iteration   3: 3.039 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.194 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   5.618 ms/op
                 existUser·p0.999:  11.819 ms/op
                 existUser·p0.9999: 20.836 ms/op
                 existUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310959
  mean =      3.086 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9677 
    [ 2.500,  5.000) = 297446 
    [ 5.000,  7.500) = 2839 
    [ 7.500, 10.000) = 522 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     11.796 ms/op
     p(99.9900) =     22.807 ms/op
     p(99.9990) =     24.314 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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
# Warmup Iteration   1: 7.929 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.010 ms/op
Iteration   1: 3.271 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.153 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  12.030 ms/op
                 getUser·p0.9999: 24.492 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   2: 3.228 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   5.358 ms/op
                 getUser·p0.999:  11.600 ms/op
                 getUser·p0.9999: 23.173 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   3: 3.348 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.442 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.692 ms/op
                 getUser·p0.999:  16.564 ms/op
                 getUser·p0.9999: 27.016 ms/op
                 getUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292374
  mean =      3.282 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10395 
    [ 2.500,  5.000) = 274421 
    [ 5.000,  7.500) = 6421 
    [ 7.500, 10.000) = 661 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     15.864 ms/op
     p(99.9900) =     25.283 ms/op
     p(99.9990) =     27.661 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


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
# Warmup Iteration   1: 10.421 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.365 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.876 ±(99.9%) 0.011 ms/op
Iteration   1: 3.795 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  20.590 ms/op
                 listUser·p0.9999: 22.563 ms/op
                 listUser·p1.00:   25.264 ms/op

Iteration   2: 3.739 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  14.762 ms/op
                 listUser·p0.9999: 21.576 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   3: 3.727 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.798 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  12.616 ms/op
                 listUser·p0.9999: 20.513 ms/op
                 listUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255584
  mean =      3.754 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 249826 
    [ 5.000,  7.500) = 3949 
    [ 7.500, 10.000) = 929 
    [10.000, 12.500) = 321 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.798 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     15.155 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     25.191 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.764 ± 4.638  ops/ms
ClientPb.existUser                       thrpt       3  10.292 ± 7.334  ops/ms
ClientPb.getUser                         thrpt       3   9.735 ± 2.288  ops/ms
ClientPb.listUser                        thrpt       3   8.420 ± 2.360  ops/ms
ClientPb.createUser                       avgt       3   3.260 ± 0.842   ms/op
ClientPb.existUser                        avgt       3   3.105 ± 0.514   ms/op
ClientPb.getUser                          avgt       3   3.123 ± 0.480   ms/op
ClientPb.listUser                         avgt       3   3.626 ± 0.354   ms/op
ClientPb.createUser                     sample  291993   3.285 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.636           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.695           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.440           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.626           ms/op
ClientPb.existUser                      sample  310959   3.086 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.023           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.346           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.341           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.796           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.807           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.576           ms/op
ClientPb.getUser                        sample  292374   3.282 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.153           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.592           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.029           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.864           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.283           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.722           ms/op
ClientPb.listUser                       sample  255584   3.754 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.798           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.055           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.652           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.155           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.282           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.264           ms/op
