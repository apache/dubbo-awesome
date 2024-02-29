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
# Warmup Iteration   1: 4.728 ops/ms
# Warmup Iteration   2: 12.248 ops/ms
# Warmup Iteration   3: 12.563 ops/ms
Iteration   1: 12.876 ops/ms
Iteration   2: 12.778 ops/ms
Iteration   3: 12.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.882 ±(99.9%) 1.967 ops/ms [Average]
  (min, avg, max) = (12.778, 12.882, 12.993), stdev = 0.108
  CI (99.9%): [10.915, 14.849] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.310 ops/ms
# Warmup Iteration   2: 12.973 ops/ms
# Warmup Iteration   3: 13.264 ops/ms
Iteration   1: 13.306 ops/ms
Iteration   2: 13.193 ops/ms
Iteration   3: 13.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.251 ±(99.9%) 1.031 ops/ms [Average]
  (min, avg, max) = (13.193, 13.251, 13.306), stdev = 0.056
  CI (99.9%): [12.221, 14.282] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.221 ops/ms
# Warmup Iteration   2: 12.362 ops/ms
# Warmup Iteration   3: 12.783 ops/ms
Iteration   1: 12.864 ops/ms
Iteration   2: 12.713 ops/ms
Iteration   3: 12.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.774 ±(99.9%) 1.456 ops/ms [Average]
  (min, avg, max) = (12.713, 12.774, 12.864), stdev = 0.080
  CI (99.9%): [11.318, 14.230] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.591 ops/ms
# Warmup Iteration   2: 10.631 ops/ms
# Warmup Iteration   3: 10.744 ops/ms
Iteration   1: 10.733 ops/ms
Iteration   2: 10.813 ops/ms
Iteration   3: 10.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.735 ±(99.9%) 1.407 ops/ms [Average]
  (min, avg, max) = (10.659, 10.735, 10.813), stdev = 0.077
  CI (99.9%): [9.328, 12.142] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.932 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.004 ms/op
Iteration   1: 2.473 ±(99.9%) 0.004 ms/op
Iteration   2: 2.444 ±(99.9%) 0.004 ms/op
Iteration   3: 2.435 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.450 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (2.435, 2.450, 2.473), stdev = 0.020
  CI (99.9%): [2.084, 2.817] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.587 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.437 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.416 ±(99.9%) 0.004 ms/op
Iteration   1: 2.408 ±(99.9%) 0.004 ms/op
Iteration   2: 2.411 ±(99.9%) 0.004 ms/op
Iteration   3: 2.414 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.411 ±(99.9%) 0.048 ms/op [Average]
  (min, avg, max) = (2.408, 2.411, 2.414), stdev = 0.003
  CI (99.9%): [2.363, 2.459] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.652 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.004 ms/op
Iteration   1: 2.407 ±(99.9%) 0.004 ms/op
Iteration   2: 2.429 ±(99.9%) 0.003 ms/op
Iteration   3: 2.447 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.428 ±(99.9%) 0.366 ms/op [Average]
  (min, avg, max) = (2.407, 2.428, 2.447), stdev = 0.020
  CI (99.9%): [2.062, 2.793] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.539 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.005 ms/op
Iteration   1: 3.010 ±(99.9%) 0.004 ms/op
Iteration   2: 3.004 ±(99.9%) 0.006 ms/op
Iteration   3: 3.004 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.006 ±(99.9%) 0.068 ms/op [Average]
  (min, avg, max) = (3.004, 3.006, 3.010), stdev = 0.004
  CI (99.9%): [2.939, 3.074] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.056 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.845 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.784 ms/op
                 createUser·p0.999:  6.617 ms/op
                 createUser·p0.9999: 13.695 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   4.035 ms/op
                 createUser·p0.999:  9.824 ms/op
                 createUser·p0.9999: 13.303 ms/op
                 createUser·p1.00:   15.221 ms/op

Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.571 ms/op
                 createUser·p0.50:   2.494 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  8.303 ms/op
                 createUser·p0.9999: 9.994 ms/op
                 createUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 388400
  mean =      2.470 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 193275 
    [ 2.500,  3.750) = 190706 
    [ 3.750,  5.000) = 3462 
    [ 5.000,  6.250) = 393 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 171 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      8.897 ms/op
     p(99.9900) =     13.222 ms/op
     p(99.9990) =     14.794 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.649 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.420 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.405 ±(99.9%) 0.005 ms/op
Iteration   1: 2.413 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.995 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  5.828 ms/op
                 existUser·p0.9999: 13.332 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   2: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  6.382 ms/op
                 existUser·p0.9999: 13.646 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.699 ms/op
                 existUser·p0.999:  8.385 ms/op
                 existUser·p0.9999: 11.808 ms/op
                 existUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395006
  mean =      2.428 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 198254 
    [ 2.500,  3.750) = 193554 
    [ 3.750,  5.000) = 2413 
    [ 5.000,  6.250) = 283 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =      7.405 ms/op
     p(99.9900) =     13.132 ms/op
     p(99.9990) =     14.043 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.047 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.006 ms/op
Iteration   1: 2.507 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.088 ms/op
                 getUser·p0.999:  11.419 ms/op
                 getUser·p0.9999: 14.090 ms/op
                 getUser·p1.00:   15.139 ms/op

Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.957 ms/op
                 getUser·p0.999:  9.060 ms/op
                 getUser·p0.9999: 14.160 ms/op
                 getUser·p1.00:   15.663 ms/op

Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  6.295 ms/op
                 getUser·p0.9999: 11.141 ms/op
                 getUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385660
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 193053 
    [ 2.500,  3.750) = 187474 
    [ 3.750,  5.000) = 4150 
    [ 5.000,  6.250) = 488 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =      6.704 ms/op
     p(99.9900) =     14.008 ms/op
     p(99.9990) =     15.569 ms/op
     p(99.9999) =     15.663 ms/op
    p(100.0000) =     15.663 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.599 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.994 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.968 ±(99.9%) 0.008 ms/op
Iteration   1: 2.932 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.912 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.471 ms/op
                 listUser·p0.999:  8.601 ms/op
                 listUser·p0.9999: 11.588 ms/op
                 listUser·p1.00:   12.255 ms/op

Iteration   2: 2.932 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.816 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 12.011 ms/op
                 listUser·p1.00:   13.173 ms/op

Iteration   3: 2.922 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.760 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   5.325 ms/op
                 listUser·p0.999:  8.782 ms/op
                 listUser·p0.9999: 10.436 ms/op
                 listUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 327448
  mean =      2.929 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 191 
    [ 1.250,  2.500) = 106348 
    [ 2.500,  3.750) = 185730 
    [ 3.750,  5.000) = 28873 
    [ 5.000,  6.250) = 5157 
    [ 6.250,  7.500) = 453 
    [ 7.500,  8.750) = 345 
    [ 8.750, 10.000) = 194 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =      8.873 ms/op
     p(99.9900) =     11.592 ms/op
     p(99.9990) =     12.365 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.882 ± 1.967  ops/ms
ClientPb.existUser                       thrpt       3  13.251 ± 1.031  ops/ms
ClientPb.getUser                         thrpt       3  12.774 ± 1.456  ops/ms
ClientPb.listUser                        thrpt       3  10.735 ± 1.407  ops/ms
ClientPb.createUser                       avgt       3   2.450 ± 0.367   ms/op
ClientPb.existUser                        avgt       3   2.411 ± 0.048   ms/op
ClientPb.getUser                          avgt       3   2.428 ± 0.366   ms/op
ClientPb.listUser                         avgt       3   3.006 ± 0.068   ms/op
ClientPb.createUser                     sample  388400   2.470 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.571           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.507           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.897           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.222           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.221           ms/op
ClientPb.existUser                      sample  395006   2.428 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.930           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.405           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.132           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.418           ms/op
ClientPb.getUser                        sample  385660   2.487 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.794           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.704           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.008           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.663           ms/op
ClientPb.listUser                       sample  327448   2.929 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.816           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.797           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.431           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.873           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.592           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.173           ms/op
