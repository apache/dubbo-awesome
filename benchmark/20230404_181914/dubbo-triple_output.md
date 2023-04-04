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
# Warmup Iteration   1: 2.682 ops/ms
# Warmup Iteration   2: 6.339 ops/ms
# Warmup Iteration   3: 9.103 ops/ms
Iteration   1: 9.987 ops/ms
Iteration   2: 9.855 ops/ms
Iteration   3: 10.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.017 ±(99.9%) 3.269 ops/ms [Average]
  (min, avg, max) = (9.855, 10.017, 10.210), stdev = 0.179
  CI (99.9%): [6.748, 13.287] (assumes normal distribution)


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
# Warmup Iteration   1: 3.539 ops/ms
# Warmup Iteration   2: 9.452 ops/ms
# Warmup Iteration   3: 9.779 ops/ms
Iteration   1: 10.048 ops/ms
Iteration   2: 10.033 ops/ms
Iteration   3: 10.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.067 ±(99.9%) 0.863 ops/ms [Average]
  (min, avg, max) = (10.033, 10.067, 10.121), stdev = 0.047
  CI (99.9%): [9.204, 10.931] (assumes normal distribution)


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
# Warmup Iteration   1: 3.686 ops/ms
# Warmup Iteration   2: 9.261 ops/ms
# Warmup Iteration   3: 9.727 ops/ms
Iteration   1: 10.276 ops/ms
Iteration   2: 10.029 ops/ms
Iteration   3: 9.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.980 ±(99.9%) 5.881 ops/ms [Average]
  (min, avg, max) = (9.637, 9.980, 10.276), stdev = 0.322
  CI (99.9%): [4.100, 15.861] (assumes normal distribution)


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
# Warmup Iteration   1: 3.538 ops/ms
# Warmup Iteration   2: 7.741 ops/ms
# Warmup Iteration   3: 8.387 ops/ms
Iteration   1: 8.303 ops/ms
Iteration   2: 7.977 ops/ms
Iteration   3: 8.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.287 ±(99.9%) 5.521 ops/ms [Average]
  (min, avg, max) = (7.977, 8.287, 8.581), stdev = 0.303
  CI (99.9%): [2.766, 13.808] (assumes normal distribution)


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
# Warmup Iteration   1: 8.733 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.004 ms/op
Iteration   1: 3.299 ±(99.9%) 0.008 ms/op
Iteration   2: 3.275 ±(99.9%) 0.003 ms/op
Iteration   3: 3.131 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.235 ±(99.9%) 1.663 ms/op [Average]
  (min, avg, max) = (3.131, 3.235, 3.299), stdev = 0.091
  CI (99.9%): [1.572, 4.898] (assumes normal distribution)


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
# Warmup Iteration   1: 7.872 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.005 ms/op
Iteration   1: 3.046 ±(99.9%) 0.002 ms/op
Iteration   2: 3.032 ±(99.9%) 0.005 ms/op
Iteration   3: 3.061 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.047 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (3.032, 3.047, 3.061), stdev = 0.014
  CI (99.9%): [2.783, 3.310] (assumes normal distribution)


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
# Warmup Iteration   1: 7.668 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.467 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.004 ms/op
Iteration   1: 3.062 ±(99.9%) 0.004 ms/op
Iteration   2: 3.229 ±(99.9%) 0.009 ms/op
Iteration   3: 3.106 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.132 ±(99.9%) 1.579 ms/op [Average]
  (min, avg, max) = (3.062, 3.132, 3.229), stdev = 0.087
  CI (99.9%): [1.553, 4.711] (assumes normal distribution)


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
# Warmup Iteration   1: 9.171 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.238 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.005 ms/op
Iteration   1: 3.784 ±(99.9%) 0.007 ms/op
Iteration   2: 3.789 ±(99.9%) 0.006 ms/op
Iteration   3: 3.761 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.778 ±(99.9%) 0.279 ms/op [Average]
  (min, avg, max) = (3.761, 3.778, 3.789), stdev = 0.015
  CI (99.9%): [3.499, 4.057] (assumes normal distribution)


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
# Warmup Iteration   1: 7.954 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.800 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.010 ms/op
Iteration   1: 3.314 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.303 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   6.226 ms/op
                 createUser·p0.999:  17.518 ms/op
                 createUser·p0.9999: 26.815 ms/op
                 createUser·p1.00:   27.820 ms/op

Iteration   2: 3.187 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  19.966 ms/op
                 createUser·p0.9999: 24.903 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   3: 3.105 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.671 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.244 ms/op
                 createUser·p0.95:   3.584 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  12.026 ms/op
                 createUser·p0.9999: 17.830 ms/op
                 createUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299881
  mean =      3.200 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18048 
    [ 2.500,  5.000) = 274679 
    [ 5.000,  7.500) = 6209 
    [ 7.500, 10.000) = 509 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     15.647 ms/op
     p(99.9900) =     25.429 ms/op
     p(99.9990) =     27.329 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 6.877 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.477 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
Iteration   1: 3.155 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.023 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  12.330 ms/op
                 existUser·p0.9999: 19.263 ms/op
                 existUser·p1.00:   20.021 ms/op

Iteration   2: 3.105 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  9.119 ms/op
                 existUser·p0.9999: 22.437 ms/op
                 existUser·p1.00:   23.855 ms/op

Iteration   3: 3.208 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.538 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  9.182 ms/op
                 existUser·p0.9999: 20.678 ms/op
                 existUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303944
  mean =      3.155 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22420 
    [ 2.500,  5.000) = 276774 
    [ 5.000,  7.500) = 4147 
    [ 7.500, 10.000) = 262 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     12.288 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     22.833 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 7.319 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.410 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.009 ms/op
Iteration   1: 3.295 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.442 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  17.524 ms/op
                 getUser·p0.9999: 20.218 ms/op
                 getUser·p1.00:   20.972 ms/op

Iteration   2: 3.158 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  10.502 ms/op
                 getUser·p0.9999: 21.885 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   3: 3.303 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.620 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   6.365 ms/op
                 getUser·p0.999:  16.816 ms/op
                 getUser·p0.9999: 22.282 ms/op
                 getUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294976
  mean =      3.251 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16821 
    [ 2.500,  5.000) = 270129 
    [ 5.000,  7.500) = 6822 
    [ 7.500, 10.000) = 660 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 152 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     16.499 ms/op
     p(99.9900) =     21.824 ms/op
     p(99.9990) =     22.938 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 8.899 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.967 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.761 ±(99.9%) 0.011 ms/op
Iteration   1: 3.691 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.673 ms/op
                 listUser·p0.999:  14.123 ms/op
                 listUser·p0.9999: 19.475 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   2: 3.685 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.226 ms/op
                 listUser·p0.999:  12.092 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   3: 3.726 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.170 ms/op
                 listUser·p0.99:   6.431 ms/op
                 listUser·p0.999:  13.124 ms/op
                 listUser·p0.9999: 16.424 ms/op
                 listUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259443
  mean =      3.700 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 253466 
    [ 5.000,  7.500) = 4606 
    [ 7.500, 10.000) = 743 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.452 ms/op
     p(99.9000) =     13.573 ms/op
     p(99.9900) =     19.007 ms/op
     p(99.9990) =     20.087 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.017 ± 3.269  ops/ms
ClientPb.existUser                       thrpt       3  10.067 ± 0.863  ops/ms
ClientPb.getUser                         thrpt       3   9.980 ± 5.881  ops/ms
ClientPb.listUser                        thrpt       3   8.287 ± 5.521  ops/ms
ClientPb.createUser                       avgt       3   3.235 ± 1.663   ms/op
ClientPb.existUser                        avgt       3   3.047 ± 0.263   ms/op
ClientPb.getUser                          avgt       3   3.132 ± 1.579   ms/op
ClientPb.listUser                         avgt       3   3.778 ± 0.279   ms/op
ClientPb.createUser                     sample  299881   3.200 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.223           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.596           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.792           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.647           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.429           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.820           ms/op
ClientPb.existUser                      sample  303944   3.155 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.023           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.478           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.333           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.288           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.561           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.855           ms/op
ClientPb.getUser                        sample  294976   3.251 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.976           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.670           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.111           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.499           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.824           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.216           ms/op
ClientPb.listUser                       sample  259443   3.700 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.462           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.617           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.452           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.573           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.007           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.185           ms/op
