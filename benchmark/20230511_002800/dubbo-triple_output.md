# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.133 ops/ms
# Warmup Iteration   2: 6.036 ops/ms
# Warmup Iteration   3: 8.592 ops/ms
Iteration   1: 9.458 ops/ms
Iteration   2: 9.288 ops/ms
Iteration   3: 9.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.315 ±(99.9%) 2.402 ops/ms [Average]
  (min, avg, max) = (9.198, 9.315, 9.458), stdev = 0.132
  CI (99.9%): [6.913, 11.717] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.944 ops/ms
# Warmup Iteration   2: 8.888 ops/ms
# Warmup Iteration   3: 9.321 ops/ms
Iteration   1: 9.452 ops/ms
Iteration   2: 9.762 ops/ms
Iteration   3: 9.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.674 ±(99.9%) 3.532 ops/ms [Average]
  (min, avg, max) = (9.452, 9.674, 9.807), stdev = 0.194
  CI (99.9%): [6.142, 13.206] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.776 ops/ms
# Warmup Iteration   2: 7.986 ops/ms
# Warmup Iteration   3: 9.094 ops/ms
Iteration   1: 9.274 ops/ms
Iteration   2: 9.381 ops/ms
Iteration   3: 9.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.412 ±(99.9%) 2.842 ops/ms [Average]
  (min, avg, max) = (9.274, 9.412, 9.581), stdev = 0.156
  CI (99.9%): [6.569, 12.254] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.890 ops/ms
# Warmup Iteration   2: 7.044 ops/ms
# Warmup Iteration   3: 7.819 ops/ms
Iteration   1: 7.945 ops/ms
Iteration   2: 8.060 ops/ms
Iteration   3: 8.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.053 ±(99.9%) 1.917 ops/ms [Average]
  (min, avg, max) = (7.945, 8.053, 8.155), stdev = 0.105
  CI (99.9%): [6.136, 9.970] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.463 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.008 ms/op
Iteration   1: 3.630 ±(99.9%) 0.004 ms/op
Iteration   2: 3.442 ±(99.9%) 0.007 ms/op
Iteration   3: 3.278 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.450 ±(99.9%) 3.212 ms/op [Average]
  (min, avg, max) = (3.278, 3.450, 3.630), stdev = 0.176
  CI (99.9%): [0.238, 6.662] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.458 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.003 ms/op
Iteration   1: 3.357 ±(99.9%) 0.004 ms/op
Iteration   2: 3.319 ±(99.9%) 0.011 ms/op
Iteration   3: 3.326 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.334 ±(99.9%) 0.369 ms/op [Average]
  (min, avg, max) = (3.319, 3.334, 3.357), stdev = 0.020
  CI (99.9%): [2.964, 3.703] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.526 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.007 ms/op
Iteration   1: 3.491 ±(99.9%) 0.004 ms/op
Iteration   2: 3.461 ±(99.9%) 0.007 ms/op
Iteration   3: 3.434 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.462 ±(99.9%) 0.523 ms/op [Average]
  (min, avg, max) = (3.434, 3.462, 3.491), stdev = 0.029
  CI (99.9%): [2.939, 3.985] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.915 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.398 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.007 ms/op
Iteration   1: 4.170 ±(99.9%) 0.004 ms/op
Iteration   2: 3.983 ±(99.9%) 0.008 ms/op
Iteration   3: 4.084 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.079 ±(99.9%) 1.707 ms/op [Average]
  (min, avg, max) = (3.983, 4.079, 4.170), stdev = 0.094
  CI (99.9%): [2.372, 5.786] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.427 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.167 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.010 ms/op
Iteration   1: 3.421 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  20.506 ms/op
                 createUser·p0.9999: 25.428 ms/op
                 createUser·p1.00:   26.411 ms/op

Iteration   2: 3.413 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.393 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  22.226 ms/op
                 createUser·p0.9999: 28.548 ms/op
                 createUser·p1.00:   28.803 ms/op

Iteration   3: 3.417 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.194 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  18.567 ms/op
                 createUser·p0.9999: 28.038 ms/op
                 createUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280937
  mean =      3.417 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13097 
    [ 2.500,  5.000) = 262555 
    [ 5.000,  7.500) = 4246 
    [ 7.500, 10.000) = 471 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 76 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     18.776 ms/op
     p(99.9900) =     28.017 ms/op
     p(99.9990) =     28.744 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.999 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.478 ±(99.9%) 0.008 ms/op
Iteration   1: 3.452 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   4.050 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   6.529 ms/op
                 existUser·p0.999:  20.920 ms/op
                 existUser·p0.9999: 23.977 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   2: 3.349 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.724 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   5.810 ms/op
                 existUser·p0.999:  23.320 ms/op
                 existUser·p0.9999: 27.882 ms/op
                 existUser·p1.00:   28.869 ms/op

Iteration   3: 3.318 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.382 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  18.468 ms/op
                 existUser·p0.9999: 36.986 ms/op
                 existUser·p1.00:   38.470 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284565
  mean =      3.372 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11901 
    [ 2.500,  5.000) = 265752 
    [ 5.000,  7.500) = 5952 
    [ 7.500, 10.000) = 536 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     20.940 ms/op
     p(99.9900) =     34.734 ms/op
     p(99.9990) =     38.273 ms/op
     p(99.9999) =     38.470 ms/op
    p(100.0000) =     38.470 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.921 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 3.851 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.608 ±(99.9%) 0.011 ms/op
Iteration   1: 3.519 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.493 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  21.924 ms/op
                 getUser·p0.9999: 25.130 ms/op
                 getUser·p1.00:   26.083 ms/op

Iteration   2: 3.521 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  21.954 ms/op
                 getUser·p0.9999: 29.032 ms/op
                 getUser·p1.00:   30.343 ms/op

Iteration   3: 3.519 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.038 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  21.168 ms/op
                 getUser·p0.9999: 30.171 ms/op
                 getUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272643
  mean =      3.520 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6061 
    [ 2.500,  5.000) = 259286 
    [ 5.000,  7.500) = 5815 
    [ 7.500, 10.000) = 971 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.324 ms/op
     p(99.9000) =     21.430 ms/op
     p(99.9900) =     29.295 ms/op
     p(99.9990) =     31.300 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.016 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.528 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.137 ±(99.9%) 0.015 ms/op
Iteration   1: 4.023 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  20.792 ms/op
                 listUser·p0.9999: 24.842 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   2: 4.024 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.511 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  15.991 ms/op
                 listUser·p0.9999: 17.760 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   3: 4.032 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.576 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  18.186 ms/op
                 listUser·p0.9999: 23.298 ms/op
                 listUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238197
  mean =      4.026 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 229818 
    [ 5.000,  7.500) = 6311 
    [ 7.500, 10.000) = 1246 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 252 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     17.426 ms/op
     p(99.9900) =     24.064 ms/op
     p(99.9990) =     25.219 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.315 ± 2.402  ops/ms
ClientPb.existUser                       thrpt       3   9.674 ± 3.532  ops/ms
ClientPb.getUser                         thrpt       3   9.412 ± 2.842  ops/ms
ClientPb.listUser                        thrpt       3   8.053 ± 1.917  ops/ms
ClientPb.createUser                       avgt       3   3.450 ± 3.212   ms/op
ClientPb.existUser                        avgt       3   3.334 ± 0.369   ms/op
ClientPb.getUser                          avgt       3   3.462 ± 0.523   ms/op
ClientPb.listUser                         avgt       3   4.079 ± 1.707   ms/op
ClientPb.createUser                     sample  280937   3.417 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.861           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.857           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.776           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.017           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.803           ms/op
ClientPb.existUser                      sample  284565   3.372 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.899           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.997           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.940           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.734           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.470           ms/op
ClientPb.getUser                        sample  272643   3.520 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.757           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.350           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.324           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.430           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.295           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.882           ms/op
ClientPb.listUser                       sample  238197   4.026 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.286           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.266           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.426           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.064           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.149           ms/op
