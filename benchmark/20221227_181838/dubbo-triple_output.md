# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.204 ops/ms
# Warmup Iteration   2: 5.786 ops/ms
# Warmup Iteration   3: 8.721 ops/ms
Iteration   1: 9.160 ops/ms
Iteration   2: 9.245 ops/ms
Iteration   3: 9.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.299 ±(99.9%) 3.159 ops/ms [Average]
  (min, avg, max) = (9.160, 9.299, 9.493), stdev = 0.173
  CI (99.9%): [6.140, 12.459] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.558 ops/ms
# Warmup Iteration   2: 8.840 ops/ms
# Warmup Iteration   3: 9.741 ops/ms
Iteration   1: 9.687 ops/ms
Iteration   2: 9.710 ops/ms
Iteration   3: 9.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.773 ±(99.9%) 2.335 ops/ms [Average]
  (min, avg, max) = (9.687, 9.773, 9.920), stdev = 0.128
  CI (99.9%): [7.438, 12.107] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.723 ops/ms
# Warmup Iteration   2: 8.413 ops/ms
# Warmup Iteration   3: 8.829 ops/ms
Iteration   1: 9.370 ops/ms
Iteration   2: 9.625 ops/ms
Iteration   3: 9.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.517 ±(99.9%) 2.408 ops/ms [Average]
  (min, avg, max) = (9.370, 9.517, 9.625), stdev = 0.132
  CI (99.9%): [7.110, 11.925] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.680 ops/ms
# Warmup Iteration   2: 7.313 ops/ms
# Warmup Iteration   3: 7.886 ops/ms
Iteration   1: 8.048 ops/ms
Iteration   2: 8.209 ops/ms
Iteration   3: 7.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.051 ±(99.9%) 2.853 ops/ms [Average]
  (min, avg, max) = (7.896, 8.051, 8.209), stdev = 0.156
  CI (99.9%): [5.199, 10.904] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.512 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.867 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.003 ms/op
Iteration   1: 3.486 ±(99.9%) 0.009 ms/op
Iteration   2: 3.306 ±(99.9%) 0.010 ms/op
Iteration   3: 3.353 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.382 ±(99.9%) 1.700 ms/op [Average]
  (min, avg, max) = (3.306, 3.382, 3.486), stdev = 0.093
  CI (99.9%): [1.682, 5.082] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 9.090 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.006 ms/op
Iteration   1: 3.351 ±(99.9%) 0.012 ms/op
Iteration   2: 3.279 ±(99.9%) 0.009 ms/op
Iteration   3: 3.337 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.322 ±(99.9%) 0.694 ms/op [Average]
  (min, avg, max) = (3.279, 3.322, 3.351), stdev = 0.038
  CI (99.9%): [2.629, 4.016] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 11.017 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.608 ±(99.9%) 0.004 ms/op
Iteration   1: 3.530 ±(99.9%) 0.009 ms/op
Iteration   2: 3.423 ±(99.9%) 0.011 ms/op
Iteration   3: 3.373 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.442 ±(99.9%) 1.461 ms/op [Average]
  (min, avg, max) = (3.373, 3.442, 3.530), stdev = 0.080
  CI (99.9%): [1.981, 4.903] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.060 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.410 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.010 ms/op
Iteration   1: 4.122 ±(99.9%) 0.006 ms/op
Iteration   2: 4.126 ±(99.9%) 0.007 ms/op
Iteration   3: 3.928 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.059 ±(99.9%) 2.057 ms/op [Average]
  (min, avg, max) = (3.928, 4.059, 4.126), stdev = 0.113
  CI (99.9%): [2.002, 6.116] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.745 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.472 ±(99.9%) 0.010 ms/op
Iteration   1: 3.319 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.696 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  20.864 ms/op
                 createUser·p0.9999: 23.892 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   2: 3.382 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.546 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  22.622 ms/op
                 createUser·p0.9999: 25.151 ms/op
                 createUser·p1.00:   26.051 ms/op

Iteration   3: 3.484 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.606 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  17.556 ms/op
                 createUser·p0.9999: 25.887 ms/op
                 createUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282607
  mean =      3.394 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16704 
    [ 2.500,  5.000) = 259277 
    [ 5.000,  7.500) = 5381 
    [ 7.500, 10.000) = 751 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 154 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.546 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     19.487 ms/op
     p(99.9900) =     25.657 ms/op
     p(99.9990) =     26.155 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.610 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.467 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.009 ms/op
Iteration   1: 3.253 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.876 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   4.061 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  9.643 ms/op
                 existUser·p0.9999: 21.731 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   2: 3.166 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  9.943 ms/op
                 existUser·p0.9999: 24.667 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   3: 3.297 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   4.063 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  13.974 ms/op
                 existUser·p0.9999: 22.938 ms/op
                 existUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296530
  mean =      3.238 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21214 
    [ 2.500,  5.000) = 269756 
    [ 5.000,  7.500) = 4961 
    [ 7.500, 10.000) = 291 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 151 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     10.532 ms/op
     p(99.9900) =     23.146 ms/op
     p(99.9990) =     24.973 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.092 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.745 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.011 ms/op
Iteration   1: 3.356 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  20.364 ms/op
                 getUser·p0.9999: 23.050 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   2: 3.476 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.567 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   7.236 ms/op
                 getUser·p0.999:  21.946 ms/op
                 getUser·p0.9999: 24.635 ms/op
                 getUser·p1.00:   25.100 ms/op

Iteration   3: 3.435 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.462 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  9.368 ms/op
                 getUser·p0.9999: 23.248 ms/op
                 getUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280406
  mean =      3.422 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8423 
    [ 2.500,  5.000) = 262232 
    [ 5.000,  7.500) = 8309 
    [ 7.500, 10.000) = 1042 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 149 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     14.618 ms/op
     p(99.9900) =     24.213 ms/op
     p(99.9990) =     24.779 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.884 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.013 ms/op
Iteration   1: 3.895 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  19.300 ms/op
                 listUser·p0.9999: 23.009 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   2: 3.961 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  15.681 ms/op
                 listUser·p0.9999: 19.202 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   3: 3.872 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.470 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.762 ms/op
                 listUser·p0.9999: 18.973 ms/op
                 listUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245246
  mean =      3.909 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 238212 
    [ 5.000,  7.500) = 5219 
    [ 7.500, 10.000) = 1011 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.156 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     23.814 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.299 ± 3.159  ops/ms
ClientPb.existUser                       thrpt       3   9.773 ± 2.335  ops/ms
ClientPb.getUser                         thrpt       3   9.517 ± 2.408  ops/ms
ClientPb.listUser                        thrpt       3   8.051 ± 2.853  ops/ms
ClientPb.createUser                       avgt       3   3.382 ± 1.700   ms/op
ClientPb.existUser                        avgt       3   3.322 ± 0.694   ms/op
ClientPb.getUser                          avgt       3   3.442 ± 1.461   ms/op
ClientPb.listUser                         avgt       3   4.059 ± 2.057   ms/op
ClientPb.createUser                     sample  282607   3.394 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.546           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.865           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.487           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.657           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.214           ms/op
ClientPb.existUser                      sample  296530   3.238 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.800           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.494           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.530           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.532           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.146           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.952           ms/op
ClientPb.getUser                        sample  280406   3.422 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.243           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.342           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.840           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.618           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.213           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.100           ms/op
ClientPb.listUser                       sample  245246   3.909 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.405           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.793           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.156           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.811           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.889           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.904           ms/op
