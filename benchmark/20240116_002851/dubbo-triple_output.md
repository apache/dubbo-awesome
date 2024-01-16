# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.957 ops/ms
# Warmup Iteration   2: 12.003 ops/ms
# Warmup Iteration   3: 12.329 ops/ms
Iteration   1: 12.529 ops/ms
Iteration   2: 12.569 ops/ms
Iteration   3: 12.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.633 ±(99.9%) 2.679 ops/ms [Average]
  (min, avg, max) = (12.529, 12.633, 12.801), stdev = 0.147
  CI (99.9%): [9.954, 15.313] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.612 ops/ms
# Warmup Iteration   2: 13.285 ops/ms
# Warmup Iteration   3: 13.313 ops/ms
Iteration   1: 13.224 ops/ms
Iteration   2: 13.359 ops/ms
Iteration   3: 13.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.295 ±(99.9%) 1.237 ops/ms [Average]
  (min, avg, max) = (13.224, 13.295, 13.359), stdev = 0.068
  CI (99.9%): [12.058, 14.532] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.925 ops/ms
# Warmup Iteration   2: 12.610 ops/ms
# Warmup Iteration   3: 12.848 ops/ms
Iteration   1: 12.861 ops/ms
Iteration   2: 12.557 ops/ms
Iteration   3: 12.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.773 ±(99.9%) 3.433 ops/ms [Average]
  (min, avg, max) = (12.557, 12.773, 12.901), stdev = 0.188
  CI (99.9%): [9.340, 16.206] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.490 ops/ms
# Warmup Iteration   2: 10.338 ops/ms
# Warmup Iteration   3: 10.674 ops/ms
Iteration   1: 10.749 ops/ms
Iteration   2: 10.714 ops/ms
Iteration   3: 10.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.758 ±(99.9%) 0.871 ops/ms [Average]
  (min, avg, max) = (10.714, 10.758, 10.809), stdev = 0.048
  CI (99.9%): [9.886, 11.629] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.113 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.501 ±(99.9%) 0.004 ms/op
Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
Iteration   3: 2.508 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.511 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (2.501, 2.511, 2.524), stdev = 0.012
  CI (99.9%): [2.294, 2.729] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.636 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.388 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.423 ±(99.9%) 0.004 ms/op
Iteration   1: 2.374 ±(99.9%) 0.005 ms/op
Iteration   2: 2.429 ±(99.9%) 0.003 ms/op
Iteration   3: 2.380 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.395 ±(99.9%) 0.548 ms/op [Average]
  (min, avg, max) = (2.374, 2.395, 2.429), stdev = 0.030
  CI (99.9%): [1.846, 2.943] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.932 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.004 ms/op
Iteration   1: 2.456 ±(99.9%) 0.004 ms/op
Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
Iteration   3: 2.474 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.462 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (2.455, 2.462, 2.474), stdev = 0.010
  CI (99.9%): [2.272, 2.651] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.850 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.006 ms/op
Iteration   1: 3.034 ±(99.9%) 0.006 ms/op
Iteration   2: 3.020 ±(99.9%) 0.004 ms/op
Iteration   3: 3.035 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.030 ±(99.9%) 0.147 ms/op [Average]
  (min, avg, max) = (3.020, 3.030, 3.035), stdev = 0.008
  CI (99.9%): [2.883, 3.176] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.293 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.006 ms/op
Iteration   1: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  9.063 ms/op
                 createUser·p0.9999: 13.849 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.629 ms/op
                 createUser·p0.999:  7.784 ms/op
                 createUser·p0.9999: 12.815 ms/op
                 createUser·p1.00:   13.451 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.791 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.944 ms/op
                 createUser·p0.999:  9.043 ms/op
                 createUser·p0.9999: 11.950 ms/op
                 createUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385083
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 187504 
    [ 2.500,  3.750) = 193617 
    [ 3.750,  5.000) = 3011 
    [ 5.000,  6.250) = 411 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     13.148 ms/op
     p(99.9990) =     14.158 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.727 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.466 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
Iteration   1: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.021 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.355 ms/op
                 existUser·p0.999:  5.649 ms/op
                 existUser·p0.9999: 13.514 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.423 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.461 ms/op
                 existUser·p0.999:  6.088 ms/op
                 existUser·p0.9999: 10.683 ms/op
                 existUser·p1.00:   11.780 ms/op

Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  8.558 ms/op
                 existUser·p0.9999: 15.871 ms/op
                 existUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394992
  mean =      2.428 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 194614 
    [ 2.500,  3.750) = 197588 
    [ 3.750,  5.000) = 2037 
    [ 5.000,  6.250) = 294 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      3.531 ms/op
     p(99.9000) =      7.111 ms/op
     p(99.9900) =     13.656 ms/op
     p(99.9990) =     16.779 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.978 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.842 ms/op
                 getUser·p0.999:  7.114 ms/op
                 getUser·p0.9999: 14.123 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.828 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.862 ms/op
                 getUser·p0.9999: 12.306 ms/op
                 getUser·p1.00:   13.238 ms/op

Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   4.092 ms/op
                 getUser·p0.999:  6.430 ms/op
                 getUser·p0.9999: 11.272 ms/op
                 getUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388518
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 193816 
    [ 2.500,  3.750) = 189030 
    [ 3.750,  5.000) = 3763 
    [ 5.000,  6.250) = 1384 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =      7.160 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     14.413 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.620 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.008 ms/op
Iteration   1: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.840 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.359 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 11.721 ms/op
                 listUser·p1.00:   12.255 ms/op

Iteration   2: 3.001 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.813 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  8.970 ms/op
                 listUser·p0.9999: 10.465 ms/op
                 listUser·p1.00:   11.452 ms/op

Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  10.371 ms/op
                 listUser·p0.9999: 12.805 ms/op
                 listUser·p1.00:   13.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320001
  mean =      2.997 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 140 
    [ 1.250,  2.500) = 95753 
    [ 2.500,  3.750) = 186560 
    [ 3.750,  5.000) = 30513 
    [ 5.000,  6.250) = 5604 
    [ 6.250,  7.500) = 716 
    [ 7.500,  8.750) = 223 
    [ 8.750, 10.000) = 260 
    [10.000, 11.250) = 164 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     11.944 ms/op
     p(99.9990) =     13.222 ms/op
     p(99.9999) =     13.304 ms/op
    p(100.0000) =     13.304 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.633 ± 2.679  ops/ms
ClientPb.existUser                       thrpt       3  13.295 ± 1.237  ops/ms
ClientPb.getUser                         thrpt       3  12.773 ± 3.433  ops/ms
ClientPb.listUser                        thrpt       3  10.758 ± 0.871  ops/ms
ClientPb.createUser                       avgt       3   2.511 ± 0.217   ms/op
ClientPb.existUser                        avgt       3   2.395 ± 0.548   ms/op
ClientPb.getUser                          avgt       3   2.462 ± 0.189   ms/op
ClientPb.listUser                         avgt       3   3.030 ± 0.147   ms/op
ClientPb.createUser                     sample  385083   2.491 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.791           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.028           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.148           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.303           ms/op
ClientPb.existUser                      sample  394992   2.428 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.854           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.111           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.656           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.941           ms/op
ClientPb.getUser                        sample  388518   2.469 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.828           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.063           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.160           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.337           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.024           ms/op
ClientPb.listUser                       sample  320001   2.997 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.813           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.699           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.944           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.304           ms/op
