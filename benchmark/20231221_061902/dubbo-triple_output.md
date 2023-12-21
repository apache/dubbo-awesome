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
# Warmup Iteration   1: 4.987 ops/ms
# Warmup Iteration   2: 12.075 ops/ms
# Warmup Iteration   3: 12.264 ops/ms
Iteration   1: 12.414 ops/ms
Iteration   2: 12.515 ops/ms
Iteration   3: 12.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.501 ±(99.9%) 1.480 ops/ms [Average]
  (min, avg, max) = (12.414, 12.501, 12.575), stdev = 0.081
  CI (99.9%): [11.021, 13.982] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.361 ops/ms
# Warmup Iteration   2: 12.966 ops/ms
# Warmup Iteration   3: 13.087 ops/ms
Iteration   1: 13.002 ops/ms
Iteration   2: 13.035 ops/ms
Iteration   3: 12.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.005 ±(99.9%) 0.511 ops/ms [Average]
  (min, avg, max) = (12.979, 13.005, 13.035), stdev = 0.028
  CI (99.9%): [12.494, 13.516] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.050 ops/ms
# Warmup Iteration   2: 12.648 ops/ms
# Warmup Iteration   3: 12.882 ops/ms
Iteration   1: 12.882 ops/ms
Iteration   2: 12.976 ops/ms
Iteration   3: 12.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.935 ±(99.9%) 0.884 ops/ms [Average]
  (min, avg, max) = (12.882, 12.935, 12.976), stdev = 0.048
  CI (99.9%): [12.052, 13.819] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 6.677 ops/ms
# Warmup Iteration   2: 10.658 ops/ms
# Warmup Iteration   3: 10.659 ops/ms
Iteration   1: 10.695 ops/ms
Iteration   2: 10.778 ops/ms
Iteration   3: 10.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.755 ±(99.9%) 0.945 ops/ms [Average]
  (min, avg, max) = (10.695, 10.755, 10.791), stdev = 0.052
  CI (99.9%): [9.810, 11.700] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 3.871 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
Iteration   1: 2.511 ±(99.9%) 0.003 ms/op
Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
Iteration   3: 2.500 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.508 ±(99.9%) 0.130 ms/op [Average]
  (min, avg, max) = (2.500, 2.508, 2.513), stdev = 0.007
  CI (99.9%): [2.378, 2.637] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.766 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.437 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.004 ms/op
Iteration   1: 2.448 ±(99.9%) 0.005 ms/op
Iteration   2: 2.456 ±(99.9%) 0.004 ms/op
Iteration   3: 2.461 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.455 ±(99.9%) 0.125 ms/op [Average]
  (min, avg, max) = (2.448, 2.455, 2.461), stdev = 0.007
  CI (99.9%): [2.329, 2.580] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.999 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.504 ±(99.9%) 0.004 ms/op
Iteration   3: 2.501 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.499 ±(99.9%) 0.119 ms/op [Average]
  (min, avg, max) = (2.492, 2.499, 2.504), stdev = 0.006
  CI (99.9%): [2.380, 2.617] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.594 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
Iteration   1: 2.978 ±(99.9%) 0.005 ms/op
Iteration   2: 2.975 ±(99.9%) 0.005 ms/op
Iteration   3: 2.951 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.968 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (2.951, 2.968, 2.978), stdev = 0.015
  CI (99.9%): [2.698, 3.237] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.108 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.669 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.560 ±(99.9%) 0.006 ms/op
Iteration   1: 2.546 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   4.162 ms/op
                 createUser·p0.999:  10.261 ms/op
                 createUser·p0.9999: 13.213 ms/op
                 createUser·p1.00:   14.123 ms/op

Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  9.961 ms/op
                 createUser·p0.9999: 12.080 ms/op
                 createUser·p1.00:   12.468 ms/op

Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.026 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  9.863 ms/op
                 createUser·p0.9999: 15.120 ms/op
                 createUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378068
  mean =      2.537 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 181256 
    [ 2.500,  3.750) = 192068 
    [ 3.750,  5.000) = 3587 
    [ 5.000,  6.250) = 604 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 186 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      9.895 ms/op
     p(99.9900) =     13.228 ms/op
     p(99.9990) =     16.559 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


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
# Warmup Iteration   1: 3.500 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
Iteration   1: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  5.471 ms/op
                 existUser·p0.9999: 14.155 ms/op
                 existUser·p1.00:   14.483 ms/op

Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.965 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  6.753 ms/op
                 existUser·p0.9999: 12.164 ms/op
                 existUser·p1.00:   13.566 ms/op

Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  5.945 ms/op
                 existUser·p0.9999: 12.062 ms/op
                 existUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388613
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 192131 
    [ 2.500,  3.750) = 193639 
    [ 3.750,  5.000) = 2151 
    [ 5.000,  6.250) = 284 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.547 ms/op
     p(99.9000) =      6.037 ms/op
     p(99.9900) =     13.355 ms/op
     p(99.9990) =     14.354 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


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
# Warmup Iteration   1: 3.869 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.793 ms/op
                 getUser·p0.999:  8.866 ms/op
                 getUser·p0.9999: 13.294 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.974 ms/op
                 getUser·p0.999:  6.605 ms/op
                 getUser·p0.9999: 12.344 ms/op
                 getUser·p1.00:   12.730 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.518 ms/op
                 getUser·p0.999:  8.635 ms/op
                 getUser·p0.9999: 12.409 ms/op
                 getUser·p1.00:   12.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385276
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 192079 
    [ 2.500,  3.750) = 188976 
    [ 3.750,  5.000) = 3182 
    [ 5.000,  6.250) = 551 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 139 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      6.664 ms/op
     p(99.9900) =     12.943 ms/op
     p(99.9990) =     13.835 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 4.569 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.009 ms/op
Iteration   1: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.966 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.840 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.521 ms/op
                 listUser·p0.9999: 9.634 ms/op
                 listUser·p1.00:   10.404 ms/op

Iteration   2: 2.983 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 10.167 ms/op
                 listUser·p1.00:   11.518 ms/op

Iteration   3: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.473 ms/op
                 listUser·p0.999:  9.575 ms/op
                 listUser·p0.9999: 10.831 ms/op
                 listUser·p1.00:   11.289 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321402
  mean =      2.984 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 157 
    [ 1.250,  2.500) = 97895 
    [ 2.500,  3.750) = 187047 
    [ 3.750,  5.000) = 29479 
    [ 5.000,  6.250) = 5487 
    [ 6.250,  7.500) = 721 
    [ 7.500,  8.750) = 251 
    [ 8.750, 10.000) = 274 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      8.988 ms/op
     p(99.9900) =     10.385 ms/op
     p(99.9990) =     11.289 ms/op
     p(99.9999) =     11.518 ms/op
    p(100.0000) =     11.518 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.501 ± 1.480  ops/ms
ClientPb.existUser                       thrpt       3  13.005 ± 0.511  ops/ms
ClientPb.getUser                         thrpt       3  12.935 ± 0.884  ops/ms
ClientPb.listUser                        thrpt       3  10.755 ± 0.945  ops/ms
ClientPb.createUser                       avgt       3   2.508 ± 0.130   ms/op
ClientPb.existUser                        avgt       3   2.455 ± 0.125   ms/op
ClientPb.getUser                          avgt       3   2.499 ± 0.119   ms/op
ClientPb.listUser                         avgt       3   2.968 ± 0.270   ms/op
ClientPb.createUser                     sample  378068   2.537 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.818           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.895           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.228           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.630           ms/op
ClientPb.existUser                      sample  388613   2.468 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.965           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.037           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.355           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.483           ms/op
ClientPb.getUser                        sample  385276   2.490 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.863           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.664           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.943           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.270           ms/op
ClientPb.listUser                       sample  321402   2.984 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.919           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.988           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.385           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.518           ms/op
