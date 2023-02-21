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
# Warmup Iteration   1: 2.655 ops/ms
# Warmup Iteration   2: 6.295 ops/ms
# Warmup Iteration   3: 9.571 ops/ms
Iteration   1: 9.331 ops/ms
Iteration   2: 9.451 ops/ms
Iteration   3: 10.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.598 ±(99.9%) 6.625 ops/ms [Average]
  (min, avg, max) = (9.331, 9.598, 10.011), stdev = 0.363
  CI (99.9%): [2.973, 16.223] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.860 ops/ms
# Warmup Iteration   2: 9.389 ops/ms
# Warmup Iteration   3: 10.197 ops/ms
Iteration   1: 9.953 ops/ms
Iteration   2: 10.109 ops/ms
Iteration   3: 10.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.218 ±(99.9%) 6.060 ops/ms [Average]
  (min, avg, max) = (9.953, 10.218, 10.591), stdev = 0.332
  CI (99.9%): [4.158, 16.278] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.134 ops/ms
# Warmup Iteration   2: 9.196 ops/ms
# Warmup Iteration   3: 9.955 ops/ms
Iteration   1: 10.209 ops/ms
Iteration   2: 9.976 ops/ms
Iteration   3: 10.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.113 ±(99.9%) 2.226 ops/ms [Average]
  (min, avg, max) = (9.976, 10.113, 10.209), stdev = 0.122
  CI (99.9%): [7.887, 12.339] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.610 ops/ms
# Warmup Iteration   2: 7.849 ops/ms
# Warmup Iteration   3: 8.433 ops/ms
Iteration   1: 8.658 ops/ms
Iteration   2: 8.525 ops/ms
Iteration   3: 8.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.619 ±(99.9%) 1.503 ops/ms [Average]
  (min, avg, max) = (8.525, 8.619, 8.675), stdev = 0.082
  CI (99.9%): [7.117, 10.122] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.795 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.006 ms/op
Iteration   1: 3.328 ±(99.9%) 0.003 ms/op
Iteration   2: 3.118 ±(99.9%) 0.003 ms/op
Iteration   3: 3.068 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.171 ±(99.9%) 2.520 ms/op [Average]
  (min, avg, max) = (3.068, 3.171, 3.328), stdev = 0.138
  CI (99.9%): [0.651, 5.691] (assumes normal distribution)


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
# Warmup Iteration   1: 6.949 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.333 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.173 ±(99.9%) 0.004 ms/op
Iteration   1: 3.015 ±(99.9%) 0.008 ms/op
Iteration   2: 3.070 ±(99.9%) 0.009 ms/op
Iteration   3: 3.130 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.072 ±(99.9%) 1.054 ms/op [Average]
  (min, avg, max) = (3.015, 3.072, 3.130), stdev = 0.058
  CI (99.9%): [2.018, 4.125] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.473 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.422 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.448 ±(99.9%) 0.004 ms/op
Iteration   1: 3.092 ±(99.9%) 0.002 ms/op
Iteration   2: 3.174 ±(99.9%) 0.005 ms/op
Iteration   3: 3.166 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.144 ±(99.9%) 0.829 ms/op [Average]
  (min, avg, max) = (3.092, 3.144, 3.174), stdev = 0.045
  CI (99.9%): [2.315, 3.973] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.850 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.747 ±(99.9%) 0.004 ms/op
Iteration   1: 3.683 ±(99.9%) 0.005 ms/op
Iteration   2: 3.642 ±(99.9%) 0.008 ms/op
Iteration   3: 3.704 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.677 ±(99.9%) 0.574 ms/op [Average]
  (min, avg, max) = (3.642, 3.677, 3.704), stdev = 0.031
  CI (99.9%): [3.102, 4.251] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.650 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.314 ±(99.9%) 0.009 ms/op
Iteration   1: 3.157 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.487 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  11.453 ms/op
                 createUser·p0.9999: 20.074 ms/op
                 createUser·p1.00:   20.840 ms/op

Iteration   2: 3.319 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.255 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.423 ms/op
                 createUser·p0.999:  19.484 ms/op
                 createUser·p0.9999: 22.770 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   3: 3.205 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  16.251 ms/op
                 createUser·p0.9999: 19.924 ms/op
                 createUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297432
  mean =      3.226 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21921 
    [ 2.500,  5.000) = 267897 
    [ 5.000,  7.500) = 6708 
    [ 7.500, 10.000) = 489 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 198 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     23.758 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 7.274 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.008 ms/op
Iteration   1: 3.129 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.182 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  9.093 ms/op
                 existUser·p0.9999: 32.786 ms/op
                 existUser·p1.00:   33.358 ms/op

Iteration   2: 3.130 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  9.067 ms/op
                 existUser·p0.9999: 22.359 ms/op
                 existUser·p1.00:   23.429 ms/op

Iteration   3: 3.221 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  13.009 ms/op
                 existUser·p0.9999: 22.741 ms/op
                 existUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303635
  mean =      3.159 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18670 
    [ 2.500,  5.000) = 278886 
    [ 5.000,  7.500) = 5384 
    [ 7.500, 10.000) = 307 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     12.993 ms/op
     p(99.9900) =     31.511 ms/op
     p(99.9990) =     33.160 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


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
# Warmup Iteration   1: 7.676 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.505 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.008 ms/op
Iteration   1: 3.296 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  10.748 ms/op
                 getUser·p0.9999: 20.620 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   2: 3.166 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.217 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  11.403 ms/op
                 getUser·p0.9999: 22.276 ms/op
                 getUser·p1.00:   23.790 ms/op

Iteration   3: 3.284 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.430 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.804 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  9.910 ms/op
                 getUser·p0.9999: 30.863 ms/op
                 getUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295262
  mean =      3.247 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16093 
    [ 2.500,  5.000) = 269824 
    [ 5.000,  7.500) = 8382 
    [ 7.500, 10.000) = 614 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     10.625 ms/op
     p(99.9900) =     25.459 ms/op
     p(99.9990) =     31.855 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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
# Warmup Iteration   1: 9.245 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.012 ms/op
Iteration   1: 3.698 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.798 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.398 ms/op
                 listUser·p0.999:  15.088 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   2: 3.746 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   19.562 ms/op

Iteration   3: 3.769 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.731 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  12.803 ms/op
                 listUser·p0.9999: 15.368 ms/op
                 listUser·p1.00:   15.434 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256693
  mean =      3.737 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 73 
    [ 2.500,  5.000) = 248667 
    [ 5.000,  7.500) = 6003 
    [ 7.500, 10.000) = 1249 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 304 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.731 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     18.940 ms/op
     p(99.9990) =     20.248 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.598 ± 6.625  ops/ms
ClientPb.existUser                       thrpt       3  10.218 ± 6.060  ops/ms
ClientPb.getUser                         thrpt       3  10.113 ± 2.226  ops/ms
ClientPb.listUser                        thrpt       3   8.619 ± 1.503  ops/ms
ClientPb.createUser                       avgt       3   3.171 ± 2.520   ms/op
ClientPb.existUser                        avgt       3   3.072 ± 1.054   ms/op
ClientPb.getUser                          avgt       3   3.144 ± 0.829   ms/op
ClientPb.listUser                         avgt       3   3.677 ± 0.574   ms/op
ClientPb.createUser                     sample  297432   3.226 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.963           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.572           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.087           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.400           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.053           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.855           ms/op
ClientPb.existUser                      sample  303635   3.159 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.100           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.899           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.513           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.993           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.511           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.358           ms/op
ClientPb.getUser                        sample  295262   3.247 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.217           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.645           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.111           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.625           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.459           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.700           ms/op
ClientPb.listUser                       sample  256693   3.737 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.731           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.609           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.047           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.857           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.894           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.940           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.611           ms/op
