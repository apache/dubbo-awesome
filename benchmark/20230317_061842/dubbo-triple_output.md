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
# Warmup Iteration   1: 2.416 ops/ms
# Warmup Iteration   2: 6.132 ops/ms
# Warmup Iteration   3: 9.095 ops/ms
Iteration   1: 9.791 ops/ms
Iteration   2: 9.931 ops/ms
Iteration   3: 9.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.832 ±(99.9%) 1.573 ops/ms [Average]
  (min, avg, max) = (9.774, 9.832, 9.931), stdev = 0.086
  CI (99.9%): [8.258, 11.405] (assumes normal distribution)


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
# Warmup Iteration   1: 3.290 ops/ms
# Warmup Iteration   2: 9.424 ops/ms
# Warmup Iteration   3: 9.890 ops/ms
Iteration   1: 9.441 ops/ms
Iteration   2: 10.216 ops/ms
Iteration   3: 10.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.000 ±(99.9%) 8.920 ops/ms [Average]
  (min, avg, max) = (9.441, 10.000, 10.344), stdev = 0.489
  CI (99.9%): [1.081, 18.920] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.318 ops/ms
# Warmup Iteration   2: 8.914 ops/ms
# Warmup Iteration   3: 9.943 ops/ms
Iteration   1: 10.072 ops/ms
Iteration   2: 9.987 ops/ms
Iteration   3: 10.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.033 ±(99.9%) 0.781 ops/ms [Average]
  (min, avg, max) = (9.987, 10.033, 10.072), stdev = 0.043
  CI (99.9%): [9.251, 10.814] (assumes normal distribution)


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
# Warmup Iteration   1: 3.530 ops/ms
# Warmup Iteration   2: 7.911 ops/ms
# Warmup Iteration   3: 8.269 ops/ms
Iteration   1: 8.316 ops/ms
Iteration   2: 8.421 ops/ms
Iteration   3: 8.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.450 ±(99.9%) 2.760 ops/ms [Average]
  (min, avg, max) = (8.316, 8.450, 8.614), stdev = 0.151
  CI (99.9%): [5.690, 11.211] (assumes normal distribution)


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
# Warmup Iteration   1: 7.785 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.519 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.003 ms/op
Iteration   1: 3.187 ±(99.9%) 0.004 ms/op
Iteration   2: 3.112 ±(99.9%) 0.002 ms/op
Iteration   3: 3.135 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.145 ±(99.9%) 0.701 ms/op [Average]
  (min, avg, max) = (3.112, 3.145, 3.187), stdev = 0.038
  CI (99.9%): [2.443, 3.846] (assumes normal distribution)


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
# Warmup Iteration   1: 7.383 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.301 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.004 ms/op
Iteration   1: 3.169 ±(99.9%) 0.008 ms/op
Iteration   2: 3.049 ±(99.9%) 0.004 ms/op
Iteration   3: 3.087 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.102 ±(99.9%) 1.123 ms/op [Average]
  (min, avg, max) = (3.049, 3.102, 3.169), stdev = 0.062
  CI (99.9%): [1.979, 4.225] (assumes normal distribution)


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
# Warmup Iteration   1: 8.078 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.570 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.002 ms/op
Iteration   1: 3.188 ±(99.9%) 0.004 ms/op
Iteration   2: 3.138 ±(99.9%) 0.003 ms/op
Iteration   3: 3.175 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.167 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (3.138, 3.167, 3.188), stdev = 0.026
  CI (99.9%): [2.695, 3.638] (assumes normal distribution)


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
# Warmup Iteration   1: 8.184 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.954 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.826 ±(99.9%) 0.008 ms/op
Iteration   1: 3.788 ±(99.9%) 0.008 ms/op
Iteration   2: 3.648 ±(99.9%) 0.011 ms/op
Iteration   3: 3.745 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.727 ±(99.9%) 1.315 ms/op [Average]
  (min, avg, max) = (3.648, 3.727, 3.788), stdev = 0.072
  CI (99.9%): [2.413, 5.042] (assumes normal distribution)


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
# Warmup Iteration   1: 8.343 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.008 ms/op
Iteration   1: 3.187 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  12.904 ms/op
                 createUser·p0.9999: 18.970 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   2: 3.130 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  11.743 ms/op
                 createUser·p0.9999: 25.323 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   3: 3.147 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  15.278 ms/op
                 createUser·p0.9999: 21.037 ms/op
                 createUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304006
  mean =      3.155 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10603 
    [ 2.500,  5.000) = 288244 
    [ 5.000,  7.500) = 4246 
    [ 7.500, 10.000) = 467 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     23.940 ms/op
     p(99.9990) =     25.786 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 8.310 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
Iteration   1: 3.145 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.090 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   6.038 ms/op
                 existUser·p0.999:  9.376 ms/op
                 existUser·p0.9999: 19.950 ms/op
                 existUser·p1.00:   20.447 ms/op

Iteration   2: 3.141 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.042 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  13.415 ms/op
                 existUser·p0.9999: 31.228 ms/op
                 existUser·p1.00:   31.752 ms/op

Iteration   3: 3.222 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.579 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  8.585 ms/op
                 existUser·p0.9999: 23.857 ms/op
                 existUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302842
  mean =      3.169 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18195 
    [ 2.500,  5.000) = 277557 
    [ 5.000,  7.500) = 6287 
    [ 7.500, 10.000) = 385 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     29.950 ms/op
     p(99.9990) =     31.751 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 8.717 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.667 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.009 ms/op
Iteration   1: 3.316 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.395 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  17.709 ms/op
                 getUser·p0.9999: 23.661 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   2: 3.215 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.430 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   5.300 ms/op
                 getUser·p0.999:  9.701 ms/op
                 getUser·p0.9999: 26.022 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   3: 3.198 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.153 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   5.928 ms/op
                 getUser·p0.999:  10.484 ms/op
                 getUser·p0.9999: 21.397 ms/op
                 getUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296211
  mean =      3.242 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14352 
    [ 2.500,  5.000) = 274201 
    [ 5.000,  7.500) = 6756 
    [ 7.500, 10.000) = 529 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     16.056 ms/op
     p(99.9900) =     24.650 ms/op
     p(99.9990) =     26.576 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 9.171 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.785 ±(99.9%) 0.010 ms/op
Iteration   1: 3.904 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  14.480 ms/op
                 listUser·p0.9999: 25.256 ms/op
                 listUser·p1.00:   25.657 ms/op

Iteration   2: 3.758 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.864 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  12.714 ms/op
                 listUser·p0.9999: 16.843 ms/op
                 listUser·p1.00:   16.876 ms/op

Iteration   3: 3.740 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  12.599 ms/op
                 listUser·p0.9999: 17.924 ms/op
                 listUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252912
  mean =      3.799 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 244316 
    [ 5.000,  7.500) = 6757 
    [ 7.500, 10.000) = 1158 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 265 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.864 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     13.076 ms/op
     p(99.9900) =     23.499 ms/op
     p(99.9990) =     25.590 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.832 ± 1.573  ops/ms
ClientPb.existUser                       thrpt       3  10.000 ± 8.920  ops/ms
ClientPb.getUser                         thrpt       3  10.033 ± 0.781  ops/ms
ClientPb.listUser                        thrpt       3   8.450 ± 2.760  ops/ms
ClientPb.createUser                       avgt       3   3.145 ± 0.701   ms/op
ClientPb.existUser                        avgt       3   3.102 ± 1.123   ms/op
ClientPb.getUser                          avgt       3   3.167 ± 0.472   ms/op
ClientPb.listUser                         avgt       3   3.727 ± 1.315   ms/op
ClientPb.createUser                     sample  304006   3.155 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.143           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.523           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.756           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.612           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.270           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.940           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.083           ms/op
ClientPb.existUser                      sample  302842   3.169 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.042           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.571           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.353           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.950           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.752           ms/op
ClientPb.getUser                        sample  296211   3.242 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.153           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.674           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.988           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.056           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.650           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.001           ms/op
ClientPb.listUser                       sample  252912   3.799 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.864           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.125           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.996           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.076           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.499           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.657           ms/op
