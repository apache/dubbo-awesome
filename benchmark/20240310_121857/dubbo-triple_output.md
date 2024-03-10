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
# Warmup Iteration   1: 4.889 ops/ms
# Warmup Iteration   2: 12.496 ops/ms
# Warmup Iteration   3: 12.759 ops/ms
Iteration   1: 12.895 ops/ms
Iteration   2: 12.934 ops/ms
Iteration   3: 13.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.962 ±(99.9%) 1.546 ops/ms [Average]
  (min, avg, max) = (12.895, 12.962, 13.057), stdev = 0.085
  CI (99.9%): [11.416, 14.508] (assumes normal distribution)


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
# Warmup Iteration   1: 8.441 ops/ms
# Warmup Iteration   2: 13.369 ops/ms
# Warmup Iteration   3: 13.327 ops/ms
Iteration   1: 13.397 ops/ms
Iteration   2: 13.460 ops/ms
Iteration   3: 13.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.443 ±(99.9%) 0.750 ops/ms [Average]
  (min, avg, max) = (13.397, 13.443, 13.474), stdev = 0.041
  CI (99.9%): [12.694, 14.193] (assumes normal distribution)


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
# Warmup Iteration   1: 7.838 ops/ms
# Warmup Iteration   2: 12.816 ops/ms
# Warmup Iteration   3: 13.146 ops/ms
Iteration   1: 13.126 ops/ms
Iteration   2: 13.029 ops/ms
Iteration   3: 13.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.100 ±(99.9%) 1.135 ops/ms [Average]
  (min, avg, max) = (13.029, 13.100, 13.146), stdev = 0.062
  CI (99.9%): [11.965, 14.235] (assumes normal distribution)


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
# Warmup Iteration   1: 6.719 ops/ms
# Warmup Iteration   2: 10.315 ops/ms
# Warmup Iteration   3: 10.730 ops/ms
Iteration   1: 10.721 ops/ms
Iteration   2: 10.536 ops/ms
Iteration   3: 10.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.667 ±(99.9%) 2.078 ops/ms [Average]
  (min, avg, max) = (10.536, 10.667, 10.744), stdev = 0.114
  CI (99.9%): [8.589, 12.745] (assumes normal distribution)


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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.003 ms/op
Iteration   1: 2.518 ±(99.9%) 0.005 ms/op
Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
Iteration   3: 2.441 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.480 ±(99.9%) 0.701 ms/op [Average]
  (min, avg, max) = (2.441, 2.480, 2.518), stdev = 0.038
  CI (99.9%): [1.778, 3.181] (assumes normal distribution)


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
# Warmup Iteration   1: 3.765 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.431 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.417 ±(99.9%) 0.003 ms/op
Iteration   1: 2.405 ±(99.9%) 0.003 ms/op
Iteration   2: 2.403 ±(99.9%) 0.003 ms/op
Iteration   3: 2.403 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.403 ±(99.9%) 0.023 ms/op [Average]
  (min, avg, max) = (2.403, 2.403, 2.405), stdev = 0.001
  CI (99.9%): [2.380, 2.427] (assumes normal distribution)


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.003 ms/op
Iteration   1: 2.430 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
Iteration   3: 2.462 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.444 ±(99.9%) 0.299 ms/op [Average]
  (min, avg, max) = (2.430, 2.444, 2.462), stdev = 0.016
  CI (99.9%): [2.145, 2.742] (assumes normal distribution)


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
# Warmup Iteration   1: 4.706 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
Iteration   1: 2.981 ±(99.9%) 0.006 ms/op
Iteration   2: 2.989 ±(99.9%) 0.005 ms/op
Iteration   3: 2.971 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.980 ±(99.9%) 0.170 ms/op [Average]
  (min, avg, max) = (2.971, 2.980, 2.989), stdev = 0.009
  CI (99.9%): [2.811, 3.150] (assumes normal distribution)


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
# Warmup Iteration   1: 4.303 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.463 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.575 ms/op
                 createUser·p0.50:   2.490 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  11.468 ms/op
                 createUser·p0.9999: 14.107 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.912 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 16.679 ms/op
                 createUser·p1.00:   17.859 ms/op

Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  9.437 ms/op
                 createUser·p0.9999: 12.501 ms/op
                 createUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389551
  mean =      2.461 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 193662 
    [ 2.500,  3.750) = 190682 
    [ 3.750,  5.000) = 3995 
    [ 5.000,  6.250) = 620 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.953 ms/op
     p(99.9000) =      9.526 ms/op
     p(99.9900) =     14.396 ms/op
     p(99.9990) =     17.541 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 3.544 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.433 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.382 ±(99.9%) 0.005 ms/op
Iteration   1: 2.380 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.879 ms/op
                 existUser·p0.95:   2.982 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  8.814 ms/op
                 existUser·p0.9999: 13.257 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   2: 2.404 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   4.177 ms/op
                 existUser·p0.999:  6.660 ms/op
                 existUser·p0.9999: 11.667 ms/op
                 existUser·p1.00:   12.468 ms/op

Iteration   3: 2.379 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.888 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  6.313 ms/op
                 existUser·p0.9999: 10.142 ms/op
                 existUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 401748
  mean =      2.387 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 207540 
    [ 2.500,  3.750) = 190447 
    [ 3.750,  5.000) = 2790 
    [ 5.000,  6.250) = 448 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 123 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 122 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.445 ms/op
     p(90.0000) =      2.892 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      6.679 ms/op
     p(99.9900) =     12.577 ms/op
     p(99.9990) =     13.500 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 3.936 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.006 ms/op
Iteration   1: 2.435 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   2.953 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  6.446 ms/op
                 getUser·p0.9999: 17.686 ms/op
                 getUser·p1.00:   18.645 ms/op

Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.459 ms/op
                 getUser·p0.9999: 12.219 ms/op
                 getUser·p1.00:   12.550 ms/op

Iteration   3: 2.443 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  6.646 ms/op
                 getUser·p0.9999: 11.205 ms/op
                 getUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 392547
  mean =      2.443 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 198848 
    [ 2.500,  3.750) = 188010 
    [ 3.750,  5.000) = 4477 
    [ 5.000,  6.250) = 707 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      4.059 ms/op
     p(99.9000) =      6.472 ms/op
     p(99.9900) =     17.007 ms/op
     p(99.9990) =     18.158 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 4.785 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.009 ms/op
Iteration   1: 3.011 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.126 ms/op
                 listUser·p0.9999: 10.830 ms/op
                 listUser·p1.00:   12.042 ms/op

Iteration   2: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.864 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  10.519 ms/op
                 listUser·p0.9999: 13.235 ms/op
                 listUser·p1.00:   13.828 ms/op

Iteration   3: 2.983 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.382 ms/op
                 listUser·p0.999:  9.074 ms/op
                 listUser·p0.9999: 10.687 ms/op
                 listUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318734
  mean =      3.010 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 174 
    [ 1.250,  2.500) = 90738 
    [ 2.500,  3.750) = 188356 
    [ 3.750,  5.000) = 32883 
    [ 5.000,  6.250) = 5353 
    [ 6.250,  7.500) = 598 
    [ 7.500,  8.750) = 226 
    [ 8.750, 10.000) = 205 
    [10.000, 11.250) = 138 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.212 ms/op
     p(99.9900) =     12.110 ms/op
     p(99.9990) =     13.730 ms/op
     p(99.9999) =     13.828 ms/op
    p(100.0000) =     13.828 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.962 ± 1.546  ops/ms
ClientPb.existUser                       thrpt       3  13.443 ± 0.750  ops/ms
ClientPb.getUser                         thrpt       3  13.100 ± 1.135  ops/ms
ClientPb.listUser                        thrpt       3  10.667 ± 2.078  ops/ms
ClientPb.createUser                       avgt       3   2.480 ± 0.701   ms/op
ClientPb.existUser                        avgt       3   2.403 ± 0.023   ms/op
ClientPb.getUser                          avgt       3   2.444 ± 0.299   ms/op
ClientPb.listUser                         avgt       3   2.980 ± 0.170   ms/op
ClientPb.createUser                     sample  389551   2.461 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.575           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.507           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.986           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.526           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.396           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.940           ms/op
ClientPb.existUser                      sample  401748   2.387 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.787           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.445           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.892           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.679           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.577           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.205           ms/op
ClientPb.getUser                        sample  392547   2.443 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.924           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.970           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.472           ms/op
ClientPb.getUser:getUser·p0.9999        sample          17.007           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.645           ms/op
ClientPb.listUser                       sample  318734   3.010 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.857           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.212           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.110           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.828           ms/op
