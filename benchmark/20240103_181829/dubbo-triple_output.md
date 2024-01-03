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
# Warmup Iteration   1: 4.945 ops/ms
# Warmup Iteration   2: 11.777 ops/ms
# Warmup Iteration   3: 12.143 ops/ms
Iteration   1: 12.439 ops/ms
Iteration   2: 12.448 ops/ms
Iteration   3: 12.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.456 ±(99.9%) 0.404 ops/ms [Average]
  (min, avg, max) = (12.439, 12.456, 12.481), stdev = 0.022
  CI (99.9%): [12.052, 12.860] (assumes normal distribution)


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
# Warmup Iteration   1: 7.798 ops/ms
# Warmup Iteration   2: 12.878 ops/ms
# Warmup Iteration   3: 12.840 ops/ms
Iteration   1: 12.888 ops/ms
Iteration   2: 12.873 ops/ms
Iteration   3: 12.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.846 ±(99.9%) 1.099 ops/ms [Average]
  (min, avg, max) = (12.777, 12.846, 12.888), stdev = 0.060
  CI (99.9%): [11.747, 13.945] (assumes normal distribution)


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
# Warmup Iteration   1: 8.018 ops/ms
# Warmup Iteration   2: 12.594 ops/ms
# Warmup Iteration   3: 12.591 ops/ms
Iteration   1: 12.624 ops/ms
Iteration   2: 12.610 ops/ms
Iteration   3: 12.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.654 ±(99.9%) 1.183 ops/ms [Average]
  (min, avg, max) = (12.610, 12.654, 12.728), stdev = 0.065
  CI (99.9%): [11.471, 13.837] (assumes normal distribution)


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
# Warmup Iteration   1: 6.893 ops/ms
# Warmup Iteration   2: 10.300 ops/ms
# Warmup Iteration   3: 10.281 ops/ms
Iteration   1: 10.457 ops/ms
Iteration   2: 10.458 ops/ms
Iteration   3: 10.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.459 ±(99.9%) 0.051 ops/ms [Average]
  (min, avg, max) = (10.457, 10.459, 10.462), stdev = 0.003
  CI (99.9%): [10.407, 10.510] (assumes normal distribution)


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
# Warmup Iteration   1: 4.235 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.643 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.004 ms/op
Iteration   1: 2.565 ±(99.9%) 0.003 ms/op
Iteration   2: 2.616 ±(99.9%) 0.003 ms/op
Iteration   3: 2.551 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.577 ±(99.9%) 0.624 ms/op [Average]
  (min, avg, max) = (2.551, 2.577, 2.616), stdev = 0.034
  CI (99.9%): [1.953, 3.202] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.849 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.004 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
Iteration   2: 2.488 ±(99.9%) 0.004 ms/op
Iteration   3: 2.523 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.504 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (2.488, 2.504, 2.523), stdev = 0.017
  CI (99.9%): [2.188, 2.820] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.928 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.005 ms/op
Iteration   1: 2.528 ±(99.9%) 0.004 ms/op
Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
Iteration   3: 2.540 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.542 ±(99.9%) 0.258 ms/op [Average]
  (min, avg, max) = (2.528, 2.542, 2.556), stdev = 0.014
  CI (99.9%): [2.284, 2.800] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.739 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.005 ms/op
Iteration   1: 3.032 ±(99.9%) 0.006 ms/op
Iteration   2: 3.010 ±(99.9%) 0.004 ms/op
Iteration   3: 3.010 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.017 ±(99.9%) 0.233 ms/op [Average]
  (min, avg, max) = (3.010, 3.017, 3.032), stdev = 0.013
  CI (99.9%): [2.784, 3.251] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.235 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.716 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.006 ms/op
Iteration   1: 2.529 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  12.183 ms/op
                 createUser·p0.9999: 14.107 ms/op
                 createUser·p1.00:   14.664 ms/op

Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.600 ms/op
                 createUser·p0.999:  7.735 ms/op
                 createUser·p0.9999: 12.604 ms/op
                 createUser·p1.00:   13.206 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  8.853 ms/op
                 createUser·p0.9999: 10.414 ms/op
                 createUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382894
  mean =      2.504 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 184146 
    [ 2.500,  3.750) = 194855 
    [ 3.750,  5.000) = 2971 
    [ 5.000,  6.250) = 374 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 137 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      8.880 ms/op
     p(99.9900) =     13.596 ms/op
     p(99.9990) =     14.533 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.176 ms/op
                 existUser·p0.99:   3.813 ms/op
                 existUser·p0.999:  8.062 ms/op
                 existUser·p0.9999: 14.256 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  6.192 ms/op
                 existUser·p0.9999: 12.960 ms/op
                 existUser·p1.00:   13.369 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  7.519 ms/op
                 existUser·p0.9999: 12.534 ms/op
                 existUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385853
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 188448 
    [ 2.500,  3.750) = 193781 
    [ 3.750,  5.000) = 2915 
    [ 5.000,  6.250) = 243 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      7.414 ms/op
     p(99.9900) =     13.540 ms/op
     p(99.9990) =     14.352 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


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
# Warmup Iteration   1: 4.083 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.006 ms/op
Iteration   1: 2.533 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  11.452 ms/op
                 getUser·p0.9999: 16.357 ms/op
                 getUser·p1.00:   16.810 ms/op

Iteration   2: 2.567 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   2.613 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.281 ms/op
                 getUser·p0.99:   4.145 ms/op
                 getUser·p0.999:  8.888 ms/op
                 getUser·p0.9999: 14.059 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.626 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.670 ms/op
                 getUser·p0.999:  8.444 ms/op
                 getUser·p0.9999: 10.526 ms/op
                 getUser·p1.00:   11.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378415
  mean =      2.535 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 184741 
    [ 2.500,  3.750) = 189086 
    [ 3.750,  5.000) = 3743 
    [ 5.000,  6.250) = 372 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      8.847 ms/op
     p(99.9900) =     15.807 ms/op
     p(99.9990) =     16.584 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 4.764 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.009 ms/op
Iteration   1: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.579 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  8.552 ms/op
                 listUser·p0.9999: 10.737 ms/op
                 listUser·p1.00:   14.254 ms/op

Iteration   2: 2.968 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.976 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.785 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  9.639 ms/op
                 listUser·p0.9999: 11.990 ms/op
                 listUser·p1.00:   12.714 ms/op

Iteration   3: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.931 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  10.052 ms/op
                 listUser·p0.9999: 12.624 ms/op
                 listUser·p1.00:   14.418 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321973
  mean =      2.980 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 159 
    [ 1.250,  2.500) = 97367 
    [ 2.500,  3.750) = 187567 
    [ 3.750,  5.000) = 30403 
    [ 5.000,  6.250) = 5150 
    [ 6.250,  7.500) = 711 
    [ 7.500,  8.750) = 189 
    [ 8.750, 10.000) = 210 
    [10.000, 11.250) = 152 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     11.760 ms/op
     p(99.9990) =     13.882 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.456 ± 0.404  ops/ms
ClientPb.existUser                       thrpt       3  12.846 ± 1.099  ops/ms
ClientPb.getUser                         thrpt       3  12.654 ± 1.183  ops/ms
ClientPb.listUser                        thrpt       3  10.459 ± 0.051  ops/ms
ClientPb.createUser                       avgt       3   2.577 ± 0.624   ms/op
ClientPb.existUser                        avgt       3   2.504 ± 0.316   ms/op
ClientPb.getUser                          avgt       3   2.542 ± 0.258   ms/op
ClientPb.listUser                         avgt       3   3.017 ± 0.233   ms/op
ClientPb.createUser                     sample  382894   2.504 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.824           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.880           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.596           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.664           ms/op
ClientPb.existUser                      sample  385853   2.486 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.915           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.414           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.540           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.565           ms/op
ClientPb.getUser                        sample  378415   2.535 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.626           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.576           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.847           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.807           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.810           ms/op
ClientPb.listUser                       sample  321973   2.980 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.579           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.470           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.760           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.418           ms/op
