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
# Warmup Iteration   1: 4.429 ops/ms
# Warmup Iteration   2: 11.430 ops/ms
# Warmup Iteration   3: 12.021 ops/ms
Iteration   1: 12.346 ops/ms
Iteration   2: 12.228 ops/ms
Iteration   3: 12.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.325 ±(99.9%) 1.604 ops/ms [Average]
  (min, avg, max) = (12.228, 12.325, 12.400), stdev = 0.088
  CI (99.9%): [10.721, 13.929] (assumes normal distribution)


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
# Warmup Iteration   1: 8.274 ops/ms
# Warmup Iteration   2: 13.329 ops/ms
# Warmup Iteration   3: 13.229 ops/ms
Iteration   1: 13.257 ops/ms
Iteration   2: 13.334 ops/ms
Iteration   3: 13.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.314 ±(99.9%) 0.918 ops/ms [Average]
  (min, avg, max) = (13.257, 13.314, 13.352), stdev = 0.050
  CI (99.9%): [12.396, 14.232] (assumes normal distribution)


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
# Warmup Iteration   1: 7.947 ops/ms
# Warmup Iteration   2: 12.403 ops/ms
# Warmup Iteration   3: 12.518 ops/ms
Iteration   1: 12.714 ops/ms
Iteration   2: 12.849 ops/ms
Iteration   3: 12.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.676 ±(99.9%) 3.562 ops/ms [Average]
  (min, avg, max) = (12.465, 12.676, 12.849), stdev = 0.195
  CI (99.9%): [9.114, 16.238] (assumes normal distribution)


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
# Warmup Iteration   1: 6.728 ops/ms
# Warmup Iteration   2: 10.288 ops/ms
# Warmup Iteration   3: 10.379 ops/ms
Iteration   1: 10.313 ops/ms
Iteration   2: 10.388 ops/ms
Iteration   3: 10.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.346 ±(99.9%) 0.705 ops/ms [Average]
  (min, avg, max) = (10.313, 10.346, 10.388), stdev = 0.039
  CI (99.9%): [9.641, 11.051] (assumes normal distribution)


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
# Warmup Iteration   1: 4.305 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.561 ±(99.9%) 0.003 ms/op
Iteration   1: 2.578 ±(99.9%) 0.004 ms/op
Iteration   2: 2.533 ±(99.9%) 0.004 ms/op
Iteration   3: 2.534 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.548 ±(99.9%) 0.467 ms/op [Average]
  (min, avg, max) = (2.533, 2.548, 2.578), stdev = 0.026
  CI (99.9%): [2.081, 3.015] (assumes normal distribution)


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
# Warmup Iteration   1: 3.717 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.003 ms/op
Iteration   1: 2.433 ±(99.9%) 0.004 ms/op
Iteration   2: 2.434 ±(99.9%) 0.003 ms/op
Iteration   3: 2.416 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.428 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (2.416, 2.428, 2.434), stdev = 0.010
  CI (99.9%): [2.245, 2.611] (assumes normal distribution)


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
# Warmup Iteration   1: 4.026 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.518 ±(99.9%) 0.004 ms/op
Iteration   2: 2.564 ±(99.9%) 0.003 ms/op
Iteration   3: 2.539 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.540 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (2.518, 2.540, 2.564), stdev = 0.023
  CI (99.9%): [2.122, 2.959] (assumes normal distribution)


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
# Warmup Iteration   1: 4.997 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.005 ms/op
Iteration   1: 3.075 ±(99.9%) 0.006 ms/op
Iteration   2: 3.060 ±(99.9%) 0.005 ms/op
Iteration   3: 3.083 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.073 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (3.060, 3.073, 3.083), stdev = 0.012
  CI (99.9%): [2.857, 3.289] (assumes normal distribution)


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.655 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.005 ms/op
Iteration   1: 2.557 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  11.878 ms/op
                 createUser·p0.9999: 17.694 ms/op
                 createUser·p1.00:   18.547 ms/op

Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.478 ms/op
                 createUser·p0.999:  10.142 ms/op
                 createUser·p0.9999: 11.944 ms/op
                 createUser·p1.00:   12.222 ms/op

Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  7.343 ms/op
                 createUser·p0.9999: 11.071 ms/op
                 createUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378887
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 182642 
    [ 2.500,  3.750) = 191695 
    [ 3.750,  5.000) = 3344 
    [ 5.000,  6.250) = 622 
    [ 6.250,  7.500) = 119 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      8.835 ms/op
     p(99.9900) =     15.532 ms/op
     p(99.9990) =     18.333 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 3.795 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
Iteration   1: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  6.448 ms/op
                 existUser·p0.9999: 13.042 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  5.333 ms/op
                 existUser·p0.9999: 12.976 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.834 ms/op
                 existUser·p0.999:  8.958 ms/op
                 existUser·p0.9999: 12.176 ms/op
                 existUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388354
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 191078 
    [ 2.500,  3.750) = 194162 
    [ 3.750,  5.000) = 2383 
    [ 5.000,  6.250) = 315 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 141 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.584 ms/op
     p(99.9000) =      6.241 ms/op
     p(99.9900) =     12.927 ms/op
     p(99.9990) =     13.463 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


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
# Warmup Iteration   1: 3.931 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.006 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.629 ms/op
                 getUser·p0.999:  5.103 ms/op
                 getUser·p0.9999: 13.649 ms/op
                 getUser·p1.00:   14.221 ms/op

Iteration   2: 2.527 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.289 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  6.762 ms/op
                 getUser·p0.9999: 12.222 ms/op
                 getUser·p1.00:   12.763 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.727 ms/op
                 getUser·p0.999:  7.151 ms/op
                 getUser·p0.9999: 14.750 ms/op
                 getUser·p1.00:   15.811 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384728
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 189524 
    [ 2.500,  3.750) = 190123 
    [ 3.750,  5.000) = 3924 
    [ 5.000,  6.250) = 668 
    [ 6.250,  7.500) = 118 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =      6.496 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     15.565 ms/op
     p(99.9999) =     15.811 ms/op
    p(100.0000) =     15.811 ms/op


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
# Warmup Iteration   1: 4.821 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.009 ms/op
Iteration   1: 3.065 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.757 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.865 ms/op
                 listUser·p0.999:  9.236 ms/op
                 listUser·p0.9999: 12.578 ms/op
                 listUser·p1.00:   13.877 ms/op

Iteration   2: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.817 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.988 ms/op
                 listUser·p0.9999: 13.241 ms/op
                 listUser·p1.00:   14.664 ms/op

Iteration   3: 3.026 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.881 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  8.978 ms/op
                 listUser·p0.9999: 10.764 ms/op
                 listUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315346
  mean =      3.041 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 87560 
    [ 2.500,  3.750) = 186877 
    [ 3.750,  5.000) = 32578 
    [ 5.000,  6.250) = 6778 
    [ 6.250,  7.500) = 792 
    [ 7.500,  8.750) = 188 
    [ 8.750, 10.000) = 282 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     12.517 ms/op
     p(99.9990) =     14.249 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.325 ± 1.604  ops/ms
ClientPb.existUser                       thrpt       3  13.314 ± 0.918  ops/ms
ClientPb.getUser                         thrpt       3  12.676 ± 3.562  ops/ms
ClientPb.listUser                        thrpt       3  10.346 ± 0.705  ops/ms
ClientPb.createUser                       avgt       3   2.548 ± 0.467   ms/op
ClientPb.existUser                        avgt       3   2.428 ± 0.183   ms/op
ClientPb.getUser                          avgt       3   2.540 ± 0.419   ms/op
ClientPb.listUser                         avgt       3   3.073 ± 0.216   ms/op
ClientPb.createUser                     sample  378887   2.530 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.859           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.835           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.532           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.547           ms/op
ClientPb.existUser                      sample  388354   2.469 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.813           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.241           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.927           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.697           ms/op
ClientPb.getUser                        sample  384728   2.493 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.745           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.496           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.763           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.811           ms/op
ClientPb.listUser                       sample  315346   3.041 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.757           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.982           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.710           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.517           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.664           ms/op
