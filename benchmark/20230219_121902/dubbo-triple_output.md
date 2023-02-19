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
# Warmup Iteration   1: 2.182 ops/ms
# Warmup Iteration   2: 5.769 ops/ms
# Warmup Iteration   3: 8.758 ops/ms
Iteration   1: 9.142 ops/ms
Iteration   2: 9.225 ops/ms
Iteration   3: 9.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.279 ±(99.9%) 3.116 ops/ms [Average]
  (min, avg, max) = (9.142, 9.279, 9.470), stdev = 0.171
  CI (99.9%): [6.163, 12.395] (assumes normal distribution)


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
# Warmup Iteration   1: 3.180 ops/ms
# Warmup Iteration   2: 9.157 ops/ms
# Warmup Iteration   3: 9.624 ops/ms
Iteration   1: 9.810 ops/ms
Iteration   2: 10.025 ops/ms
Iteration   3: 10.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.966 ±(99.9%) 2.492 ops/ms [Average]
  (min, avg, max) = (9.810, 9.966, 10.064), stdev = 0.137
  CI (99.9%): [7.475, 12.458] (assumes normal distribution)


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
# Warmup Iteration   1: 3.269 ops/ms
# Warmup Iteration   2: 8.582 ops/ms
# Warmup Iteration   3: 9.507 ops/ms
Iteration   1: 9.654 ops/ms
Iteration   2: 9.552 ops/ms
Iteration   3: 9.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.654 ±(99.9%) 1.854 ops/ms [Average]
  (min, avg, max) = (9.552, 9.654, 9.755), stdev = 0.102
  CI (99.9%): [7.800, 11.508] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.823 ops/ms
# Warmup Iteration   2: 7.664 ops/ms
# Warmup Iteration   3: 7.793 ops/ms
Iteration   1: 7.785 ops/ms
Iteration   2: 8.197 ops/ms
Iteration   3: 8.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.068 ±(99.9%) 4.470 ops/ms [Average]
  (min, avg, max) = (7.785, 8.068, 8.221), stdev = 0.245
  CI (99.9%): [3.597, 12.538] (assumes normal distribution)


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
# Warmup Iteration   1: 9.709 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.938 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.610 ±(99.9%) 0.004 ms/op
Iteration   1: 3.373 ±(99.9%) 0.008 ms/op
Iteration   2: 3.351 ±(99.9%) 0.011 ms/op
Iteration   3: 3.215 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.313 ±(99.9%) 1.561 ms/op [Average]
  (min, avg, max) = (3.215, 3.313, 3.373), stdev = 0.086
  CI (99.9%): [1.753, 4.874] (assumes normal distribution)


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
# Warmup Iteration   1: 8.228 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.006 ms/op
Iteration   1: 3.309 ±(99.9%) 0.013 ms/op
Iteration   2: 3.139 ±(99.9%) 0.009 ms/op
Iteration   3: 3.204 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.217 ±(99.9%) 1.565 ms/op [Average]
  (min, avg, max) = (3.139, 3.217, 3.309), stdev = 0.086
  CI (99.9%): [1.652, 4.783] (assumes normal distribution)


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
# Warmup Iteration   1: 8.028 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.005 ms/op
Iteration   1: 3.452 ±(99.9%) 0.006 ms/op
Iteration   2: 3.226 ±(99.9%) 0.010 ms/op
Iteration   3: 3.307 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.328 ±(99.9%) 2.088 ms/op [Average]
  (min, avg, max) = (3.226, 3.328, 3.452), stdev = 0.114
  CI (99.9%): [1.240, 5.416] (assumes normal distribution)


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
# Warmup Iteration   1: 10.278 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.340 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.010 ms/op
Iteration   1: 3.940 ±(99.9%) 0.010 ms/op
Iteration   2: 3.800 ±(99.9%) 0.011 ms/op
Iteration   3: 3.980 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.907 ±(99.9%) 1.721 ms/op [Average]
  (min, avg, max) = (3.800, 3.907, 3.980), stdev = 0.094
  CI (99.9%): [2.185, 5.628] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.820 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.913 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.279 ±(99.9%) 0.008 ms/op
Iteration   1: 3.342 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.821 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  18.051 ms/op
                 createUser·p0.9999: 21.365 ms/op
                 createUser·p1.00:   21.660 ms/op

Iteration   2: 3.520 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  20.774 ms/op
                 createUser·p0.9999: 25.226 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   3: 3.367 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.300 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  20.022 ms/op
                 createUser·p0.9999: 22.675 ms/op
                 createUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281453
  mean =      3.407 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10513 
    [ 2.500,  5.000) = 265231 
    [ 5.000,  7.500) = 4780 
    [ 7.500, 10.000) = 346 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 162 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     18.991 ms/op
     p(99.9900) =     23.883 ms/op
     p(99.9990) =     25.395 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 8.236 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.581 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.007 ms/op
Iteration   1: 3.247 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  15.159 ms/op
                 existUser·p0.9999: 23.729 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   2: 3.216 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.409 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.816 ms/op
                 existUser·p0.999:  12.829 ms/op
                 existUser·p0.9999: 22.192 ms/op
                 existUser·p1.00:   24.576 ms/op

Iteration   3: 3.419 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.954 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  17.386 ms/op
                 existUser·p0.9999: 24.726 ms/op
                 existUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291307
  mean =      3.292 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13430 
    [ 2.500,  5.000) = 273598 
    [ 5.000,  7.500) = 3105 
    [ 7.500, 10.000) = 729 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 147 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     16.969 ms/op
     p(99.9900) =     23.720 ms/op
     p(99.9990) =     25.404 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 10.252 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.677 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.485 ±(99.9%) 0.011 ms/op
Iteration   1: 3.570 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  14.134 ms/op
                 getUser·p0.9999: 21.728 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   2: 3.486 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.794 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  22.462 ms/op
                 getUser·p0.9999: 25.806 ms/op
                 getUser·p1.00:   26.804 ms/op

Iteration   3: 3.362 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.550 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.190 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  18.416 ms/op
                 getUser·p0.9999: 27.000 ms/op
                 getUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276453
  mean =      3.471 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14918 
    [ 2.500,  5.000) = 251227 
    [ 5.000,  7.500) = 9228 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     15.991 ms/op
     p(99.9900) =     26.139 ms/op
     p(99.9990) =     27.442 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 10.612 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.798 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.119 ±(99.9%) 0.013 ms/op
Iteration   1: 4.016 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.729 ms/op
                 listUser·p0.999:  20.120 ms/op
                 listUser·p0.9999: 23.594 ms/op
                 listUser·p1.00:   25.100 ms/op

Iteration   2: 3.977 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.964 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  14.696 ms/op
                 listUser·p0.9999: 22.510 ms/op
                 listUser·p1.00:   23.101 ms/op

Iteration   3: 3.988 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.964 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  15.712 ms/op
                 listUser·p0.9999: 19.399 ms/op
                 listUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240183
  mean =      3.993 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 229121 
    [ 5.000,  7.500) = 8465 
    [ 7.500, 10.000) = 1668 
    [10.000, 12.500) = 343 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     15.857 ms/op
     p(99.9900) =     22.773 ms/op
     p(99.9990) =     24.897 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.279 ± 3.116  ops/ms
ClientPb.existUser                       thrpt       3   9.966 ± 2.492  ops/ms
ClientPb.getUser                         thrpt       3   9.654 ± 1.854  ops/ms
ClientPb.listUser                        thrpt       3   8.068 ± 4.470  ops/ms
ClientPb.createUser                       avgt       3   3.313 ± 1.561   ms/op
ClientPb.existUser                        avgt       3   3.217 ± 1.565   ms/op
ClientPb.getUser                          avgt       3   3.328 ± 2.088   ms/op
ClientPb.listUser                         avgt       3   3.907 ± 1.721   ms/op
ClientPb.createUser                     sample  281453   3.407 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.274           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.269           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.636           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.991           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.883           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.723           ms/op
ClientPb.existUser                      sample  291307   3.292 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.954           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.480           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.969           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.720           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.657           ms/op
ClientPb.getUser                        sample  276453   3.471 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.051           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.063           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.555           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.144           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.991           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.139           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.689           ms/op
ClientPb.listUser                       sample  240183   3.993 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.268           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.777           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.602           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.857           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.773           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.100           ms/op
