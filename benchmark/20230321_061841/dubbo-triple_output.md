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
# Warmup Iteration   1: 2.687 ops/ms
# Warmup Iteration   2: 6.177 ops/ms
# Warmup Iteration   3: 9.043 ops/ms
Iteration   1: 9.778 ops/ms
Iteration   2: 9.927 ops/ms
Iteration   3: 9.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.726 ±(99.9%) 4.218 ops/ms [Average]
  (min, avg, max) = (9.474, 9.726, 9.927), stdev = 0.231
  CI (99.9%): [5.508, 13.944] (assumes normal distribution)


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
# Warmup Iteration   1: 3.358 ops/ms
# Warmup Iteration   2: 9.307 ops/ms
# Warmup Iteration   3: 10.449 ops/ms
Iteration   1: 10.505 ops/ms
Iteration   2: 10.568 ops/ms
Iteration   3: 9.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.277 ±(99.9%) 8.217 ops/ms [Average]
  (min, avg, max) = (9.758, 10.277, 10.568), stdev = 0.450
  CI (99.9%): [2.061, 18.494] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.287 ops/ms
# Warmup Iteration   2: 9.012 ops/ms
# Warmup Iteration   3: 9.450 ops/ms
Iteration   1: 9.786 ops/ms
Iteration   2: 10.366 ops/ms
Iteration   3: 9.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.995 ±(99.9%) 5.884 ops/ms [Average]
  (min, avg, max) = (9.786, 9.995, 10.366), stdev = 0.323
  CI (99.9%): [4.110, 15.879] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.230 ops/ms
# Warmup Iteration   2: 7.819 ops/ms
# Warmup Iteration   3: 8.472 ops/ms
Iteration   1: 8.419 ops/ms
Iteration   2: 8.479 ops/ms
Iteration   3: 8.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.473 ±(99.9%) 0.935 ops/ms [Average]
  (min, avg, max) = (8.419, 8.473, 8.521), stdev = 0.051
  CI (99.9%): [7.538, 9.408] (assumes normal distribution)


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
# Warmup Iteration   1: 7.269 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.453 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.004 ms/op
Iteration   1: 3.133 ±(99.9%) 0.005 ms/op
Iteration   2: 3.170 ±(99.9%) 0.008 ms/op
Iteration   3: 3.065 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.123 ±(99.9%) 0.978 ms/op [Average]
  (min, avg, max) = (3.065, 3.123, 3.170), stdev = 0.054
  CI (99.9%): [2.144, 4.101] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.190 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.403 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.004 ms/op
Iteration   1: 3.033 ±(99.9%) 0.003 ms/op
Iteration   2: 3.085 ±(99.9%) 0.008 ms/op
Iteration   3: 3.059 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.059 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (3.033, 3.059, 3.085), stdev = 0.026
  CI (99.9%): [2.585, 3.532] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.136 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.374 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.300 ±(99.9%) 0.004 ms/op
Iteration   1: 3.214 ±(99.9%) 0.007 ms/op
Iteration   2: 3.195 ±(99.9%) 0.003 ms/op
Iteration   3: 3.183 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.198 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (3.183, 3.198, 3.214), stdev = 0.016
  CI (99.9%): [2.911, 3.484] (assumes normal distribution)


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
# Warmup Iteration   1: 8.925 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.007 ms/op
Iteration   1: 3.892 ±(99.9%) 0.007 ms/op
Iteration   2: 3.769 ±(99.9%) 0.008 ms/op
Iteration   3: 3.673 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.778 ±(99.9%) 2.004 ms/op [Average]
  (min, avg, max) = (3.673, 3.778, 3.892), stdev = 0.110
  CI (99.9%): [1.774, 5.781] (assumes normal distribution)


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
# Warmup Iteration   1: 8.442 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.827 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.325 ±(99.9%) 0.009 ms/op
Iteration   1: 3.182 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  18.082 ms/op
                 createUser·p0.9999: 21.394 ms/op
                 createUser·p1.00:   22.053 ms/op

Iteration   2: 3.241 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  17.072 ms/op
                 createUser·p0.9999: 26.018 ms/op
                 createUser·p1.00:   27.263 ms/op

Iteration   3: 3.311 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  17.381 ms/op
                 createUser·p0.9999: 25.133 ms/op
                 createUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295766
  mean =      3.244 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19768 
    [ 2.500,  5.000) = 268929 
    [ 5.000,  7.500) = 6070 
    [ 7.500, 10.000) = 478 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     17.924 ms/op
     p(99.9900) =     25.166 ms/op
     p(99.9990) =     27.099 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 7.101 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 3.352 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.007 ms/op
Iteration   1: 3.106 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  10.279 ms/op
                 existUser·p0.9999: 18.995 ms/op
                 existUser·p1.00:   19.956 ms/op

Iteration   2: 3.199 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  14.664 ms/op
                 existUser·p0.9999: 21.399 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   3: 3.156 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.321 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  8.206 ms/op
                 existUser·p0.9999: 23.785 ms/op
                 existUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304196
  mean =      3.153 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29876 
    [ 2.500,  5.000) = 268374 
    [ 5.000,  7.500) = 5301 
    [ 7.500, 10.000) = 340 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     10.302 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     24.207 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 7.473 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.349 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.009 ms/op
Iteration   1: 3.241 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   6.216 ms/op
                 getUser·p0.999:  16.168 ms/op
                 getUser·p0.9999: 21.004 ms/op
                 getUser·p1.00:   21.823 ms/op

Iteration   2: 3.180 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  11.820 ms/op
                 getUser·p0.9999: 25.428 ms/op
                 getUser·p1.00:   26.116 ms/op

Iteration   3: 3.160 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.315 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  10.991 ms/op
                 getUser·p0.9999: 23.065 ms/op
                 getUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300478
  mean =      3.193 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15522 
    [ 2.500,  5.000) = 277174 
    [ 5.000,  7.500) = 6827 
    [ 7.500, 10.000) = 602 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 9.134 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.773 ±(99.9%) 0.011 ms/op
Iteration   1: 3.714 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  16.384 ms/op
                 listUser·p0.9999: 18.211 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   2: 3.685 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   3.535 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.170 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  14.025 ms/op
                 listUser·p0.9999: 19.758 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   3: 3.848 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  13.386 ms/op
                 listUser·p0.9999: 15.188 ms/op
                 listUser·p1.00:   15.254 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256049
  mean =      3.748 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 247480 
    [ 5.000,  7.500) = 6601 
    [ 7.500, 10.000) = 1265 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 274 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.483 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     14.123 ms/op
     p(99.9900) =     18.055 ms/op
     p(99.9990) =     20.312 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.726 ± 4.218  ops/ms
ClientPb.existUser                       thrpt       3  10.277 ± 8.217  ops/ms
ClientPb.getUser                         thrpt       3   9.995 ± 5.884  ops/ms
ClientPb.listUser                        thrpt       3   8.473 ± 0.935  ops/ms
ClientPb.createUser                       avgt       3   3.123 ± 0.978   ms/op
ClientPb.existUser                        avgt       3   3.059 ± 0.473   ms/op
ClientPb.getUser                          avgt       3   3.198 ± 0.287   ms/op
ClientPb.listUser                         avgt       3   3.778 ± 2.004   ms/op
ClientPb.createUser                     sample  295766   3.244 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.092           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.043           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.924           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.166           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.263           ms/op
ClientPb.existUser                      sample  304196   3.153 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.055           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.498           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.448           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.302           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.086           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.559           ms/op
ClientPb.getUser                        sample  300478   3.193 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.976           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.572           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.039           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.029           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.811           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.281           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.116           ms/op
ClientPb.listUser                       sample  256049   3.748 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.483           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.666           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.084           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.062           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.123           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.055           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.382           ms/op
