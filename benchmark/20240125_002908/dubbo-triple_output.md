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
# Warmup Iteration   1: 4.936 ops/ms
# Warmup Iteration   2: 11.997 ops/ms
# Warmup Iteration   3: 12.304 ops/ms
Iteration   1: 12.638 ops/ms
Iteration   2: 12.509 ops/ms
Iteration   3: 12.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.589 ±(99.9%) 1.283 ops/ms [Average]
  (min, avg, max) = (12.509, 12.589, 12.638), stdev = 0.070
  CI (99.9%): [11.306, 13.872] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.362 ops/ms
# Warmup Iteration   2: 13.064 ops/ms
# Warmup Iteration   3: 13.210 ops/ms
Iteration   1: 13.307 ops/ms
Iteration   2: 13.283 ops/ms
Iteration   3: 13.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.247 ±(99.9%) 1.547 ops/ms [Average]
  (min, avg, max) = (13.150, 13.247, 13.307), stdev = 0.085
  CI (99.9%): [11.700, 14.794] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.015 ops/ms
# Warmup Iteration   2: 12.533 ops/ms
# Warmup Iteration   3: 12.854 ops/ms
Iteration   1: 12.860 ops/ms
Iteration   2: 12.978 ops/ms
Iteration   3: 12.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.936 ±(99.9%) 1.204 ops/ms [Average]
  (min, avg, max) = (12.860, 12.936, 12.978), stdev = 0.066
  CI (99.9%): [11.732, 14.141] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.457 ops/ms
# Warmup Iteration   2: 10.456 ops/ms
# Warmup Iteration   3: 10.793 ops/ms
Iteration   1: 10.847 ops/ms
Iteration   2: 10.854 ops/ms
Iteration   3: 10.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.832 ±(99.9%) 0.602 ops/ms [Average]
  (min, avg, max) = (10.794, 10.832, 10.854), stdev = 0.033
  CI (99.9%): [10.230, 11.434] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.801 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
Iteration   3: 2.503 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.507 ±(99.9%) 0.077 ms/op [Average]
  (min, avg, max) = (2.503, 2.507, 2.511), stdev = 0.004
  CI (99.9%): [2.430, 2.584] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.708 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.003 ms/op
Iteration   1: 2.429 ±(99.9%) 0.004 ms/op
Iteration   2: 2.417 ±(99.9%) 0.004 ms/op
Iteration   3: 2.437 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.428 ±(99.9%) 0.181 ms/op [Average]
  (min, avg, max) = (2.417, 2.428, 2.437), stdev = 0.010
  CI (99.9%): [2.247, 2.609] (assumes normal distribution)


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.480 ±(99.9%) 0.004 ms/op
Iteration   3: 2.511 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.494 ±(99.9%) 0.278 ms/op [Average]
  (min, avg, max) = (2.480, 2.494, 2.511), stdev = 0.015
  CI (99.9%): [2.216, 2.773] (assumes normal distribution)


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
# Warmup Iteration   1: 4.669 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.005 ms/op
Iteration   2: 3.002 ±(99.9%) 0.006 ms/op
Iteration   3: 3.013 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.005 ±(99.9%) 0.133 ms/op [Average]
  (min, avg, max) = (2.999, 3.005, 3.013), stdev = 0.007
  CI (99.9%): [2.872, 3.137] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.254 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.641 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.006 ms/op
Iteration   1: 2.543 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.668 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  11.116 ms/op
                 createUser·p0.9999: 13.271 ms/op
                 createUser·p1.00:   13.664 ms/op

Iteration   2: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  10.460 ms/op
                 createUser·p0.9999: 12.435 ms/op
                 createUser·p1.00:   12.698 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.920 ms/op
                 createUser·p0.999:  8.755 ms/op
                 createUser·p0.9999: 11.403 ms/op
                 createUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379949
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 184109 
    [ 2.500,  3.750) = 190905 
    [ 3.750,  5.000) = 3409 
    [ 5.000,  6.250) = 959 
    [ 6.250,  7.500) = 104 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 179 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =      8.783 ms/op
     p(99.9900) =     12.861 ms/op
     p(99.9990) =     13.500 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.685 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.461 ms/op
                 existUser·p0.999:  6.709 ms/op
                 existUser·p0.9999: 13.468 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   2: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.816 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  7.841 ms/op
                 existUser·p0.9999: 12.253 ms/op
                 existUser·p1.00:   12.517 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.451 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.644 ms/op
                 existUser·p0.999:  6.038 ms/op
                 existUser·p0.9999: 11.780 ms/op
                 existUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390653
  mean =      2.454 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 194493 
    [ 2.500,  3.750) = 193401 
    [ 3.750,  5.000) = 2047 
    [ 5.000,  6.250) = 245 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.451 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.531 ms/op
     p(99.9000) =      7.217 ms/op
     p(99.9900) =     12.860 ms/op
     p(99.9990) =     13.621 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.918 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
Iteration   1: 2.490 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.499 ms/op
                 getUser·p0.999:  9.743 ms/op
                 getUser·p0.9999: 24.718 ms/op
                 getUser·p1.00:   26.116 ms/op

Iteration   2: 2.511 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  10.267 ms/op
                 getUser·p0.9999: 14.239 ms/op
                 getUser·p1.00:   14.975 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.629 ms/op
                 getUser·p0.999:  6.245 ms/op
                 getUser·p0.9999: 11.502 ms/op
                 getUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384607
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 190485 
    [ 2.500,  5.000) = 192743 
    [ 5.000,  7.500) = 986 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      7.789 ms/op
     p(99.9900) =     14.674 ms/op
     p(99.9990) =     25.647 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.565 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.009 ms/op
Iteration   1: 3.039 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  8.313 ms/op
                 listUser·p0.9999: 11.598 ms/op
                 listUser·p1.00:   11.993 ms/op

Iteration   2: 3.043 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  10.727 ms/op
                 listUser·p0.9999: 20.463 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   3: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.507 ms/op
                 listUser·p0.9999: 10.933 ms/op
                 listUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316001
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 90903 
    [ 2.500,  5.000) = 216946 
    [ 5.000,  7.500) = 7525 
    [ 7.500, 10.000) = 417 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     19.536 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.589 ± 1.283  ops/ms
ClientPb.existUser                       thrpt       3  13.247 ± 1.547  ops/ms
ClientPb.getUser                         thrpt       3  12.936 ± 1.204  ops/ms
ClientPb.listUser                        thrpt       3  10.832 ± 0.602  ops/ms
ClientPb.createUser                       avgt       3   2.507 ± 0.077   ms/op
ClientPb.existUser                        avgt       3   2.428 ± 0.181   ms/op
ClientPb.getUser                          avgt       3   2.494 ± 0.278   ms/op
ClientPb.listUser                         avgt       3   3.005 ± 0.133   ms/op
ClientPb.createUser                     sample  379949   2.524 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.668           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.783           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.861           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.664           ms/op
ClientPb.existUser                      sample  390653   2.454 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.451           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.217           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.860           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.025           ms/op
ClientPb.getUser                        sample  384607   2.494 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.726           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.789           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.674           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.116           ms/op
ClientPb.listUser                       sample  316001   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.900           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.421           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.536           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.332           ms/op
