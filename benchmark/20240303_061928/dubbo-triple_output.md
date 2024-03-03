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
# Warmup Iteration   1: 4.454 ops/ms
# Warmup Iteration   2: 11.910 ops/ms
# Warmup Iteration   3: 12.510 ops/ms
Iteration   1: 12.931 ops/ms
Iteration   2: 13.044 ops/ms
Iteration   3: 12.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.988 ±(99.9%) 1.031 ops/ms [Average]
  (min, avg, max) = (12.931, 12.988, 13.044), stdev = 0.057
  CI (99.9%): [11.957, 14.020] (assumes normal distribution)


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
# Warmup Iteration   1: 7.986 ops/ms
# Warmup Iteration   2: 13.101 ops/ms
# Warmup Iteration   3: 13.388 ops/ms
Iteration   1: 13.387 ops/ms
Iteration   2: 13.407 ops/ms
Iteration   3: 13.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.347 ±(99.9%) 1.580 ops/ms [Average]
  (min, avg, max) = (13.248, 13.347, 13.407), stdev = 0.087
  CI (99.9%): [11.767, 14.927] (assumes normal distribution)


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
# Warmup Iteration   1: 7.709 ops/ms
# Warmup Iteration   2: 12.592 ops/ms
# Warmup Iteration   3: 12.889 ops/ms
Iteration   1: 13.050 ops/ms
Iteration   2: 13.041 ops/ms
Iteration   3: 12.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.987 ±(99.9%) 1.847 ops/ms [Average]
  (min, avg, max) = (12.870, 12.987, 13.050), stdev = 0.101
  CI (99.9%): [11.140, 14.834] (assumes normal distribution)


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
# Warmup Iteration   1: 6.463 ops/ms
# Warmup Iteration   2: 10.472 ops/ms
# Warmup Iteration   3: 10.585 ops/ms
Iteration   1: 10.717 ops/ms
Iteration   2: 10.764 ops/ms
Iteration   3: 10.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.779 ±(99.9%) 1.297 ops/ms [Average]
  (min, avg, max) = (10.717, 10.779, 10.857), stdev = 0.071
  CI (99.9%): [9.482, 12.076] (assumes normal distribution)


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
# Warmup Iteration   1: 3.917 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.004 ms/op
Iteration   1: 2.473 ±(99.9%) 0.005 ms/op
Iteration   2: 2.430 ±(99.9%) 0.003 ms/op
Iteration   3: 2.443 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.449 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (2.430, 2.449, 2.473), stdev = 0.022
  CI (99.9%): [2.051, 2.847] (assumes normal distribution)


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
# Warmup Iteration   1: 3.672 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.371 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.381 ±(99.9%) 0.003 ms/op
Iteration   1: 2.372 ±(99.9%) 0.003 ms/op
Iteration   2: 2.364 ±(99.9%) 0.003 ms/op
Iteration   3: 2.383 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.373 ±(99.9%) 0.181 ms/op [Average]
  (min, avg, max) = (2.364, 2.373, 2.383), stdev = 0.010
  CI (99.9%): [2.192, 2.554] (assumes normal distribution)


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
# Warmup Iteration   1: 4.043 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.004 ms/op
Iteration   1: 2.521 ±(99.9%) 0.004 ms/op
Iteration   2: 2.464 ±(99.9%) 0.003 ms/op
Iteration   3: 2.480 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.488 ±(99.9%) 0.541 ms/op [Average]
  (min, avg, max) = (2.464, 2.488, 2.521), stdev = 0.030
  CI (99.9%): [1.947, 3.029] (assumes normal distribution)


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
# Warmup Iteration   1: 4.904 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
Iteration   1: 3.022 ±(99.9%) 0.005 ms/op
Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
Iteration   3: 3.014 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.020 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (3.014, 3.020, 3.024), stdev = 0.005
  CI (99.9%): [2.921, 3.119] (assumes normal distribution)


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
# Warmup Iteration   1: 4.306 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.624 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   2.503 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  6.359 ms/op
                 createUser·p0.9999: 13.237 ms/op
                 createUser·p1.00:   14.057 ms/op

Iteration   2: 2.464 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  6.263 ms/op
                 createUser·p0.9999: 12.486 ms/op
                 createUser·p1.00:   13.206 ms/op

Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  9.205 ms/op
                 createUser·p0.9999: 10.748 ms/op
                 createUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389974
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 193401 
    [ 2.500,  3.750) = 192375 
    [ 3.750,  5.000) = 3372 
    [ 5.000,  6.250) = 297 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 158 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      8.897 ms/op
     p(99.9900) =     12.911 ms/op
     p(99.9990) =     14.010 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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
# Warmup Iteration   1: 3.700 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.421 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.363 ±(99.9%) 0.005 ms/op
Iteration   1: 2.371 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   2.417 ms/op
                 existUser·p0.90:   2.879 ms/op
                 existUser·p0.95:   2.990 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  5.769 ms/op
                 existUser·p0.9999: 16.663 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   2: 2.403 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  8.749 ms/op
                 existUser·p0.9999: 15.124 ms/op
                 existUser·p1.00:   15.712 ms/op

Iteration   3: 2.384 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.896 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  8.222 ms/op
                 existUser·p0.9999: 12.350 ms/op
                 existUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 401941
  mean =      2.386 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 209470 
    [ 2.500,  3.750) = 189345 
    [ 3.750,  5.000) = 2460 
    [ 5.000,  6.250) = 141 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 128 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.441 ms/op
     p(90.0000) =      2.900 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      3.596 ms/op
     p(99.9000) =      8.282 ms/op
     p(99.9900) =     15.509 ms/op
     p(99.9990) =     17.366 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 3.699 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.006 ms/op
Iteration   1: 2.405 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   2.433 ms/op
                 getUser·p0.90:   2.916 ms/op
                 getUser·p0.95:   3.027 ms/op
                 getUser·p0.99:   3.670 ms/op
                 getUser·p0.999:  6.032 ms/op
                 getUser·p0.9999: 17.577 ms/op
                 getUser·p1.00:   18.317 ms/op

Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.945 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  8.587 ms/op
                 getUser·p0.9999: 12.550 ms/op
                 getUser·p1.00:   13.353 ms/op

Iteration   3: 2.413 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.655 ms/op
                 getUser·p0.50:   2.417 ms/op
                 getUser·p0.90:   2.949 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  5.665 ms/op
                 getUser·p0.9999: 10.551 ms/op
                 getUser·p1.00:   11.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 396862
  mean =      2.417 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 204042 
    [ 2.500,  3.750) = 188228 
    [ 3.750,  5.000) = 3518 
    [ 5.000,  6.250) = 511 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      2.441 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =      7.612 ms/op
     p(99.9900) =     13.773 ms/op
     p(99.9990) =     18.123 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 4.612 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.008 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.008 ms/op
Iteration   1: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.080 ms/op
                 listUser·p0.9999: 11.334 ms/op
                 listUser·p1.00:   13.828 ms/op

Iteration   2: 2.976 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.767 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.732 ms/op
                 listUser·p0.9999: 16.377 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   3: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.406 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 10.971 ms/op
                 listUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321519
  mean =      2.983 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 98266 
    [ 2.500,  3.750) = 184540 
    [ 3.750,  5.000) = 31140 
    [ 5.000,  6.250) = 6108 
    [ 6.250,  7.500) = 668 
    [ 7.500,  8.750) = 167 
    [ 8.750, 10.000) = 274 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     14.953 ms/op
     p(99.9990) =     16.737 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.988 ± 1.031  ops/ms
ClientPb.existUser                       thrpt       3  13.347 ± 1.580  ops/ms
ClientPb.getUser                         thrpt       3  12.987 ± 1.847  ops/ms
ClientPb.listUser                        thrpt       3  10.779 ± 1.297  ops/ms
ClientPb.createUser                       avgt       3   2.449 ± 0.398   ms/op
ClientPb.existUser                        avgt       3   2.373 ± 0.181   ms/op
ClientPb.getUser                          avgt       3   2.488 ± 0.541   ms/op
ClientPb.listUser                         avgt       3   3.020 ± 0.099   ms/op
ClientPb.createUser                     sample  389974   2.459 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.838           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.515           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.986           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.897           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.911           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.057           ms/op
ClientPb.existUser                      sample  401941   2.386 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.864           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.441           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.900           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.282           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.509           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.564           ms/op
ClientPb.getUser                        sample  396862   2.417 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.655           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.441           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.937           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.612           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.773           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.317           ms/op
ClientPb.listUser                       sample  321519   2.983 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.767           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.454           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.953           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.810           ms/op
