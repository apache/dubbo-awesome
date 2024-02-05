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
# Warmup Iteration   1: 4.855 ops/ms
# Warmup Iteration   2: 12.270 ops/ms
# Warmup Iteration   3: 12.518 ops/ms
Iteration   1: 12.599 ops/ms
Iteration   2: 12.745 ops/ms
Iteration   3: 12.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.712 ±(99.9%) 1.833 ops/ms [Average]
  (min, avg, max) = (12.599, 12.712, 12.792), stdev = 0.100
  CI (99.9%): [10.879, 14.545] (assumes normal distribution)


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
# Warmup Iteration   1: 8.179 ops/ms
# Warmup Iteration   2: 12.965 ops/ms
# Warmup Iteration   3: 13.030 ops/ms
Iteration   1: 13.015 ops/ms
Iteration   2: 13.122 ops/ms
Iteration   3: 12.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.030 ±(99.9%) 1.569 ops/ms [Average]
  (min, avg, max) = (12.952, 13.030, 13.122), stdev = 0.086
  CI (99.9%): [11.461, 14.599] (assumes normal distribution)


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
# Warmup Iteration   1: 7.924 ops/ms
# Warmup Iteration   2: 12.624 ops/ms
# Warmup Iteration   3: 12.839 ops/ms
Iteration   1: 12.847 ops/ms
Iteration   2: 12.654 ops/ms
Iteration   3: 12.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.821 ±(99.9%) 2.830 ops/ms [Average]
  (min, avg, max) = (12.654, 12.821, 12.961), stdev = 0.155
  CI (99.9%): [9.991, 15.651] (assumes normal distribution)


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
# Warmup Iteration   1: 6.940 ops/ms
# Warmup Iteration   2: 10.418 ops/ms
# Warmup Iteration   3: 10.742 ops/ms
Iteration   1: 10.651 ops/ms
Iteration   2: 10.805 ops/ms
Iteration   3: 10.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.721 ±(99.9%) 1.416 ops/ms [Average]
  (min, avg, max) = (10.651, 10.721, 10.805), stdev = 0.078
  CI (99.9%): [9.305, 12.137] (assumes normal distribution)


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.549 ±(99.9%) 0.004 ms/op
Iteration   2: 2.549 ±(99.9%) 0.005 ms/op
Iteration   3: 2.529 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.542 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (2.529, 2.542, 2.549), stdev = 0.012
  CI (99.9%): [2.327, 2.757] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.680 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
Iteration   2: 2.433 ±(99.9%) 0.004 ms/op
Iteration   3: 2.452 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.451 ±(99.9%) 0.326 ms/op [Average]
  (min, avg, max) = (2.433, 2.451, 2.468), stdev = 0.018
  CI (99.9%): [2.125, 2.777] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.970 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.474 ±(99.9%) 0.004 ms/op
Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
Iteration   3: 2.491 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.487 ±(99.9%) 0.198 ms/op [Average]
  (min, avg, max) = (2.474, 2.487, 2.495), stdev = 0.011
  CI (99.9%): [2.289, 2.685] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.693 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.004 ms/op
Iteration   1: 3.001 ±(99.9%) 0.004 ms/op
Iteration   2: 3.007 ±(99.9%) 0.004 ms/op
Iteration   3: 3.020 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.009 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (3.001, 3.009, 3.020), stdev = 0.010
  CI (99.9%): [2.832, 3.187] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.928 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.006 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.739 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.982 ms/op
                 createUser·p0.999:  10.269 ms/op
                 createUser·p0.9999: 13.068 ms/op
                 createUser·p1.00:   13.451 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.637 ms/op
                 createUser·p0.999:  8.954 ms/op
                 createUser·p0.9999: 12.163 ms/op
                 createUser·p1.00:   12.567 ms/op

Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.940 ms/op
                 createUser·p0.999:  8.962 ms/op
                 createUser·p0.9999: 13.402 ms/op
                 createUser·p1.00:   14.975 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382979
  mean =      2.504 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 188327 
    [ 2.500,  3.750) = 190090 
    [ 3.750,  5.000) = 3730 
    [ 5.000,  6.250) = 376 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     13.016 ms/op
     p(99.9990) =     13.817 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


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
# Warmup Iteration   1: 3.795 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.576 ms/op
                 existUser·p0.999:  6.960 ms/op
                 existUser·p0.9999: 13.730 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  5.546 ms/op
                 existUser·p0.9999: 14.053 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  8.782 ms/op
                 existUser·p0.9999: 11.616 ms/op
                 existUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390987
  mean =      2.453 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 195722 
    [ 2.500,  3.750) = 192184 
    [ 3.750,  5.000) = 2343 
    [ 5.000,  6.250) = 284 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.604 ms/op
     p(99.9000) =      6.496 ms/op
     p(99.9900) =     13.664 ms/op
     p(99.9990) =     14.239 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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
# Warmup Iteration   1: 3.880 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.007 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.650 ms/op
                 getUser·p0.999:  10.983 ms/op
                 getUser·p0.9999: 13.275 ms/op
                 getUser·p1.00:   13.451 ms/op

Iteration   2: 2.543 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  9.376 ms/op
                 getUser·p0.9999: 12.904 ms/op
                 getUser·p1.00:   14.483 ms/op

Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  7.749 ms/op
                 getUser·p0.9999: 10.603 ms/op
                 getUser·p1.00:   10.830 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381236
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 188001 
    [ 2.500,  3.750) = 188956 
    [ 3.750,  5.000) = 3257 
    [ 5.000,  6.250) = 511 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      8.241 ms/op
     p(99.9900) =     13.023 ms/op
     p(99.9990) =     13.782 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


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
# Warmup Iteration   1: 4.800 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.008 ms/op
Iteration   1: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.437 ms/op
                 listUser·p0.9999: 10.781 ms/op
                 listUser·p1.00:   11.420 ms/op

Iteration   2: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.688 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  8.810 ms/op
                 listUser·p0.9999: 10.941 ms/op
                 listUser·p1.00:   11.813 ms/op

Iteration   3: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.971 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  10.093 ms/op
                 listUser·p0.9999: 12.269 ms/op
                 listUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317520
  mean =      3.021 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 91035 
    [ 2.500,  3.750) = 186688 
    [ 3.750,  5.000) = 32264 
    [ 5.000,  6.250) = 6058 
    [ 6.250,  7.500) = 722 
    [ 7.500,  8.750) = 150 
    [ 8.750, 10.000) = 240 
    [10.000, 11.250) = 153 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     11.710 ms/op
     p(99.9990) =     12.460 ms/op
     p(99.9999) =     12.550 ms/op
    p(100.0000) =     12.550 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.712 ± 1.833  ops/ms
ClientPb.existUser                       thrpt       3  13.030 ± 1.569  ops/ms
ClientPb.getUser                         thrpt       3  12.821 ± 2.830  ops/ms
ClientPb.listUser                        thrpt       3  10.721 ± 1.416  ops/ms
ClientPb.createUser                       avgt       3   2.542 ± 0.215   ms/op
ClientPb.existUser                        avgt       3   2.451 ± 0.326   ms/op
ClientPb.getUser                          avgt       3   2.487 ± 0.198   ms/op
ClientPb.listUser                         avgt       3   3.009 ± 0.177   ms/op
ClientPb.createUser                     sample  382979   2.504 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.739           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.962           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.016           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.975           ms/op
ClientPb.existUser                      sample  390987   2.453 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.000           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.496           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.664           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.352           ms/op
ClientPb.getUser                        sample  381236   2.516 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.811           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.241           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.023           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.483           ms/op
ClientPb.listUser                       sample  317520   3.021 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.688           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.568           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.710           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.550           ms/op
