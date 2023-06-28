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
# Warmup Iteration   1: 2.366 ops/ms
# Warmup Iteration   2: 5.520 ops/ms
# Warmup Iteration   3: 9.139 ops/ms
Iteration   1: 9.776 ops/ms
Iteration   2: 9.856 ops/ms
Iteration   3: 9.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.805 ±(99.9%) 0.800 ops/ms [Average]
  (min, avg, max) = (9.776, 9.805, 9.856), stdev = 0.044
  CI (99.9%): [9.005, 10.606] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.231 ops/ms
# Warmup Iteration   2: 9.342 ops/ms
# Warmup Iteration   3: 10.167 ops/ms
Iteration   1: 10.098 ops/ms
Iteration   2: 10.285 ops/ms
Iteration   3: 10.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.235 ±(99.9%) 2.193 ops/ms [Average]
  (min, avg, max) = (10.098, 10.235, 10.323), stdev = 0.120
  CI (99.9%): [8.042, 12.428] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.624 ops/ms
# Warmup Iteration   2: 8.577 ops/ms
# Warmup Iteration   3: 9.570 ops/ms
Iteration   1: 10.077 ops/ms
Iteration   2: 10.309 ops/ms
Iteration   3: 9.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.097 ±(99.9%) 3.696 ops/ms [Average]
  (min, avg, max) = (9.906, 10.097, 10.309), stdev = 0.203
  CI (99.9%): [6.401, 13.794] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.369 ops/ms
# Warmup Iteration   2: 7.888 ops/ms
# Warmup Iteration   3: 8.620 ops/ms
Iteration   1: 8.454 ops/ms
Iteration   2: 8.466 ops/ms
Iteration   3: 8.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.558 ±(99.9%) 3.104 ops/ms [Average]
  (min, avg, max) = (8.454, 8.558, 8.755), stdev = 0.170
  CI (99.9%): [5.454, 11.663] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.951 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.004 ms/op
Iteration   1: 3.159 ±(99.9%) 0.009 ms/op
Iteration   2: 3.171 ±(99.9%) 0.003 ms/op
Iteration   3: 3.119 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.150 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (3.119, 3.150, 3.171), stdev = 0.028
  CI (99.9%): [2.647, 3.653] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.128 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.331 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.008 ms/op
Iteration   1: 3.034 ±(99.9%) 0.002 ms/op
Iteration   2: 3.033 ±(99.9%) 0.003 ms/op
Iteration   3: 3.141 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.069 ±(99.9%) 1.138 ms/op [Average]
  (min, avg, max) = (3.033, 3.069, 3.141), stdev = 0.062
  CI (99.9%): [1.931, 4.208] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.096 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.409 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.255 ±(99.9%) 0.004 ms/op
Iteration   1: 3.264 ±(99.9%) 0.007 ms/op
Iteration   2: 3.102 ±(99.9%) 0.004 ms/op
Iteration   3: 3.266 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.211 ±(99.9%) 1.721 ms/op [Average]
  (min, avg, max) = (3.102, 3.211, 3.266), stdev = 0.094
  CI (99.9%): [1.490, 4.932] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.637 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.219 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.006 ms/op
Iteration   1: 3.720 ±(99.9%) 0.008 ms/op
Iteration   2: 3.740 ±(99.9%) 0.007 ms/op
Iteration   3: 3.674 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.711 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (3.674, 3.711, 3.740), stdev = 0.034
  CI (99.9%): [3.091, 4.331] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.264 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.630 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.008 ms/op
Iteration   1: 3.113 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  8.696 ms/op
                 createUser·p0.9999: 21.749 ms/op
                 createUser·p1.00:   22.315 ms/op

Iteration   2: 3.254 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.255 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  15.891 ms/op
                 createUser·p0.9999: 21.043 ms/op
                 createUser·p1.00:   22.020 ms/op

Iteration   3: 3.132 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.600 ms/op
                 createUser·p0.99:   5.161 ms/op
                 createUser·p0.999:  15.303 ms/op
                 createUser·p0.9999: 24.019 ms/op
                 createUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302984
  mean =      3.165 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17502 
    [ 2.500,  5.000) = 281197 
    [ 5.000,  7.500) = 3287 
    [ 7.500, 10.000) = 597 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 160 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.035 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     15.221 ms/op
     p(99.9900) =     21.978 ms/op
     p(99.9990) =     24.216 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.427 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.424 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.008 ms/op
Iteration   1: 3.195 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.649 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  8.265 ms/op
                 existUser·p0.9999: 30.147 ms/op
                 existUser·p1.00:   30.736 ms/op

Iteration   2: 3.169 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  13.771 ms/op
                 existUser·p0.9999: 26.081 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   3: 3.141 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   5.168 ms/op
                 existUser·p0.999:  8.297 ms/op
                 existUser·p0.9999: 23.855 ms/op
                 existUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302544
  mean =      3.168 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27756 
    [ 2.500,  5.000) = 270807 
    [ 5.000,  7.500) = 3389 
    [ 7.500, 10.000) = 198 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     11.837 ms/op
     p(99.9900) =     29.311 ms/op
     p(99.9990) =     30.736 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


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
# Warmup Iteration   1: 9.018 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.560 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.009 ms/op
Iteration   1: 3.350 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.425 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   4.141 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  18.058 ms/op
                 getUser·p0.9999: 23.753 ms/op
                 getUser·p1.00:   24.150 ms/op

Iteration   2: 3.131 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.375 ms/op
                 getUser·p0.95:   3.572 ms/op
                 getUser·p0.99:   5.095 ms/op
                 getUser·p0.999:  10.842 ms/op
                 getUser·p0.9999: 27.332 ms/op
                 getUser·p1.00:   28.115 ms/op

Iteration   3: 3.224 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  11.270 ms/op
                 getUser·p0.9999: 25.264 ms/op
                 getUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296827
  mean =      3.232 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8553 
    [ 2.500,  5.000) = 279886 
    [ 5.000,  7.500) = 7244 
    [ 7.500, 10.000) = 725 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.291 ms/op
     p(99.9000) =     14.090 ms/op
     p(99.9900) =     25.830 ms/op
     p(99.9990) =     27.988 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 9.515 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.153 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.797 ±(99.9%) 0.011 ms/op
Iteration   1: 3.735 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.234 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  15.155 ms/op
                 listUser·p0.9999: 22.217 ms/op
                 listUser·p1.00:   23.724 ms/op

Iteration   2: 3.750 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.735 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  14.774 ms/op
                 listUser·p0.9999: 17.984 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   3: 3.760 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  12.501 ms/op
                 listUser·p0.9999: 15.303 ms/op
                 listUser·p1.00:   15.335 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255933
  mean =      3.748 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 249197 
    [ 5.000,  7.500) = 4664 
    [ 7.500, 10.000) = 1380 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.610 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     14.533 ms/op
     p(99.9900) =     20.428 ms/op
     p(99.9990) =     23.632 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.805 ± 0.800  ops/ms
ClientPb.existUser                       thrpt       3  10.235 ± 2.193  ops/ms
ClientPb.getUser                         thrpt       3  10.097 ± 3.696  ops/ms
ClientPb.listUser                        thrpt       3   8.558 ± 3.104  ops/ms
ClientPb.createUser                       avgt       3   3.150 ± 0.503   ms/op
ClientPb.existUser                        avgt       3   3.069 ± 1.138   ms/op
ClientPb.getUser                          avgt       3   3.211 ± 1.721   ms/op
ClientPb.listUser                         avgt       3   3.711 ± 0.620   ms/op
ClientPb.createUser                     sample  302984   3.165 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.035           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.498           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.399           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.221           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.978           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.445           ms/op
ClientPb.existUser                      sample  302544   3.168 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.978           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.412           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.284           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.837           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.311           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.736           ms/op
ClientPb.getUser                        sample  296827   3.232 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.756           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.291           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.090           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.830           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.115           ms/op
ClientPb.listUser                       sample  255933   3.748 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.610           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.654           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.994           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.127           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.533           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.428           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.724           ms/op
