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
# Warmup Iteration   1: 4.774 ops/ms
# Warmup Iteration   2: 12.147 ops/ms
# Warmup Iteration   3: 12.445 ops/ms
Iteration   1: 12.382 ops/ms
Iteration   2: 12.671 ops/ms
Iteration   3: 12.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.582 ±(99.9%) 3.159 ops/ms [Average]
  (min, avg, max) = (12.382, 12.582, 12.692), stdev = 0.173
  CI (99.9%): [9.422, 15.741] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.901 ops/ms
# Warmup Iteration   2: 12.957 ops/ms
# Warmup Iteration   3: 13.019 ops/ms
Iteration   1: 13.237 ops/ms
Iteration   2: 13.302 ops/ms
Iteration   3: 13.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.266 ±(99.9%) 0.610 ops/ms [Average]
  (min, avg, max) = (13.237, 13.266, 13.302), stdev = 0.033
  CI (99.9%): [12.656, 13.876] (assumes normal distribution)


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
# Warmup Iteration   1: 8.081 ops/ms
# Warmup Iteration   2: 12.707 ops/ms
# Warmup Iteration   3: 13.060 ops/ms
Iteration   1: 13.279 ops/ms
Iteration   2: 13.429 ops/ms
Iteration   3: 13.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.372 ±(99.9%) 1.486 ops/ms [Average]
  (min, avg, max) = (13.279, 13.372, 13.429), stdev = 0.081
  CI (99.9%): [11.886, 14.858] (assumes normal distribution)


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
# Warmup Iteration   1: 7.030 ops/ms
# Warmup Iteration   2: 10.619 ops/ms
# Warmup Iteration   3: 10.841 ops/ms
Iteration   1: 10.887 ops/ms
Iteration   2: 10.851 ops/ms
Iteration   3: 10.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.872 ±(99.9%) 0.338 ops/ms [Average]
  (min, avg, max) = (10.851, 10.872, 10.887), stdev = 0.019
  CI (99.9%): [10.534, 11.209] (assumes normal distribution)


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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.003 ms/op
Iteration   1: 2.481 ±(99.9%) 0.004 ms/op
Iteration   2: 2.442 ±(99.9%) 0.004 ms/op
Iteration   3: 2.447 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.457 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (2.442, 2.457, 2.481), stdev = 0.021
  CI (99.9%): [2.069, 2.845] (assumes normal distribution)


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
# Warmup Iteration   1: 3.641 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.395 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.384 ±(99.9%) 0.003 ms/op
Iteration   1: 2.375 ±(99.9%) 0.003 ms/op
Iteration   2: 2.373 ±(99.9%) 0.003 ms/op
Iteration   3: 2.377 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.375 ±(99.9%) 0.040 ms/op [Average]
  (min, avg, max) = (2.373, 2.375, 2.377), stdev = 0.002
  CI (99.9%): [2.335, 2.415] (assumes normal distribution)


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
# Warmup Iteration   1: 3.796 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.003 ms/op
Iteration   1: 2.441 ±(99.9%) 0.004 ms/op
Iteration   2: 2.444 ±(99.9%) 0.004 ms/op
Iteration   3: 2.436 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.441 ±(99.9%) 0.074 ms/op [Average]
  (min, avg, max) = (2.436, 2.441, 2.444), stdev = 0.004
  CI (99.9%): [2.367, 2.514] (assumes normal distribution)


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
# Warmup Iteration   1: 4.550 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.007 ms/op
Iteration   1: 2.974 ±(99.9%) 0.005 ms/op
Iteration   2: 2.989 ±(99.9%) 0.005 ms/op
Iteration   3: 2.990 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.985 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (2.974, 2.985, 2.990), stdev = 0.009
  CI (99.9%): [2.820, 3.149] (assumes normal distribution)


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
# Warmup Iteration   1: 4.022 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.647 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.609 ms/op
                 createUser·p0.999:  6.229 ms/op
                 createUser·p0.9999: 13.582 ms/op
                 createUser·p1.00:   14.434 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.654 ms/op
                 createUser·p0.999:  9.771 ms/op
                 createUser·p0.9999: 12.603 ms/op
                 createUser·p1.00:   12.993 ms/op

Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   4.059 ms/op
                 createUser·p0.999:  8.815 ms/op
                 createUser·p0.9999: 10.340 ms/op
                 createUser·p1.00:   13.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389034
  mean =      2.465 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 189451 
    [ 2.500,  3.750) = 195610 
    [ 3.750,  5.000) = 2904 
    [ 5.000,  6.250) = 483 
    [ 6.250,  7.500) = 101 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 130 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     12.993 ms/op
     p(99.9990) =     14.245 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


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
# Warmup Iteration   1: 3.734 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.410 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.404 ±(99.9%) 0.005 ms/op
Iteration   1: 2.416 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.736 ms/op
                 existUser·p0.999:  7.663 ms/op
                 existUser·p0.9999: 13.730 ms/op
                 existUser·p1.00:   14.483 ms/op

Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  6.610 ms/op
                 existUser·p0.9999: 13.615 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   3: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  5.703 ms/op
                 existUser·p0.9999: 13.504 ms/op
                 existUser·p1.00:   14.991 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395326
  mean =      2.426 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 198779 
    [ 2.500,  3.750) = 192318 
    [ 3.750,  5.000) = 3177 
    [ 5.000,  6.250) = 583 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      6.117 ms/op
     p(99.9900) =     13.697 ms/op
     p(99.9990) =     14.484 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.006 ms/op
Iteration   1: 2.430 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.957 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   3.596 ms/op
                 getUser·p0.999:  7.413 ms/op
                 getUser·p0.9999: 13.055 ms/op
                 getUser·p1.00:   13.730 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   4.096 ms/op
                 getUser·p0.999:  6.853 ms/op
                 getUser·p0.9999: 13.392 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   3: 2.433 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   2.437 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  5.449 ms/op
                 getUser·p0.9999: 13.971 ms/op
                 getUser·p1.00:   14.418 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 392290
  mean =      2.445 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 199740 
    [ 2.500,  3.750) = 188273 
    [ 3.750,  5.000) = 3264 
    [ 5.000,  6.250) = 485 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      6.817 ms/op
     p(99.9900) =     13.382 ms/op
     p(99.9990) =     14.249 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


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
# Warmup Iteration   1: 4.728 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.009 ms/op
Iteration   1: 2.961 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.816 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  8.831 ms/op
                 listUser·p0.9999: 10.112 ms/op
                 listUser·p1.00:   10.945 ms/op

Iteration   2: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.852 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.732 ms/op
                 listUser·p0.9999: 11.670 ms/op
                 listUser·p1.00:   12.354 ms/op

Iteration   3: 2.951 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.757 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 11.078 ms/op
                 listUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323534
  mean =      2.964 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 152 
    [ 1.250,  2.500) = 101777 
    [ 2.500,  3.750) = 183969 
    [ 3.750,  5.000) = 30346 
    [ 5.000,  6.250) = 5974 
    [ 6.250,  7.500) = 649 
    [ 7.500,  8.750) = 215 
    [ 8.750, 10.000) = 298 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     11.125 ms/op
     p(99.9990) =     11.989 ms/op
     p(99.9999) =     12.354 ms/op
    p(100.0000) =     12.354 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.582 ± 3.159  ops/ms
ClientPb.existUser                       thrpt       3  13.266 ± 0.610  ops/ms
ClientPb.getUser                         thrpt       3  13.372 ± 1.486  ops/ms
ClientPb.listUser                        thrpt       3  10.872 ± 0.338  ops/ms
ClientPb.createUser                       avgt       3   2.457 ± 0.388   ms/op
ClientPb.existUser                        avgt       3   2.375 ± 0.040   ms/op
ClientPb.getUser                          avgt       3   2.441 ± 0.074   ms/op
ClientPb.listUser                         avgt       3   2.985 ± 0.164   ms/op
ClientPb.createUser                     sample  389034   2.465 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.776           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.986           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.756           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.191           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.993           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.434           ms/op
ClientPb.existUser                      sample  395326   2.426 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.881           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.117           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.697           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.991           ms/op
ClientPb.getUser                        sample  392290   2.445 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.778           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.462           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.982           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.817           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.382           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.451           ms/op
ClientPb.listUser                       sample  323534   2.964 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.757           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.241           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.125           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.354           ms/op
