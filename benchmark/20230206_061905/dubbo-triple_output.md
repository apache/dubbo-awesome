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
# Warmup Iteration   1: 0.902 ops/ms
# Warmup Iteration   2: 2.126 ops/ms
# Warmup Iteration   3: 4.993 ops/ms
Iteration   1: 5.967 ops/ms
Iteration   2: 6.215 ops/ms
Iteration   3: 6.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.140 ±(99.9%) 2.738 ops/ms [Average]
  (min, avg, max) = (5.967, 6.140, 6.237), stdev = 0.150
  CI (99.9%): [3.401, 8.878] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.739 ops/ms
# Warmup Iteration   2: 5.674 ops/ms
# Warmup Iteration   3: 6.289 ops/ms
Iteration   1: 6.157 ops/ms
Iteration   2: 6.297 ops/ms
Iteration   3: 6.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.273 ±(99.9%) 1.928 ops/ms [Average]
  (min, avg, max) = (6.157, 6.273, 6.365), stdev = 0.106
  CI (99.9%): [4.345, 8.201] (assumes normal distribution)


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
# Warmup Iteration   1: 1.678 ops/ms
# Warmup Iteration   2: 4.731 ops/ms
# Warmup Iteration   3: 6.115 ops/ms
Iteration   1: 6.281 ops/ms
Iteration   2: 6.079 ops/ms
Iteration   3: 6.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.173 ±(99.9%) 1.857 ops/ms [Average]
  (min, avg, max) = (6.079, 6.173, 6.281), stdev = 0.102
  CI (99.9%): [4.317, 8.030] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.578 ops/ms
# Warmup Iteration   2: 4.423 ops/ms
# Warmup Iteration   3: 4.876 ops/ms
Iteration   1: 5.004 ops/ms
Iteration   2: 5.123 ops/ms
Iteration   3: 5.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.169 ±(99.9%) 3.486 ops/ms [Average]
  (min, avg, max) = (5.004, 5.169, 5.378), stdev = 0.191
  CI (99.9%): [1.683, 8.654] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 18.555 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 6.549 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.446 ±(99.9%) 0.009 ms/op
Iteration   1: 5.120 ±(99.9%) 0.015 ms/op
Iteration   2: 5.124 ±(99.9%) 0.016 ms/op
Iteration   3: 5.149 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.131 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (5.120, 5.131, 5.149), stdev = 0.015
  CI (99.9%): [4.851, 5.411] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 15.968 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.807 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.150 ±(99.9%) 0.011 ms/op
Iteration   1: 4.737 ±(99.9%) 0.016 ms/op
Iteration   2: 4.574 ±(99.9%) 0.010 ms/op
Iteration   3: 4.792 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.701 ±(99.9%) 2.072 ms/op [Average]
  (min, avg, max) = (4.574, 4.701, 4.792), stdev = 0.114
  CI (99.9%): [2.629, 6.772] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 14.972 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 5.978 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.250 ±(99.9%) 0.012 ms/op
Iteration   1: 5.332 ±(99.9%) 0.008 ms/op
Iteration   2: 5.029 ±(99.9%) 0.016 ms/op
Iteration   3: 5.015 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.126 ±(99.9%) 3.271 ms/op [Average]
  (min, avg, max) = (5.015, 5.126, 5.332), stdev = 0.179
  CI (99.9%): [1.854, 8.397] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 16.303 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 7.021 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.157 ±(99.9%) 0.015 ms/op
Iteration   1: 5.855 ±(99.9%) 0.023 ms/op
Iteration   2: 5.861 ±(99.9%) 0.016 ms/op
Iteration   3: 5.676 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.797 ±(99.9%) 1.918 ms/op [Average]
  (min, avg, max) = (5.676, 5.797, 5.861), stdev = 0.105
  CI (99.9%): [3.879, 7.716] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.992 ±(99.9%) 0.269 ms/op
# Warmup Iteration   2: 6.560 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.342 ±(99.9%) 0.020 ms/op
Iteration   1: 5.212 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.355 ms/op
                 createUser·p0.50:   4.887 ms/op
                 createUser·p0.90:   6.349 ms/op
                 createUser·p0.95:   7.381 ms/op
                 createUser·p0.99:   10.404 ms/op
                 createUser·p0.999:  21.910 ms/op
                 createUser·p0.9999: 24.805 ms/op
                 createUser·p1.00:   25.002 ms/op

Iteration   2: 5.177 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.563 ms/op
                 createUser·p0.50:   4.940 ms/op
                 createUser·p0.90:   6.259 ms/op
                 createUser·p0.95:   6.996 ms/op
                 createUser·p0.99:   9.044 ms/op
                 createUser·p0.999:  23.984 ms/op
                 createUser·p0.9999: 28.755 ms/op
                 createUser·p1.00:   31.064 ms/op

Iteration   3: 5.501 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.970 ms/op
                 createUser·p0.50:   5.202 ms/op
                 createUser·p0.90:   6.816 ms/op
                 createUser·p0.95:   7.799 ms/op
                 createUser·p0.99:   10.611 ms/op
                 createUser·p0.999:  23.487 ms/op
                 createUser·p0.9999: 34.780 ms/op
                 createUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 181358
  mean =      5.293 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 91018 
    [ 5.000,  7.500) = 81764 
    [ 7.500, 10.000) = 6681 
    [10.000, 12.500) = 1167 
    [12.500, 15.000) = 343 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.563 ms/op
     p(50.0000) =      4.997 ms/op
     p(90.0000) =      6.480 ms/op
     p(95.0000) =      7.414 ms/op
     p(99.0000) =     10.027 ms/op
     p(99.9000) =     22.020 ms/op
     p(99.9900) =     33.312 ms/op
     p(99.9990) =     36.516 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 17.446 ±(99.9%) 0.258 ms/op
# Warmup Iteration   2: 5.665 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.170 ±(99.9%) 0.019 ms/op
Iteration   1: 5.104 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.433 ms/op
                 existUser·p0.50:   4.882 ms/op
                 existUser·p0.90:   6.078 ms/op
                 existUser·p0.95:   6.840 ms/op
                 existUser·p0.99:   9.355 ms/op
                 existUser·p0.999:  22.161 ms/op
                 existUser·p0.9999: 26.320 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   2: 5.284 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.290 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   6.488 ms/op
                 existUser·p0.95:   7.430 ms/op
                 existUser·p0.99:   10.207 ms/op
                 existUser·p0.999:  16.909 ms/op
                 existUser·p0.9999: 27.589 ms/op
                 existUser·p1.00:   29.295 ms/op

Iteration   3: 5.350 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.433 ms/op
                 existUser·p0.50:   5.038 ms/op
                 existUser·p0.90:   6.521 ms/op
                 existUser·p0.95:   7.520 ms/op
                 existUser·p0.99:   10.863 ms/op
                 existUser·p0.999:  28.443 ms/op
                 existUser·p0.9999: 33.899 ms/op
                 existUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182892
  mean =      5.244 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 94935 
    [ 5.000,  7.500) = 79948 
    [ 7.500, 10.000) = 5938 
    [10.000, 12.500) = 1303 
    [12.500, 15.000) = 429 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.290 ms/op
     p(50.0000) =      4.973 ms/op
     p(90.0000) =      6.365 ms/op
     p(95.0000) =      7.291 ms/op
     p(99.0000) =     10.207 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     31.298 ms/op
     p(99.9990) =     34.910 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 18.190 ±(99.9%) 0.287 ms/op
# Warmup Iteration   2: 6.331 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.493 ±(99.9%) 0.021 ms/op
Iteration   1: 5.424 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.384 ms/op
                 getUser·p0.50:   5.071 ms/op
                 getUser·p0.90:   6.488 ms/op
                 getUser·p0.95:   8.094 ms/op
                 getUser·p0.99:   11.469 ms/op
                 getUser·p0.999:  21.004 ms/op
                 getUser·p0.9999: 24.445 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   2: 5.366 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.761 ms/op
                 getUser·p0.50:   5.054 ms/op
                 getUser·p0.90:   6.332 ms/op
                 getUser·p0.95:   7.414 ms/op
                 getUser·p0.99:   11.502 ms/op
                 getUser·p0.999:  23.685 ms/op
                 getUser·p0.9999: 30.213 ms/op
                 getUser·p1.00:   31.687 ms/op

Iteration   3: 5.131 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.068 ms/op
                 getUser·p0.50:   4.899 ms/op
                 getUser·p0.90:   5.997 ms/op
                 getUser·p0.95:   6.783 ms/op
                 getUser·p0.99:   9.552 ms/op
                 getUser·p0.999:  24.795 ms/op
                 getUser·p0.9999: 29.927 ms/op
                 getUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 180853
  mean =      5.304 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 90328 
    [ 5.000,  7.500) = 81826 
    [ 7.500, 10.000) = 6076 
    [10.000, 12.500) = 1555 
    [12.500, 15.000) = 577 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.068 ms/op
     p(50.0000) =      5.005 ms/op
     p(90.0000) =      6.267 ms/op
     p(95.0000) =      7.422 ms/op
     p(99.0000) =     10.928 ms/op
     p(99.9000) =     22.123 ms/op
     p(99.9900) =     29.849 ms/op
     p(99.9990) =     31.475 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.135 ±(99.9%) 0.325 ms/op
# Warmup Iteration   2: 7.700 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.427 ±(99.9%) 0.026 ms/op
Iteration   1: 6.203 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.970 ms/op
                 listUser·p0.50:   5.857 ms/op
                 listUser·p0.90:   7.274 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   13.222 ms/op
                 listUser·p0.999:  29.066 ms/op
                 listUser·p0.9999: 34.472 ms/op
                 listUser·p1.00:   34.734 ms/op

Iteration   2: 6.147 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.650 ms/op
                 listUser·p0.50:   5.800 ms/op
                 listUser·p0.90:   7.373 ms/op
                 listUser·p0.95:   8.372 ms/op
                 listUser·p0.99:   11.583 ms/op
                 listUser·p0.999:  27.924 ms/op
                 listUser·p0.9999: 31.458 ms/op
                 listUser·p1.00:   31.850 ms/op

Iteration   3: 6.159 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   5.816 ms/op
                 listUser·p0.90:   7.234 ms/op
                 listUser·p0.95:   8.364 ms/op
                 listUser·p0.99:   12.190 ms/op
                 listUser·p0.999:  27.166 ms/op
                 listUser·p0.9999: 32.499 ms/op
                 listUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 155500
  mean =      6.170 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 10062 
    [ 5.000,  7.500) = 132000 
    [ 7.500, 10.000) = 9816 
    [10.000, 12.500) = 2114 
    [12.500, 15.000) = 828 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 99 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.126 ms/op
     p(50.0000) =      5.825 ms/op
     p(90.0000) =      7.299 ms/op
     p(95.0000) =      8.421 ms/op
     p(99.0000) =     12.386 ms/op
     p(99.9000) =     28.131 ms/op
     p(99.9900) =     33.649 ms/op
     p(99.9990) =     34.698 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.140 ± 2.738  ops/ms
ClientPb.existUser                       thrpt       3   6.273 ± 1.928  ops/ms
ClientPb.getUser                         thrpt       3   6.173 ± 1.857  ops/ms
ClientPb.listUser                        thrpt       3   5.169 ± 3.486  ops/ms
ClientPb.createUser                       avgt       3   5.131 ± 0.280   ms/op
ClientPb.existUser                        avgt       3   4.701 ± 2.072   ms/op
ClientPb.getUser                          avgt       3   5.126 ± 3.271   ms/op
ClientPb.listUser                         avgt       3   5.797 ± 1.918   ms/op
ClientPb.createUser                     sample  181358   5.293 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.563           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.997           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.480           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.414           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.027           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.020           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.312           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.569           ms/op
ClientPb.existUser                      sample  182892   5.244 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.290           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.973           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.365           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.291           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.207           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.022           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.298           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.127           ms/op
ClientPb.getUser                        sample  180853   5.304 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.068           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.005           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.267           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.422           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.928           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.123           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.849           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.687           ms/op
ClientPb.listUser                       sample  155500   6.170 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.126           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.825           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.299           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.421           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.386           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.131           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.649           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.734           ms/op
