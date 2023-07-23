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
# Warmup Iteration   1: 2.559 ops/ms
# Warmup Iteration   2: 6.740 ops/ms
# Warmup Iteration   3: 9.513 ops/ms
Iteration   1: 10.062 ops/ms
Iteration   2: 10.252 ops/ms
Iteration   3: 10.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.194 ±(99.9%) 2.090 ops/ms [Average]
  (min, avg, max) = (10.062, 10.194, 10.269), stdev = 0.115
  CI (99.9%): [8.104, 12.285] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.787 ops/ms
# Warmup Iteration   2: 9.327 ops/ms
# Warmup Iteration   3: 10.271 ops/ms
Iteration   1: 9.877 ops/ms
Iteration   2: 9.718 ops/ms
Iteration   3: 10.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.984 ±(99.9%) 6.072 ops/ms [Average]
  (min, avg, max) = (9.718, 9.984, 10.358), stdev = 0.333
  CI (99.9%): [3.912, 16.057] (assumes normal distribution)


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
# Warmup Iteration   1: 3.436 ops/ms
# Warmup Iteration   2: 9.126 ops/ms
# Warmup Iteration   3: 9.704 ops/ms
Iteration   1: 9.753 ops/ms
Iteration   2: 10.185 ops/ms
Iteration   3: 10.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.987 ±(99.9%) 3.987 ops/ms [Average]
  (min, avg, max) = (9.753, 9.987, 10.185), stdev = 0.219
  CI (99.9%): [6.000, 13.974] (assumes normal distribution)


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
# Warmup Iteration   1: 3.241 ops/ms
# Warmup Iteration   2: 7.693 ops/ms
# Warmup Iteration   3: 8.495 ops/ms
Iteration   1: 8.644 ops/ms
Iteration   2: 8.517 ops/ms
Iteration   3: 8.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.480 ±(99.9%) 3.387 ops/ms [Average]
  (min, avg, max) = (8.278, 8.480, 8.644), stdev = 0.186
  CI (99.9%): [5.093, 11.867] (assumes normal distribution)


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
# Warmup Iteration   1: 8.609 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.518 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.004 ms/op
Iteration   1: 3.282 ±(99.9%) 0.006 ms/op
Iteration   2: 3.294 ±(99.9%) 0.004 ms/op
Iteration   3: 3.232 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.269 ±(99.9%) 0.602 ms/op [Average]
  (min, avg, max) = (3.232, 3.269, 3.294), stdev = 0.033
  CI (99.9%): [2.667, 3.871] (assumes normal distribution)


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
# Warmup Iteration   1: 8.679 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.209 ±(99.9%) 0.003 ms/op
Iteration   1: 3.108 ±(99.9%) 0.004 ms/op
Iteration   2: 2.989 ±(99.9%) 0.003 ms/op
Iteration   3: 3.007 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.035 ±(99.9%) 1.164 ms/op [Average]
  (min, avg, max) = (2.989, 3.035, 3.108), stdev = 0.064
  CI (99.9%): [1.870, 4.199] (assumes normal distribution)


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
# Warmup Iteration   1: 8.717 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.630 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.403 ±(99.9%) 0.004 ms/op
Iteration   1: 3.229 ±(99.9%) 0.006 ms/op
Iteration   2: 3.145 ±(99.9%) 0.001 ms/op
Iteration   3: 3.439 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.271 ±(99.9%) 2.764 ms/op [Average]
  (min, avg, max) = (3.145, 3.271, 3.439), stdev = 0.152
  CI (99.9%): [0.507, 6.035] (assumes normal distribution)


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
# Warmup Iteration   1: 8.703 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.769 ±(99.9%) 0.006 ms/op
Iteration   1: 3.752 ±(99.9%) 0.006 ms/op
Iteration   2: 3.641 ±(99.9%) 0.010 ms/op
Iteration   3: 3.733 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.709 ±(99.9%) 1.086 ms/op [Average]
  (min, avg, max) = (3.641, 3.709, 3.752), stdev = 0.060
  CI (99.9%): [2.623, 4.794] (assumes normal distribution)


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
# Warmup Iteration   1: 7.805 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.008 ms/op
Iteration   1: 3.151 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  18.645 ms/op
                 createUser·p0.9999: 23.527 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   2: 3.212 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.524 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  10.279 ms/op
                 createUser·p0.9999: 22.544 ms/op
                 createUser·p1.00:   22.872 ms/op

Iteration   3: 3.297 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.583 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   5.504 ms/op
                 createUser·p0.999:  15.008 ms/op
                 createUser·p0.9999: 20.477 ms/op
                 createUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298138
  mean =      3.219 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18855 
    [ 2.500,  5.000) = 273905 
    [ 5.000,  7.500) = 4668 
    [ 7.500, 10.000) = 319 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     15.918 ms/op
     p(99.9900) =     22.714 ms/op
     p(99.9990) =     24.721 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 6.871 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.211 ±(99.9%) 0.009 ms/op
Iteration   1: 3.001 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.184 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.142 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  10.666 ms/op
                 existUser·p0.9999: 19.923 ms/op
                 existUser·p1.00:   21.168 ms/op

Iteration   2: 3.047 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.378 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  9.322 ms/op
                 existUser·p0.9999: 26.952 ms/op
                 existUser·p1.00:   28.344 ms/op

Iteration   3: 3.197 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.526 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  12.386 ms/op
                 existUser·p0.9999: 19.956 ms/op
                 existUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311652
  mean =      3.079 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17546 
    [ 2.500,  5.000) = 289837 
    [ 5.000,  7.500) = 3362 
    [ 7.500, 10.000) = 469 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     11.256 ms/op
     p(99.9900) =     25.253 ms/op
     p(99.9990) =     27.882 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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
# Warmup Iteration   1: 8.733 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.010 ms/op
Iteration   1: 3.172 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.518 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  18.186 ms/op
                 getUser·p0.9999: 19.857 ms/op
                 getUser·p1.00:   21.004 ms/op

Iteration   2: 3.200 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.033 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   5.407 ms/op
                 getUser·p0.999:  15.630 ms/op
                 getUser·p0.9999: 22.249 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   3: 3.255 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.665 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  13.746 ms/op
                 getUser·p0.9999: 20.486 ms/op
                 getUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299189
  mean =      3.209 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12736 
    [ 2.500,  5.000) = 280502 
    [ 5.000,  7.500) = 5089 
    [ 7.500, 10.000) = 399 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 159 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     15.565 ms/op
     p(99.9900) =     21.698 ms/op
     p(99.9990) =     22.644 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 8.508 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.784 ±(99.9%) 0.013 ms/op
Iteration   1: 3.733 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.688 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  15.286 ms/op
                 listUser·p0.9999: 19.806 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   2: 3.705 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  12.410 ms/op
                 listUser·p0.9999: 14.844 ms/op
                 listUser·p1.00:   14.893 ms/op

Iteration   3: 3.734 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.052 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  14.014 ms/op
                 listUser·p0.9999: 19.511 ms/op
                 listUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257600
  mean =      3.724 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 95 
    [ 2.500,  5.000) = 251223 
    [ 5.000,  7.500) = 4502 
    [ 7.500, 10.000) = 1095 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 274 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.688 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     13.474 ms/op
     p(99.9900) =     19.497 ms/op
     p(99.9990) =     20.530 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.194 ± 2.090  ops/ms
ClientPb.existUser                       thrpt       3   9.984 ± 6.072  ops/ms
ClientPb.getUser                         thrpt       3   9.987 ± 3.987  ops/ms
ClientPb.listUser                        thrpt       3   8.480 ± 3.387  ops/ms
ClientPb.createUser                       avgt       3   3.269 ± 0.602   ms/op
ClientPb.existUser                        avgt       3   3.035 ± 1.164   ms/op
ClientPb.getUser                          avgt       3   3.271 ± 2.764   ms/op
ClientPb.listUser                         avgt       3   3.709 ± 1.086   ms/op
ClientPb.createUser                     sample  298138   3.219 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.268           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.629           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.918           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.714           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.657           ms/op
ClientPb.existUser                      sample  311652   3.079 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.184           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.341           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.256           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.253           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.344           ms/op
ClientPb.getUser                        sample  299189   3.209 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.033           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.539           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.530           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.565           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.698           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.970           ms/op
ClientPb.listUser                       sample  257600   3.724 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.688           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.808           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.474           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.497           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.775           ms/op
