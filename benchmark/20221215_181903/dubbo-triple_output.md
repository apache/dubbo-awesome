# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.061 ops/ms
# Warmup Iteration   2: 5.544 ops/ms
# Warmup Iteration   3: 8.798 ops/ms
Iteration   1: 9.335 ops/ms
Iteration   2: 9.264 ops/ms
Iteration   3: 9.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.472 ±(99.9%) 5.497 ops/ms [Average]
  (min, avg, max) = (9.264, 9.472, 9.817), stdev = 0.301
  CI (99.9%): [3.975, 14.969] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.096 ops/ms
# Warmup Iteration   2: 8.758 ops/ms
# Warmup Iteration   3: 9.458 ops/ms
Iteration   1: 9.779 ops/ms
Iteration   2: 10.113 ops/ms
Iteration   3: 10.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.983 ±(99.9%) 3.266 ops/ms [Average]
  (min, avg, max) = (9.779, 9.983, 10.113), stdev = 0.179
  CI (99.9%): [6.716, 13.249] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.167 ops/ms
# Warmup Iteration   2: 8.505 ops/ms
# Warmup Iteration   3: 9.501 ops/ms
Iteration   1: 9.714 ops/ms
Iteration   2: 9.664 ops/ms
Iteration   3: 9.997 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.792 ±(99.9%) 3.279 ops/ms [Average]
  (min, avg, max) = (9.664, 9.792, 9.997), stdev = 0.180
  CI (99.9%): [6.513, 13.071] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.767 ops/ms
# Warmup Iteration   2: 7.270 ops/ms
# Warmup Iteration   3: 7.717 ops/ms
Iteration   1: 8.029 ops/ms
Iteration   2: 8.165 ops/ms
Iteration   3: 7.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.032 ±(99.9%) 2.379 ops/ms [Average]
  (min, avg, max) = (7.904, 8.032, 8.165), stdev = 0.130
  CI (99.9%): [5.654, 10.411] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.625 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.006 ms/op
Iteration   1: 3.337 ±(99.9%) 0.011 ms/op
Iteration   2: 3.376 ±(99.9%) 0.009 ms/op
Iteration   3: 3.310 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.341 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (3.310, 3.341, 3.376), stdev = 0.033
  CI (99.9%): [2.734, 3.947] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.001 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.593 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.249 ±(99.9%) 0.008 ms/op
Iteration   1: 3.249 ±(99.9%) 0.011 ms/op
Iteration   2: 3.241 ±(99.9%) 0.005 ms/op
Iteration   3: 3.313 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.267 ±(99.9%) 0.721 ms/op [Average]
  (min, avg, max) = (3.241, 3.267, 3.313), stdev = 0.040
  CI (99.9%): [2.546, 3.989] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.701 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.229 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.008 ms/op
Iteration   1: 3.484 ±(99.9%) 0.003 ms/op
Iteration   2: 3.295 ±(99.9%) 0.005 ms/op
Iteration   3: 3.508 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.429 ±(99.9%) 2.126 ms/op [Average]
  (min, avg, max) = (3.295, 3.429, 3.508), stdev = 0.117
  CI (99.9%): [1.303, 5.555] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.869 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.008 ms/op
Iteration   1: 3.916 ±(99.9%) 0.014 ms/op
Iteration   2: 3.875 ±(99.9%) 0.016 ms/op
Iteration   3: 3.837 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.876 ±(99.9%) 0.717 ms/op [Average]
  (min, avg, max) = (3.837, 3.876, 3.916), stdev = 0.039
  CI (99.9%): [3.159, 4.594] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.708 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.548 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.011 ms/op
Iteration   1: 3.381 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  21.706 ms/op
                 createUser·p0.9999: 23.646 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   2: 3.508 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.696 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   6.316 ms/op
                 createUser·p0.999:  22.441 ms/op
                 createUser·p0.9999: 26.247 ms/op
                 createUser·p1.00:   26.935 ms/op

Iteration   3: 3.410 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.346 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   6.242 ms/op
                 createUser·p0.999:  20.495 ms/op
                 createUser·p0.9999: 26.214 ms/op
                 createUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279494
  mean =      3.432 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13337 
    [ 2.500,  5.000) = 257902 
    [ 5.000,  7.500) = 7224 
    [ 7.500, 10.000) = 577 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 158 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     20.693 ms/op
     p(99.9900) =     26.151 ms/op
     p(99.9990) =     27.074 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.174 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.009 ms/op
Iteration   1: 3.279 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.634 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  12.194 ms/op
                 existUser·p0.9999: 23.240 ms/op
                 existUser·p1.00:   23.822 ms/op

Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.210 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.858 ms/op
                 existUser·p0.999:  10.760 ms/op
                 existUser·p0.9999: 30.139 ms/op
                 existUser·p1.00:   30.933 ms/op

Iteration   3: 3.234 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.139 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  14.836 ms/op
                 existUser·p0.9999: 25.395 ms/op
                 existUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296966
  mean =      3.232 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10613 
    [ 2.500,  5.000) = 281762 
    [ 5.000,  7.500) = 3564 
    [ 7.500, 10.000) = 520 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     13.027 ms/op
     p(99.9900) =     29.131 ms/op
     p(99.9990) =     30.671 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.625 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.639 ±(99.9%) 0.013 ms/op
Iteration   1: 3.482 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.993 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  20.257 ms/op
                 getUser·p0.9999: 24.341 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   2: 3.323 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.520 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  21.468 ms/op
                 getUser·p0.9999: 27.767 ms/op
                 getUser·p1.00:   28.115 ms/op

Iteration   3: 3.536 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.618 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  11.141 ms/op
                 getUser·p0.9999: 27.341 ms/op
                 getUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278321
  mean =      3.445 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6861 
    [ 2.500,  5.000) = 262086 
    [ 5.000,  7.500) = 7783 
    [ 7.500, 10.000) = 1120 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 81 

  Percentiles, ms/op:
      p(0.0000) =      0.993 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     15.603 ms/op
     p(99.9900) =     27.361 ms/op
     p(99.9990) =     28.038 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.230 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.386 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.237 ±(99.9%) 0.015 ms/op
Iteration   1: 4.006 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  20.819 ms/op
                 listUser·p0.9999: 23.529 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   2: 3.889 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.671 ms/op
                 listUser·p0.999:  15.887 ms/op
                 listUser·p0.9999: 18.799 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   3: 3.921 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  16.211 ms/op
                 listUser·p0.9999: 21.299 ms/op
                 listUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243564
  mean =      3.938 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 237216 
    [ 5.000,  7.500) = 4668 
    [ 7.500, 10.000) = 977 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 222 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.466 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     22.554 ms/op
     p(99.9990) =     24.332 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.472 ± 5.497  ops/ms
ClientPb.existUser                       thrpt       3   9.983 ± 3.266  ops/ms
ClientPb.getUser                         thrpt       3   9.792 ± 3.279  ops/ms
ClientPb.listUser                        thrpt       3   8.032 ± 2.379  ops/ms
ClientPb.createUser                       avgt       3   3.341 ± 0.606   ms/op
ClientPb.existUser                        avgt       3   3.267 ± 0.721   ms/op
ClientPb.getUser                          avgt       3   3.429 ± 2.126   ms/op
ClientPb.listUser                         avgt       3   3.876 ± 0.717   ms/op
ClientPb.createUser                     sample  279494   3.432 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.346           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.128           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.693           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.151           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.754           ms/op
ClientPb.existUser                      sample  296966   3.232 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.139           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.027           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.131           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.933           ms/op
ClientPb.getUser                        sample  278321   3.445 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.993           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.277           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.685           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.603           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.361           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.410           ms/op
ClientPb.listUser                       sample  243564   3.938 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.466           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.157           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.791           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.039           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.554           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.379           ms/op
