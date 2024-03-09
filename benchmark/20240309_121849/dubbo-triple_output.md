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
# Warmup Iteration   1: 4.432 ops/ms
# Warmup Iteration   2: 12.234 ops/ms
# Warmup Iteration   3: 12.591 ops/ms
Iteration   1: 12.519 ops/ms
Iteration   2: 12.590 ops/ms
Iteration   3: 12.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.590 ±(99.9%) 1.287 ops/ms [Average]
  (min, avg, max) = (12.519, 12.590, 12.660), stdev = 0.071
  CI (99.9%): [11.303, 13.877] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.720 ops/ms
# Warmup Iteration   2: 13.324 ops/ms
# Warmup Iteration   3: 13.564 ops/ms
Iteration   1: 13.542 ops/ms
Iteration   2: 13.402 ops/ms
Iteration   3: 13.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.375 ±(99.9%) 3.304 ops/ms [Average]
  (min, avg, max) = (13.182, 13.375, 13.542), stdev = 0.181
  CI (99.9%): [10.071, 16.679] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.834 ops/ms
# Warmup Iteration   2: 12.761 ops/ms
# Warmup Iteration   3: 12.772 ops/ms
Iteration   1: 12.907 ops/ms
Iteration   2: 12.814 ops/ms
Iteration   3: 12.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.886 ±(99.9%) 1.167 ops/ms [Average]
  (min, avg, max) = (12.814, 12.886, 12.937), stdev = 0.064
  CI (99.9%): [11.719, 14.053] (assumes normal distribution)


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
# Warmup Iteration   1: 6.888 ops/ms
# Warmup Iteration   2: 10.661 ops/ms
# Warmup Iteration   3: 10.694 ops/ms
Iteration   1: 10.652 ops/ms
Iteration   2: 10.674 ops/ms
Iteration   3: 10.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.645 ±(99.9%) 0.607 ops/ms [Average]
  (min, avg, max) = (10.609, 10.645, 10.674), stdev = 0.033
  CI (99.9%): [10.038, 11.252] (assumes normal distribution)


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
# Warmup Iteration   1: 3.985 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.505 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
Iteration   3: 2.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.493 ±(99.9%) 0.240 ms/op [Average]
  (min, avg, max) = (2.479, 2.493, 2.505), stdev = 0.013
  CI (99.9%): [2.253, 2.733] (assumes normal distribution)


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
# Warmup Iteration   1: 3.592 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.443 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.423 ±(99.9%) 0.003 ms/op
Iteration   1: 2.438 ±(99.9%) 0.004 ms/op
Iteration   2: 2.429 ±(99.9%) 0.004 ms/op
Iteration   3: 2.434 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.433 ±(99.9%) 0.080 ms/op [Average]
  (min, avg, max) = (2.429, 2.433, 2.438), stdev = 0.004
  CI (99.9%): [2.353, 2.514] (assumes normal distribution)


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
# Warmup Iteration   1: 3.866 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.004 ms/op
Iteration   1: 2.434 ±(99.9%) 0.004 ms/op
Iteration   2: 2.466 ±(99.9%) 0.003 ms/op
Iteration   3: 2.436 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.445 ±(99.9%) 0.325 ms/op [Average]
  (min, avg, max) = (2.434, 2.445, 2.466), stdev = 0.018
  CI (99.9%): [2.121, 2.770] (assumes normal distribution)


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
# Warmup Iteration   1: 4.553 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
Iteration   1: 2.990 ±(99.9%) 0.005 ms/op
Iteration   2: 2.997 ±(99.9%) 0.005 ms/op
Iteration   3: 2.999 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.996 ±(99.9%) 0.085 ms/op [Average]
  (min, avg, max) = (2.990, 2.996, 2.999), stdev = 0.005
  CI (99.9%): [2.910, 3.081] (assumes normal distribution)


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
# Warmup Iteration   1: 4.100 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.657 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.006 ms/op
Iteration   1: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.820 ms/op
                 createUser·p0.999:  10.197 ms/op
                 createUser·p0.9999: 14.369 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  9.449 ms/op
                 createUser·p0.9999: 12.440 ms/op
                 createUser·p1.00:   12.976 ms/op

Iteration   3: 2.531 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.018 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   4.084 ms/op
                 createUser·p0.999:  9.355 ms/op
                 createUser·p0.9999: 15.691 ms/op
                 createUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381538
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 185137 
    [ 2.500,  3.750) = 191970 
    [ 3.750,  5.000) = 3377 
    [ 5.000,  6.250) = 505 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      9.370 ms/op
     p(99.9900) =     14.631 ms/op
     p(99.9990) =     16.728 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 3.594 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.406 ±(99.9%) 0.005 ms/op
Iteration   1: 2.438 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  8.158 ms/op
                 existUser·p0.9999: 21.623 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  6.103 ms/op
                 existUser·p0.9999: 13.557 ms/op
                 existUser·p1.00:   15.991 ms/op

Iteration   3: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.890 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.736 ms/op
                 existUser·p0.999:  8.218 ms/op
                 existUser·p0.9999: 14.318 ms/op
                 existUser·p1.00:   14.582 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394159
  mean =      2.433 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 197095 
    [ 2.500,  5.000) = 196078 
    [ 5.000,  7.500) = 580 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      7.984 ms/op
     p(99.9900) =     14.889 ms/op
     p(99.9990) =     21.858 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.510 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
Iteration   1: 2.441 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.673 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.712 ms/op
                 getUser·p0.999:  5.956 ms/op
                 getUser·p0.9999: 13.484 ms/op
                 getUser·p1.00:   13.779 ms/op

Iteration   2: 2.456 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.990 ms/op
                 getUser·p0.999:  7.732 ms/op
                 getUser·p0.9999: 20.741 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   3: 2.423 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.945 ms/op
                 getUser·p0.95:   3.043 ms/op
                 getUser·p0.99:   3.514 ms/op
                 getUser·p0.999:  6.523 ms/op
                 getUser·p0.9999: 11.072 ms/op
                 getUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 393132
  mean =      2.440 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 199258 
    [ 2.500,  5.000) = 193038 
    [ 5.000,  7.500) = 449 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      6.549 ms/op
     p(99.9900) =     13.615 ms/op
     p(99.9990) =     21.470 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 4.659 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.009 ms/op
Iteration   1: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.257 ms/op
                 listUser·p0.9999: 10.750 ms/op
                 listUser·p1.00:   11.846 ms/op

Iteration   2: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 12.965 ms/op
                 listUser·p1.00:   13.517 ms/op

Iteration   3: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.931 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 11.637 ms/op
                 listUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320507
  mean =      2.993 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 194 
    [ 1.250,  2.500) = 94152 
    [ 2.500,  3.750) = 187952 
    [ 3.750,  5.000) = 31132 
    [ 5.000,  6.250) = 5784 
    [ 6.250,  7.500) = 646 
    [ 7.500,  8.750) = 232 
    [ 8.750, 10.000) = 216 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     12.042 ms/op
     p(99.9990) =     13.221 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.590 ± 1.287  ops/ms
ClientPb.existUser                       thrpt       3  13.375 ± 3.304  ops/ms
ClientPb.getUser                         thrpt       3  12.886 ± 1.167  ops/ms
ClientPb.listUser                        thrpt       3  10.645 ± 0.607  ops/ms
ClientPb.createUser                       avgt       3   2.493 ± 0.240   ms/op
ClientPb.existUser                        avgt       3   2.433 ± 0.080   ms/op
ClientPb.getUser                          avgt       3   2.445 ± 0.325   ms/op
ClientPb.listUser                         avgt       3   2.996 ± 0.085   ms/op
ClientPb.createUser                     sample  381538   2.514 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.907           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.370           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.631           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.810           ms/op
ClientPb.existUser                      sample  394159   2.433 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.849           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.984           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.889           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.053           ms/op
ClientPb.getUser                        sample  393132   2.440 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.673           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.466           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.961           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.549           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.615           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.594           ms/op
ClientPb.listUser                       sample  320507   2.993 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.903           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.208           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.042           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.517           ms/op
