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
# Warmup Iteration   1: 5.192 ops/ms
# Warmup Iteration   2: 12.068 ops/ms
# Warmup Iteration   3: 12.513 ops/ms
Iteration   1: 12.629 ops/ms
Iteration   2: 12.745 ops/ms
Iteration   3: 12.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.743 ±(99.9%) 2.063 ops/ms [Average]
  (min, avg, max) = (12.629, 12.743, 12.856), stdev = 0.113
  CI (99.9%): [10.681, 14.806] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.117 ops/ms
# Warmup Iteration   2: 13.297 ops/ms
# Warmup Iteration   3: 13.169 ops/ms
Iteration   1: 13.228 ops/ms
Iteration   2: 13.392 ops/ms
Iteration   3: 13.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.322 ±(99.9%) 1.539 ops/ms [Average]
  (min, avg, max) = (13.228, 13.322, 13.392), stdev = 0.084
  CI (99.9%): [11.783, 14.860] (assumes normal distribution)


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
# Warmup Iteration   1: 7.785 ops/ms
# Warmup Iteration   2: 12.808 ops/ms
# Warmup Iteration   3: 12.847 ops/ms
Iteration   1: 12.858 ops/ms
Iteration   2: 13.154 ops/ms
Iteration   3: 13.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.105 ±(99.9%) 4.127 ops/ms [Average]
  (min, avg, max) = (12.858, 13.105, 13.303), stdev = 0.226
  CI (99.9%): [8.978, 17.232] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.710 ops/ms
# Warmup Iteration   2: 10.650 ops/ms
# Warmup Iteration   3: 10.673 ops/ms
Iteration   1: 10.649 ops/ms
Iteration   2: 10.754 ops/ms
Iteration   3: 10.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.757 ±(99.9%) 1.996 ops/ms [Average]
  (min, avg, max) = (10.649, 10.757, 10.868), stdev = 0.109
  CI (99.9%): [8.761, 12.753] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.176 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
Iteration   1: 2.464 ±(99.9%) 0.007 ms/op
Iteration   2: 2.453 ±(99.9%) 0.009 ms/op
Iteration   3: 2.455 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.457 ±(99.9%) 0.104 ms/op [Average]
  (min, avg, max) = (2.453, 2.457, 2.464), stdev = 0.006
  CI (99.9%): [2.353, 2.561] (assumes normal distribution)


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
# Warmup Iteration   1: 3.706 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.378 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.367 ±(99.9%) 0.004 ms/op
Iteration   1: 2.346 ±(99.9%) 0.005 ms/op
Iteration   2: 2.373 ±(99.9%) 0.005 ms/op
Iteration   3: 2.379 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.366 ±(99.9%) 0.326 ms/op [Average]
  (min, avg, max) = (2.346, 2.366, 2.379), stdev = 0.018
  CI (99.9%): [2.040, 2.692] (assumes normal distribution)


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
# Warmup Iteration   1: 3.776 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.006 ms/op
Iteration   1: 2.446 ±(99.9%) 0.004 ms/op
Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
Iteration   3: 2.490 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.462 ±(99.9%) 0.448 ms/op [Average]
  (min, avg, max) = (2.446, 2.462, 2.490), stdev = 0.025
  CI (99.9%): [2.013, 2.910] (assumes normal distribution)


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
# Warmup Iteration   1: 5.011 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.005 ms/op
Iteration   1: 2.966 ±(99.9%) 0.004 ms/op
Iteration   2: 2.967 ±(99.9%) 0.006 ms/op
Iteration   3: 2.990 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.974 ±(99.9%) 0.246 ms/op [Average]
  (min, avg, max) = (2.966, 2.974, 2.990), stdev = 0.013
  CI (99.9%): [2.728, 3.221] (assumes normal distribution)


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.634 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   2.445 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.482 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  11.995 ms/op
                 createUser·p0.9999: 15.349 ms/op
                 createUser·p1.00:   15.663 ms/op

Iteration   2: 2.505 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.365 ms/op
                 createUser·p0.50:   2.474 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.383 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  11.065 ms/op
                 createUser·p0.9999: 14.664 ms/op
                 createUser·p1.00:   15.696 ms/op

Iteration   3: 2.465 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   2.376 ms/op
                 createUser·p0.90:   3.187 ms/op
                 createUser·p0.95:   3.543 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  7.186 ms/op
                 createUser·p0.9999: 11.944 ms/op
                 createUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385237
  mean =      2.490 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 319 
    [ 1.250,  2.500) = 205818 
    [ 2.500,  3.750) = 167702 
    [ 3.750,  5.000) = 10061 
    [ 5.000,  6.250) = 727 
    [ 6.250,  7.500) = 141 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 77 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.365 ms/op
     p(50.0000) =      2.425 ms/op
     p(90.0000) =      3.150 ms/op
     p(95.0000) =      3.469 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      9.761 ms/op
     p(99.9900) =     14.893 ms/op
     p(99.9990) =     15.647 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


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
# Warmup Iteration   1: 3.701 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
Iteration   1: 2.447 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.605 ms/op
                 existUser·p0.50:   2.392 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.805 ms/op
                 existUser·p0.999:  8.237 ms/op
                 existUser·p0.9999: 14.975 ms/op
                 existUser·p1.00:   15.712 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.817 ms/op
                 existUser·p0.999:  8.893 ms/op
                 existUser·p0.9999: 15.061 ms/op
                 existUser·p1.00:   17.039 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.545 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  5.925 ms/op
                 existUser·p0.9999: 11.749 ms/op
                 existUser·p1.00:   14.254 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389034
  mean =      2.465 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 203727 
    [ 2.500,  3.750) = 180808 
    [ 3.750,  5.000) = 3432 
    [ 5.000,  6.250) = 487 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      2.429 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      8.025 ms/op
     p(99.9900) =     14.811 ms/op
     p(99.9990) =     15.712 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 3.824 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.006 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.400 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  8.203 ms/op
                 getUser·p0.9999: 14.811 ms/op
                 getUser·p1.00:   15.450 ms/op

Iteration   2: 2.474 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   2.392 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.371 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  9.101 ms/op
                 getUser·p0.9999: 13.718 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.721 ms/op
                 getUser·p0.50:   2.404 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.314 ms/op
                 getUser·p0.99:   4.149 ms/op
                 getUser·p0.999:  8.108 ms/op
                 getUser·p0.9999: 12.190 ms/op
                 getUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388367
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 112 
    [ 1.250,  2.500) = 212402 
    [ 2.500,  3.750) = 168675 
    [ 3.750,  5.000) = 5974 
    [ 5.000,  6.250) = 784 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 131 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      2.400 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.273 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =      7.947 ms/op
     p(99.9900) =     13.801 ms/op
     p(99.9990) =     15.232 ms/op
     p(99.9999) =     15.450 ms/op
    p(100.0000) =     15.450 ms/op


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
# Warmup Iteration   1: 4.763 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.009 ms/op
Iteration   1: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.809 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 12.364 ms/op
                 listUser·p1.00:   12.714 ms/op

Iteration   2: 3.014 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.826 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  10.699 ms/op
                 listUser·p0.9999: 17.033 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   3: 3.001 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.108 ms/op
                 listUser·p0.9999: 10.874 ms/op
                 listUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319483
  mean =      3.002 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 93844 
    [ 2.500,  5.000) = 218206 
    [ 5.000,  7.500) = 6657 
    [ 7.500, 10.000) = 482 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.863 ms/op
     p(99.9900) =     14.307 ms/op
     p(99.9990) =     19.451 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.743 ± 2.063  ops/ms
ClientPb.existUser                       thrpt       3  13.322 ± 1.539  ops/ms
ClientPb.getUser                         thrpt       3  13.105 ± 4.127  ops/ms
ClientPb.listUser                        thrpt       3  10.757 ± 1.996  ops/ms
ClientPb.createUser                       avgt       3   2.457 ± 0.104   ms/op
ClientPb.existUser                        avgt       3   2.366 ± 0.326   ms/op
ClientPb.getUser                          avgt       3   2.462 ± 0.448   ms/op
ClientPb.listUser                         avgt       3   2.974 ± 0.246   ms/op
ClientPb.createUser                     sample  385237   2.490 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.365           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.425           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.469           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.366           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.761           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.893           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.696           ms/op
ClientPb.existUser                      sample  389034   2.465 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.545           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.429           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.025           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.811           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.039           ms/op
ClientPb.getUser                        sample  388367   2.469 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.721           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.273           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.947           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.801           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.450           ms/op
ClientPb.listUser                       sample  319483   3.002 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.809           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.863           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.307           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.218           ms/op
