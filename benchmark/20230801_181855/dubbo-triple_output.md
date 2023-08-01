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
# Warmup Iteration   1: 2.537 ops/ms
# Warmup Iteration   2: 5.785 ops/ms
# Warmup Iteration   3: 9.338 ops/ms
Iteration   1: 9.633 ops/ms
Iteration   2: 10.036 ops/ms
Iteration   3: 9.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.887 ±(99.9%) 4.029 ops/ms [Average]
  (min, avg, max) = (9.633, 9.887, 10.036), stdev = 0.221
  CI (99.9%): [5.858, 13.917] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.812 ops/ms
# Warmup Iteration   2: 9.367 ops/ms
# Warmup Iteration   3: 10.299 ops/ms
Iteration   1: 9.927 ops/ms
Iteration   2: 10.112 ops/ms
Iteration   3: 10.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.229 ±(99.9%) 6.835 ops/ms [Average]
  (min, avg, max) = (9.927, 10.229, 10.648), stdev = 0.375
  CI (99.9%): [3.394, 17.064] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.462 ops/ms
# Warmup Iteration   2: 8.036 ops/ms
# Warmup Iteration   3: 9.392 ops/ms
Iteration   1: 9.366 ops/ms
Iteration   2: 10.090 ops/ms
Iteration   3: 9.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.735 ±(99.9%) 6.603 ops/ms [Average]
  (min, avg, max) = (9.366, 9.735, 10.090), stdev = 0.362
  CI (99.9%): [3.132, 16.339] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.508 ops/ms
# Warmup Iteration   2: 7.661 ops/ms
# Warmup Iteration   3: 8.126 ops/ms
Iteration   1: 8.204 ops/ms
Iteration   2: 8.551 ops/ms
Iteration   3: 8.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.323 ±(99.9%) 3.616 ops/ms [Average]
  (min, avg, max) = (8.204, 8.323, 8.551), stdev = 0.198
  CI (99.9%): [4.707, 11.938] (assumes normal distribution)


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
# Warmup Iteration   1: 9.205 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.542 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.006 ms/op
Iteration   1: 3.294 ±(99.9%) 0.005 ms/op
Iteration   2: 3.331 ±(99.9%) 0.005 ms/op
Iteration   3: 3.222 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.282 ±(99.9%) 1.010 ms/op [Average]
  (min, avg, max) = (3.222, 3.282, 3.331), stdev = 0.055
  CI (99.9%): [2.272, 4.293] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.103 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.490 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.002 ms/op
Iteration   1: 3.055 ±(99.9%) 0.005 ms/op
Iteration   2: 3.233 ±(99.9%) 0.006 ms/op
Iteration   3: 3.173 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.154 ±(99.9%) 1.651 ms/op [Average]
  (min, avg, max) = (3.055, 3.154, 3.233), stdev = 0.090
  CI (99.9%): [1.503, 4.805] (assumes normal distribution)


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
# Warmup Iteration   1: 8.174 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.580 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.369 ±(99.9%) 0.003 ms/op
Iteration   1: 3.291 ±(99.9%) 0.006 ms/op
Iteration   2: 3.214 ±(99.9%) 0.004 ms/op
Iteration   3: 3.235 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.246 ±(99.9%) 0.725 ms/op [Average]
  (min, avg, max) = (3.214, 3.246, 3.291), stdev = 0.040
  CI (99.9%): [2.521, 3.972] (assumes normal distribution)


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
# Warmup Iteration   1: 8.676 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.817 ±(99.9%) 0.010 ms/op
Iteration   1: 3.769 ±(99.9%) 0.009 ms/op
Iteration   2: 3.705 ±(99.9%) 0.010 ms/op
Iteration   3: 3.818 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.764 ±(99.9%) 1.036 ms/op [Average]
  (min, avg, max) = (3.705, 3.764, 3.818), stdev = 0.057
  CI (99.9%): [2.728, 4.800] (assumes normal distribution)


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
# Warmup Iteration   1: 7.239 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.009 ms/op
Iteration   1: 3.313 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  15.083 ms/op
                 createUser·p0.9999: 24.412 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   2: 3.166 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  13.582 ms/op
                 createUser·p0.9999: 25.964 ms/op
                 createUser·p1.00:   27.689 ms/op

Iteration   3: 3.360 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  17.891 ms/op
                 createUser·p0.9999: 31.391 ms/op
                 createUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292678
  mean =      3.277 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18372 
    [ 2.500,  5.000) = 267594 
    [ 5.000,  7.500) = 5563 
    [ 7.500, 10.000) = 749 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     15.296 ms/op
     p(99.9900) =     29.974 ms/op
     p(99.9990) =     31.800 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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
# Warmup Iteration   1: 7.882 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.551 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.008 ms/op
Iteration   1: 3.195 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.341 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  9.173 ms/op
                 existUser·p0.9999: 20.283 ms/op
                 existUser·p1.00:   22.184 ms/op

Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  11.682 ms/op
                 existUser·p0.9999: 24.174 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   3: 3.225 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.297 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  16.532 ms/op
                 existUser·p0.9999: 26.643 ms/op
                 existUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300111
  mean =      3.195 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25130 
    [ 2.500,  5.000) = 267672 
    [ 5.000,  7.500) = 6132 
    [ 7.500, 10.000) = 720 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.297 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     12.162 ms/op
     p(99.9900) =     24.903 ms/op
     p(99.9990) =     26.902 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 7.301 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.386 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.284 ±(99.9%) 0.009 ms/op
Iteration   1: 3.155 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.407 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  18.645 ms/op
                 getUser·p0.9999: 20.705 ms/op
                 getUser·p1.00:   21.889 ms/op

Iteration   2: 3.229 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  15.634 ms/op
                 getUser·p0.9999: 23.931 ms/op
                 getUser·p1.00:   25.788 ms/op

Iteration   3: 3.271 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.438 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  11.015 ms/op
                 getUser·p0.9999: 23.888 ms/op
                 getUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298030
  mean =      3.218 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8190 
    [ 2.500,  5.000) = 283094 
    [ 5.000,  7.500) = 5149 
    [ 7.500, 10.000) = 1105 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 160 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     18.285 ms/op
     p(99.9900) =     23.436 ms/op
     p(99.9990) =     24.248 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 8.922 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.076 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.013 ms/op
Iteration   1: 3.793 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.778 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  15.172 ms/op
                 listUser·p0.9999: 23.527 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   2: 3.809 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.686 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  12.911 ms/op
                 listUser·p0.9999: 20.500 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 3.800 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.441 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  11.616 ms/op
                 listUser·p0.9999: 17.957 ms/op
                 listUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252425
  mean =      3.800 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 243339 
    [ 5.000,  7.500) = 6376 
    [ 7.500, 10.000) = 1987 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.686 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     13.189 ms/op
     p(99.9900) =     21.619 ms/op
     p(99.9990) =     24.947 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.887 ± 4.029  ops/ms
ClientPb.existUser                       thrpt       3  10.229 ± 6.835  ops/ms
ClientPb.getUser                         thrpt       3   9.735 ± 6.603  ops/ms
ClientPb.listUser                        thrpt       3   8.323 ± 3.616  ops/ms
ClientPb.createUser                       avgt       3   3.282 ± 1.010   ms/op
ClientPb.existUser                        avgt       3   3.154 ± 1.651   ms/op
ClientPb.getUser                          avgt       3   3.246 ± 0.725   ms/op
ClientPb.listUser                         avgt       3   3.764 ± 1.036   ms/op
ClientPb.createUser                     sample  292678   3.277 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.651           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.145           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.644           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.296           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.974           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.440           ms/op
ClientPb.existUser                      sample  300111   3.195 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.297           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.022           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.628           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.162           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.903           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.935           ms/op
ClientPb.getUser                        sample  298030   3.218 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.053           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.518           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.013           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.285           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.436           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.788           ms/op
ClientPb.listUser                       sample  252425   3.800 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.686           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.096           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.569           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.189           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.619           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.854           ms/op
