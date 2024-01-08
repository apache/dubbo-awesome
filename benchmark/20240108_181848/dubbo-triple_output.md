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
# Warmup Iteration   1: 3.928 ops/ms
# Warmup Iteration   2: 11.605 ops/ms
# Warmup Iteration   3: 11.974 ops/ms
Iteration   1: 12.454 ops/ms
Iteration   2: 12.328 ops/ms
Iteration   3: 12.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.360 ±(99.9%) 1.510 ops/ms [Average]
  (min, avg, max) = (12.298, 12.360, 12.454), stdev = 0.083
  CI (99.9%): [10.850, 13.870] (assumes normal distribution)


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
# Warmup Iteration   1: 7.327 ops/ms
# Warmup Iteration   2: 12.665 ops/ms
# Warmup Iteration   3: 12.787 ops/ms
Iteration   1: 12.841 ops/ms
Iteration   2: 12.731 ops/ms
Iteration   3: 12.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.797 ±(99.9%) 1.064 ops/ms [Average]
  (min, avg, max) = (12.731, 12.797, 12.841), stdev = 0.058
  CI (99.9%): [11.732, 13.861] (assumes normal distribution)


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
# Warmup Iteration   1: 7.666 ops/ms
# Warmup Iteration   2: 12.272 ops/ms
# Warmup Iteration   3: 12.483 ops/ms
Iteration   1: 12.457 ops/ms
Iteration   2: 12.485 ops/ms
Iteration   3: 12.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.457 ±(99.9%) 0.525 ops/ms [Average]
  (min, avg, max) = (12.428, 12.457, 12.485), stdev = 0.029
  CI (99.9%): [11.932, 12.982] (assumes normal distribution)


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
# Warmup Iteration   1: 6.186 ops/ms
# Warmup Iteration   2: 10.147 ops/ms
# Warmup Iteration   3: 10.141 ops/ms
Iteration   1: 10.282 ops/ms
Iteration   2: 10.232 ops/ms
Iteration   3: 10.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.288 ±(99.9%) 1.083 ops/ms [Average]
  (min, avg, max) = (10.232, 10.288, 10.351), stdev = 0.059
  CI (99.9%): [9.205, 11.371] (assumes normal distribution)


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
# Warmup Iteration   1: 4.590 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.660 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.602 ±(99.9%) 0.004 ms/op
Iteration   1: 2.600 ±(99.9%) 0.004 ms/op
Iteration   2: 2.606 ±(99.9%) 0.004 ms/op
Iteration   3: 2.586 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.597 ±(99.9%) 0.188 ms/op [Average]
  (min, avg, max) = (2.586, 2.597, 2.606), stdev = 0.010
  CI (99.9%): [2.410, 2.785] (assumes normal distribution)


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.004 ms/op
Iteration   1: 2.465 ±(99.9%) 0.004 ms/op
Iteration   2: 2.500 ±(99.9%) 0.004 ms/op
Iteration   3: 2.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.483 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (2.465, 2.483, 2.500), stdev = 0.018
  CI (99.9%): [2.160, 2.805] (assumes normal distribution)


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
# Warmup Iteration   1: 4.057 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.004 ms/op
Iteration   1: 2.538 ±(99.9%) 0.005 ms/op
Iteration   2: 2.565 ±(99.9%) 0.003 ms/op
Iteration   3: 2.513 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.539 ±(99.9%) 0.479 ms/op [Average]
  (min, avg, max) = (2.513, 2.539, 2.565), stdev = 0.026
  CI (99.9%): [2.060, 3.018] (assumes normal distribution)


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
# Warmup Iteration   1: 4.773 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.006 ms/op
Iteration   1: 3.083 ±(99.9%) 0.005 ms/op
Iteration   2: 3.118 ±(99.9%) 0.006 ms/op
Iteration   3: 3.089 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.097 ±(99.9%) 0.337 ms/op [Average]
  (min, avg, max) = (3.083, 3.097, 3.118), stdev = 0.018
  CI (99.9%): [2.760, 3.433] (assumes normal distribution)


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
# Warmup Iteration   1: 4.620 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.736 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.570 ±(99.9%) 0.006 ms/op
Iteration   1: 2.582 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  11.930 ms/op
                 createUser·p0.9999: 13.783 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   2: 2.555 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  9.354 ms/op
                 createUser·p0.9999: 13.386 ms/op
                 createUser·p1.00:   14.172 ms/op

Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.234 ms/op
                 createUser·p0.99:   3.810 ms/op
                 createUser·p0.999:  9.470 ms/op
                 createUser·p0.9999: 11.647 ms/op
                 createUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374489
  mean =      2.560 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 177602 
    [ 2.500,  3.750) = 192073 
    [ 3.750,  5.000) = 3829 
    [ 5.000,  6.250) = 416 
    [ 6.250,  7.500) = 116 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 147 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     13.386 ms/op
     p(99.9990) =     14.083 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
Iteration   1: 2.535 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.610 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.088 ms/op
                 existUser·p0.95:   3.195 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  5.414 ms/op
                 existUser·p0.9999: 13.910 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.539 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.155 ms/op
                 existUser·p0.50:   2.630 ms/op
                 existUser·p0.90:   3.076 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  9.945 ms/op
                 existUser·p0.9999: 13.779 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   3: 2.581 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.017 ms/op
                 existUser·p0.50:   2.662 ms/op
                 existUser·p0.90:   3.125 ms/op
                 existUser·p0.95:   3.260 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  8.423 ms/op
                 existUser·p0.9999: 12.888 ms/op
                 existUser·p1.00:   13.828 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 376008
  mean =      2.551 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 181410 
    [ 2.500,  3.750) = 190458 
    [ 3.750,  5.000) = 2939 
    [ 5.000,  6.250) = 656 
    [ 6.250,  7.500) = 119 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 117 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      8.225 ms/op
     p(99.9900) =     13.720 ms/op
     p(99.9990) =     14.254 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


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
# Warmup Iteration   1: 3.955 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.006 ms/op
Iteration   1: 2.561 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.689 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.301 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  12.364 ms/op
                 getUser·p0.9999: 13.992 ms/op
                 getUser·p1.00:   14.713 ms/op

Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.802 ms/op
                 getUser·p0.999:  9.737 ms/op
                 getUser·p0.9999: 15.113 ms/op
                 getUser·p1.00:   15.335 ms/op

Iteration   3: 2.579 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.022 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.150 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   3.781 ms/op
                 getUser·p0.999:  8.881 ms/op
                 getUser·p0.9999: 10.886 ms/op
                 getUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374500
  mean =      2.561 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 181830 
    [ 2.500,  3.750) = 187487 
    [ 3.750,  5.000) = 3819 
    [ 5.000,  6.250) = 862 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     14.041 ms/op
     p(99.9990) =     15.241 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


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
# Warmup Iteration   1: 5.027 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.009 ms/op
Iteration   1: 3.142 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.743 ms/op
                 listUser·p0.50:   3.064 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   5.874 ms/op
                 listUser·p0.999:  9.683 ms/op
                 listUser·p0.9999: 11.387 ms/op
                 listUser·p1.00:   12.239 ms/op

Iteration   2: 3.110 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.046 ms/op
                 listUser·p0.50:   3.047 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  9.817 ms/op
                 listUser·p0.9999: 11.169 ms/op
                 listUser·p1.00:   12.419 ms/op

Iteration   3: 3.143 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.060 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   5.816 ms/op
                 listUser·p0.999:  9.970 ms/op
                 listUser·p0.9999: 11.895 ms/op
                 listUser·p1.00:   13.058 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 306301
  mean =      3.131 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 70905 
    [ 2.500,  3.750) = 186708 
    [ 3.750,  5.000) = 39246 
    [ 5.000,  6.250) = 7670 
    [ 6.250,  7.500) = 1033 
    [ 7.500,  8.750) = 151 
    [ 8.750, 10.000) = 250 
    [10.000, 11.250) = 206 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =      9.830 ms/op
     p(99.9900) =     11.665 ms/op
     p(99.9990) =     12.547 ms/op
     p(99.9999) =     13.058 ms/op
    p(100.0000) =     13.058 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.360 ± 1.510  ops/ms
ClientPb.existUser                       thrpt       3  12.797 ± 1.064  ops/ms
ClientPb.getUser                         thrpt       3  12.457 ± 0.525  ops/ms
ClientPb.listUser                        thrpt       3  10.288 ± 1.083  ops/ms
ClientPb.createUser                       avgt       3   2.597 ± 0.188   ms/op
ClientPb.existUser                        avgt       3   2.483 ± 0.323   ms/op
ClientPb.getUser                          avgt       3   2.539 ± 0.479   ms/op
ClientPb.listUser                         avgt       3   3.097 ± 0.337   ms/op
ClientPb.createUser                     sample  374489   2.560 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.939           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.470           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.386           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.189           ms/op
ClientPb.existUser                      sample  376008   2.551 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.610           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.630           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.225           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.720           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.647           ms/op
ClientPb.getUser                        sample  374500   2.561 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.689           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.576           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.946           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.041           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.335           ms/op
ClientPb.listUser                       sample  306301   3.131 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.743           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.060           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.067           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.825           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.830           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.665           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.058           ms/op
