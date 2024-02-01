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
# Warmup Iteration   1: 5.273 ops/ms
# Warmup Iteration   2: 12.287 ops/ms
# Warmup Iteration   3: 12.566 ops/ms
Iteration   1: 12.793 ops/ms
Iteration   2: 12.763 ops/ms
Iteration   3: 12.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.805 ±(99.9%) 0.913 ops/ms [Average]
  (min, avg, max) = (12.763, 12.805, 12.861), stdev = 0.050
  CI (99.9%): [11.893, 13.718] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.326 ops/ms
# Warmup Iteration   2: 13.164 ops/ms
# Warmup Iteration   3: 13.140 ops/ms
Iteration   1: 13.009 ops/ms
Iteration   2: 13.165 ops/ms
Iteration   3: 13.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.092 ±(99.9%) 1.425 ops/ms [Average]
  (min, avg, max) = (13.009, 13.092, 13.165), stdev = 0.078
  CI (99.9%): [11.667, 14.517] (assumes normal distribution)


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
# Warmup Iteration   1: 7.858 ops/ms
# Warmup Iteration   2: 12.929 ops/ms
# Warmup Iteration   3: 12.834 ops/ms
Iteration   1: 12.850 ops/ms
Iteration   2: 13.064 ops/ms
Iteration   3: 12.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.968 ±(99.9%) 1.986 ops/ms [Average]
  (min, avg, max) = (12.850, 12.968, 13.064), stdev = 0.109
  CI (99.9%): [10.982, 14.954] (assumes normal distribution)


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
# Warmup Iteration   1: 6.920 ops/ms
# Warmup Iteration   2: 10.697 ops/ms
# Warmup Iteration   3: 10.772 ops/ms
Iteration   1: 10.843 ops/ms
Iteration   2: 10.789 ops/ms
Iteration   3: 10.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.800 ±(99.9%) 0.702 ops/ms [Average]
  (min, avg, max) = (10.768, 10.800, 10.843), stdev = 0.038
  CI (99.9%): [10.098, 11.502] (assumes normal distribution)


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
# Warmup Iteration   1: 3.830 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.004 ms/op
Iteration   1: 2.536 ±(99.9%) 0.003 ms/op
Iteration   2: 2.536 ±(99.9%) 0.004 ms/op
Iteration   3: 2.534 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.535 ±(99.9%) 0.025 ms/op [Average]
  (min, avg, max) = (2.534, 2.535, 2.536), stdev = 0.001
  CI (99.9%): [2.510, 2.560] (assumes normal distribution)


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
# Warmup Iteration   1: 3.724 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.004 ms/op
Iteration   1: 2.448 ±(99.9%) 0.004 ms/op
Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
Iteration   3: 2.452 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.462 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (2.448, 2.462, 2.486), stdev = 0.021
  CI (99.9%): [2.077, 2.847] (assumes normal distribution)


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
# Warmup Iteration   1: 3.873 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.004 ms/op
Iteration   1: 2.498 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.505 ±(99.9%) 0.102 ms/op [Average]
  (min, avg, max) = (2.498, 2.505, 2.509), stdev = 0.006
  CI (99.9%): [2.403, 2.606] (assumes normal distribution)


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
# Warmup Iteration   1: 4.804 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
Iteration   2: 2.986 ±(99.9%) 0.005 ms/op
Iteration   3: 2.993 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.998 ±(99.9%) 0.252 ms/op [Average]
  (min, avg, max) = (2.986, 2.998, 3.013), stdev = 0.014
  CI (99.9%): [2.745, 3.250] (assumes normal distribution)


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
# Warmup Iteration   1: 4.066 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.674 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.006 ms/op
Iteration   1: 2.531 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  11.633 ms/op
                 createUser·p0.9999: 13.691 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   2: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.568 ms/op
                 createUser·p0.999:  9.419 ms/op
                 createUser·p0.9999: 12.222 ms/op
                 createUser·p1.00:   13.189 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.797 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  8.144 ms/op
                 createUser·p0.9999: 10.043 ms/op
                 createUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379875
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 183580 
    [ 2.500,  3.750) = 192854 
    [ 3.750,  5.000) = 2615 
    [ 5.000,  6.250) = 322 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      8.202 ms/op
     p(99.9900) =     13.271 ms/op
     p(99.9990) =     14.113 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 3.610 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
Iteration   1: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   2.433 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.412 ms/op
                 existUser·p0.999:  5.736 ms/op
                 existUser·p0.9999: 14.381 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   2: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   2.421 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  8.337 ms/op
                 existUser·p0.9999: 13.416 ms/op
                 existUser·p1.00:   13.959 ms/op

Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.741 ms/op
                 existUser·p0.999:  7.552 ms/op
                 existUser·p0.9999: 12.059 ms/op
                 existUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394062
  mean =      2.434 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 203099 
    [ 2.500,  3.750) = 187819 
    [ 3.750,  5.000) = 2292 
    [ 5.000,  6.250) = 351 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 130 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      2.437 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.588 ms/op
     p(99.9000) =      8.134 ms/op
     p(99.9900) =     13.445 ms/op
     p(99.9990) =     14.583 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 3.733 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
Iteration   1: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.588 ms/op
                 getUser·p0.999:  6.726 ms/op
                 getUser·p0.9999: 14.196 ms/op
                 getUser·p1.00:   14.893 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  9.658 ms/op
                 getUser·p0.9999: 12.341 ms/op
                 getUser·p1.00:   12.698 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  8.490 ms/op
                 getUser·p0.9999: 10.977 ms/op
                 getUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385500
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 194575 
    [ 2.500,  3.750) = 186319 
    [ 3.750,  5.000) = 3618 
    [ 5.000,  6.250) = 511 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     13.196 ms/op
     p(99.9990) =     14.865 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 4.734 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.008 ms/op
Iteration   1: 2.962 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.962 ms/op
                 listUser·p0.9999: 13.953 ms/op
                 listUser·p1.00:   15.679 ms/op

Iteration   2: 2.956 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  9.351 ms/op
                 listUser·p0.9999: 10.705 ms/op
                 listUser·p1.00:   11.125 ms/op

Iteration   3: 2.953 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.923 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.785 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 10.996 ms/op
                 listUser·p1.00:   11.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324354
  mean =      2.957 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 157 
    [ 1.250,  2.500) = 102324 
    [ 2.500,  3.750) = 187382 
    [ 3.750,  5.000) = 27999 
    [ 5.000,  6.250) = 5325 
    [ 6.250,  7.500) = 484 
    [ 7.500,  8.750) = 161 
    [ 8.750, 10.000) = 304 
    [10.000, 11.250) = 186 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      9.667 ms/op
     p(99.9900) =     11.258 ms/op
     p(99.9990) =     15.606 ms/op
     p(99.9999) =     15.679 ms/op
    p(100.0000) =     15.679 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.805 ± 0.913  ops/ms
ClientPb.existUser                       thrpt       3  13.092 ± 1.425  ops/ms
ClientPb.getUser                         thrpt       3  12.968 ± 1.986  ops/ms
ClientPb.listUser                        thrpt       3  10.800 ± 0.702  ops/ms
ClientPb.createUser                       avgt       3   2.535 ± 0.025   ms/op
ClientPb.existUser                        avgt       3   2.462 ± 0.385   ms/op
ClientPb.getUser                          avgt       3   2.505 ± 0.102   ms/op
ClientPb.listUser                         avgt       3   2.998 ± 0.252   ms/op
ClientPb.createUser                     sample  379875   2.526 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.797           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.202           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.271           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.039           ms/op
ClientPb.existUser                      sample  394062   2.434 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.928           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.437           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.134           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.445           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.713           ms/op
ClientPb.getUser                        sample  385500   2.488 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.913           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.478           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.405           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.196           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.893           ms/op
ClientPb.listUser                       sample  324354   2.957 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.860           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.793           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.667           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.258           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.679           ms/op
