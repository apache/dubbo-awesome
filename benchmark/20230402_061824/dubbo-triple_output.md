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
# Warmup Iteration   1: 2.760 ops/ms
# Warmup Iteration   2: 6.036 ops/ms
# Warmup Iteration   3: 9.102 ops/ms
Iteration   1: 9.534 ops/ms
Iteration   2: 9.732 ops/ms
Iteration   3: 9.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.646 ±(99.9%) 1.863 ops/ms [Average]
  (min, avg, max) = (9.534, 9.646, 9.732), stdev = 0.102
  CI (99.9%): [7.783, 11.510] (assumes normal distribution)


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
# Warmup Iteration   1: 3.685 ops/ms
# Warmup Iteration   2: 8.803 ops/ms
# Warmup Iteration   3: 10.320 ops/ms
Iteration   1: 10.150 ops/ms
Iteration   2: 10.700 ops/ms
Iteration   3: 10.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.369 ±(99.9%) 5.327 ops/ms [Average]
  (min, avg, max) = (10.150, 10.369, 10.700), stdev = 0.292
  CI (99.9%): [5.042, 15.695] (assumes normal distribution)


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
# Warmup Iteration   1: 3.397 ops/ms
# Warmup Iteration   2: 8.573 ops/ms
# Warmup Iteration   3: 10.238 ops/ms
Iteration   1: 10.244 ops/ms
Iteration   2: 9.617 ops/ms
Iteration   3: 10.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.005 ±(99.9%) 6.187 ops/ms [Average]
  (min, avg, max) = (9.617, 10.005, 10.244), stdev = 0.339
  CI (99.9%): [3.818, 16.192] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.536 ops/ms
# Warmup Iteration   2: 7.594 ops/ms
# Warmup Iteration   3: 8.141 ops/ms
Iteration   1: 8.529 ops/ms
Iteration   2: 8.024 ops/ms
Iteration   3: 7.997 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.184 ±(99.9%) 5.465 ops/ms [Average]
  (min, avg, max) = (7.997, 8.184, 8.529), stdev = 0.300
  CI (99.9%): [2.718, 13.649] (assumes normal distribution)


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
# Warmup Iteration   1: 7.657 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.513 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.008 ms/op
Iteration   1: 3.186 ±(99.9%) 0.010 ms/op
Iteration   2: 3.178 ±(99.9%) 0.006 ms/op
Iteration   3: 3.157 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.174 ±(99.9%) 0.273 ms/op [Average]
  (min, avg, max) = (3.157, 3.174, 3.186), stdev = 0.015
  CI (99.9%): [2.901, 3.447] (assumes normal distribution)


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
# Warmup Iteration   1: 7.262 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.265 ±(99.9%) 0.003 ms/op
Iteration   1: 2.994 ±(99.9%) 0.003 ms/op
Iteration   2: 3.189 ±(99.9%) 0.008 ms/op
Iteration   3: 3.186 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.123 ±(99.9%) 2.044 ms/op [Average]
  (min, avg, max) = (2.994, 3.123, 3.189), stdev = 0.112
  CI (99.9%): [1.079, 5.167] (assumes normal distribution)


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
# Warmup Iteration   1: 8.698 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.006 ms/op
Iteration   1: 3.252 ±(99.9%) 0.005 ms/op
Iteration   2: 3.130 ±(99.9%) 0.006 ms/op
Iteration   3: 3.099 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.160 ±(99.9%) 1.476 ms/op [Average]
  (min, avg, max) = (3.099, 3.160, 3.252), stdev = 0.081
  CI (99.9%): [1.684, 4.636] (assumes normal distribution)


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
# Warmup Iteration   1: 10.274 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.004 ms/op
Iteration   1: 3.748 ±(99.9%) 0.007 ms/op
Iteration   2: 3.655 ±(99.9%) 0.009 ms/op
Iteration   3: 3.590 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.664 ±(99.9%) 1.446 ms/op [Average]
  (min, avg, max) = (3.590, 3.664, 3.748), stdev = 0.079
  CI (99.9%): [2.218, 5.111] (assumes normal distribution)


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
# Warmup Iteration   1: 8.445 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.008 ms/op
Iteration   1: 3.165 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  17.268 ms/op
                 createUser·p0.9999: 19.985 ms/op
                 createUser·p1.00:   20.447 ms/op

Iteration   2: 3.230 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  11.302 ms/op
                 createUser·p0.9999: 24.521 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   3: 3.176 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.399 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  9.552 ms/op
                 createUser·p0.9999: 20.808 ms/op
                 createUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300936
  mean =      3.190 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9131 
    [ 2.500,  5.000) = 286936 
    [ 5.000,  7.500) = 4073 
    [ 7.500, 10.000) = 327 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     15.500 ms/op
     p(99.9900) =     23.655 ms/op
     p(99.9990) =     25.264 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 7.346 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.388 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.007 ms/op
Iteration   1: 3.146 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  12.648 ms/op
                 existUser·p0.9999: 26.373 ms/op
                 existUser·p1.00:   27.623 ms/op

Iteration   2: 3.182 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.204 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   4.073 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  8.640 ms/op
                 existUser·p0.9999: 22.184 ms/op
                 existUser·p1.00:   22.905 ms/op

Iteration   3: 3.210 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  12.452 ms/op
                 existUser·p0.9999: 23.953 ms/op
                 existUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301828
  mean =      3.179 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18066 
    [ 2.500,  5.000) = 278103 
    [ 5.000,  7.500) = 4928 
    [ 7.500, 10.000) = 330 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 145 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     12.474 ms/op
     p(99.9900) =     25.297 ms/op
     p(99.9990) =     26.869 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 7.995 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.466 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.452 ±(99.9%) 0.011 ms/op
Iteration   1: 3.178 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  17.072 ms/op
                 getUser·p0.9999: 19.888 ms/op
                 getUser·p1.00:   20.808 ms/op

Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.169 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   5.431 ms/op
                 getUser·p0.999:  10.469 ms/op
                 getUser·p0.9999: 21.783 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   3: 3.147 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.580 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  11.370 ms/op
                 getUser·p0.9999: 20.906 ms/op
                 getUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304601
  mean =      3.149 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6840 
    [ 2.500,  5.000) = 292048 
    [ 5.000,  7.500) = 5002 
    [ 7.500, 10.000) = 302 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     14.955 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     22.334 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 9.354 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.155 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.011 ms/op
Iteration   1: 3.950 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   7.602 ms/op
                 listUser·p0.999:  16.905 ms/op
                 listUser·p0.9999: 20.182 ms/op
                 listUser·p1.00:   20.840 ms/op

Iteration   2: 3.959 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.716 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  15.616 ms/op
                 listUser·p0.9999: 20.624 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   3: 3.748 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.988 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  12.501 ms/op
                 listUser·p0.9999: 14.696 ms/op
                 listUser·p1.00:   14.926 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247190
  mean =      3.883 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 99 
    [ 2.500,  5.000) = 234216 
    [ 5.000,  7.500) = 10232 
    [ 7.500, 10.000) = 1862 
    [10.000, 12.500) = 342 
    [12.500, 15.000) = 260 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     14.235 ms/op
     p(99.9900) =     19.590 ms/op
     p(99.9990) =     21.317 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.646 ± 1.863  ops/ms
ClientPb.existUser                       thrpt       3  10.369 ± 5.327  ops/ms
ClientPb.getUser                         thrpt       3  10.005 ± 6.187  ops/ms
ClientPb.listUser                        thrpt       3   8.184 ± 5.465  ops/ms
ClientPb.createUser                       avgt       3   3.174 ± 0.273   ms/op
ClientPb.existUser                        avgt       3   3.123 ± 2.044   ms/op
ClientPb.getUser                          avgt       3   3.160 ± 1.476   ms/op
ClientPb.listUser                         avgt       3   3.664 ± 1.446   ms/op
ClientPb.createUser                     sample  300936   3.190 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.061           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.572           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.382           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.500           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.655           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.395           ms/op
ClientPb.existUser                      sample  301828   3.179 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.006           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.920           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.546           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.474           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.297           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.623           ms/op
ClientPb.getUser                        sample  304601   3.149 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.169           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.453           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.711           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.775           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.955           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.463           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.577           ms/op
ClientPb.listUser                       sample  247190   3.883 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.988           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.723           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.128           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.594           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.235           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.590           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.922           ms/op
