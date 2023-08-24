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
# Warmup Iteration   1: 2.472 ops/ms
# Warmup Iteration   2: 6.260 ops/ms
# Warmup Iteration   3: 8.998 ops/ms
Iteration   1: 9.696 ops/ms
Iteration   2: 9.561 ops/ms
Iteration   3: 9.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.647 ±(99.9%) 1.358 ops/ms [Average]
  (min, avg, max) = (9.561, 9.647, 9.696), stdev = 0.074
  CI (99.9%): [8.289, 11.004] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.377 ops/ms
# Warmup Iteration   2: 9.272 ops/ms
# Warmup Iteration   3: 10.245 ops/ms
Iteration   1: 10.169 ops/ms
Iteration   2: 10.341 ops/ms
Iteration   3: 10.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.317 ±(99.9%) 2.520 ops/ms [Average]
  (min, avg, max) = (10.169, 10.317, 10.442), stdev = 0.138
  CI (99.9%): [7.797, 12.837] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.456 ops/ms
# Warmup Iteration   2: 8.979 ops/ms
# Warmup Iteration   3: 9.594 ops/ms
Iteration   1: 9.582 ops/ms
Iteration   2: 10.044 ops/ms
Iteration   3: 9.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.759 ±(99.9%) 4.541 ops/ms [Average]
  (min, avg, max) = (9.582, 9.759, 10.044), stdev = 0.249
  CI (99.9%): [5.218, 14.300] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.858 ops/ms
# Warmup Iteration   2: 7.382 ops/ms
# Warmup Iteration   3: 8.210 ops/ms
Iteration   1: 8.361 ops/ms
Iteration   2: 8.465 ops/ms
Iteration   3: 8.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.439 ±(99.9%) 1.245 ops/ms [Average]
  (min, avg, max) = (8.361, 8.439, 8.490), stdev = 0.068
  CI (99.9%): [7.194, 9.683] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.111 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.005 ms/op
Iteration   1: 3.222 ±(99.9%) 0.007 ms/op
Iteration   2: 3.300 ±(99.9%) 0.004 ms/op
Iteration   3: 3.263 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.262 ±(99.9%) 0.715 ms/op [Average]
  (min, avg, max) = (3.222, 3.262, 3.300), stdev = 0.039
  CI (99.9%): [2.546, 3.977] (assumes normal distribution)


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
# Warmup Iteration   1: 7.425 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.005 ms/op
Iteration   1: 3.148 ±(99.9%) 0.003 ms/op
Iteration   2: 3.195 ±(99.9%) 0.005 ms/op
Iteration   3: 3.082 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.142 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (3.082, 3.142, 3.195), stdev = 0.057
  CI (99.9%): [2.103, 4.180] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.753 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.486 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.005 ms/op
Iteration   1: 3.277 ±(99.9%) 0.008 ms/op
Iteration   2: 3.225 ±(99.9%) 0.003 ms/op
Iteration   3: 3.312 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.271 ±(99.9%) 0.800 ms/op [Average]
  (min, avg, max) = (3.225, 3.271, 3.312), stdev = 0.044
  CI (99.9%): [2.471, 4.071] (assumes normal distribution)


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
# Warmup Iteration   1: 9.293 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.028 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.009 ms/op
Iteration   1: 3.784 ±(99.9%) 0.009 ms/op
Iteration   2: 3.851 ±(99.9%) 0.006 ms/op
Iteration   3: 3.787 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.807 ±(99.9%) 0.690 ms/op [Average]
  (min, avg, max) = (3.784, 3.807, 3.851), stdev = 0.038
  CI (99.9%): [3.117, 4.497] (assumes normal distribution)


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
# Warmup Iteration   1: 8.213 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.009 ms/op
Iteration   1: 3.223 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  19.005 ms/op
                 createUser·p0.9999: 26.235 ms/op
                 createUser·p1.00:   27.066 ms/op

Iteration   2: 3.326 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.128 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.910 ms/op
                 createUser·p0.999:  17.173 ms/op
                 createUser·p0.9999: 23.311 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   3: 3.225 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  14.575 ms/op
                 createUser·p0.9999: 25.468 ms/op
                 createUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294577
  mean =      3.257 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18048 
    [ 2.500,  5.000) = 270055 
    [ 5.000,  7.500) = 5251 
    [ 7.500, 10.000) = 730 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     17.548 ms/op
     p(99.9900) =     25.577 ms/op
     p(99.9990) =     27.066 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.638 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.009 ms/op
Iteration   1: 3.242 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.366 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.145 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  13.615 ms/op
                 existUser·p0.9999: 23.138 ms/op
                 existUser·p1.00:   25.035 ms/op

Iteration   2: 3.078 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.524 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  10.682 ms/op
                 existUser·p0.9999: 27.630 ms/op
                 existUser·p1.00:   28.967 ms/op

Iteration   3: 3.156 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  11.088 ms/op
                 existUser·p0.9999: 23.627 ms/op
                 existUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304210
  mean =      3.157 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22287 
    [ 2.500,  5.000) = 275036 
    [ 5.000,  7.500) = 5729 
    [ 7.500, 10.000) = 754 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 139 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.366 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     11.940 ms/op
     p(99.9900) =     25.719 ms/op
     p(99.9990) =     28.302 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 7.754 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.410 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.011 ms/op
Iteration   1: 3.291 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  18.606 ms/op
                 getUser·p0.9999: 20.915 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   2: 3.183 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.567 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  10.807 ms/op
                 getUser·p0.9999: 23.884 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   3: 3.190 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   5.907 ms/op
                 getUser·p0.999:  10.530 ms/op
                 getUser·p0.9999: 21.129 ms/op
                 getUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297909
  mean =      3.221 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7583 
    [ 2.500,  5.000) = 281882 
    [ 5.000,  7.500) = 7019 
    [ 7.500, 10.000) = 1055 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     14.911 ms/op
     p(99.9900) =     21.873 ms/op
     p(99.9990) =     24.445 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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
# Warmup Iteration   1: 9.036 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.223 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.014 ms/op
Iteration   1: 3.769 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   7.195 ms/op
                 listUser·p0.999:  14.451 ms/op
                 listUser·p0.9999: 22.184 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   2: 3.750 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   7.107 ms/op
                 listUser·p0.999:  13.380 ms/op
                 listUser·p0.9999: 16.187 ms/op
                 listUser·p1.00:   16.335 ms/op

Iteration   3: 3.765 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.677 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  13.042 ms/op
                 listUser·p0.9999: 15.868 ms/op
                 listUser·p1.00:   15.925 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255273
  mean =      3.761 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 247311 
    [ 5.000,  7.500) = 5581 
    [ 7.500, 10.000) = 1575 
    [10.000, 12.500) = 322 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     22.542 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.647 ± 1.358  ops/ms
ClientPb.existUser                       thrpt       3  10.317 ± 2.520  ops/ms
ClientPb.getUser                         thrpt       3   9.759 ± 4.541  ops/ms
ClientPb.listUser                        thrpt       3   8.439 ± 1.245  ops/ms
ClientPb.createUser                       avgt       3   3.262 ± 0.715   ms/op
ClientPb.existUser                        avgt       3   3.142 ± 1.039   ms/op
ClientPb.getUser                          avgt       3   3.271 ± 0.800   ms/op
ClientPb.listUser                         avgt       3   3.807 ± 0.690   ms/op
ClientPb.createUser                     sample  294577   3.257 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.128           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.666           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.775           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.548           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.577           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.361           ms/op
ClientPb.existUser                      sample  304210   3.157 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.366           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.445           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.940           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.719           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.967           ms/op
ClientPb.getUser                        sample  297909   3.221 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.973           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.518           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.177           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.911           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.873           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.510           ms/op
ClientPb.listUser                       sample  255273   3.761 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.348           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.026           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.340           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.599           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.939           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.807           ms/op
