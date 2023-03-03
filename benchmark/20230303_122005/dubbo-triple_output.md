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
# Warmup Iteration   1: 2.586 ops/ms
# Warmup Iteration   2: 5.675 ops/ms
# Warmup Iteration   3: 9.524 ops/ms
Iteration   1: 10.087 ops/ms
Iteration   2: 10.284 ops/ms
Iteration   3: 9.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.083 ±(99.9%) 3.698 ops/ms [Average]
  (min, avg, max) = (9.879, 10.083, 10.284), stdev = 0.203
  CI (99.9%): [6.385, 13.781] (assumes normal distribution)


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
# Warmup Iteration   1: 3.717 ops/ms
# Warmup Iteration   2: 9.359 ops/ms
# Warmup Iteration   3: 10.023 ops/ms
Iteration   1: 10.743 ops/ms
Iteration   2: 10.735 ops/ms
Iteration   3: 10.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.710 ±(99.9%) 0.927 ops/ms [Average]
  (min, avg, max) = (10.651, 10.710, 10.743), stdev = 0.051
  CI (99.9%): [9.783, 11.637] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.720 ops/ms
# Warmup Iteration   2: 9.723 ops/ms
# Warmup Iteration   3: 9.667 ops/ms
Iteration   1: 9.997 ops/ms
Iteration   2: 10.316 ops/ms
Iteration   3: 10.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.106 ±(99.9%) 3.327 ops/ms [Average]
  (min, avg, max) = (9.997, 10.106, 10.316), stdev = 0.182
  CI (99.9%): [6.778, 13.433] (assumes normal distribution)


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
# Warmup Iteration   1: 3.485 ops/ms
# Warmup Iteration   2: 8.008 ops/ms
# Warmup Iteration   3: 8.628 ops/ms
Iteration   1: 8.403 ops/ms
Iteration   2: 8.721 ops/ms
Iteration   3: 8.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.599 ±(99.9%) 3.124 ops/ms [Average]
  (min, avg, max) = (8.403, 8.599, 8.721), stdev = 0.171
  CI (99.9%): [5.474, 11.723] (assumes normal distribution)


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
# Warmup Iteration   1: 8.619 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.405 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.237 ±(99.9%) 0.005 ms/op
Iteration   1: 3.212 ±(99.9%) 0.008 ms/op
Iteration   2: 3.176 ±(99.9%) 0.005 ms/op
Iteration   3: 3.193 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.194 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (3.176, 3.194, 3.212), stdev = 0.018
  CI (99.9%): [2.861, 3.526] (assumes normal distribution)


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
# Warmup Iteration   1: 8.087 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.600 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.338 ±(99.9%) 0.004 ms/op
Iteration   1: 3.087 ±(99.9%) 0.006 ms/op
Iteration   2: 3.258 ±(99.9%) 0.006 ms/op
Iteration   3: 3.107 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.151 ±(99.9%) 1.707 ms/op [Average]
  (min, avg, max) = (3.087, 3.151, 3.258), stdev = 0.094
  CI (99.9%): [1.443, 4.858] (assumes normal distribution)


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
# Warmup Iteration   1: 8.088 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.527 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.005 ms/op
Iteration   1: 3.161 ±(99.9%) 0.004 ms/op
Iteration   2: 3.206 ±(99.9%) 0.003 ms/op
Iteration   3: 3.223 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.197 ±(99.9%) 0.584 ms/op [Average]
  (min, avg, max) = (3.161, 3.197, 3.223), stdev = 0.032
  CI (99.9%): [2.613, 3.780] (assumes normal distribution)


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
# Warmup Iteration   1: 9.737 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.236 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.006 ms/op
Iteration   1: 3.592 ±(99.9%) 0.013 ms/op
Iteration   2: 3.743 ±(99.9%) 0.009 ms/op
Iteration   3: 3.614 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.650 ±(99.9%) 1.485 ms/op [Average]
  (min, avg, max) = (3.592, 3.650, 3.743), stdev = 0.081
  CI (99.9%): [2.164, 5.135] (assumes normal distribution)


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
# Warmup Iteration   1: 7.932 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.519 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.314 ±(99.9%) 0.010 ms/op
Iteration   1: 3.116 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.262 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  15.585 ms/op
                 createUser·p0.9999: 20.447 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   2: 3.121 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.273 ms/op
                 createUser·p0.95:   3.596 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  19.974 ms/op
                 createUser·p0.9999: 29.246 ms/op
                 createUser·p1.00:   30.507 ms/op

Iteration   3: 3.083 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.293 ms/op
                 createUser·p0.95:   3.482 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  15.358 ms/op
                 createUser·p0.9999: 23.221 ms/op
                 createUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 308731
  mean =      3.107 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15444 
    [ 2.500,  5.000) = 289310 
    [ 5.000,  7.500) = 3188 
    [ 7.500, 10.000) = 340 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     16.208 ms/op
     p(99.9900) =     27.267 ms/op
     p(99.9990) =     30.272 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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
# Warmup Iteration   1: 6.745 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.417 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
Iteration   1: 3.234 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.286 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  9.404 ms/op
                 existUser·p0.9999: 20.658 ms/op
                 existUser·p1.00:   21.529 ms/op

Iteration   2: 3.130 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.565 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  10.067 ms/op
                 existUser·p0.9999: 26.160 ms/op
                 existUser·p1.00:   27.263 ms/op

Iteration   3: 3.090 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.503 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  13.189 ms/op
                 existUser·p0.9999: 24.860 ms/op
                 existUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304506
  mean =      3.150 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19938 
    [ 2.500,  5.000) = 278284 
    [ 5.000,  7.500) = 5584 
    [ 7.500, 10.000) = 360 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     12.124 ms/op
     p(99.9900) =     25.020 ms/op
     p(99.9990) =     26.999 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 7.293 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.417 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.009 ms/op
Iteration   1: 3.308 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.782 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  20.472 ms/op
                 getUser·p0.9999: 25.657 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   2: 3.193 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.321 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  14.320 ms/op
                 getUser·p0.9999: 20.773 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   3: 3.123 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.580 ms/op
                 getUser·p0.99:   5.992 ms/op
                 getUser·p0.999:  12.495 ms/op
                 getUser·p0.9999: 19.522 ms/op
                 getUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299118
  mean =      3.206 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11336 
    [ 2.500,  5.000) = 279996 
    [ 5.000,  7.500) = 6671 
    [ 7.500, 10.000) = 667 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     16.104 ms/op
     p(99.9900) =     24.576 ms/op
     p(99.9990) =     25.690 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


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
# Warmup Iteration   1: 9.577 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.812 ±(99.9%) 0.011 ms/op
Iteration   1: 3.899 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   8.290 ms/op
                 listUser·p0.999:  15.811 ms/op
                 listUser·p0.9999: 23.750 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   2: 3.765 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.776 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.220 ms/op
                 listUser·p0.999:  15.139 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   3: 3.740 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  12.780 ms/op
                 listUser·p0.9999: 15.106 ms/op
                 listUser·p1.00:   15.221 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252478
  mean =      3.800 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 243409 
    [ 5.000,  7.500) = 6232 
    [ 7.500, 10.000) = 1788 
    [10.000, 12.500) = 410 
    [12.500, 15.000) = 340 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.776 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      7.668 ms/op
     p(99.9000) =     14.885 ms/op
     p(99.9900) =     22.037 ms/op
     p(99.9990) =     24.229 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.083 ± 3.698  ops/ms
ClientPb.existUser                       thrpt       3  10.710 ± 0.927  ops/ms
ClientPb.getUser                         thrpt       3  10.106 ± 3.327  ops/ms
ClientPb.listUser                        thrpt       3   8.599 ± 3.124  ops/ms
ClientPb.createUser                       avgt       3   3.194 ± 0.333   ms/op
ClientPb.existUser                        avgt       3   3.151 ± 1.707   ms/op
ClientPb.getUser                          avgt       3   3.197 ± 0.584   ms/op
ClientPb.listUser                         avgt       3   3.650 ± 1.485   ms/op
ClientPb.createUser                     sample  308731   3.107 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.063           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.576           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.208           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.267           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.507           ms/op
ClientPb.existUser                      sample  304506   3.150 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.286           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.396           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.124           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.020           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.263           ms/op
ClientPb.getUser                        sample  299118   3.206 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.206           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.609           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.300           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.104           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.576           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.690           ms/op
ClientPb.listUser                       sample  252478   3.800 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.776           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.654           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.125           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.668           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.885           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.037           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.379           ms/op
