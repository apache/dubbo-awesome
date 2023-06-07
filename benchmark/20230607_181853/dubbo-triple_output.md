# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.170 ops/ms
# Warmup Iteration   2: 5.771 ops/ms
# Warmup Iteration   3: 8.866 ops/ms
Iteration   1: 9.374 ops/ms
Iteration   2: 9.276 ops/ms
Iteration   3: 9.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.393 ±(99.9%) 2.340 ops/ms [Average]
  (min, avg, max) = (9.276, 9.393, 9.530), stdev = 0.128
  CI (99.9%): [7.053, 11.733] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.083 ops/ms
# Warmup Iteration   2: 8.612 ops/ms
# Warmup Iteration   3: 9.503 ops/ms
Iteration   1: 9.689 ops/ms
Iteration   2: 9.520 ops/ms
Iteration   3: 9.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.557 ±(99.9%) 2.158 ops/ms [Average]
  (min, avg, max) = (9.461, 9.557, 9.689), stdev = 0.118
  CI (99.9%): [7.399, 11.715] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.081 ops/ms
# Warmup Iteration   2: 8.559 ops/ms
# Warmup Iteration   3: 8.948 ops/ms
Iteration   1: 9.285 ops/ms
Iteration   2: 9.511 ops/ms
Iteration   3: 9.403 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.400 ±(99.9%) 2.059 ops/ms [Average]
  (min, avg, max) = (9.285, 9.400, 9.511), stdev = 0.113
  CI (99.9%): [7.341, 11.459] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.642 ops/ms
# Warmup Iteration   2: 7.359 ops/ms
# Warmup Iteration   3: 7.744 ops/ms
Iteration   1: 7.822 ops/ms
Iteration   2: 8.174 ops/ms
Iteration   3: 7.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.980 ±(99.9%) 3.258 ops/ms [Average]
  (min, avg, max) = (7.822, 7.980, 8.174), stdev = 0.179
  CI (99.9%): [4.722, 11.239] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.554 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.619 ±(99.9%) 0.009 ms/op
Iteration   1: 3.409 ±(99.9%) 0.011 ms/op
Iteration   2: 3.324 ±(99.9%) 0.008 ms/op
Iteration   3: 3.498 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.411 ±(99.9%) 1.587 ms/op [Average]
  (min, avg, max) = (3.324, 3.411, 3.498), stdev = 0.087
  CI (99.9%): [1.823, 4.998] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.261 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.468 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.005 ms/op
Iteration   1: 3.270 ±(99.9%) 0.005 ms/op
Iteration   2: 3.243 ±(99.9%) 0.004 ms/op
Iteration   3: 3.351 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.288 ±(99.9%) 1.023 ms/op [Average]
  (min, avg, max) = (3.243, 3.288, 3.351), stdev = 0.056
  CI (99.9%): [2.265, 4.311] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.248 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.007 ms/op
Iteration   1: 3.473 ±(99.9%) 0.007 ms/op
Iteration   2: 3.454 ±(99.9%) 0.004 ms/op
Iteration   3: 3.354 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.427 ±(99.9%) 1.169 ms/op [Average]
  (min, avg, max) = (3.354, 3.427, 3.473), stdev = 0.064
  CI (99.9%): [2.258, 4.596] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.385 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.009 ms/op
Iteration   1: 3.976 ±(99.9%) 0.011 ms/op
Iteration   2: 4.001 ±(99.9%) 0.009 ms/op
Iteration   3: 3.983 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.987 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (3.976, 3.987, 4.001), stdev = 0.013
  CI (99.9%): [3.750, 4.224] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.047 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.010 ms/op
Iteration   1: 3.364 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.622 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  24.282 ms/op
                 createUser·p0.9999: 28.393 ms/op
                 createUser·p1.00:   28.967 ms/op

Iteration   2: 3.374 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.516 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  23.404 ms/op
                 createUser·p0.9999: 29.508 ms/op
                 createUser·p1.00:   30.179 ms/op

Iteration   3: 3.436 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.212 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   6.396 ms/op
                 createUser·p0.999:  19.300 ms/op
                 createUser·p0.9999: 25.559 ms/op
                 createUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282971
  mean =      3.391 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5227 
    [ 2.500,  5.000) = 270773 
    [ 5.000,  7.500) = 5801 
    [ 7.500, 10.000) = 630 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     28.400 ms/op
     p(99.9990) =     29.999 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.357 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.009 ms/op
Iteration   1: 3.192 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.366 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.598 ms/op
                 existUser·p0.999:  9.393 ms/op
                 existUser·p0.9999: 36.371 ms/op
                 existUser·p1.00:   36.831 ms/op

Iteration   2: 3.357 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.305 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   6.447 ms/op
                 existUser·p0.999:  23.167 ms/op
                 existUser·p0.9999: 26.935 ms/op
                 existUser·p1.00:   27.787 ms/op

Iteration   3: 3.361 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.139 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   6.265 ms/op
                 existUser·p0.999:  11.817 ms/op
                 existUser·p0.9999: 23.362 ms/op
                 existUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290523
  mean =      3.302 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6399 
    [ 2.500,  5.000) = 277934 
    [ 5.000,  7.500) = 5049 
    [ 7.500, 10.000) = 666 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     12.131 ms/op
     p(99.9900) =     34.931 ms/op
     p(99.9990) =     36.700 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.507 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.706 ±(99.9%) 0.013 ms/op
Iteration   1: 3.500 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.561 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  21.750 ms/op
                 getUser·p0.9999: 27.586 ms/op
                 getUser·p1.00:   28.443 ms/op

Iteration   2: 3.309 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  14.940 ms/op
                 getUser·p0.9999: 31.719 ms/op
                 getUser·p1.00:   32.145 ms/op

Iteration   3: 3.390 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.491 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.204 ms/op
                 getUser·p0.999:  20.808 ms/op
                 getUser·p0.9999: 28.288 ms/op
                 getUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282397
  mean =      3.398 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7732 
    [ 2.500,  5.000) = 268128 
    [ 5.000,  7.500) = 5409 
    [ 7.500, 10.000) = 657 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     21.018 ms/op
     p(99.9900) =     30.057 ms/op
     p(99.9990) =     31.879 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.412 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.566 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.123 ±(99.9%) 0.014 ms/op
Iteration   1: 4.064 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.778 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.445 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  17.411 ms/op
                 listUser·p0.9999: 22.577 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   2: 4.054 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  19.300 ms/op
                 listUser·p0.9999: 24.052 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   3: 4.033 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.878 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  14.828 ms/op
                 listUser·p0.9999: 17.973 ms/op
                 listUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236935
  mean =      4.051 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 225610 
    [ 5.000,  7.500) = 9062 
    [ 7.500, 10.000) = 1289 
    [10.000, 12.500) = 364 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 189 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     16.565 ms/op
     p(99.9900) =     23.658 ms/op
     p(99.9990) =     24.572 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.393 ± 2.340  ops/ms
ClientPb.existUser                       thrpt       3   9.557 ± 2.158  ops/ms
ClientPb.getUser                         thrpt       3   9.400 ± 2.059  ops/ms
ClientPb.listUser                        thrpt       3   7.980 ± 3.258  ops/ms
ClientPb.createUser                       avgt       3   3.411 ± 1.587   ms/op
ClientPb.existUser                        avgt       3   3.288 ± 1.023   ms/op
ClientPb.getUser                          avgt       3   3.427 ± 1.169   ms/op
ClientPb.listUser                         avgt       3   3.987 ± 0.237   ms/op
ClientPb.createUser                     sample  282971   3.391 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.212           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.141           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.980           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.333           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.400           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.179           ms/op
ClientPb.existUser                      sample  290523   3.302 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.139           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.030           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.947           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.131           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.931           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.831           ms/op
ClientPb.getUser                        sample  282397   3.398 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.953           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.103           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.018           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.057           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.145           ms/op
ClientPb.listUser                       sample  236935   4.051 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.462           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.381           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.565           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.658           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.904           ms/op
