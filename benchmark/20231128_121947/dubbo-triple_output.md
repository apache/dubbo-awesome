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
# Warmup Iteration   1: 5.008 ops/ms
# Warmup Iteration   2: 12.532 ops/ms
# Warmup Iteration   3: 12.919 ops/ms
Iteration   1: 12.946 ops/ms
Iteration   2: 13.024 ops/ms
Iteration   3: 13.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.018 ±(99.9%) 1.247 ops/ms [Average]
  (min, avg, max) = (12.946, 13.018, 13.082), stdev = 0.068
  CI (99.9%): [11.771, 14.265] (assumes normal distribution)


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
# Warmup Iteration   1: 7.812 ops/ms
# Warmup Iteration   2: 13.218 ops/ms
# Warmup Iteration   3: 13.242 ops/ms
Iteration   1: 13.351 ops/ms
Iteration   2: 13.223 ops/ms
Iteration   3: 13.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.262 ±(99.9%) 1.405 ops/ms [Average]
  (min, avg, max) = (13.213, 13.262, 13.351), stdev = 0.077
  CI (99.9%): [11.857, 14.668] (assumes normal distribution)


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
# Warmup Iteration   1: 8.081 ops/ms
# Warmup Iteration   2: 12.816 ops/ms
# Warmup Iteration   3: 12.983 ops/ms
Iteration   1: 12.755 ops/ms
Iteration   2: 13.177 ops/ms
Iteration   3: 13.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.020 ±(99.9%) 4.213 ops/ms [Average]
  (min, avg, max) = (12.755, 13.020, 13.177), stdev = 0.231
  CI (99.9%): [8.808, 17.233] (assumes normal distribution)


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
# Warmup Iteration   1: 6.649 ops/ms
# Warmup Iteration   2: 10.777 ops/ms
# Warmup Iteration   3: 10.916 ops/ms
Iteration   1: 10.852 ops/ms
Iteration   2: 10.763 ops/ms
Iteration   3: 10.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.849 ±(99.9%) 1.548 ops/ms [Average]
  (min, avg, max) = (10.763, 10.849, 10.933), stdev = 0.085
  CI (99.9%): [9.301, 12.397] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.949 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.531 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.003 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.003 ms/op
Iteration   3: 2.464 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.488 ±(99.9%) 0.411 ms/op [Average]
  (min, avg, max) = (2.464, 2.488, 2.509), stdev = 0.023
  CI (99.9%): [2.077, 2.900] (assumes normal distribution)


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
# Warmup Iteration   1: 3.742 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.423 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.003 ms/op
Iteration   1: 2.433 ±(99.9%) 0.004 ms/op
Iteration   2: 2.422 ±(99.9%) 0.003 ms/op
Iteration   3: 2.442 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.432 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (2.422, 2.432, 2.442), stdev = 0.010
  CI (99.9%): [2.250, 2.615] (assumes normal distribution)


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.004 ms/op
Iteration   1: 2.465 ±(99.9%) 0.003 ms/op
Iteration   2: 2.465 ±(99.9%) 0.003 ms/op
Iteration   3: 2.438 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.456 ±(99.9%) 0.283 ms/op [Average]
  (min, avg, max) = (2.438, 2.456, 2.465), stdev = 0.016
  CI (99.9%): [2.173, 2.739] (assumes normal distribution)


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
# Warmup Iteration   1: 4.527 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
Iteration   1: 2.975 ±(99.9%) 0.005 ms/op
Iteration   2: 2.975 ±(99.9%) 0.006 ms/op
Iteration   3: 2.970 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.973 ±(99.9%) 0.054 ms/op [Average]
  (min, avg, max) = (2.970, 2.973, 2.975), stdev = 0.003
  CI (99.9%): [2.919, 3.027] (assumes normal distribution)


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
# Warmup Iteration   1: 4.046 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.006 ms/op
Iteration   1: 2.476 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.562 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  6.474 ms/op
                 createUser·p0.9999: 13.664 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   3.604 ms/op
                 createUser·p0.999:  8.663 ms/op
                 createUser·p0.9999: 11.649 ms/op
                 createUser·p1.00:   11.944 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  9.142 ms/op
                 createUser·p0.9999: 12.846 ms/op
                 createUser·p1.00:   14.270 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 388483
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 191029 
    [ 2.500,  3.750) = 194021 
    [ 3.750,  5.000) = 2606 
    [ 5.000,  6.250) = 323 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      9.102 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     14.190 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.722 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
Iteration   1: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.387 ms/op
                 existUser·p0.999:  6.537 ms/op
                 existUser·p0.9999: 14.284 ms/op
                 existUser·p1.00:   14.483 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.703 ms/op
                 existUser·p0.999:  6.930 ms/op
                 existUser·p0.9999: 12.813 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.908 ms/op
                 existUser·p0.999:  7.644 ms/op
                 existUser·p0.9999: 12.109 ms/op
                 existUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391100
  mean =      2.452 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 194806 
    [ 2.500,  3.750) = 192779 
    [ 3.750,  5.000) = 2412 
    [ 5.000,  6.250) = 611 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      7.544 ms/op
     p(99.9900) =     13.695 ms/op
     p(99.9990) =     14.358 ms/op
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
# Warmup Iteration   1: 3.912 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.510 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.006 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  8.481 ms/op
                 getUser·p0.9999: 13.913 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.789 ms/op
                 getUser·p0.999:  7.550 ms/op
                 getUser·p0.9999: 12.960 ms/op
                 getUser·p1.00:   13.107 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.067 ms/op
                 getUser·p0.999:  8.048 ms/op
                 getUser·p0.9999: 10.784 ms/op
                 getUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387019
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 192084 
    [ 2.500,  3.750) = 189842 
    [ 3.750,  5.000) = 3930 
    [ 5.000,  6.250) = 652 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.924 ms/op
     p(99.9000) =      7.559 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     14.352 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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
# Warmup Iteration   1: 4.724 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.968 ±(99.9%) 0.009 ms/op
Iteration   1: 2.939 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.408 ms/op
                 listUser·p0.9999: 11.358 ms/op
                 listUser·p1.00:   12.141 ms/op

Iteration   2: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.639 ms/op
                 listUser·p0.999:  9.486 ms/op
                 listUser·p0.9999: 11.808 ms/op
                 listUser·p1.00:   12.796 ms/op

Iteration   3: 2.954 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 11.111 ms/op
                 listUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324685
  mean =      2.954 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 157 
    [ 1.250,  2.500) = 104722 
    [ 2.500,  3.750) = 183450 
    [ 3.750,  5.000) = 29282 
    [ 5.000,  6.250) = 5635 
    [ 6.250,  7.500) = 707 
    [ 7.500,  8.750) = 298 
    [ 8.750, 10.000) = 281 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     11.445 ms/op
     p(99.9990) =     12.337 ms/op
     p(99.9999) =     12.796 ms/op
    p(100.0000) =     12.796 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.018 ± 1.247  ops/ms
ClientPb.existUser                       thrpt       3  13.262 ± 1.405  ops/ms
ClientPb.getUser                         thrpt       3  13.020 ± 4.213  ops/ms
ClientPb.listUser                        thrpt       3  10.849 ± 1.548  ops/ms
ClientPb.createUser                       avgt       3   2.488 ± 0.411   ms/op
ClientPb.existUser                        avgt       3   2.432 ± 0.183   ms/op
ClientPb.getUser                          avgt       3   2.456 ± 0.283   ms/op
ClientPb.listUser                         avgt       3   2.973 ± 0.054   ms/op
ClientPb.createUser                     sample  388483   2.469 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.562           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.998           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.102           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.206           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.270           ms/op
ClientPb.existUser                      sample  391100   2.452 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.812           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.544           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.695           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.483           ms/op
ClientPb.getUser                        sample  387019   2.478 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.782           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.559           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.468           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.418           ms/op
ClientPb.listUser                       sample  324685   2.954 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.915           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.888           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.290           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.445           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.796           ms/op
