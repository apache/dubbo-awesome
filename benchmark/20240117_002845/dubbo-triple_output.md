# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.418 ops/ms
# Warmup Iteration   2: 11.932 ops/ms
# Warmup Iteration   3: 12.285 ops/ms
Iteration   1: 12.353 ops/ms
Iteration   2: 12.541 ops/ms
Iteration   3: 12.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.495 ±(99.9%) 2.305 ops/ms [Average]
  (min, avg, max) = (12.353, 12.495, 12.593), stdev = 0.126
  CI (99.9%): [10.190, 14.800] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.229 ops/ms
# Warmup Iteration   2: 12.943 ops/ms
# Warmup Iteration   3: 12.939 ops/ms
Iteration   1: 13.015 ops/ms
Iteration   2: 13.011 ops/ms
Iteration   3: 12.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.973 ±(99.9%) 1.282 ops/ms [Average]
  (min, avg, max) = (12.892, 12.973, 13.015), stdev = 0.070
  CI (99.9%): [11.691, 14.255] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.602 ops/ms
# Warmup Iteration   2: 12.434 ops/ms
# Warmup Iteration   3: 12.439 ops/ms
Iteration   1: 12.683 ops/ms
Iteration   2: 12.548 ops/ms
Iteration   3: 12.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.578 ±(99.9%) 1.706 ops/ms [Average]
  (min, avg, max) = (12.503, 12.578, 12.683), stdev = 0.094
  CI (99.9%): [10.872, 14.284] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.274 ops/ms
# Warmup Iteration   2: 10.334 ops/ms
# Warmup Iteration   3: 10.542 ops/ms
Iteration   1: 10.466 ops/ms
Iteration   2: 10.535 ops/ms
Iteration   3: 10.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.492 ±(99.9%) 0.685 ops/ms [Average]
  (min, avg, max) = (10.466, 10.492, 10.535), stdev = 0.038
  CI (99.9%): [9.807, 11.176] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.019 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.004 ms/op
Iteration   1: 2.607 ±(99.9%) 0.005 ms/op
Iteration   2: 2.545 ±(99.9%) 0.003 ms/op
Iteration   3: 2.546 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.566 ±(99.9%) 0.652 ms/op [Average]
  (min, avg, max) = (2.545, 2.566, 2.607), stdev = 0.036
  CI (99.9%): [1.914, 3.218] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.672 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.428 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.414 ±(99.9%) 0.004 ms/op
Iteration   1: 2.425 ±(99.9%) 0.003 ms/op
Iteration   2: 2.427 ±(99.9%) 0.003 ms/op
Iteration   3: 2.426 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.426 ±(99.9%) 0.018 ms/op [Average]
  (min, avg, max) = (2.425, 2.426, 2.427), stdev = 0.001
  CI (99.9%): [2.408, 2.444] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.805 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.501 ±(99.9%) 0.004 ms/op
Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
Iteration   3: 2.474 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.502 ±(99.9%) 0.508 ms/op [Average]
  (min, avg, max) = (2.474, 2.502, 2.530), stdev = 0.028
  CI (99.9%): [1.994, 3.009] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.597 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.005 ms/op
Iteration   1: 2.993 ±(99.9%) 0.005 ms/op
Iteration   2: 3.015 ±(99.9%) 0.004 ms/op
Iteration   3: 3.021 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.010 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (2.993, 3.010, 3.021), stdev = 0.015
  CI (99.9%): [2.740, 3.279] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.240 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.651 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.006 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  10.444 ms/op
                 createUser·p0.9999: 14.191 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.564 ms/op
                 createUser·p0.999:  7.096 ms/op
                 createUser·p0.9999: 13.418 ms/op
                 createUser·p1.00:   14.057 ms/op

Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.494 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  9.486 ms/op
                 createUser·p0.9999: 17.760 ms/op
                 createUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383104
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 186375 
    [ 2.500,  5.000) = 195442 
    [ 5.000,  7.500) = 852 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     14.401 ms/op
     p(99.9990) =     20.391 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.876 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
Iteration   1: 2.484 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  5.721 ms/op
                 existUser·p0.9999: 13.781 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.965 ms/op
                 existUser·p0.999:  6.086 ms/op
                 existUser·p0.9999: 13.077 ms/op
                 existUser·p1.00:   13.533 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.554 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.703 ms/op
                 existUser·p0.999:  9.045 ms/op
                 existUser·p0.9999: 12.003 ms/op
                 existUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384796
  mean =      2.492 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 188891 
    [ 2.500,  3.750) = 192008 
    [ 3.750,  5.000) = 2973 
    [ 5.000,  6.250) = 498 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      6.201 ms/op
     p(99.9900) =     13.116 ms/op
     p(99.9990) =     13.971 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.910 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.006 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.666 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.781 ms/op
                 getUser·p0.999:  6.185 ms/op
                 getUser·p0.9999: 13.622 ms/op
                 getUser·p1.00:   14.434 ms/op

Iteration   2: 2.533 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.877 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   3.994 ms/op
                 getUser·p0.999:  5.705 ms/op
                 getUser·p0.9999: 12.162 ms/op
                 getUser·p1.00:   12.943 ms/op

Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.953 ms/op
                 getUser·p0.999:  9.113 ms/op
                 getUser·p0.9999: 12.621 ms/op
                 getUser·p1.00:   13.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380841
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 187913 
    [ 2.500,  3.750) = 187954 
    [ 3.750,  5.000) = 3918 
    [ 5.000,  6.250) = 617 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.908 ms/op
     p(99.9000) =      6.136 ms/op
     p(99.9900) =     13.033 ms/op
     p(99.9990) =     14.257 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.705 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.009 ms/op
Iteration   1: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.044 ms/op
                 listUser·p0.9999: 11.281 ms/op
                 listUser·p1.00:   11.911 ms/op

Iteration   2: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  9.641 ms/op
                 listUser·p0.9999: 10.739 ms/op
                 listUser·p1.00:   11.436 ms/op

Iteration   3: 3.034 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.976 ms/op
                 listUser·p0.9999: 11.624 ms/op
                 listUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315654
  mean =      3.038 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 88370 
    [ 2.500,  3.750) = 186478 
    [ 3.750,  5.000) = 33164 
    [ 5.000,  6.250) = 6202 
    [ 6.250,  7.500) = 628 
    [ 7.500,  8.750) = 228 
    [ 8.750, 10.000) = 239 
    [10.000, 11.250) = 181 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     11.296 ms/op
     p(99.9990) =     12.502 ms/op
     p(99.9999) =     13.255 ms/op
    p(100.0000) =     13.255 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.495 ± 2.305  ops/ms
ClientPb.existUser                       thrpt       3  12.973 ± 1.282  ops/ms
ClientPb.getUser                         thrpt       3  12.578 ± 1.706  ops/ms
ClientPb.listUser                        thrpt       3  10.492 ± 0.685  ops/ms
ClientPb.createUser                       avgt       3   2.566 ± 0.652   ms/op
ClientPb.existUser                        avgt       3   2.426 ± 0.018   ms/op
ClientPb.getUser                          avgt       3   2.502 ± 0.508   ms/op
ClientPb.listUser                         avgt       3   3.010 ± 0.270   ms/op
ClientPb.createUser                     sample  383104   2.503 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.494           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.486           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.401           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.150           ms/op
ClientPb.existUser                      sample  384796   2.492 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.869           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.201           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.116           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.303           ms/op
ClientPb.getUser                        sample  380841   2.518 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.666           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.136           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.033           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.434           ms/op
ClientPb.listUser                       sample  315654   3.038 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.870           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.486           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.296           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.255           ms/op
