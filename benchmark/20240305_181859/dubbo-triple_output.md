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
# Warmup Iteration   1: 5.078 ops/ms
# Warmup Iteration   2: 12.364 ops/ms
# Warmup Iteration   3: 12.561 ops/ms
Iteration   1: 12.805 ops/ms
Iteration   2: 12.872 ops/ms
Iteration   3: 12.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.884 ±(99.9%) 1.555 ops/ms [Average]
  (min, avg, max) = (12.805, 12.884, 12.974), stdev = 0.085
  CI (99.9%): [11.329, 14.439] (assumes normal distribution)


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
# Warmup Iteration   1: 8.385 ops/ms
# Warmup Iteration   2: 13.222 ops/ms
# Warmup Iteration   3: 13.322 ops/ms
Iteration   1: 13.211 ops/ms
Iteration   2: 13.165 ops/ms
Iteration   3: 13.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.178 ±(99.9%) 0.522 ops/ms [Average]
  (min, avg, max) = (13.158, 13.178, 13.211), stdev = 0.029
  CI (99.9%): [12.656, 13.700] (assumes normal distribution)


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
# Warmup Iteration   1: 8.006 ops/ms
# Warmup Iteration   2: 12.742 ops/ms
# Warmup Iteration   3: 12.894 ops/ms
Iteration   1: 12.970 ops/ms
Iteration   2: 12.815 ops/ms
Iteration   3: 12.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.917 ±(99.9%) 1.613 ops/ms [Average]
  (min, avg, max) = (12.815, 12.917, 12.970), stdev = 0.088
  CI (99.9%): [11.303, 14.530] (assumes normal distribution)


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
# Warmup Iteration   1: 6.647 ops/ms
# Warmup Iteration   2: 10.642 ops/ms
# Warmup Iteration   3: 10.693 ops/ms
Iteration   1: 10.746 ops/ms
Iteration   2: 10.773 ops/ms
Iteration   3: 10.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.744 ±(99.9%) 0.541 ops/ms [Average]
  (min, avg, max) = (10.713, 10.744, 10.773), stdev = 0.030
  CI (99.9%): [10.203, 11.285] (assumes normal distribution)


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
# Warmup Iteration   1: 4.145 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.522 ±(99.9%) 0.003 ms/op
Iteration   3: 2.491 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.507 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (2.491, 2.507, 2.522), stdev = 0.016
  CI (99.9%): [2.220, 2.795] (assumes normal distribution)


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
# Warmup Iteration   1: 3.795 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.003 ms/op
Iteration   1: 2.415 ±(99.9%) 0.004 ms/op
Iteration   2: 2.435 ±(99.9%) 0.004 ms/op
Iteration   3: 2.443 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.431 ±(99.9%) 0.266 ms/op [Average]
  (min, avg, max) = (2.415, 2.431, 2.443), stdev = 0.015
  CI (99.9%): [2.164, 2.697] (assumes normal distribution)


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
# Warmup Iteration   1: 3.846 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.003 ms/op
Iteration   1: 2.446 ±(99.9%) 0.003 ms/op
Iteration   2: 2.435 ±(99.9%) 0.003 ms/op
Iteration   3: 2.462 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.447 ±(99.9%) 0.242 ms/op [Average]
  (min, avg, max) = (2.435, 2.447, 2.462), stdev = 0.013
  CI (99.9%): [2.206, 2.689] (assumes normal distribution)


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
# Warmup Iteration   1: 4.634 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.004 ms/op
Iteration   1: 3.022 ±(99.9%) 0.006 ms/op
Iteration   2: 3.003 ±(99.9%) 0.005 ms/op
Iteration   3: 3.017 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.014 ±(99.9%) 0.172 ms/op [Average]
  (min, avg, max) = (3.003, 3.014, 3.022), stdev = 0.009
  CI (99.9%): [2.842, 3.185] (assumes normal distribution)


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
# Warmup Iteration   1: 4.208 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.894 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  8.305 ms/op
                 createUser·p0.9999: 14.598 ms/op
                 createUser·p1.00:   15.598 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  5.895 ms/op
                 createUser·p0.9999: 12.009 ms/op
                 createUser·p1.00:   12.173 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  9.098 ms/op
                 createUser·p0.9999: 10.928 ms/op
                 createUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389264
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 190178 
    [ 2.500,  3.750) = 195418 
    [ 3.750,  5.000) = 2656 
    [ 5.000,  6.250) = 496 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 147 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     12.632 ms/op
     p(99.9990) =     15.358 ms/op
     p(99.9999) =     15.598 ms/op
    p(100.0000) =     15.598 ms/op


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
Iteration   1: 2.414 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.576 ms/op
                 existUser·p0.999:  5.905 ms/op
                 existUser·p0.9999: 13.218 ms/op
                 existUser·p1.00:   13.730 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.017 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  6.160 ms/op
                 existUser·p0.9999: 12.730 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.997 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.809 ms/op
                 existUser·p0.999:  6.169 ms/op
                 existUser·p0.9999: 14.811 ms/op
                 existUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393053
  mean =      2.441 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 196649 
    [ 2.500,  3.750) = 193087 
    [ 3.750,  5.000) = 2482 
    [ 5.000,  6.250) = 389 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 135 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      6.160 ms/op
     p(99.9900) =     13.436 ms/op
     p(99.9990) =     16.843 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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
# Warmup Iteration   1: 3.882 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.006 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  11.122 ms/op
                 getUser·p0.9999: 13.156 ms/op
                 getUser·p1.00:   13.697 ms/op

Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.946 ms/op
                 getUser·p0.999:  9.019 ms/op
                 getUser·p0.9999: 16.237 ms/op
                 getUser·p1.00:   17.433 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.727 ms/op
                 getUser·p0.999:  6.589 ms/op
                 getUser·p0.9999: 11.847 ms/op
                 getUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385512
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 191981 
    [ 2.500,  3.750) = 189006 
    [ 3.750,  5.000) = 3487 
    [ 5.000,  6.250) = 493 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     13.269 ms/op
     p(99.9990) =     16.410 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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
# Warmup Iteration   1: 4.530 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.008 ms/op
Iteration   1: 2.963 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  8.389 ms/op
                 listUser·p0.9999: 13.006 ms/op
                 listUser·p1.00:   15.008 ms/op

Iteration   2: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.879 ms/op
                 listUser·p0.9999: 11.472 ms/op
                 listUser·p1.00:   12.878 ms/op

Iteration   3: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 11.715 ms/op
                 listUser·p1.00:   12.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320910
  mean =      2.989 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 93013 
    [ 2.500,  3.750) = 189961 
    [ 3.750,  5.000) = 31415 
    [ 5.000,  6.250) = 5259 
    [ 6.250,  7.500) = 408 
    [ 7.500,  8.750) = 247 
    [ 8.750, 10.000) = 223 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     12.351 ms/op
     p(99.9990) =     14.027 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.884 ± 1.555  ops/ms
ClientPb.existUser                       thrpt       3  13.178 ± 0.522  ops/ms
ClientPb.getUser                         thrpt       3  12.917 ± 1.613  ops/ms
ClientPb.listUser                        thrpt       3  10.744 ± 0.541  ops/ms
ClientPb.createUser                       avgt       3   2.507 ± 0.287   ms/op
ClientPb.existUser                        avgt       3   2.431 ± 0.266   ms/op
ClientPb.getUser                          avgt       3   2.447 ± 0.242   ms/op
ClientPb.listUser                         avgt       3   3.014 ± 0.172   ms/op
ClientPb.createUser                     sample  389264   2.464 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.891           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.544           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.990           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.028           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.632           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.598           ms/op
ClientPb.existUser                      sample  393053   2.441 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.829           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.160           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.436           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.876           ms/op
ClientPb.getUser                        sample  385512   2.488 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.679           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.995           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.269           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.433           ms/op
ClientPb.listUser                       sample  320910   2.989 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.870           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.456           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.601           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.351           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.008           ms/op
