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
# Warmup Iteration   1: 2.021 ops/ms
# Warmup Iteration   2: 5.113 ops/ms
# Warmup Iteration   3: 8.209 ops/ms
Iteration   1: 8.502 ops/ms
Iteration   2: 8.441 ops/ms
Iteration   3: 8.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.427 ±(99.9%) 1.495 ops/ms [Average]
  (min, avg, max) = (8.340, 8.427, 8.502), stdev = 0.082
  CI (99.9%): [6.933, 9.922] (assumes normal distribution)


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
# Warmup Iteration   1: 2.508 ops/ms
# Warmup Iteration   2: 7.819 ops/ms
# Warmup Iteration   3: 8.677 ops/ms
Iteration   1: 8.766 ops/ms
Iteration   2: 9.199 ops/ms
Iteration   3: 9.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.108 ±(99.9%) 5.585 ops/ms [Average]
  (min, avg, max) = (8.766, 9.108, 9.358), stdev = 0.306
  CI (99.9%): [3.522, 14.693] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.151 ops/ms
# Warmup Iteration   2: 6.739 ops/ms
# Warmup Iteration   3: 8.666 ops/ms
Iteration   1: 7.346 ops/ms
Iteration   2: 8.799 ops/ms
Iteration   3: 8.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.325 ±(99.9%) 15.467 ops/ms [Average]
  (min, avg, max) = (7.346, 8.325, 8.830), stdev = 0.848
  CI (99.9%): [≈ 0, 23.792] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.303 ops/ms
# Warmup Iteration   2: 6.367 ops/ms
# Warmup Iteration   3: 7.183 ops/ms
Iteration   1: 7.317 ops/ms
Iteration   2: 7.622 ops/ms
Iteration   3: 7.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.424 ±(99.9%) 3.121 ops/ms [Average]
  (min, avg, max) = (7.317, 7.424, 7.622), stdev = 0.171
  CI (99.9%): [4.304, 10.545] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 11.445 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.386 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.823 ±(99.9%) 0.005 ms/op
Iteration   1: 3.779 ±(99.9%) 0.005 ms/op
Iteration   2: 3.582 ±(99.9%) 0.006 ms/op
Iteration   3: 3.482 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.615 ±(99.9%) 2.756 ms/op [Average]
  (min, avg, max) = (3.482, 3.615, 3.779), stdev = 0.151
  CI (99.9%): [0.858, 6.371] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.749 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.961 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.428 ±(99.9%) 0.006 ms/op
Iteration   1: 3.482 ±(99.9%) 0.007 ms/op
Iteration   2: 3.469 ±(99.9%) 0.003 ms/op
Iteration   3: 3.703 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.551 ±(99.9%) 2.403 ms/op [Average]
  (min, avg, max) = (3.469, 3.551, 3.703), stdev = 0.132
  CI (99.9%): [1.148, 5.954] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 10.165 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.007 ms/op
Iteration   1: 3.495 ±(99.9%) 0.009 ms/op
Iteration   2: 3.502 ±(99.9%) 0.007 ms/op
Iteration   3: 3.681 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.559 ±(99.9%) 1.921 ms/op [Average]
  (min, avg, max) = (3.495, 3.559, 3.681), stdev = 0.105
  CI (99.9%): [1.639, 5.480] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.047 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.134 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.184 ±(99.9%) 0.006 ms/op
Iteration   1: 4.235 ±(99.9%) 0.011 ms/op
Iteration   2: 4.172 ±(99.9%) 0.007 ms/op
Iteration   3: 4.432 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.280 ±(99.9%) 2.466 ms/op [Average]
  (min, avg, max) = (4.172, 4.280, 4.432), stdev = 0.135
  CI (99.9%): [1.814, 6.745] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.237 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.420 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.017 ms/op
Iteration   1: 3.618 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.516 ms/op
                 createUser·p0.50:   3.506 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   7.291 ms/op
                 createUser·p0.999:  20.565 ms/op
                 createUser·p0.9999: 25.264 ms/op
                 createUser·p1.00:   26.903 ms/op

Iteration   2: 3.592 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.233 ms/op
                 createUser·p0.50:   3.482 ms/op
                 createUser·p0.90:   4.186 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   6.668 ms/op
                 createUser·p0.999:  23.952 ms/op
                 createUser·p0.9999: 27.859 ms/op
                 createUser·p1.00:   28.770 ms/op

Iteration   3: 3.515 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  21.955 ms/op
                 createUser·p0.9999: 29.652 ms/op
                 createUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 268399
  mean =      3.575 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4185 
    [ 2.500,  5.000) = 255564 
    [ 5.000,  7.500) = 6612 
    [ 7.500, 10.000) = 1242 
    [10.000, 12.500) = 406 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     21.240 ms/op
     p(99.9900) =     28.912 ms/op
     p(99.9990) =     30.704 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.078 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.011 ms/op
Iteration   1: 3.561 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.528 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.948 ms/op
                 existUser·p0.99:   6.980 ms/op
                 existUser·p0.999:  13.591 ms/op
                 existUser·p0.9999: 25.136 ms/op
                 existUser·p1.00:   27.034 ms/op

Iteration   2: 3.746 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.683 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.612 ms/op
                 existUser·p0.99:   8.012 ms/op
                 existUser·p0.999:  24.773 ms/op
                 existUser·p0.9999: 30.719 ms/op
                 existUser·p1.00:   31.261 ms/op

Iteration   3: 3.727 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.348 ms/op
                 existUser·p0.50:   3.523 ms/op
                 existUser·p0.90:   4.773 ms/op
                 existUser·p0.95:   5.300 ms/op
                 existUser·p0.99:   7.522 ms/op
                 existUser·p0.999:  15.796 ms/op
                 existUser·p0.9999: 35.744 ms/op
                 existUser·p1.00:   38.142 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 261023
  mean =      3.676 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5105 
    [ 2.500,  5.000) = 238273 
    [ 5.000,  7.500) = 14772 
    [ 7.500, 10.000) = 2130 
    [10.000, 12.500) = 341 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 39 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     34.734 ms/op
     p(99.9990) =     36.136 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.840 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.015 ms/op
Iteration   1: 3.849 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.808 ms/op
                 getUser·p0.50:   3.748 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   7.406 ms/op
                 getUser·p0.999:  14.169 ms/op
                 getUser·p0.9999: 28.564 ms/op
                 getUser·p1.00:   30.015 ms/op

Iteration   2: 3.759 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   7.119 ms/op
                 getUser·p0.999:  25.919 ms/op
                 getUser·p0.9999: 37.158 ms/op
                 getUser·p1.00:   38.011 ms/op

Iteration   3: 3.844 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.851 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  13.369 ms/op
                 getUser·p0.9999: 30.824 ms/op
                 getUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 251264
  mean =      3.817 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1407 
    [ 2.500,  5.000) = 238943 
    [ 5.000,  7.500) = 8838 
    [ 7.500, 10.000) = 1200 
    [10.000, 12.500) = 527 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     13.794 ms/op
     p(99.9900) =     35.512 ms/op
     p(99.9990) =     37.945 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.051 ±(99.9%) 0.222 ms/op
# Warmup Iteration   2: 5.181 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.707 ±(99.9%) 0.016 ms/op
Iteration   1: 4.429 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   4.260 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   8.372 ms/op
                 listUser·p0.999:  20.709 ms/op
                 listUser·p0.9999: 36.700 ms/op
                 listUser·p1.00:   36.831 ms/op

Iteration   2: 4.573 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.083 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.739 ms/op
                 listUser·p0.99:   9.339 ms/op
                 listUser·p0.999:  17.026 ms/op
                 listUser·p0.9999: 27.001 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   3: 4.520 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.040 ms/op
                 listUser·p0.50:   4.317 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   6.169 ms/op
                 listUser·p0.99:   9.767 ms/op
                 listUser·p0.999:  16.417 ms/op
                 listUser·p0.9999: 18.863 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 212756
  mean =      4.506 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 189857 
    [ 5.000,  7.500) = 16913 
    [ 7.500, 10.000) = 4449 
    [10.000, 12.500) = 863 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.835 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      9.290 ms/op
     p(99.9000) =     18.227 ms/op
     p(99.9900) =     35.656 ms/op
     p(99.9990) =     36.700 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   8.427 ±  1.495  ops/ms
ClientPb.existUser                       thrpt       3   9.108 ±  5.585  ops/ms
ClientPb.getUser                         thrpt       3   8.325 ± 15.467  ops/ms
ClientPb.listUser                        thrpt       3   7.424 ±  3.121  ops/ms
ClientPb.createUser                       avgt       3   3.615 ±  2.756   ms/op
ClientPb.existUser                        avgt       3   3.551 ±  2.403   ms/op
ClientPb.getUser                          avgt       3   3.559 ±  1.921   ms/op
ClientPb.listUser                         avgt       3   4.280 ±  2.466   ms/op
ClientPb.createUser                     sample  268399   3.575 ±  0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.980            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.469            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.141            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.555            ms/op
ClientPb.createUser:createUser·p0.99    sample           6.849            ms/op
ClientPb.createUser:createUser·p0.999   sample          21.240            ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.912            ms/op
ClientPb.createUser:createUser·p1.00    sample          31.588            ms/op
ClientPb.existUser                      sample  261023   3.676 ±  0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.348            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.469            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.678            ms/op
ClientPb.existUser:existUser·p0.95      sample           5.284            ms/op
ClientPb.existUser:existUser·p0.99      sample           7.660            ms/op
ClientPb.existUser:existUser·p0.999     sample          17.269            ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.734            ms/op
ClientPb.existUser:existUser·p1.00      sample          38.142            ms/op
ClientPb.getUser                        sample  251264   3.817 ±  0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.296            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.695            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.358            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.841            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.143            ms/op
ClientPb.getUser:getUser·p0.999         sample          13.794            ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.512            ms/op
ClientPb.getUser:getUser·p1.00          sample          38.011            ms/op
ClientPb.listUser                       sample  212756   4.506 ±  0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.835            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.325            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.038            ms/op
ClientPb.listUser:listUser·p0.95        sample           5.751            ms/op
ClientPb.listUser:listUser·p0.99        sample           9.290            ms/op
ClientPb.listUser:listUser·p0.999       sample          18.227            ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.656            ms/op
ClientPb.listUser:listUser·p1.00        sample          36.831            ms/op
