# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.859 ops/ms
# Warmup Iteration   2: 12.263 ops/ms
# Warmup Iteration   3: 12.651 ops/ms
Iteration   1: 12.817 ops/ms
Iteration   2: 13.020 ops/ms
Iteration   3: 13.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.959 ±(99.9%) 2.253 ops/ms [Average]
  (min, avg, max) = (12.817, 12.959, 13.040), stdev = 0.124
  CI (99.9%): [10.706, 15.212] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.520 ops/ms
# Warmup Iteration   2: 13.161 ops/ms
# Warmup Iteration   3: 13.369 ops/ms
Iteration   1: 13.459 ops/ms
Iteration   2: 13.366 ops/ms
Iteration   3: 13.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.380 ±(99.9%) 1.327 ops/ms [Average]
  (min, avg, max) = (13.315, 13.380, 13.459), stdev = 0.073
  CI (99.9%): [12.053, 14.707] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.190 ops/ms
# Warmup Iteration   2: 12.723 ops/ms
# Warmup Iteration   3: 12.906 ops/ms
Iteration   1: 13.048 ops/ms
Iteration   2: 12.930 ops/ms
Iteration   3: 13.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.034 ±(99.9%) 1.787 ops/ms [Average]
  (min, avg, max) = (12.930, 13.034, 13.124), stdev = 0.098
  CI (99.9%): [11.247, 14.822] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.084 ops/ms
# Warmup Iteration   2: 10.500 ops/ms
# Warmup Iteration   3: 10.738 ops/ms
Iteration   1: 10.755 ops/ms
Iteration   2: 10.739 ops/ms
Iteration   3: 10.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.770 ±(99.9%) 0.742 ops/ms [Average]
  (min, avg, max) = (10.739, 10.770, 10.816), stdev = 0.041
  CI (99.9%): [10.028, 11.512] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.750 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.004 ms/op
Iteration   1: 2.457 ±(99.9%) 0.003 ms/op
Iteration   2: 2.445 ±(99.9%) 0.005 ms/op
Iteration   3: 2.463 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.455 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (2.445, 2.455, 2.463), stdev = 0.009
  CI (99.9%): [2.290, 2.620] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.965 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.397 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.416 ±(99.9%) 0.004 ms/op
Iteration   1: 2.424 ±(99.9%) 0.004 ms/op
Iteration   2: 2.407 ±(99.9%) 0.003 ms/op
Iteration   3: 2.395 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.409 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (2.395, 2.409, 2.424), stdev = 0.014
  CI (99.9%): [2.147, 2.670] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.857 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.464 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.004 ms/op
Iteration   1: 2.452 ±(99.9%) 0.003 ms/op
Iteration   2: 2.433 ±(99.9%) 0.003 ms/op
Iteration   3: 2.451 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.446 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (2.433, 2.446, 2.452), stdev = 0.011
  CI (99.9%): [2.247, 2.644] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.777 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.005 ms/op
Iteration   1: 2.945 ±(99.9%) 0.005 ms/op
Iteration   2: 2.972 ±(99.9%) 0.004 ms/op
Iteration   3: 2.980 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.966 ±(99.9%) 0.329 ms/op [Average]
  (min, avg, max) = (2.945, 2.966, 2.980), stdev = 0.018
  CI (99.9%): [2.637, 3.295] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.220 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.613 ms/op
                 createUser·p0.999:  6.058 ms/op
                 createUser·p0.9999: 13.533 ms/op
                 createUser·p1.00:   14.352 ms/op

Iteration   2: 2.448 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.611 ms/op
                 createUser·p0.999:  6.384 ms/op
                 createUser·p0.9999: 11.843 ms/op
                 createUser·p1.00:   12.927 ms/op

Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   2.521 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  8.773 ms/op
                 createUser·p0.9999: 11.599 ms/op
                 createUser·p1.00:   16.122 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 391129
  mean =      2.451 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 193500 
    [ 2.500,  3.750) = 194228 
    [ 3.750,  5.000) = 2671 
    [ 5.000,  6.250) = 252 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 132 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =      8.731 ms/op
     p(99.9900) =     13.074 ms/op
     p(99.9990) =     14.112 ms/op
     p(99.9999) =     16.122 ms/op
    p(100.0000) =     16.122 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.606 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.430 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.411 ±(99.9%) 0.005 ms/op
Iteration   1: 2.401 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.588 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.342 ms/op
                 existUser·p0.999:  5.724 ms/op
                 existUser·p0.9999: 14.162 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  8.487 ms/op
                 existUser·p0.9999: 12.383 ms/op
                 existUser·p1.00:   12.911 ms/op

Iteration   3: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.017 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  7.343 ms/op
                 existUser·p0.9999: 12.173 ms/op
                 existUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397241
  mean =      2.415 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 199725 
    [ 2.500,  3.750) = 194890 
    [ 3.750,  5.000) = 1985 
    [ 5.000,  6.250) = 153 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 190 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.482 ms/op
     p(99.9000) =      8.327 ms/op
     p(99.9900) =     12.535 ms/op
     p(99.9990) =     14.436 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.913 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  7.796 ms/op
                 getUser·p0.9999: 14.304 ms/op
                 getUser·p1.00:   15.270 ms/op

Iteration   2: 2.499 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  9.520 ms/op
                 getUser·p0.9999: 12.020 ms/op
                 getUser·p1.00:   13.304 ms/op

Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.612 ms/op
                 getUser·p0.999:  6.419 ms/op
                 getUser·p0.9999: 10.289 ms/op
                 getUser·p1.00:   11.125 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387704
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 193535 
    [ 2.500,  3.750) = 189187 
    [ 3.750,  5.000) = 4090 
    [ 5.000,  6.250) = 406 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      7.701 ms/op
     p(99.9900) =     13.594 ms/op
     p(99.9990) =     14.434 ms/op
     p(99.9999) =     15.270 ms/op
    p(100.0000) =     15.270 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.626 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.008 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.008 ms/op
Iteration   1: 2.959 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.749 ms/op
                 listUser·p0.9999: 11.885 ms/op
                 listUser·p1.00:   12.419 ms/op

Iteration   2: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.781 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.437 ms/op
                 listUser·p0.9999: 12.043 ms/op
                 listUser·p1.00:   12.698 ms/op

Iteration   3: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.785 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.823 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  8.782 ms/op
                 listUser·p0.9999: 9.917 ms/op
                 listUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322617
  mean =      2.973 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 138 
    [ 1.250,  2.500) = 101066 
    [ 2.500,  3.750) = 184821 
    [ 3.750,  5.000) = 29846 
    [ 5.000,  6.250) = 5451 
    [ 6.250,  7.500) = 615 
    [ 7.500,  8.750) = 318 
    [ 8.750, 10.000) = 265 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     11.378 ms/op
     p(99.9990) =     12.393 ms/op
     p(99.9999) =     12.698 ms/op
    p(100.0000) =     12.698 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.959 ± 2.253  ops/ms
ClientPb.existUser                       thrpt       3  13.380 ± 1.327  ops/ms
ClientPb.getUser                         thrpt       3  13.034 ± 1.787  ops/ms
ClientPb.listUser                        thrpt       3  10.770 ± 0.742  ops/ms
ClientPb.createUser                       avgt       3   2.455 ± 0.165   ms/op
ClientPb.existUser                        avgt       3   2.409 ± 0.262   ms/op
ClientPb.getUser                          avgt       3   2.446 ± 0.199   ms/op
ClientPb.listUser                         avgt       3   2.966 ± 0.329   ms/op
ClientPb.createUser                     sample  391129   2.451 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.945           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.523           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.978           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.666           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.731           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.074           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.122           ms/op
ClientPb.existUser                      sample  397241   2.415 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.588           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.482           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.327           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.535           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.533           ms/op
ClientPb.getUser                        sample  387704   2.474 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.770           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.701           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.594           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.270           ms/op
ClientPb.listUser                       sample  322617   2.973 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.781           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.864           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.378           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.698           ms/op
