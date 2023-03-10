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
# Warmup Iteration   1: 2.495 ops/ms
# Warmup Iteration   2: 6.358 ops/ms
# Warmup Iteration   3: 9.332 ops/ms
Iteration   1: 9.835 ops/ms
Iteration   2: 9.230 ops/ms
Iteration   3: 10.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.803 ±(99.9%) 10.179 ops/ms [Average]
  (min, avg, max) = (9.230, 9.803, 10.345), stdev = 0.558
  CI (99.9%): [≈ 0, 19.982] (assumes normal distribution)


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
# Warmup Iteration   1: 3.522 ops/ms
# Warmup Iteration   2: 9.160 ops/ms
# Warmup Iteration   3: 10.269 ops/ms
Iteration   1: 10.123 ops/ms
Iteration   2: 9.939 ops/ms
Iteration   3: 10.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.225 ±(99.9%) 6.370 ops/ms [Average]
  (min, avg, max) = (9.939, 10.225, 10.614), stdev = 0.349
  CI (99.9%): [3.855, 16.595] (assumes normal distribution)


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
# Warmup Iteration   1: 3.493 ops/ms
# Warmup Iteration   2: 9.386 ops/ms
# Warmup Iteration   3: 9.771 ops/ms
Iteration   1: 9.770 ops/ms
Iteration   2: 9.892 ops/ms
Iteration   3: 10.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.986 ±(99.9%) 5.034 ops/ms [Average]
  (min, avg, max) = (9.770, 9.986, 10.297), stdev = 0.276
  CI (99.9%): [4.952, 15.020] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.349 ops/ms
# Warmup Iteration   2: 7.729 ops/ms
# Warmup Iteration   3: 8.350 ops/ms
Iteration   1: 8.563 ops/ms
Iteration   2: 8.547 ops/ms
Iteration   3: 8.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.624 ±(99.9%) 2.198 ops/ms [Average]
  (min, avg, max) = (8.547, 8.624, 8.763), stdev = 0.120
  CI (99.9%): [6.426, 10.822] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.016 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.529 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.005 ms/op
Iteration   1: 3.198 ±(99.9%) 0.003 ms/op
Iteration   2: 3.199 ±(99.9%) 0.003 ms/op
Iteration   3: 3.301 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.233 ±(99.9%) 1.085 ms/op [Average]
  (min, avg, max) = (3.198, 3.233, 3.301), stdev = 0.059
  CI (99.9%): [2.148, 4.318] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.557 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.003 ms/op
Iteration   1: 3.094 ±(99.9%) 0.004 ms/op
Iteration   2: 3.123 ±(99.9%) 0.007 ms/op
Iteration   3: 3.148 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.122 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (3.094, 3.122, 3.148), stdev = 0.027
  CI (99.9%): [2.633, 3.611] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 8.700 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.425 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.002 ms/op
Iteration   1: 3.161 ±(99.9%) 0.003 ms/op
Iteration   2: 3.150 ±(99.9%) 0.005 ms/op
Iteration   3: 3.356 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.223 ±(99.9%) 2.113 ms/op [Average]
  (min, avg, max) = (3.150, 3.223, 3.356), stdev = 0.116
  CI (99.9%): [1.110, 5.335] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 10.067 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.741 ±(99.9%) 0.010 ms/op
Iteration   1: 3.743 ±(99.9%) 0.005 ms/op
Iteration   2: 3.656 ±(99.9%) 0.010 ms/op
Iteration   3: 3.688 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.695 ±(99.9%) 0.803 ms/op [Average]
  (min, avg, max) = (3.656, 3.695, 3.743), stdev = 0.044
  CI (99.9%): [2.892, 4.498] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.862 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.269 ±(99.9%) 0.010 ms/op
Iteration   1: 3.171 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  10.595 ms/op
                 createUser·p0.9999: 19.363 ms/op
                 createUser·p1.00:   20.251 ms/op

Iteration   2: 3.190 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  19.792 ms/op
                 createUser·p0.9999: 25.230 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   3: 3.237 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.651 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  16.490 ms/op
                 createUser·p0.9999: 18.055 ms/op
                 createUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299896
  mean =      3.199 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17444 
    [ 2.500,  5.000) = 277519 
    [ 5.000,  7.500) = 3833 
    [ 7.500, 10.000) = 637 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 165 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     23.921 ms/op
     p(99.9990) =     25.429 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.934 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.403 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.006 ms/op
Iteration   1: 3.261 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  9.993 ms/op
                 existUser·p0.9999: 18.153 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   2: 3.223 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.696 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  15.750 ms/op
                 existUser·p0.9999: 22.809 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   3: 3.175 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  12.166 ms/op
                 existUser·p0.9999: 23.591 ms/op
                 existUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297858
  mean =      3.219 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26507 
    [ 2.500,  5.000) = 263528 
    [ 5.000,  7.500) = 6787 
    [ 7.500, 10.000) = 576 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     15.434 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     24.544 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 7.569 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.009 ms/op
Iteration   1: 3.247 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  12.084 ms/op
                 getUser·p0.9999: 21.861 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   2: 3.215 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.495 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  10.642 ms/op
                 getUser·p0.9999: 23.269 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   3: 3.235 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  12.979 ms/op
                 getUser·p0.9999: 21.627 ms/op
                 getUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296798
  mean =      3.232 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19837 
    [ 2.500,  5.000) = 269738 
    [ 5.000,  7.500) = 6362 
    [ 7.500, 10.000) = 513 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 169 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     12.976 ms/op
     p(99.9900) =     22.162 ms/op
     p(99.9990) =     23.691 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.575 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.013 ms/op
Iteration   1: 3.773 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   7.017 ms/op
                 listUser·p0.999:  15.403 ms/op
                 listUser·p0.9999: 19.498 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   2: 3.940 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.502 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  13.678 ms/op
                 listUser·p0.9999: 14.891 ms/op
                 listUser·p1.00:   15.008 ms/op

Iteration   3: 3.839 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  12.578 ms/op
                 listUser·p0.9999: 15.439 ms/op
                 listUser·p1.00:   15.548 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249372
  mean =      3.849 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 241261 
    [ 5.000,  7.500) = 6134 
    [ 7.500, 10.000) = 1362 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 274 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     13.642 ms/op
     p(99.9900) =     17.928 ms/op
     p(99.9990) =     19.825 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   9.803 ± 10.179  ops/ms
ClientPb.existUser                       thrpt       3  10.225 ±  6.370  ops/ms
ClientPb.getUser                         thrpt       3   9.986 ±  5.034  ops/ms
ClientPb.listUser                        thrpt       3   8.624 ±  2.198  ops/ms
ClientPb.createUser                       avgt       3   3.233 ±  1.085   ms/op
ClientPb.existUser                        avgt       3   3.122 ±  0.489   ms/op
ClientPb.getUser                          avgt       3   3.223 ±  2.113   ms/op
ClientPb.listUser                         avgt       3   3.695 ±  0.803   ms/op
ClientPb.createUser                     sample  299896   3.199 ±  0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.022            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.109            ms/op
ClientPb.createUser:createUser·p0.90    sample           3.592            ms/op
ClientPb.createUser:createUser·p0.95    sample           3.985            ms/op
ClientPb.createUser:createUser·p0.99    sample           5.571            ms/op
ClientPb.createUser:createUser·p0.999   sample          16.908            ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.921            ms/op
ClientPb.createUser:createUser·p1.00    sample          26.182            ms/op
ClientPb.existUser                      sample  297858   3.219 ±  0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.862            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.478            ms/op
ClientPb.existUser:existUser·p0.95      sample           3.977            ms/op
ClientPb.existUser:existUser·p0.99      sample           5.546            ms/op
ClientPb.existUser:existUser·p0.999     sample          15.434            ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.741            ms/op
ClientPb.existUser:existUser·p1.00      sample          24.740            ms/op
ClientPb.getUser                        sample  296798   3.232 ±  0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.161            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.617            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.026            ms/op
ClientPb.getUser:getUser·p0.99          sample           5.784            ms/op
ClientPb.getUser:getUser·p0.999         sample          12.976            ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.162            ms/op
ClientPb.getUser:getUser·p1.00          sample          23.691            ms/op
ClientPb.listUser                       sample  249372   3.849 ±  0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.502            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.768            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.194            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473            ms/op
ClientPb.listUser:listUser·p0.99        sample           7.070            ms/op
ClientPb.listUser:listUser·p0.999       sample          13.642            ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.928            ms/op
ClientPb.listUser:listUser·p1.00        sample          20.087            ms/op
