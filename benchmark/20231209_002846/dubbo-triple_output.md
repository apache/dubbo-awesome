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
# Warmup Iteration   1: 4.143 ops/ms
# Warmup Iteration   2: 11.642 ops/ms
# Warmup Iteration   3: 12.010 ops/ms
Iteration   1: 12.070 ops/ms
Iteration   2: 12.254 ops/ms
Iteration   3: 12.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.240 ±(99.9%) 2.970 ops/ms [Average]
  (min, avg, max) = (12.070, 12.240, 12.395), stdev = 0.163
  CI (99.9%): [9.270, 15.210] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.454 ops/ms
# Warmup Iteration   2: 12.738 ops/ms
# Warmup Iteration   3: 12.606 ops/ms
Iteration   1: 12.597 ops/ms
Iteration   2: 12.643 ops/ms
Iteration   3: 12.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.663 ±(99.9%) 1.414 ops/ms [Average]
  (min, avg, max) = (12.597, 12.663, 12.748), stdev = 0.078
  CI (99.9%): [11.249, 14.077] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.862 ops/ms
# Warmup Iteration   2: 12.054 ops/ms
# Warmup Iteration   3: 12.391 ops/ms
Iteration   1: 12.256 ops/ms
Iteration   2: 12.395 ops/ms
Iteration   3: 12.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.272 ±(99.9%) 2.118 ops/ms [Average]
  (min, avg, max) = (12.165, 12.272, 12.395), stdev = 0.116
  CI (99.9%): [10.154, 14.390] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.973 ops/ms
# Warmup Iteration   2: 10.270 ops/ms
# Warmup Iteration   3: 10.428 ops/ms
Iteration   1: 10.464 ops/ms
Iteration   2: 10.406 ops/ms
Iteration   3: 10.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.472 ±(99.9%) 1.283 ops/ms [Average]
  (min, avg, max) = (10.406, 10.472, 10.546), stdev = 0.070
  CI (99.9%): [9.190, 11.755] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.375 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.657 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.595 ±(99.9%) 0.005 ms/op
Iteration   1: 2.624 ±(99.9%) 0.004 ms/op
Iteration   2: 2.585 ±(99.9%) 0.004 ms/op
Iteration   3: 2.636 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.615 ±(99.9%) 0.490 ms/op [Average]
  (min, avg, max) = (2.585, 2.615, 2.636), stdev = 0.027
  CI (99.9%): [2.125, 3.105] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.850 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.004 ms/op
Iteration   1: 2.533 ±(99.9%) 0.004 ms/op
Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
Iteration   3: 2.520 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.523 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (2.517, 2.523, 2.533), stdev = 0.009
  CI (99.9%): [2.363, 2.683] (assumes normal distribution)


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.628 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.597 ±(99.9%) 0.005 ms/op
Iteration   1: 2.626 ±(99.9%) 0.004 ms/op
Iteration   2: 2.582 ±(99.9%) 0.004 ms/op
Iteration   3: 2.589 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.599 ±(99.9%) 0.430 ms/op [Average]
  (min, avg, max) = (2.582, 2.599, 2.626), stdev = 0.024
  CI (99.9%): [2.169, 3.029] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.121 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
Iteration   1: 3.064 ±(99.9%) 0.006 ms/op
Iteration   2: 3.047 ±(99.9%) 0.005 ms/op
Iteration   3: 3.079 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.063 ±(99.9%) 0.294 ms/op [Average]
  (min, avg, max) = (3.047, 3.063, 3.079), stdev = 0.016
  CI (99.9%): [2.769, 3.357] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.680 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 2.747 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.615 ±(99.9%) 0.006 ms/op
Iteration   1: 2.618 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.001 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.183 ms/op
                 createUser·p0.95:   3.318 ms/op
                 createUser·p0.99:   3.990 ms/op
                 createUser·p0.999:  12.663 ms/op
                 createUser·p0.9999: 14.726 ms/op
                 createUser·p1.00:   14.975 ms/op

Iteration   2: 2.608 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.391 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.166 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  10.359 ms/op
                 createUser·p0.9999: 14.811 ms/op
                 createUser·p1.00:   15.286 ms/op

Iteration   3: 2.615 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   2.675 ms/op
                 createUser·p0.90:   3.174 ms/op
                 createUser·p0.95:   3.297 ms/op
                 createUser·p0.99:   3.887 ms/op
                 createUser·p0.999:  8.969 ms/op
                 createUser·p0.9999: 11.502 ms/op
                 createUser·p1.00:   13.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 366979
  mean =      2.613 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 172633 
    [ 2.500,  3.750) = 189294 
    [ 3.750,  5.000) = 4226 
    [ 5.000,  6.250) = 317 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.391 ms/op
     p(50.0000) =      2.662 ms/op
     p(90.0000) =      3.174 ms/op
     p(95.0000) =      3.297 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     14.164 ms/op
     p(99.9990) =     15.068 ms/op
     p(99.9999) =     15.286 ms/op
    p(100.0000) =     15.286 ms/op


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
# Warmup Iteration   1: 4.117 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.006 ms/op
Iteration   1: 2.519 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.064 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  5.443 ms/op
                 existUser·p0.9999: 13.877 ms/op
                 existUser·p1.00:   14.008 ms/op

Iteration   2: 2.533 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.088 ms/op
                 existUser·p0.95:   3.199 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  9.322 ms/op
                 existUser·p0.9999: 13.468 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.195 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  7.255 ms/op
                 existUser·p0.9999: 12.080 ms/op
                 existUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 379729
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 185573 
    [ 2.500,  3.750) = 189633 
    [ 3.750,  5.000) = 3388 
    [ 5.000,  6.250) = 611 
    [ 6.250,  7.500) = 120 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      6.661 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     14.536 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 4.144 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.643 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.579 ±(99.9%) 0.006 ms/op
Iteration   1: 2.545 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.621 ms/op
                 getUser·p0.999:  12.485 ms/op
                 getUser·p0.9999: 14.374 ms/op
                 getUser·p1.00:   15.122 ms/op

Iteration   2: 2.558 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  9.290 ms/op
                 getUser·p0.9999: 14.123 ms/op
                 getUser·p1.00:   14.549 ms/op

Iteration   3: 2.570 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.059 ms/op
                 getUser·p0.999:  9.516 ms/op
                 getUser·p0.9999: 11.747 ms/op
                 getUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374971
  mean =      2.558 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 182080 
    [ 2.500,  3.750) = 187799 
    [ 3.750,  5.000) = 3772 
    [ 5.000,  6.250) = 824 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 76 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.940 ms/op
     p(99.9000) =      9.310 ms/op
     p(99.9900) =     14.180 ms/op
     p(99.9990) =     14.619 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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
# Warmup Iteration   1: 5.280 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.009 ms/op
Iteration   1: 3.116 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.812 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.591 ms/op
                 listUser·p0.9999: 11.841 ms/op
                 listUser·p1.00:   13.615 ms/op

Iteration   2: 3.119 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.854 ms/op
                 listUser·p0.50:   3.056 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.816 ms/op
                 listUser·p0.999:  10.060 ms/op
                 listUser·p0.9999: 11.596 ms/op
                 listUser·p1.00:   12.354 ms/op

Iteration   3: 3.101 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.945 ms/op
                 listUser·p0.9999: 11.622 ms/op
                 listUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 308243
  mean =      3.112 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 73180 
    [ 2.500,  3.750) = 189548 
    [ 3.750,  5.000) = 37177 
    [ 5.000,  6.250) = 6745 
    [ 6.250,  7.500) = 799 
    [ 7.500,  8.750) = 190 
    [ 8.750, 10.000) = 244 
    [10.000, 11.250) = 210 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =      9.859 ms/op
     p(99.9900) =     11.665 ms/op
     p(99.9990) =     13.548 ms/op
     p(99.9999) =     13.615 ms/op
    p(100.0000) =     13.615 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.240 ± 2.970  ops/ms
ClientPb.existUser                       thrpt       3  12.663 ± 1.414  ops/ms
ClientPb.getUser                         thrpt       3  12.272 ± 2.118  ops/ms
ClientPb.listUser                        thrpt       3  10.472 ± 1.283  ops/ms
ClientPb.createUser                       avgt       3   2.615 ± 0.490   ms/op
ClientPb.existUser                        avgt       3   2.523 ± 0.160   ms/op
ClientPb.getUser                          avgt       3   2.599 ± 0.430   ms/op
ClientPb.listUser                         avgt       3   3.063 ± 0.294   ms/op
ClientPb.createUser                     sample  366979   2.613 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.391           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.662           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.297           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.568           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.164           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.286           ms/op
ClientPb.existUser                      sample  379729   2.525 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.813           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.560           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.858           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.661           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.713           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.860           ms/op
ClientPb.getUser                        sample  374971   2.558 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.811           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.593           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.310           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.180           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.122           ms/op
ClientPb.listUser                       sample  308243   3.112 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.812           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.052           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.743           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.859           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.665           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.615           ms/op
