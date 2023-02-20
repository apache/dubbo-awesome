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
# Warmup Iteration   1: 2.743 ops/ms
# Warmup Iteration   2: 6.834 ops/ms
# Warmup Iteration   3: 9.355 ops/ms
Iteration   1: 9.751 ops/ms
Iteration   2: 10.469 ops/ms
Iteration   3: 9.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.060 ±(99.9%) 6.738 ops/ms [Average]
  (min, avg, max) = (9.751, 10.060, 10.469), stdev = 0.369
  CI (99.9%): [3.322, 16.798] (assumes normal distribution)


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
# Warmup Iteration   1: 3.577 ops/ms
# Warmup Iteration   2: 9.189 ops/ms
# Warmup Iteration   3: 10.139 ops/ms
Iteration   1: 10.178 ops/ms
Iteration   2: 10.506 ops/ms
Iteration   3: 10.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.279 ±(99.9%) 3.595 ops/ms [Average]
  (min, avg, max) = (10.154, 10.279, 10.506), stdev = 0.197
  CI (99.9%): [6.685, 13.874] (assumes normal distribution)


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
# Warmup Iteration   1: 3.739 ops/ms
# Warmup Iteration   2: 9.126 ops/ms
# Warmup Iteration   3: 10.084 ops/ms
Iteration   1: 10.011 ops/ms
Iteration   2: 9.982 ops/ms
Iteration   3: 10.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.061 ±(99.9%) 2.060 ops/ms [Average]
  (min, avg, max) = (9.982, 10.061, 10.191), stdev = 0.113
  CI (99.9%): [8.001, 12.122] (assumes normal distribution)


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
# Warmup Iteration   1: 3.468 ops/ms
# Warmup Iteration   2: 7.892 ops/ms
# Warmup Iteration   3: 8.557 ops/ms
Iteration   1: 8.629 ops/ms
Iteration   2: 8.524 ops/ms
Iteration   3: 8.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.550 ±(99.9%) 1.282 ops/ms [Average]
  (min, avg, max) = (8.495, 8.550, 8.629), stdev = 0.070
  CI (99.9%): [7.268, 9.832] (assumes normal distribution)


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
# Warmup Iteration   1: 8.484 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.466 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.006 ms/op
Iteration   1: 3.231 ±(99.9%) 0.008 ms/op
Iteration   2: 3.239 ±(99.9%) 0.008 ms/op
Iteration   3: 3.193 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.221 ±(99.9%) 0.452 ms/op [Average]
  (min, avg, max) = (3.193, 3.221, 3.239), stdev = 0.025
  CI (99.9%): [2.769, 3.673] (assumes normal distribution)


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
# Warmup Iteration   1: 7.165 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.299 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.003 ms/op
Iteration   1: 3.139 ±(99.9%) 0.005 ms/op
Iteration   2: 3.189 ±(99.9%) 0.009 ms/op
Iteration   3: 3.129 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.152 ±(99.9%) 0.582 ms/op [Average]
  (min, avg, max) = (3.129, 3.152, 3.189), stdev = 0.032
  CI (99.9%): [2.570, 3.734] (assumes normal distribution)


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
# Warmup Iteration   1: 7.360 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.584 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.004 ms/op
Iteration   1: 3.286 ±(99.9%) 0.007 ms/op
Iteration   2: 3.190 ±(99.9%) 0.002 ms/op
Iteration   3: 3.142 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.206 ±(99.9%) 1.336 ms/op [Average]
  (min, avg, max) = (3.142, 3.206, 3.286), stdev = 0.073
  CI (99.9%): [1.871, 4.542] (assumes normal distribution)


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
# Warmup Iteration   1: 8.201 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.996 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.005 ms/op
Iteration   1: 3.757 ±(99.9%) 0.008 ms/op
Iteration   2: 3.740 ±(99.9%) 0.006 ms/op
Iteration   3: 3.884 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.793 ±(99.9%) 1.437 ms/op [Average]
  (min, avg, max) = (3.740, 3.793, 3.884), stdev = 0.079
  CI (99.9%): [2.356, 5.231] (assumes normal distribution)


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
# Warmup Iteration   1: 7.917 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.008 ms/op
Iteration   1: 3.146 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  18.726 ms/op
                 createUser·p0.9999: 31.359 ms/op
                 createUser·p1.00:   37.028 ms/op

Iteration   2: 3.120 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.554 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  11.698 ms/op
                 createUser·p0.9999: 23.396 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   3: 3.213 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  16.220 ms/op
                 createUser·p0.9999: 18.910 ms/op
                 createUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303587
  mean =      3.159 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18444 
    [ 2.500,  5.000) = 279311 
    [ 5.000,  7.500) = 5150 
    [ 7.500, 10.000) = 252 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 181 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.836 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     16.463 ms/op
     p(99.9900) =     23.417 ms/op
     p(99.9990) =     31.749 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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
# Warmup Iteration   1: 7.512 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.396 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.007 ms/op
Iteration   1: 3.396 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   6.103 ms/op
                 existUser·p0.99:   7.384 ms/op
                 existUser·p0.999:  18.311 ms/op
                 existUser·p0.9999: 21.553 ms/op
                 existUser·p1.00:   23.429 ms/op

Iteration   2: 3.025 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  13.222 ms/op
                 existUser·p0.9999: 22.413 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   3: 3.084 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.466 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  15.159 ms/op
                 existUser·p0.9999: 21.491 ms/op
                 existUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303726
  mean =      3.160 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21594 
    [ 2.500,  5.000) = 270840 
    [ 5.000,  7.500) = 9714 
    [ 7.500, 10.000) = 792 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 169 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.466 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     16.074 ms/op
     p(99.9900) =     22.237 ms/op
     p(99.9990) =     22.834 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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
# Warmup Iteration   1: 7.908 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.505 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.009 ms/op
Iteration   1: 3.302 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  16.418 ms/op
                 getUser·p0.9999: 18.885 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   2: 3.210 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  8.673 ms/op
                 getUser·p0.9999: 23.530 ms/op
                 getUser·p1.00:   24.969 ms/op

Iteration   3: 3.136 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.214 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  9.847 ms/op
                 getUser·p0.9999: 23.661 ms/op
                 getUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298337
  mean =      3.215 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11733 
    [ 2.500,  5.000) = 277719 
    [ 5.000,  7.500) = 8225 
    [ 7.500, 10.000) = 336 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.979 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     15.215 ms/op
     p(99.9900) =     22.976 ms/op
     p(99.9990) =     24.124 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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
# Warmup Iteration   1: 8.281 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.013 ms/op
Iteration   1: 3.776 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  14.442 ms/op
                 listUser·p0.9999: 24.775 ms/op
                 listUser·p1.00:   25.133 ms/op

Iteration   2: 3.723 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.825 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  13.615 ms/op
                 listUser·p0.9999: 16.974 ms/op
                 listUser·p1.00:   17.138 ms/op

Iteration   3: 3.872 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.436 ms/op
                 listUser·p0.999:  13.337 ms/op
                 listUser·p0.9999: 14.442 ms/op
                 listUser·p1.00:   14.565 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253254
  mean =      3.790 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 116 
    [ 2.500,  5.000) = 245360 
    [ 5.000,  7.500) = 5945 
    [ 7.500, 10.000) = 1137 
    [10.000, 12.500) = 277 
    [12.500, 15.000) = 312 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     13.906 ms/op
     p(99.9900) =     23.484 ms/op
     p(99.9990) =     25.050 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.060 ± 6.738  ops/ms
ClientPb.existUser                       thrpt       3  10.279 ± 3.595  ops/ms
ClientPb.getUser                         thrpt       3  10.061 ± 2.060  ops/ms
ClientPb.listUser                        thrpt       3   8.550 ± 1.282  ops/ms
ClientPb.createUser                       avgt       3   3.221 ± 0.452   ms/op
ClientPb.existUser                        avgt       3   3.152 ± 0.582   ms/op
ClientPb.getUser                          avgt       3   3.206 ± 1.336   ms/op
ClientPb.listUser                         avgt       3   3.793 ± 1.437   ms/op
ClientPb.createUser                     sample  303587   3.159 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.286           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.498           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.836           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.463           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.417           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.028           ms/op
ClientPb.existUser                      sample  303726   3.160 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.466           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.194           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.504           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.074           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.237           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.429           ms/op
ClientPb.getUser                        sample  298337   3.215 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.979           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.559           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.005           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.215           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.976           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.969           ms/op
ClientPb.listUser                       sample  253254   3.790 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.909           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.711           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.162           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.947           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.906           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.484           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.133           ms/op
