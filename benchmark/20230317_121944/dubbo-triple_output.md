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
# Warmup Iteration   1: 2.549 ops/ms
# Warmup Iteration   2: 5.756 ops/ms
# Warmup Iteration   3: 9.083 ops/ms
Iteration   1: 9.443 ops/ms
Iteration   2: 9.903 ops/ms
Iteration   3: 10.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.835 ±(99.9%) 6.624 ops/ms [Average]
  (min, avg, max) = (9.443, 9.835, 10.160), stdev = 0.363
  CI (99.9%): [3.211, 16.459] (assumes normal distribution)


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
# Warmup Iteration   1: 3.615 ops/ms
# Warmup Iteration   2: 8.935 ops/ms
# Warmup Iteration   3: 9.760 ops/ms
Iteration   1: 10.612 ops/ms
Iteration   2: 10.568 ops/ms
Iteration   3: 10.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.478 ±(99.9%) 3.564 ops/ms [Average]
  (min, avg, max) = (10.254, 10.478, 10.612), stdev = 0.195
  CI (99.9%): [6.914, 14.042] (assumes normal distribution)


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
# Warmup Iteration   1: 3.675 ops/ms
# Warmup Iteration   2: 8.986 ops/ms
# Warmup Iteration   3: 9.705 ops/ms
Iteration   1: 9.612 ops/ms
Iteration   2: 10.116 ops/ms
Iteration   3: 10.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.979 ±(99.9%) 5.860 ops/ms [Average]
  (min, avg, max) = (9.612, 9.979, 10.209), stdev = 0.321
  CI (99.9%): [4.119, 15.839] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.112 ops/ms
# Warmup Iteration   2: 7.570 ops/ms
# Warmup Iteration   3: 8.287 ops/ms
Iteration   1: 8.365 ops/ms
Iteration   2: 8.520 ops/ms
Iteration   3: 8.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.519 ±(99.9%) 2.811 ops/ms [Average]
  (min, avg, max) = (8.365, 8.519, 8.673), stdev = 0.154
  CI (99.9%): [5.708, 11.331] (assumes normal distribution)


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
# Warmup Iteration   1: 7.603 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.560 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.350 ±(99.9%) 0.003 ms/op
Iteration   1: 3.176 ±(99.9%) 0.007 ms/op
Iteration   2: 3.254 ±(99.9%) 0.008 ms/op
Iteration   3: 3.341 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.257 ±(99.9%) 1.510 ms/op [Average]
  (min, avg, max) = (3.176, 3.257, 3.341), stdev = 0.083
  CI (99.9%): [1.747, 4.767] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.685 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.362 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.005 ms/op
Iteration   1: 3.118 ±(99.9%) 0.005 ms/op
Iteration   2: 3.041 ±(99.9%) 0.008 ms/op
Iteration   3: 3.029 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.063 ±(99.9%) 0.884 ms/op [Average]
  (min, avg, max) = (3.029, 3.063, 3.118), stdev = 0.048
  CI (99.9%): [2.179, 3.946] (assumes normal distribution)


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
# Warmup Iteration   1: 7.949 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.794 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.303 ±(99.9%) 0.003 ms/op
Iteration   1: 3.397 ±(99.9%) 0.003 ms/op
Iteration   2: 3.288 ±(99.9%) 0.003 ms/op
Iteration   3: 3.137 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.274 ±(99.9%) 2.383 ms/op [Average]
  (min, avg, max) = (3.137, 3.274, 3.397), stdev = 0.131
  CI (99.9%): [0.892, 5.657] (assumes normal distribution)


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
# Warmup Iteration   1: 9.699 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.111 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.009 ms/op
Iteration   1: 3.698 ±(99.9%) 0.009 ms/op
Iteration   2: 3.718 ±(99.9%) 0.008 ms/op
Iteration   3: 3.690 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.702 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (3.690, 3.702, 3.718), stdev = 0.014
  CI (99.9%): [3.444, 3.961] (assumes normal distribution)


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
# Warmup Iteration   1: 8.064 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.237 ±(99.9%) 0.008 ms/op
Iteration   1: 3.314 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.196 ms/op
                 createUser·p0.999:  13.947 ms/op
                 createUser·p0.9999: 20.950 ms/op
                 createUser·p1.00:   21.561 ms/op

Iteration   2: 3.209 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  9.866 ms/op
                 createUser·p0.9999: 22.610 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   3: 3.155 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.171 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  13.678 ms/op
                 createUser·p0.9999: 20.017 ms/op
                 createUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297691
  mean =      3.225 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11221 
    [ 2.500,  5.000) = 279362 
    [ 5.000,  7.500) = 5976 
    [ 7.500, 10.000) = 611 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     13.587 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     23.303 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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
# Warmup Iteration   1: 6.554 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.405 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.006 ms/op
Iteration   1: 3.196 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  9.083 ms/op
                 existUser·p0.9999: 24.445 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   2: 3.145 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  12.026 ms/op
                 existUser·p0.9999: 25.385 ms/op
                 existUser·p1.00:   25.887 ms/op

Iteration   3: 3.093 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  14.123 ms/op
                 existUser·p0.9999: 24.467 ms/op
                 existUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305188
  mean =      3.144 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15425 
    [ 2.500,  5.000) = 283579 
    [ 5.000,  7.500) = 5392 
    [ 7.500, 10.000) = 418 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     12.599 ms/op
     p(99.9900) =     24.854 ms/op
     p(99.9990) =     25.777 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 7.768 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.318 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.009 ms/op
Iteration   1: 3.361 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.295 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   4.162 ms/op
                 getUser·p0.95:   5.259 ms/op
                 getUser·p0.99:   6.737 ms/op
                 getUser·p0.999:  17.531 ms/op
                 getUser·p0.9999: 20.529 ms/op
                 getUser·p1.00:   25.002 ms/op

Iteration   2: 3.312 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  16.990 ms/op
                 getUser·p0.9999: 22.982 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   3: 3.152 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  10.633 ms/op
                 getUser·p0.9999: 21.103 ms/op
                 getUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293131
  mean =      3.273 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10931 
    [ 2.500,  5.000) = 273522 
    [ 5.000,  7.500) = 7601 
    [ 7.500, 10.000) = 615 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.295 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     15.851 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     23.926 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 9.147 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.183 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.011 ms/op
Iteration   1: 3.803 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  18.273 ms/op
                 listUser·p0.9999: 24.398 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   2: 3.733 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  16.178 ms/op
                 listUser·p0.9999: 21.754 ms/op
                 listUser·p1.00:   22.184 ms/op

Iteration   3: 3.736 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.028 ms/op
                 listUser·p0.9999: 15.237 ms/op
                 listUser·p1.00:   15.286 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255341
  mean =      3.757 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 248426 
    [ 5.000,  7.500) = 5193 
    [ 7.500, 10.000) = 962 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 221 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     15.166 ms/op
     p(99.9900) =     21.673 ms/op
     p(99.9990) =     25.298 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.835 ± 6.624  ops/ms
ClientPb.existUser                       thrpt       3  10.478 ± 3.564  ops/ms
ClientPb.getUser                         thrpt       3   9.979 ± 5.860  ops/ms
ClientPb.listUser                        thrpt       3   8.519 ± 2.811  ops/ms
ClientPb.createUser                       avgt       3   3.257 ± 1.510   ms/op
ClientPb.existUser                        avgt       3   3.063 ± 0.884   ms/op
ClientPb.getUser                          avgt       3   3.274 ± 2.383   ms/op
ClientPb.listUser                         avgt       3   3.702 ± 0.259   ms/op
ClientPb.createUser                     sample  297691   3.225 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.892           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.625           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.808           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.587           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.725           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.691           ms/op
ClientPb.existUser                      sample  305188   3.144 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.642           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.506           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.961           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.546           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.599           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.854           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.887           ms/op
ClientPb.getUser                        sample  293131   3.273 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.295           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.736           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.177           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.851           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.381           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.002           ms/op
ClientPb.listUser                       sample  255341   3.757 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.914           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.650           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.059           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.849           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.166           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.673           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.788           ms/op
