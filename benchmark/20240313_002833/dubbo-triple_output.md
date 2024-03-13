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
# Warmup Iteration   1: 4.636 ops/ms
# Warmup Iteration   2: 12.333 ops/ms
# Warmup Iteration   3: 12.468 ops/ms
Iteration   1: 12.861 ops/ms
Iteration   2: 12.888 ops/ms
Iteration   3: 13.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.918 ±(99.9%) 1.402 ops/ms [Average]
  (min, avg, max) = (12.861, 12.918, 13.006), stdev = 0.077
  CI (99.9%): [11.517, 14.320] (assumes normal distribution)


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
# Warmup Iteration   1: 8.718 ops/ms
# Warmup Iteration   2: 13.296 ops/ms
# Warmup Iteration   3: 13.492 ops/ms
Iteration   1: 13.405 ops/ms
Iteration   2: 13.471 ops/ms
Iteration   3: 13.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.366 ±(99.9%) 2.355 ops/ms [Average]
  (min, avg, max) = (13.222, 13.366, 13.471), stdev = 0.129
  CI (99.9%): [11.011, 15.720] (assumes normal distribution)


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
# Warmup Iteration   1: 7.742 ops/ms
# Warmup Iteration   2: 12.972 ops/ms
# Warmup Iteration   3: 13.193 ops/ms
Iteration   1: 13.381 ops/ms
Iteration   2: 13.291 ops/ms
Iteration   3: 13.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.300 ±(99.9%) 1.411 ops/ms [Average]
  (min, avg, max) = (13.227, 13.300, 13.381), stdev = 0.077
  CI (99.9%): [11.889, 14.711] (assumes normal distribution)


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
# Warmup Iteration   1: 6.951 ops/ms
# Warmup Iteration   2: 10.752 ops/ms
# Warmup Iteration   3: 10.972 ops/ms
Iteration   1: 10.921 ops/ms
Iteration   2: 10.853 ops/ms
Iteration   3: 10.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.893 ±(99.9%) 0.644 ops/ms [Average]
  (min, avg, max) = (10.853, 10.893, 10.921), stdev = 0.035
  CI (99.9%): [10.248, 11.537] (assumes normal distribution)


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
# Warmup Iteration   1: 3.775 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.003 ms/op
Iteration   1: 2.412 ±(99.9%) 0.003 ms/op
Iteration   2: 2.442 ±(99.9%) 0.004 ms/op
Iteration   3: 2.416 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.423 ±(99.9%) 0.300 ms/op [Average]
  (min, avg, max) = (2.412, 2.423, 2.442), stdev = 0.016
  CI (99.9%): [2.123, 2.724] (assumes normal distribution)


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
# Warmup Iteration   1: 3.567 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.392 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.352 ±(99.9%) 0.004 ms/op
Iteration   1: 2.357 ±(99.9%) 0.003 ms/op
Iteration   2: 2.382 ±(99.9%) 0.004 ms/op
Iteration   3: 2.373 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.371 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (2.357, 2.371, 2.382), stdev = 0.012
  CI (99.9%): [2.143, 2.598] (assumes normal distribution)


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
# Warmup Iteration   1: 3.752 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.419 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.414 ±(99.9%) 0.004 ms/op
Iteration   1: 2.400 ±(99.9%) 0.004 ms/op
Iteration   2: 2.422 ±(99.9%) 0.003 ms/op
Iteration   3: 2.413 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.411 ±(99.9%) 0.197 ms/op [Average]
  (min, avg, max) = (2.400, 2.411, 2.422), stdev = 0.011
  CI (99.9%): [2.215, 2.608] (assumes normal distribution)


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
# Warmup Iteration   1: 4.533 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.979 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.916 ±(99.9%) 0.005 ms/op
Iteration   1: 2.925 ±(99.9%) 0.005 ms/op
Iteration   2: 2.959 ±(99.9%) 0.005 ms/op
Iteration   3: 2.953 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.946 ±(99.9%) 0.329 ms/op [Average]
  (min, avg, max) = (2.925, 2.946, 2.959), stdev = 0.018
  CI (99.9%): [2.617, 3.274] (assumes normal distribution)


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
# Warmup Iteration   1: 4.051 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
Iteration   1: 2.461 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   4.018 ms/op
                 createUser·p0.999:  8.662 ms/op
                 createUser·p0.9999: 13.976 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   2: 2.448 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   2.966 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  9.306 ms/op
                 createUser·p0.9999: 13.615 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.637 ms/op
                 createUser·p0.999:  9.017 ms/op
                 createUser·p0.9999: 10.960 ms/op
                 createUser·p1.00:   16.171 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 391100
  mean =      2.452 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 193716 
    [ 2.500,  3.750) = 193189 
    [ 3.750,  5.000) = 3077 
    [ 5.000,  6.250) = 519 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     13.615 ms/op
     p(99.9990) =     15.974 ms/op
     p(99.9999) =     16.171 ms/op
    p(100.0000) =     16.171 ms/op


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
# Warmup Iteration   1: 3.531 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.385 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.389 ±(99.9%) 0.005 ms/op
Iteration   1: 2.362 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   2.388 ms/op
                 existUser·p0.90:   2.867 ms/op
                 existUser·p0.95:   2.961 ms/op
                 existUser·p0.99:   3.277 ms/op
                 existUser·p0.999:  5.218 ms/op
                 existUser·p0.9999: 13.713 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   2: 2.377 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.867 ms/op
                 existUser·p0.95:   2.961 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  7.918 ms/op
                 existUser·p0.9999: 12.861 ms/op
                 existUser·p1.00:   13.566 ms/op

Iteration   3: 2.389 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.884 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.858 ms/op
                 existUser·p0.999:  8.864 ms/op
                 existUser·p0.9999: 11.643 ms/op
                 existUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 403617
  mean =      2.376 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 207502 
    [ 2.500,  3.750) = 192924 
    [ 3.750,  5.000) = 2179 
    [ 5.000,  6.250) = 459 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.445 ms/op
     p(90.0000) =      2.871 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =      3.539 ms/op
     p(99.9000) =      8.434 ms/op
     p(99.9900) =     12.960 ms/op
     p(99.9990) =     14.204 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.920 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.439 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.417 ±(99.9%) 0.005 ms/op
Iteration   1: 2.407 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   2.433 ms/op
                 getUser·p0.90:   2.916 ms/op
                 getUser·p0.95:   3.043 ms/op
                 getUser·p0.99:   3.822 ms/op
                 getUser·p0.999:  7.177 ms/op
                 getUser·p0.9999: 13.758 ms/op
                 getUser·p1.00:   14.533 ms/op

Iteration   2: 2.417 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   2.937 ms/op
                 getUser·p0.95:   3.060 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  10.076 ms/op
                 getUser·p0.9999: 11.911 ms/op
                 getUser·p1.00:   12.829 ms/op

Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  6.473 ms/op
                 getUser·p0.9999: 10.599 ms/op
                 getUser·p1.00:   10.879 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 396069
  mean =      2.422 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 203587 
    [ 2.500,  3.750) = 188038 
    [ 3.750,  5.000) = 3256 
    [ 5.000,  6.250) = 597 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 147 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.445 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      8.830 ms/op
     p(99.9900) =     12.983 ms/op
     p(99.9990) =     14.010 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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
# Warmup Iteration   1: 4.455 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.994 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.009 ms/op
Iteration   1: 2.976 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.746 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 11.404 ms/op
                 listUser·p1.00:   12.222 ms/op

Iteration   2: 2.944 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.935 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.277 ms/op
                 listUser·p0.9999: 12.260 ms/op
                 listUser·p1.00:   12.763 ms/op

Iteration   3: 2.951 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.202 ms/op
                 listUser·p0.9999: 10.884 ms/op
                 listUser·p1.00:   11.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324340
  mean =      2.957 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 103893 
    [ 2.500,  3.750) = 182814 
    [ 3.750,  5.000) = 30013 
    [ 5.000,  6.250) = 6258 
    [ 6.250,  7.500) = 545 
    [ 7.500,  8.750) = 221 
    [ 8.750, 10.000) = 218 
    [10.000, 11.250) = 162 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.268 ms/op
     p(99.9900) =     11.651 ms/op
     p(99.9990) =     12.444 ms/op
     p(99.9999) =     12.763 ms/op
    p(100.0000) =     12.763 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.918 ± 1.402  ops/ms
ClientPb.existUser                       thrpt       3  13.366 ± 2.355  ops/ms
ClientPb.getUser                         thrpt       3  13.300 ± 1.411  ops/ms
ClientPb.listUser                        thrpt       3  10.893 ± 0.644  ops/ms
ClientPb.createUser                       avgt       3   2.423 ± 0.300   ms/op
ClientPb.existUser                        avgt       3   2.371 ± 0.228   ms/op
ClientPb.getUser                          avgt       3   2.411 ± 0.197   ms/op
ClientPb.listUser                         avgt       3   2.946 ± 0.329   ms/op
ClientPb.createUser                     sample  391100   2.452 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.881           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.515           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.974           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.044           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.615           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.171           ms/op
ClientPb.existUser                      sample  403617   2.376 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.714           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.445           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.871           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.434           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.960           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.451           ms/op
ClientPb.getUser                        sample  396069   2.422 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.628           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.445           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.941           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.830           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.983           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.533           ms/op
ClientPb.listUser                       sample  324340   2.957 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.746           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.888           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.268           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.651           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.763           ms/op
