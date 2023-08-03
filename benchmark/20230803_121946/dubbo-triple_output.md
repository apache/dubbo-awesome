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
# Warmup Iteration   1: 2.005 ops/ms
# Warmup Iteration   2: 4.686 ops/ms
# Warmup Iteration   3: 8.891 ops/ms
Iteration   1: 8.743 ops/ms
Iteration   2: 9.279 ops/ms
Iteration   3: 9.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.051 ±(99.9%) 5.049 ops/ms [Average]
  (min, avg, max) = (8.743, 9.051, 9.279), stdev = 0.277
  CI (99.9%): [4.002, 14.100] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.720 ops/ms
# Warmup Iteration   2: 8.069 ops/ms
# Warmup Iteration   3: 9.403 ops/ms
Iteration   1: 9.671 ops/ms
Iteration   2: 9.557 ops/ms
Iteration   3: 9.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.592 ±(99.9%) 1.253 ops/ms [Average]
  (min, avg, max) = (9.548, 9.592, 9.671), stdev = 0.069
  CI (99.9%): [8.339, 10.845] (assumes normal distribution)


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
# Warmup Iteration   1: 3.053 ops/ms
# Warmup Iteration   2: 8.545 ops/ms
# Warmup Iteration   3: 8.879 ops/ms
Iteration   1: 9.204 ops/ms
Iteration   2: 9.242 ops/ms
Iteration   3: 8.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.134 ±(99.9%) 2.846 ops/ms [Average]
  (min, avg, max) = (8.955, 9.134, 9.242), stdev = 0.156
  CI (99.9%): [6.288, 11.980] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.497 ops/ms
# Warmup Iteration   2: 6.793 ops/ms
# Warmup Iteration   3: 7.339 ops/ms
Iteration   1: 7.787 ops/ms
Iteration   2: 7.848 ops/ms
Iteration   3: 7.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.805 ±(99.9%) 0.680 ops/ms [Average]
  (min, avg, max) = (7.780, 7.805, 7.848), stdev = 0.037
  CI (99.9%): [7.125, 8.485] (assumes normal distribution)


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
# Warmup Iteration   1: 9.501 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.745 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.686 ±(99.9%) 0.005 ms/op
Iteration   1: 3.478 ±(99.9%) 0.004 ms/op
Iteration   2: 3.426 ±(99.9%) 0.006 ms/op
Iteration   3: 3.415 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.440 ±(99.9%) 0.616 ms/op [Average]
  (min, avg, max) = (3.415, 3.440, 3.478), stdev = 0.034
  CI (99.9%): [2.824, 4.056] (assumes normal distribution)


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
# Warmup Iteration   1: 8.534 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.004 ms/op
Iteration   1: 3.328 ±(99.9%) 0.002 ms/op
Iteration   2: 3.364 ±(99.9%) 0.004 ms/op
Iteration   3: 3.475 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.389 ±(99.9%) 1.403 ms/op [Average]
  (min, avg, max) = (3.328, 3.389, 3.475), stdev = 0.077
  CI (99.9%): [1.987, 4.792] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.372 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.883 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.002 ms/op
Iteration   1: 3.508 ±(99.9%) 0.004 ms/op
Iteration   2: 3.551 ±(99.9%) 0.004 ms/op
Iteration   3: 3.418 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.492 ±(99.9%) 1.234 ms/op [Average]
  (min, avg, max) = (3.418, 3.492, 3.551), stdev = 0.068
  CI (99.9%): [2.258, 4.727] (assumes normal distribution)


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
# Warmup Iteration   1: 10.468 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.413 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.006 ms/op
Iteration   1: 4.223 ±(99.9%) 0.006 ms/op
Iteration   2: 4.150 ±(99.9%) 0.009 ms/op
Iteration   3: 4.016 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.130 ±(99.9%) 1.922 ms/op [Average]
  (min, avg, max) = (4.016, 4.130, 4.223), stdev = 0.105
  CI (99.9%): [2.207, 6.052] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.120 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.780 ±(99.9%) 0.013 ms/op
Iteration   1: 3.787 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   6.472 ms/op
                 createUser·p0.99:   8.017 ms/op
                 createUser·p0.999:  21.557 ms/op
                 createUser·p0.9999: 23.724 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   2: 3.519 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.745 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.275 ms/op
                 createUser·p0.999:  24.327 ms/op
                 createUser·p0.9999: 30.933 ms/op
                 createUser·p1.00:   32.440 ms/op

Iteration   3: 3.696 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.313 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   7.438 ms/op
                 createUser·p0.999:  19.808 ms/op
                 createUser·p0.9999: 28.401 ms/op
                 createUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 261993
  mean =      3.664 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2431 
    [ 2.500,  5.000) = 244280 
    [ 5.000,  7.500) = 12514 
    [ 7.500, 10.000) = 2078 
    [10.000, 12.500) = 313 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     20.808 ms/op
     p(99.9900) =     29.950 ms/op
     p(99.9990) =     32.033 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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
# Warmup Iteration   1: 10.113 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.009 ms/op
Iteration   1: 3.518 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  10.240 ms/op
                 existUser·p0.9999: 22.938 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   2: 3.375 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.134 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  21.669 ms/op
                 existUser·p0.9999: 25.281 ms/op
                 existUser·p1.00:   26.411 ms/op

Iteration   3: 3.335 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   6.324 ms/op
                 existUser·p0.999:  23.998 ms/op
                 existUser·p0.9999: 30.353 ms/op
                 existUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281635
  mean =      3.408 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10656 
    [ 2.500,  5.000) = 263270 
    [ 5.000,  7.500) = 6357 
    [ 7.500, 10.000) = 839 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     15.151 ms/op
     p(99.9900) =     28.705 ms/op
     p(99.9990) =     31.752 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 8.767 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.881 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.013 ms/op
Iteration   1: 3.643 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.614 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   7.458 ms/op
                 getUser·p0.999:  20.583 ms/op
                 getUser·p0.9999: 23.181 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   2: 3.412 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.669 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   5.996 ms/op
                 getUser·p0.999:  21.936 ms/op
                 getUser·p0.9999: 28.710 ms/op
                 getUser·p1.00:   29.295 ms/op

Iteration   3: 3.595 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.549 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   4.190 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   6.816 ms/op
                 getUser·p0.999:  9.830 ms/op
                 getUser·p0.9999: 26.681 ms/op
                 getUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270414
  mean =      3.547 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10101 
    [ 2.500,  5.000) = 250115 
    [ 5.000,  7.500) = 8377 
    [ 7.500, 10.000) = 1402 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 76 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     14.516 ms/op
     p(99.9900) =     27.293 ms/op
     p(99.9990) =     29.075 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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
# Warmup Iteration   1: 11.229 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.539 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.184 ±(99.9%) 0.014 ms/op
Iteration   1: 4.084 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.749 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   8.070 ms/op
                 listUser·p0.999:  22.879 ms/op
                 listUser·p0.9999: 27.224 ms/op
                 listUser·p1.00:   27.656 ms/op

Iteration   2: 4.018 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.971 ms/op
                 listUser·p0.999:  15.276 ms/op
                 listUser·p0.9999: 21.823 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   3: 4.088 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   7.897 ms/op
                 listUser·p0.999:  15.578 ms/op
                 listUser·p0.9999: 21.444 ms/op
                 listUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236199
  mean =      4.063 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 225956 
    [ 5.000,  7.500) = 7338 
    [ 7.500, 10.000) = 1903 
    [10.000, 12.500) = 441 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 193 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.749 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.979 ms/op
     p(99.9000) =     16.495 ms/op
     p(99.9900) =     25.440 ms/op
     p(99.9990) =     27.623 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.051 ± 5.049  ops/ms
ClientPb.existUser                       thrpt       3   9.592 ± 1.253  ops/ms
ClientPb.getUser                         thrpt       3   9.134 ± 2.846  ops/ms
ClientPb.listUser                        thrpt       3   7.805 ± 0.680  ops/ms
ClientPb.createUser                       avgt       3   3.440 ± 0.616   ms/op
ClientPb.existUser                        avgt       3   3.389 ± 1.403   ms/op
ClientPb.getUser                          avgt       3   3.492 ± 1.234   ms/op
ClientPb.listUser                         avgt       3   4.130 ± 1.922   ms/op
ClientPb.createUser                     sample  261993   3.664 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.200           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.449           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.218           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.545           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.808           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.950           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.440           ms/op
ClientPb.existUser                      sample  281635   3.408 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.540           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.234           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.151           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.705           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.752           ms/op
ClientPb.getUser                        sample  270414   3.547 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.549           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.396           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.579           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.127           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.516           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.293           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.295           ms/op
ClientPb.listUser                       sample  236199   4.063 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.749           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.979           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.495           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.440           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.656           ms/op
