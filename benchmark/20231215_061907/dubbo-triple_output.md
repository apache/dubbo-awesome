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
# Warmup Iteration   1: 5.510 ops/ms
# Warmup Iteration   2: 12.495 ops/ms
# Warmup Iteration   3: 12.633 ops/ms
Iteration   1: 12.868 ops/ms
Iteration   2: 13.139 ops/ms
Iteration   3: 13.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.034 ±(99.9%) 2.645 ops/ms [Average]
  (min, avg, max) = (12.868, 13.034, 13.139), stdev = 0.145
  CI (99.9%): [10.388, 15.679] (assumes normal distribution)


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
# Warmup Iteration   1: 8.422 ops/ms
# Warmup Iteration   2: 13.287 ops/ms
# Warmup Iteration   3: 13.288 ops/ms
Iteration   1: 13.166 ops/ms
Iteration   2: 13.279 ops/ms
Iteration   3: 13.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.238 ±(99.9%) 1.143 ops/ms [Average]
  (min, avg, max) = (13.166, 13.238, 13.279), stdev = 0.063
  CI (99.9%): [12.095, 14.382] (assumes normal distribution)


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
# Warmup Iteration   1: 7.722 ops/ms
# Warmup Iteration   2: 12.775 ops/ms
# Warmup Iteration   3: 12.907 ops/ms
Iteration   1: 13.016 ops/ms
Iteration   2: 13.023 ops/ms
Iteration   3: 12.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.972 ±(99.9%) 1.490 ops/ms [Average]
  (min, avg, max) = (12.878, 12.972, 13.023), stdev = 0.082
  CI (99.9%): [11.482, 14.462] (assumes normal distribution)


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
# Warmup Iteration   1: 6.767 ops/ms
# Warmup Iteration   2: 10.770 ops/ms
# Warmup Iteration   3: 10.617 ops/ms
Iteration   1: 10.891 ops/ms
Iteration   2: 10.831 ops/ms
Iteration   3: 10.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.862 ±(99.9%) 0.550 ops/ms [Average]
  (min, avg, max) = (10.831, 10.862, 10.891), stdev = 0.030
  CI (99.9%): [10.312, 11.412] (assumes normal distribution)


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.004 ms/op
Iteration   1: 2.467 ±(99.9%) 0.003 ms/op
Iteration   2: 2.462 ±(99.9%) 0.004 ms/op
Iteration   3: 2.482 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.471 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.462, 2.471, 2.482), stdev = 0.010
  CI (99.9%): [2.279, 2.662] (assumes normal distribution)


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
# Warmup Iteration   1: 3.594 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.004 ms/op
Iteration   1: 2.410 ±(99.9%) 0.004 ms/op
Iteration   2: 2.429 ±(99.9%) 0.004 ms/op
Iteration   3: 2.421 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.420 ±(99.9%) 0.178 ms/op [Average]
  (min, avg, max) = (2.410, 2.420, 2.429), stdev = 0.010
  CI (99.9%): [2.242, 2.598] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.011 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.419 ±(99.9%) 0.004 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
Iteration   2: 2.401 ±(99.9%) 0.005 ms/op
Iteration   3: 2.410 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.423 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (2.401, 2.423, 2.459), stdev = 0.031
  CI (99.9%): [1.855, 2.992] (assumes normal distribution)


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
# Warmup Iteration   1: 4.742 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.005 ms/op
Iteration   1: 2.970 ±(99.9%) 0.004 ms/op
Iteration   2: 2.981 ±(99.9%) 0.005 ms/op
Iteration   3: 2.962 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.971 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (2.962, 2.971, 2.981), stdev = 0.009
  CI (99.9%): [2.798, 3.144] (assumes normal distribution)


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
# Warmup Iteration   1: 4.106 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.006 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.928 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  10.170 ms/op
                 createUser·p0.9999: 13.533 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   3.580 ms/op
                 createUser·p0.999:  6.703 ms/op
                 createUser·p0.9999: 11.633 ms/op
                 createUser·p1.00:   11.993 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.858 ms/op
                 createUser·p0.999:  8.017 ms/op
                 createUser·p0.9999: 10.093 ms/op
                 createUser·p1.00:   10.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386608
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 189051 
    [ 2.500,  3.750) = 193944 
    [ 3.750,  5.000) = 2746 
    [ 5.000,  6.250) = 309 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 93 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      8.608 ms/op
     p(99.9900) =     12.901 ms/op
     p(99.9990) =     14.130 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.633 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.427 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.390 ±(99.9%) 0.005 ms/op
Iteration   1: 2.378 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.884 ms/op
                 existUser·p0.95:   2.978 ms/op
                 existUser·p0.99:   3.367 ms/op
                 existUser·p0.999:  5.094 ms/op
                 existUser·p0.9999: 13.451 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   2: 2.413 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.087 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.408 ms/op
                 existUser·p0.999:  5.530 ms/op
                 existUser·p0.9999: 12.640 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   3: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.730 ms/op
                 existUser·p0.999:  7.591 ms/op
                 existUser·p0.9999: 11.595 ms/op
                 existUser·p1.00:   16.237 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398547
  mean =      2.406 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 201455 
    [ 2.500,  3.750) = 194262 
    [ 3.750,  5.000) = 2187 
    [ 5.000,  6.250) = 194 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.920 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      3.518 ms/op
     p(99.9000) =      6.328 ms/op
     p(99.9900) =     13.011 ms/op
     p(99.9990) =     13.861 ms/op
     p(99.9999) =     16.237 ms/op
    p(100.0000) =     16.237 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.673 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.006 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  6.151 ms/op
                 getUser·p0.9999: 13.699 ms/op
                 getUser·p1.00:   14.746 ms/op

Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.007 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  8.534 ms/op
                 getUser·p0.9999: 12.244 ms/op
                 getUser·p1.00:   12.796 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   4.022 ms/op
                 getUser·p0.999:  8.913 ms/op
                 getUser·p0.9999: 11.144 ms/op
                 getUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385820
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 191157 
    [ 2.500,  3.750) = 189357 
    [ 3.750,  5.000) = 3965 
    [ 5.000,  6.250) = 802 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.969 ms/op
     p(99.9000) =      8.819 ms/op
     p(99.9900) =     13.189 ms/op
     p(99.9990) =     14.301 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.611 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.010 ms/op
Iteration   1: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 10.707 ms/op
                 listUser·p1.00:   10.764 ms/op

Iteration   2: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.865 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 11.378 ms/op
                 listUser·p1.00:   13.631 ms/op

Iteration   3: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.838 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.274 ms/op
                 listUser·p0.9999: 10.883 ms/op
                 listUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317737
  mean =      3.019 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 93407 
    [ 2.500,  3.750) = 184405 
    [ 3.750,  5.000) = 32164 
    [ 5.000,  6.250) = 6121 
    [ 6.250,  7.500) = 869 
    [ 7.500,  8.750) = 187 
    [ 8.750, 10.000) = 285 
    [10.000, 11.250) = 152 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =      9.327 ms/op
     p(99.9900) =     10.772 ms/op
     p(99.9990) =     13.451 ms/op
     p(99.9999) =     13.631 ms/op
    p(100.0000) =     13.631 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.034 ± 2.645  ops/ms
ClientPb.existUser                       thrpt       3  13.238 ± 1.143  ops/ms
ClientPb.getUser                         thrpt       3  12.972 ± 1.490  ops/ms
ClientPb.listUser                        thrpt       3  10.862 ± 0.550  ops/ms
ClientPb.createUser                       avgt       3   2.471 ± 0.191   ms/op
ClientPb.existUser                        avgt       3   2.420 ± 0.178   ms/op
ClientPb.getUser                          avgt       3   2.423 ± 0.569   ms/op
ClientPb.listUser                         avgt       3   2.971 ± 0.173   ms/op
ClientPb.createUser                     sample  386608   2.481 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.928           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.544           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.015           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.608           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.901           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.287           ms/op
ClientPb.existUser                      sample  398547   2.406 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.856           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.920           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.328           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.011           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.237           ms/op
ClientPb.getUser                        sample  385820   2.486 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.940           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.819           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.189           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.746           ms/op
ClientPb.listUser                       sample  317737   3.019 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.838           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.327           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.772           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.631           ms/op
