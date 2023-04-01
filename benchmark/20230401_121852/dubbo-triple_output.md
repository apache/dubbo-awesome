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
# Warmup Iteration   1: 2.254 ops/ms
# Warmup Iteration   2: 5.765 ops/ms
# Warmup Iteration   3: 8.392 ops/ms
Iteration   1: 9.027 ops/ms
Iteration   2: 9.468 ops/ms
Iteration   3: 8.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.160 ±(99.9%) 4.887 ops/ms [Average]
  (min, avg, max) = (8.984, 9.160, 9.468), stdev = 0.268
  CI (99.9%): [4.273, 14.047] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.679 ops/ms
# Warmup Iteration   2: 9.046 ops/ms
# Warmup Iteration   3: 9.360 ops/ms
Iteration   1: 9.679 ops/ms
Iteration   2: 9.722 ops/ms
Iteration   3: 9.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.671 ±(99.9%) 1.016 ops/ms [Average]
  (min, avg, max) = (9.612, 9.671, 9.722), stdev = 0.056
  CI (99.9%): [8.655, 10.688] (assumes normal distribution)


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
# Warmup Iteration   1: 3.121 ops/ms
# Warmup Iteration   2: 8.493 ops/ms
# Warmup Iteration   3: 9.009 ops/ms
Iteration   1: 9.565 ops/ms
Iteration   2: 9.156 ops/ms
Iteration   3: 9.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.297 ±(99.9%) 4.248 ops/ms [Average]
  (min, avg, max) = (9.156, 9.297, 9.565), stdev = 0.233
  CI (99.9%): [5.049, 13.544] (assumes normal distribution)


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
# Warmup Iteration   1: 3.110 ops/ms
# Warmup Iteration   2: 7.417 ops/ms
# Warmup Iteration   3: 7.869 ops/ms
Iteration   1: 7.870 ops/ms
Iteration   2: 8.057 ops/ms
Iteration   3: 8.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.996 ±(99.9%) 2.002 ops/ms [Average]
  (min, avg, max) = (7.870, 7.996, 8.062), stdev = 0.110
  CI (99.9%): [5.994, 9.998] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.911 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.522 ±(99.9%) 0.007 ms/op
Iteration   1: 3.421 ±(99.9%) 0.011 ms/op
Iteration   2: 3.358 ±(99.9%) 0.013 ms/op
Iteration   3: 3.559 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.446 ±(99.9%) 1.876 ms/op [Average]
  (min, avg, max) = (3.358, 3.446, 3.559), stdev = 0.103
  CI (99.9%): [1.569, 5.322] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.656 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.007 ms/op
Iteration   1: 3.214 ±(99.9%) 0.008 ms/op
Iteration   2: 3.291 ±(99.9%) 0.007 ms/op
Iteration   3: 3.214 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.240 ±(99.9%) 0.816 ms/op [Average]
  (min, avg, max) = (3.214, 3.240, 3.291), stdev = 0.045
  CI (99.9%): [2.424, 4.056] (assumes normal distribution)


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
# Warmup Iteration   1: 9.018 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.570 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.707 ±(99.9%) 0.004 ms/op
Iteration   1: 3.421 ±(99.9%) 0.005 ms/op
Iteration   2: 3.511 ±(99.9%) 0.009 ms/op
Iteration   3: 3.418 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.450 ±(99.9%) 0.968 ms/op [Average]
  (min, avg, max) = (3.418, 3.450, 3.511), stdev = 0.053
  CI (99.9%): [2.482, 4.419] (assumes normal distribution)


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
# Warmup Iteration   1: 11.233 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.269 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.012 ms/op
Iteration   1: 3.952 ±(99.9%) 0.014 ms/op
Iteration   2: 4.031 ±(99.9%) 0.010 ms/op
Iteration   3: 3.953 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.979 ±(99.9%) 0.829 ms/op [Average]
  (min, avg, max) = (3.952, 3.979, 4.031), stdev = 0.045
  CI (99.9%): [3.150, 4.808] (assumes normal distribution)


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
# Warmup Iteration   1: 9.881 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.101 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.010 ms/op
Iteration   1: 3.548 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.145 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  19.821 ms/op
                 createUser·p0.9999: 33.193 ms/op
                 createUser·p1.00:   33.751 ms/op

Iteration   2: 3.411 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.840 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  21.438 ms/op
                 createUser·p0.9999: 25.711 ms/op
                 createUser·p1.00:   26.935 ms/op

Iteration   3: 3.415 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  15.502 ms/op
                 createUser·p0.9999: 24.931 ms/op
                 createUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277478
  mean =      3.457 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3367 
    [ 2.500,  5.000) = 267034 
    [ 5.000,  7.500) = 5948 
    [ 7.500, 10.000) = 707 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     16.518 ms/op
     p(99.9900) =     31.392 ms/op
     p(99.9990) =     33.700 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 8.703 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.010 ms/op
Iteration   1: 3.276 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.446 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  16.314 ms/op
                 existUser·p0.9999: 20.462 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   2: 3.325 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.552 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  18.078 ms/op
                 existUser·p0.9999: 22.950 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   3: 3.368 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.133 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  16.089 ms/op
                 existUser·p0.9999: 30.443 ms/op
                 existUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288690
  mean =      3.323 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23855 
    [ 2.500,  5.000) = 260502 
    [ 5.000,  7.500) = 3495 
    [ 7.500, 10.000) = 381 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.514 ms/op
     p(99.9000) =     16.089 ms/op
     p(99.9900) =     28.582 ms/op
     p(99.9990) =     31.079 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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
# Warmup Iteration   1: 8.839 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.582 ±(99.9%) 0.011 ms/op
Iteration   1: 3.502 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.303 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   7.381 ms/op
                 getUser·p0.999:  12.355 ms/op
                 getUser·p0.9999: 23.458 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   2: 3.379 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.692 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   5.210 ms/op
                 getUser·p0.999:  20.876 ms/op
                 getUser·p0.9999: 23.922 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   3: 3.647 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.015 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  21.060 ms/op
                 getUser·p0.9999: 28.377 ms/op
                 getUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273680
  mean =      3.506 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9889 
    [ 2.500,  5.000) = 252934 
    [ 5.000,  7.500) = 9377 
    [ 7.500, 10.000) = 1091 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.015 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     13.009 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     28.995 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 9.356 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.192 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.000 ±(99.9%) 0.013 ms/op
Iteration   1: 3.980 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  19.697 ms/op
                 listUser·p0.9999: 25.525 ms/op
                 listUser·p1.00:   26.542 ms/op

Iteration   2: 4.055 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.722 ms/op
                 listUser·p0.999:  14.199 ms/op
                 listUser·p0.9999: 18.267 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   3: 4.034 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  13.484 ms/op
                 listUser·p0.9999: 15.373 ms/op
                 listUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238527
  mean =      4.023 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 231432 
    [ 5.000,  7.500) = 4847 
    [ 7.500, 10.000) = 1473 
    [10.000, 12.500) = 288 
    [12.500, 15.000) = 265 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     14.721 ms/op
     p(99.9900) =     24.773 ms/op
     p(99.9990) =     26.383 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.160 ± 4.887  ops/ms
ClientPb.existUser                       thrpt       3   9.671 ± 1.016  ops/ms
ClientPb.getUser                         thrpt       3   9.297 ± 4.248  ops/ms
ClientPb.listUser                        thrpt       3   7.996 ± 2.002  ops/ms
ClientPb.createUser                       avgt       3   3.446 ± 1.876   ms/op
ClientPb.existUser                        avgt       3   3.240 ± 0.816   ms/op
ClientPb.getUser                          avgt       3   3.450 ± 0.968   ms/op
ClientPb.listUser                         avgt       3   3.979 ± 0.829   ms/op
ClientPb.createUser                     sample  277478   3.457 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.840           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.305           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.841           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.518           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.392           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.751           ms/op
ClientPb.existUser                      sample  288690   3.323 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.133           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.928           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.514           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.089           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.582           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.392           ms/op
ClientPb.getUser                        sample  273680   3.506 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.015           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.579           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.717           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.009           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.428           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.360           ms/op
ClientPb.listUser                       sample  238527   4.023 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.507           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.291           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.721           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.773           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.542           ms/op
