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
# Warmup Iteration   1: 1.323 ops/ms
# Warmup Iteration   2: 2.882 ops/ms
# Warmup Iteration   3: 5.529 ops/ms
Iteration   1: 5.663 ops/ms
Iteration   2: 5.824 ops/ms
Iteration   3: 5.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.808 ±(99.9%) 2.513 ops/ms [Average]
  (min, avg, max) = (5.663, 5.808, 5.938), stdev = 0.138
  CI (99.9%): [3.295, 8.321] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.729 ops/ms
# Warmup Iteration   2: 5.078 ops/ms
# Warmup Iteration   3: 5.909 ops/ms
Iteration   1: 6.265 ops/ms
Iteration   2: 6.409 ops/ms
Iteration   3: 6.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.413 ±(99.9%) 2.738 ops/ms [Average]
  (min, avg, max) = (6.265, 6.413, 6.566), stdev = 0.150
  CI (99.9%): [3.675, 9.152] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.770 ops/ms
# Warmup Iteration   2: 4.695 ops/ms
# Warmup Iteration   3: 5.665 ops/ms
Iteration   1: 5.984 ops/ms
Iteration   2: 5.682 ops/ms
Iteration   3: 5.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.834 ±(99.9%) 2.763 ops/ms [Average]
  (min, avg, max) = (5.682, 5.834, 5.984), stdev = 0.151
  CI (99.9%): [3.070, 8.597] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.874 ops/ms
# Warmup Iteration   2: 4.468 ops/ms
# Warmup Iteration   3: 4.968 ops/ms
Iteration   1: 5.486 ops/ms
Iteration   2: 5.171 ops/ms
Iteration   3: 5.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.451 ±(99.9%) 4.822 ops/ms [Average]
  (min, avg, max) = (5.171, 5.451, 5.696), stdev = 0.264
  CI (99.9%): [0.629, 10.273] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 15.548 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.257 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.169 ±(99.9%) 0.016 ms/op
Iteration   1: 5.303 ±(99.9%) 0.012 ms/op
Iteration   2: 5.465 ±(99.9%) 0.014 ms/op
Iteration   3: 5.445 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.404 ±(99.9%) 1.612 ms/op [Average]
  (min, avg, max) = (5.303, 5.404, 5.465), stdev = 0.088
  CI (99.9%): [3.792, 7.016] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 13.945 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.926 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.224 ±(99.9%) 0.008 ms/op
Iteration   1: 4.841 ±(99.9%) 0.016 ms/op
Iteration   2: 4.742 ±(99.9%) 0.009 ms/op
Iteration   3: 4.778 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.787 ±(99.9%) 0.916 ms/op [Average]
  (min, avg, max) = (4.742, 4.787, 4.841), stdev = 0.050
  CI (99.9%): [3.871, 5.702] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.613 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 6.507 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.666 ±(99.9%) 0.011 ms/op
Iteration   1: 5.685 ±(99.9%) 0.009 ms/op
Iteration   2: 5.721 ±(99.9%) 0.009 ms/op
Iteration   3: 5.468 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.625 ±(99.9%) 2.492 ms/op [Average]
  (min, avg, max) = (5.468, 5.625, 5.721), stdev = 0.137
  CI (99.9%): [3.133, 8.116] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 17.887 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.910 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.839 ±(99.9%) 0.020 ms/op
Iteration   1: 5.861 ±(99.9%) 0.015 ms/op
Iteration   2: 5.560 ±(99.9%) 0.014 ms/op
Iteration   3: 5.547 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.656 ±(99.9%) 3.241 ms/op [Average]
  (min, avg, max) = (5.547, 5.656, 5.861), stdev = 0.178
  CI (99.9%): [2.415, 8.897] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.882 ±(99.9%) 0.246 ms/op
# Warmup Iteration   2: 6.551 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.647 ±(99.9%) 0.027 ms/op
Iteration   1: 5.381 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.804 ms/op
                 createUser·p0.50:   5.202 ms/op
                 createUser·p0.90:   6.636 ms/op
                 createUser·p0.95:   7.397 ms/op
                 createUser·p0.99:   9.470 ms/op
                 createUser·p0.999:  19.595 ms/op
                 createUser·p0.9999: 22.454 ms/op
                 createUser·p1.00:   24.150 ms/op

Iteration   2: 4.936 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   4.645 ms/op
                 createUser·p0.90:   6.267 ms/op
                 createUser·p0.95:   7.053 ms/op
                 createUser·p0.99:   9.343 ms/op
                 createUser·p0.999:  16.323 ms/op
                 createUser·p0.9999: 20.383 ms/op
                 createUser·p1.00:   21.430 ms/op

Iteration   3: 5.022 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.017 ms/op
                 createUser·p0.50:   4.760 ms/op
                 createUser·p0.90:   6.308 ms/op
                 createUser·p0.95:   7.021 ms/op
                 createUser·p0.99:   8.962 ms/op
                 createUser·p0.999:  22.718 ms/op
                 createUser·p0.9999: 27.087 ms/op
                 createUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 187950
  mean =      5.106 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 92 
    [ 2.500,  5.000) = 104937 
    [ 5.000,  7.500) = 75855 
    [ 7.500, 10.000) = 5877 
    [10.000, 12.500) = 766 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      4.858 ms/op
     p(90.0000) =      6.414 ms/op
     p(95.0000) =      7.168 ms/op
     p(99.0000) =      9.290 ms/op
     p(99.9000) =     17.993 ms/op
     p(99.9900) =     26.483 ms/op
     p(99.9990) =     27.246 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.463 ±(99.9%) 0.230 ms/op
# Warmup Iteration   2: 6.175 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.142 ±(99.9%) 0.018 ms/op
Iteration   1: 5.076 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.138 ms/op
                 existUser·p0.50:   4.817 ms/op
                 existUser·p0.90:   6.373 ms/op
                 existUser·p0.95:   7.190 ms/op
                 existUser·p0.99:   9.290 ms/op
                 existUser·p0.999:  27.251 ms/op
                 existUser·p0.9999: 36.504 ms/op
                 existUser·p1.00:   39.846 ms/op

Iteration   2: 5.385 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.343 ms/op
                 existUser·p0.50:   5.095 ms/op
                 existUser·p0.90:   6.873 ms/op
                 existUser·p0.95:   7.684 ms/op
                 existUser·p0.99:   10.142 ms/op
                 existUser·p0.999:  17.551 ms/op
                 existUser·p0.9999: 32.606 ms/op
                 existUser·p1.00:   33.554 ms/op

Iteration   3: 4.675 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.064 ms/op
                 existUser·p0.50:   4.465 ms/op
                 existUser·p0.90:   5.554 ms/op
                 existUser·p0.95:   6.365 ms/op
                 existUser·p0.99:   9.404 ms/op
                 existUser·p0.999:  16.850 ms/op
                 existUser·p0.9999: 30.507 ms/op
                 existUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 190805
  mean =      5.029 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 118005 
    [ 5.000,  7.500) = 65080 
    [ 7.500, 10.000) = 6099 
    [10.000, 12.500) = 1041 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      2.064 ms/op
     p(50.0000) =      4.743 ms/op
     p(90.0000) =      6.398 ms/op
     p(95.0000) =      7.217 ms/op
     p(99.0000) =      9.535 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     35.575 ms/op
     p(99.9990) =     37.346 ms/op
     p(99.9999) =     39.846 ms/op
    p(100.0000) =     39.846 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.557 ±(99.9%) 0.239 ms/op
# Warmup Iteration   2: 6.348 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 6.573 ±(99.9%) 0.034 ms/op
Iteration   1: 6.019 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   2.671 ms/op
                 getUser·p0.50:   5.489 ms/op
                 getUser·p0.90:   8.208 ms/op
                 getUser·p0.95:   9.978 ms/op
                 getUser·p0.99:   14.025 ms/op
                 getUser·p0.999:  20.775 ms/op
                 getUser·p0.9999: 34.451 ms/op
                 getUser·p1.00:   36.307 ms/op

Iteration   2: 5.758 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.915 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   7.537 ms/op
                 getUser·p0.95:   8.765 ms/op
                 getUser·p0.99:   11.125 ms/op
                 getUser·p0.999:  26.590 ms/op
                 getUser·p0.9999: 35.026 ms/op
                 getUser·p1.00:   36.045 ms/op

Iteration   3: 5.690 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.142 ms/op
                 getUser·p0.50:   5.259 ms/op
                 getUser·p0.90:   7.332 ms/op
                 getUser·p0.95:   8.667 ms/op
                 getUser·p0.99:   12.747 ms/op
                 getUser·p0.999:  29.032 ms/op
                 getUser·p0.9999: 33.370 ms/op
                 getUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 164866
  mean =      5.819 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 54236 
    [ 5.000,  7.500) = 93222 
    [ 7.500, 10.000) = 12133 
    [10.000, 12.500) = 3443 
    [12.500, 15.000) = 1048 
    [15.000, 17.500) = 406 
    [17.500, 20.000) = 158 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 46 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.915 ms/op
     p(50.0000) =      5.366 ms/op
     p(90.0000) =      7.627 ms/op
     p(95.0000) =      9.126 ms/op
     p(99.0000) =     12.829 ms/op
     p(99.9000) =     22.184 ms/op
     p(99.9900) =     34.375 ms/op
     p(99.9990) =     36.264 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.892 ±(99.9%) 0.336 ms/op
# Warmup Iteration   2: 7.177 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 6.292 ±(99.9%) 0.027 ms/op
Iteration   1: 6.801 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   6.373 ms/op
                 listUser·p0.90:   8.749 ms/op
                 listUser·p0.95:   10.240 ms/op
                 listUser·p0.99:   13.861 ms/op
                 listUser·p0.999:  25.428 ms/op
                 listUser·p0.9999: 29.796 ms/op
                 listUser·p1.00:   30.114 ms/op

Iteration   2: 6.217 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   5.816 ms/op
                 listUser·p0.90:   7.553 ms/op
                 listUser·p0.95:   9.093 ms/op
                 listUser·p0.99:   12.517 ms/op
                 listUser·p0.999:  30.034 ms/op
                 listUser·p0.9999: 38.591 ms/op
                 listUser·p1.00:   39.715 ms/op

Iteration   3: 6.632 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.736 ms/op
                 listUser·p0.50:   6.226 ms/op
                 listUser·p0.90:   8.241 ms/op
                 listUser·p0.95:   9.830 ms/op
                 listUser·p0.99:   14.725 ms/op
                 listUser·p0.999:  25.373 ms/op
                 listUser·p0.9999: 30.524 ms/op
                 listUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 146715
  mean =      6.541 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 8925 
    [ 5.000,  7.500) = 115845 
    [ 7.500, 10.000) = 15320 
    [10.000, 12.500) = 4302 
    [12.500, 15.000) = 1376 
    [15.000, 17.500) = 511 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      6.128 ms/op
     p(90.0000) =      8.225 ms/op
     p(95.0000) =      9.765 ms/op
     p(99.0000) =     13.631 ms/op
     p(99.9000) =     26.968 ms/op
     p(99.9900) =     36.960 ms/op
     p(99.9990) =     39.470 ms/op
     p(99.9999) =     39.715 ms/op
    p(100.0000) =     39.715 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.808 ± 2.513  ops/ms
ClientPb.existUser                       thrpt       3   6.413 ± 2.738  ops/ms
ClientPb.getUser                         thrpt       3   5.834 ± 2.763  ops/ms
ClientPb.listUser                        thrpt       3   5.451 ± 4.822  ops/ms
ClientPb.createUser                       avgt       3   5.404 ± 1.612   ms/op
ClientPb.existUser                        avgt       3   4.787 ± 0.916   ms/op
ClientPb.getUser                          avgt       3   5.625 ± 2.492   ms/op
ClientPb.listUser                         avgt       3   5.656 ± 3.241   ms/op
ClientPb.createUser                     sample  187950   5.106 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.235           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.858           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.414           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.168           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.290           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.993           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.483           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.361           ms/op
ClientPb.existUser                      sample  190805   5.029 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.064           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.743           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.398           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.217           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.535           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.400           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.575           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.846           ms/op
ClientPb.getUser                        sample  164866   5.819 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.915           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.366           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.627           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.126           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.829           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.184           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.375           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.307           ms/op
ClientPb.listUser                       sample  146715   6.541 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.846           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.128           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.225           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.765           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.631           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.968           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.960           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.715           ms/op
