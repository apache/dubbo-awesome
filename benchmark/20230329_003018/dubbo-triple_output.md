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
# Warmup Iteration   1: 2.227 ops/ms
# Warmup Iteration   2: 5.580 ops/ms
# Warmup Iteration   3: 8.706 ops/ms
Iteration   1: 9.632 ops/ms
Iteration   2: 9.291 ops/ms
Iteration   3: 9.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.468 ±(99.9%) 3.119 ops/ms [Average]
  (min, avg, max) = (9.291, 9.468, 9.632), stdev = 0.171
  CI (99.9%): [6.349, 12.587] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.967 ops/ms
# Warmup Iteration   2: 8.827 ops/ms
# Warmup Iteration   3: 9.151 ops/ms
Iteration   1: 10.022 ops/ms
Iteration   2: 9.968 ops/ms
Iteration   3: 9.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.972 ±(99.9%) 0.890 ops/ms [Average]
  (min, avg, max) = (9.925, 9.972, 10.022), stdev = 0.049
  CI (99.9%): [9.082, 10.861] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.806 ops/ms
# Warmup Iteration   2: 8.621 ops/ms
# Warmup Iteration   3: 9.339 ops/ms
Iteration   1: 9.565 ops/ms
Iteration   2: 9.740 ops/ms
Iteration   3: 9.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.629 ±(99.9%) 1.771 ops/ms [Average]
  (min, avg, max) = (9.565, 9.629, 9.740), stdev = 0.097
  CI (99.9%): [7.858, 11.400] (assumes normal distribution)


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
# Warmup Iteration   1: 2.896 ops/ms
# Warmup Iteration   2: 7.507 ops/ms
# Warmup Iteration   3: 7.833 ops/ms
Iteration   1: 8.244 ops/ms
Iteration   2: 8.119 ops/ms
Iteration   3: 8.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.185 ±(99.9%) 1.143 ops/ms [Average]
  (min, avg, max) = (8.119, 8.185, 8.244), stdev = 0.063
  CI (99.9%): [7.041, 9.328] (assumes normal distribution)


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
# Warmup Iteration   1: 9.985 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.675 ±(99.9%) 0.005 ms/op
Iteration   1: 3.411 ±(99.9%) 0.004 ms/op
Iteration   2: 3.438 ±(99.9%) 0.006 ms/op
Iteration   3: 3.321 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.390 ±(99.9%) 1.112 ms/op [Average]
  (min, avg, max) = (3.321, 3.390, 3.438), stdev = 0.061
  CI (99.9%): [2.278, 4.502] (assumes normal distribution)


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
# Warmup Iteration   1: 7.571 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.007 ms/op
Iteration   1: 3.121 ±(99.9%) 0.009 ms/op
Iteration   2: 3.198 ±(99.9%) 0.007 ms/op
Iteration   3: 3.152 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.157 ±(99.9%) 0.706 ms/op [Average]
  (min, avg, max) = (3.121, 3.157, 3.198), stdev = 0.039
  CI (99.9%): [2.451, 3.863] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.127 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.605 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.005 ms/op
Iteration   1: 3.312 ±(99.9%) 0.008 ms/op
Iteration   2: 3.278 ±(99.9%) 0.007 ms/op
Iteration   3: 3.365 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.318 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (3.278, 3.318, 3.365), stdev = 0.044
  CI (99.9%): [2.518, 4.119] (assumes normal distribution)


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
# Warmup Iteration   1: 8.753 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.167 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.011 ms/op
Iteration   1: 3.818 ±(99.9%) 0.013 ms/op
Iteration   2: 3.851 ±(99.9%) 0.009 ms/op
Iteration   3: 3.798 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.823 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (3.798, 3.823, 3.851), stdev = 0.027
  CI (99.9%): [3.333, 4.312] (assumes normal distribution)


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
# Warmup Iteration   1: 10.051 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.018 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.378 ±(99.9%) 0.011 ms/op
Iteration   1: 3.602 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   5.743 ms/op
                 createUser·p0.99:   7.340 ms/op
                 createUser·p0.999:  22.348 ms/op
                 createUser·p0.9999: 36.380 ms/op
                 createUser·p1.00:   36.962 ms/op

Iteration   2: 3.358 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  20.760 ms/op
                 createUser·p0.9999: 33.876 ms/op
                 createUser·p1.00:   34.931 ms/op

Iteration   3: 3.341 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.477 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   5.429 ms/op
                 createUser·p0.999:  21.802 ms/op
                 createUser·p0.9999: 27.081 ms/op
                 createUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279690
  mean =      3.430 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9514 
    [ 2.500,  5.000) = 260060 
    [ 5.000,  7.500) = 8710 
    [ 7.500, 10.000) = 973 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     21.430 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     36.910 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


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
# Warmup Iteration   1: 8.023 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.007 ms/op
Iteration   1: 3.406 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   4.014 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  17.605 ms/op
                 existUser·p0.9999: 20.185 ms/op
                 existUser·p1.00:   20.775 ms/op

Iteration   2: 3.338 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.587 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  8.267 ms/op
                 existUser·p0.9999: 23.919 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   3: 3.537 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   4.170 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  9.208 ms/op
                 existUser·p0.9999: 26.373 ms/op
                 existUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280060
  mean =      3.425 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12345 
    [ 2.500,  5.000) = 260848 
    [ 5.000,  7.500) = 6134 
    [ 7.500, 10.000) = 502 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     24.084 ms/op
     p(99.9990) =     26.817 ms/op
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
# Warmup Iteration   1: 8.763 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.385 ±(99.9%) 0.010 ms/op
Iteration   1: 3.369 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.378 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  19.988 ms/op
                 getUser·p0.9999: 22.675 ms/op
                 getUser·p1.00:   23.527 ms/op

Iteration   2: 3.449 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.085 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  21.745 ms/op
                 getUser·p0.9999: 26.671 ms/op
                 getUser·p1.00:   30.212 ms/op

Iteration   3: 3.323 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.874 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  19.858 ms/op
                 getUser·p0.9999: 27.144 ms/op
                 getUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283891
  mean =      3.379 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7184 
    [ 2.500,  5.000) = 269883 
    [ 5.000,  7.500) = 6035 
    [ 7.500, 10.000) = 437 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     20.272 ms/op
     p(99.9900) =     26.420 ms/op
     p(99.9990) =     27.535 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


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
# Warmup Iteration   1: 11.027 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.411 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.013 ms/op
Iteration   1: 3.926 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.417 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  20.002 ms/op
                 listUser·p0.9999: 24.900 ms/op
                 listUser·p1.00:   26.837 ms/op

Iteration   2: 3.944 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.242 ms/op
                 listUser·p0.999:  14.615 ms/op
                 listUser·p0.9999: 16.546 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   3: 4.011 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  14.680 ms/op
                 listUser·p0.9999: 16.450 ms/op
                 listUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242380
  mean =      3.960 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 232779 
    [ 5.000,  7.500) = 7750 
    [ 7.500, 10.000) = 1002 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 258 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.417 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     14.909 ms/op
     p(99.9900) =     23.888 ms/op
     p(99.9990) =     26.656 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.468 ± 3.119  ops/ms
ClientPb.existUser                       thrpt       3   9.972 ± 0.890  ops/ms
ClientPb.getUser                         thrpt       3   9.629 ± 1.771  ops/ms
ClientPb.listUser                        thrpt       3   8.185 ± 1.143  ops/ms
ClientPb.createUser                       avgt       3   3.390 ± 1.112   ms/op
ClientPb.existUser                        avgt       3   3.157 ± 0.706   ms/op
ClientPb.getUser                          avgt       3   3.318 ± 0.801   ms/op
ClientPb.listUser                         avgt       3   3.823 ± 0.489   ms/op
ClientPb.createUser                     sample  279690   3.430 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.305           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.297           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.963           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.430           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.144           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.962           ms/op
ClientPb.existUser                      sample  280060   3.425 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.188           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.088           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.497           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.620           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.241           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.084           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.066           ms/op
ClientPb.getUser                        sample  283891   3.379 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.360           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.160           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.272           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.420           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.212           ms/op
ClientPb.listUser                       sample  242380   3.960 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.417           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.914           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.909           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.888           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.837           ms/op
