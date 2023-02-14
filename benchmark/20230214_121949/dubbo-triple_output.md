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
# Warmup Iteration   1: 2.168 ops/ms
# Warmup Iteration   2: 5.725 ops/ms
# Warmup Iteration   3: 8.692 ops/ms
Iteration   1: 9.523 ops/ms
Iteration   2: 9.332 ops/ms
Iteration   3: 9.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.443 ±(99.9%) 1.812 ops/ms [Average]
  (min, avg, max) = (9.332, 9.443, 9.523), stdev = 0.099
  CI (99.9%): [7.632, 11.255] (assumes normal distribution)


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
# Warmup Iteration   1: 3.467 ops/ms
# Warmup Iteration   2: 9.260 ops/ms
# Warmup Iteration   3: 9.436 ops/ms
Iteration   1: 9.828 ops/ms
Iteration   2: 9.746 ops/ms
Iteration   3: 9.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.837 ±(99.9%) 1.737 ops/ms [Average]
  (min, avg, max) = (9.746, 9.837, 9.936), stdev = 0.095
  CI (99.9%): [8.100, 11.573] (assumes normal distribution)


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
# Warmup Iteration   1: 2.706 ops/ms
# Warmup Iteration   2: 7.936 ops/ms
# Warmup Iteration   3: 9.411 ops/ms
Iteration   1: 9.587 ops/ms
Iteration   2: 9.597 ops/ms
Iteration   3: 9.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.463 ±(99.9%) 4.075 ops/ms [Average]
  (min, avg, max) = (9.205, 9.463, 9.597), stdev = 0.223
  CI (99.9%): [5.388, 13.538] (assumes normal distribution)


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
# Warmup Iteration   1: 2.889 ops/ms
# Warmup Iteration   2: 7.332 ops/ms
# Warmup Iteration   3: 7.694 ops/ms
Iteration   1: 8.149 ops/ms
Iteration   2: 8.072 ops/ms
Iteration   3: 8.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.096 ±(99.9%) 0.839 ops/ms [Average]
  (min, avg, max) = (8.068, 8.096, 8.149), stdev = 0.046
  CI (99.9%): [7.257, 8.935] (assumes normal distribution)


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
# Warmup Iteration   1: 9.711 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.004 ms/op
Iteration   1: 3.398 ±(99.9%) 0.009 ms/op
Iteration   2: 3.493 ±(99.9%) 0.009 ms/op
Iteration   3: 3.301 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.397 ±(99.9%) 1.754 ms/op [Average]
  (min, avg, max) = (3.301, 3.397, 3.493), stdev = 0.096
  CI (99.9%): [1.644, 5.151] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.383 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.491 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.003 ms/op
Iteration   1: 3.286 ±(99.9%) 0.007 ms/op
Iteration   2: 3.188 ±(99.9%) 0.008 ms/op
Iteration   3: 3.201 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.225 ±(99.9%) 0.969 ms/op [Average]
  (min, avg, max) = (3.188, 3.225, 3.286), stdev = 0.053
  CI (99.9%): [2.256, 4.194] (assumes normal distribution)


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
# Warmup Iteration   1: 8.609 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.006 ms/op
Iteration   1: 3.409 ±(99.9%) 0.007 ms/op
Iteration   2: 3.408 ±(99.9%) 0.010 ms/op
Iteration   3: 3.331 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.383 ±(99.9%) 0.812 ms/op [Average]
  (min, avg, max) = (3.331, 3.383, 3.409), stdev = 0.045
  CI (99.9%): [2.570, 4.195] (assumes normal distribution)


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
# Warmup Iteration   1: 11.174 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.185 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.010 ms/op
Iteration   1: 3.894 ±(99.9%) 0.014 ms/op
Iteration   2: 3.957 ±(99.9%) 0.008 ms/op
Iteration   3: 4.050 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.967 ±(99.9%) 1.433 ms/op [Average]
  (min, avg, max) = (3.894, 3.967, 4.050), stdev = 0.079
  CI (99.9%): [2.534, 5.399] (assumes normal distribution)


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
# Warmup Iteration   1: 8.050 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.311 ±(99.9%) 0.009 ms/op
Iteration   1: 3.272 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.307 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  21.601 ms/op
                 createUser·p0.9999: 25.395 ms/op
                 createUser·p1.00:   26.444 ms/op

Iteration   2: 3.348 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.219 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  19.867 ms/op
                 createUser·p0.9999: 26.000 ms/op
                 createUser·p1.00:   27.394 ms/op

Iteration   3: 3.281 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.628 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  15.061 ms/op
                 createUser·p0.9999: 31.302 ms/op
                 createUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290534
  mean =      3.300 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13008 
    [ 2.500,  5.000) = 272446 
    [ 5.000,  7.500) = 4011 
    [ 7.500, 10.000) = 485 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     19.595 ms/op
     p(99.9900) =     26.114 ms/op
     p(99.9990) =     31.362 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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
# Warmup Iteration   1: 9.702 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.008 ms/op
Iteration   1: 3.260 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   6.227 ms/op
                 existUser·p0.999:  10.429 ms/op
                 existUser·p0.9999: 21.207 ms/op
                 existUser·p1.00:   22.151 ms/op

Iteration   2: 3.324 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.477 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  9.532 ms/op
                 existUser·p0.9999: 26.247 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   3: 3.388 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   4.071 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   6.144 ms/op
                 existUser·p0.999:  19.307 ms/op
                 existUser·p0.9999: 24.496 ms/op
                 existUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288496
  mean =      3.323 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10897 
    [ 2.500,  5.000) = 271466 
    [ 5.000,  7.500) = 5022 
    [ 7.500, 10.000) = 794 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     10.379 ms/op
     p(99.9900) =     24.979 ms/op
     p(99.9990) =     26.776 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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
# Warmup Iteration   1: 9.497 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.879 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.425 ±(99.9%) 0.011 ms/op
Iteration   1: 3.503 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.669 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  10.273 ms/op
                 getUser·p0.9999: 27.750 ms/op
                 getUser·p1.00:   27.886 ms/op

Iteration   2: 3.311 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  13.752 ms/op
                 getUser·p0.9999: 30.605 ms/op
                 getUser·p1.00:   31.490 ms/op

Iteration   3: 3.338 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.093 ms/op
                 getUser·p0.99:   5.555 ms/op
                 getUser·p0.999:  17.502 ms/op
                 getUser·p0.9999: 25.383 ms/op
                 getUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283805
  mean =      3.382 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11859 
    [ 2.500,  5.000) = 264792 
    [ 5.000,  7.500) = 6322 
    [ 7.500, 10.000) = 527 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     10.780 ms/op
     p(99.9900) =     29.146 ms/op
     p(99.9990) =     31.315 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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
# Warmup Iteration   1: 10.289 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.671 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.013 ms/op
Iteration   1: 4.115 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.054 ms/op
                 listUser·p0.99:   8.031 ms/op
                 listUser·p0.999:  20.648 ms/op
                 listUser·p0.9999: 25.435 ms/op
                 listUser·p1.00:   26.444 ms/op

Iteration   2: 3.962 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  16.466 ms/op
                 listUser·p0.9999: 19.268 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   3: 3.860 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.062 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.275 ms/op
                 listUser·p0.999:  13.597 ms/op
                 listUser·p0.9999: 15.532 ms/op
                 listUser·p1.00:   15.565 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241347
  mean =      3.976 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 232176 
    [ 5.000,  7.500) = 6874 
    [ 7.500, 10.000) = 1310 
    [10.000, 12.500) = 396 
    [12.500, 15.000) = 231 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     16.237 ms/op
     p(99.9900) =     24.399 ms/op
     p(99.9990) =     26.168 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.443 ± 1.812  ops/ms
ClientPb.existUser                       thrpt       3   9.837 ± 1.737  ops/ms
ClientPb.getUser                         thrpt       3   9.463 ± 4.075  ops/ms
ClientPb.listUser                        thrpt       3   8.096 ± 0.839  ops/ms
ClientPb.createUser                       avgt       3   3.397 ± 1.754   ms/op
ClientPb.existUser                        avgt       3   3.225 ± 0.969   ms/op
ClientPb.getUser                          avgt       3   3.383 ± 0.812   ms/op
ClientPb.listUser                         avgt       3   3.967 ± 1.433   ms/op
ClientPb.createUser                     sample  290534   3.300 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.219           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.633           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.661           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.595           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.114           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.440           ms/op
ClientPb.existUser                      sample  288496   3.323 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.049           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.854           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.227           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.784           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.379           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.979           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.066           ms/op
ClientPb.getUser                        sample  283805   3.382 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.764           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.226           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.780           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.146           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.490           ms/op
ClientPb.listUser                       sample  241347   3.976 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.161           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.365           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.237           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.399           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.444           ms/op
