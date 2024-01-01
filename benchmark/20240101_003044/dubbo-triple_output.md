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
# Warmup Iteration   1: 4.288 ops/ms
# Warmup Iteration   2: 11.857 ops/ms
# Warmup Iteration   3: 12.295 ops/ms
Iteration   1: 12.551 ops/ms
Iteration   2: 12.680 ops/ms
Iteration   3: 12.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.685 ±(99.9%) 2.498 ops/ms [Average]
  (min, avg, max) = (12.551, 12.685, 12.825), stdev = 0.137
  CI (99.9%): [10.187, 15.183] (assumes normal distribution)


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
# Warmup Iteration   1: 7.878 ops/ms
# Warmup Iteration   2: 12.877 ops/ms
# Warmup Iteration   3: 13.133 ops/ms
Iteration   1: 13.081 ops/ms
Iteration   2: 13.105 ops/ms
Iteration   3: 13.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.100 ±(99.9%) 0.295 ops/ms [Average]
  (min, avg, max) = (13.081, 13.100, 13.112), stdev = 0.016
  CI (99.9%): [12.804, 13.395] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.675 ops/ms
# Warmup Iteration   2: 12.535 ops/ms
# Warmup Iteration   3: 12.497 ops/ms
Iteration   1: 12.630 ops/ms
Iteration   2: 12.564 ops/ms
Iteration   3: 12.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.541 ±(99.9%) 1.866 ops/ms [Average]
  (min, avg, max) = (12.429, 12.541, 12.630), stdev = 0.102
  CI (99.9%): [10.675, 14.407] (assumes normal distribution)


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
# Warmup Iteration   1: 6.391 ops/ms
# Warmup Iteration   2: 10.630 ops/ms
# Warmup Iteration   3: 10.571 ops/ms
Iteration   1: 10.579 ops/ms
Iteration   2: 10.552 ops/ms
Iteration   3: 10.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.594 ±(99.9%) 0.938 ops/ms [Average]
  (min, avg, max) = (10.552, 10.594, 10.652), stdev = 0.051
  CI (99.9%): [9.657, 11.532] (assumes normal distribution)


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
# Warmup Iteration   1: 4.029 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.003 ms/op
Iteration   1: 2.619 ±(99.9%) 0.004 ms/op
Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
Iteration   3: 2.615 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.605 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (2.580, 2.605, 2.619), stdev = 0.021
  CI (99.9%): [2.216, 2.994] (assumes normal distribution)


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.004 ms/op
Iteration   1: 2.439 ±(99.9%) 0.003 ms/op
Iteration   2: 2.466 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.458 ±(99.9%) 0.308 ms/op [Average]
  (min, avg, max) = (2.439, 2.458, 2.470), stdev = 0.017
  CI (99.9%): [2.150, 2.767] (assumes normal distribution)


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
# Warmup Iteration   1: 3.976 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.005 ms/op
Iteration   1: 2.534 ±(99.9%) 0.003 ms/op
Iteration   2: 2.546 ±(99.9%) 0.004 ms/op
Iteration   3: 2.541 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.540 ±(99.9%) 0.102 ms/op [Average]
  (min, avg, max) = (2.534, 2.540, 2.546), stdev = 0.006
  CI (99.9%): [2.438, 2.643] (assumes normal distribution)


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
# Warmup Iteration   1: 4.797 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.004 ms/op
Iteration   1: 3.060 ±(99.9%) 0.006 ms/op
Iteration   2: 3.062 ±(99.9%) 0.005 ms/op
Iteration   3: 3.064 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.062 ±(99.9%) 0.033 ms/op [Average]
  (min, avg, max) = (3.060, 3.062, 3.064), stdev = 0.002
  CI (99.9%): [3.029, 3.095] (assumes normal distribution)


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
# Warmup Iteration   1: 4.216 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.639 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.006 ms/op
Iteration   1: 2.551 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  11.485 ms/op
                 createUser·p0.9999: 13.582 ms/op
                 createUser·p1.00:   14.680 ms/op

Iteration   2: 2.590 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  10.044 ms/op
                 createUser·p0.9999: 12.676 ms/op
                 createUser·p1.00:   13.795 ms/op

Iteration   3: 2.575 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   4.017 ms/op
                 createUser·p0.999:  9.011 ms/op
                 createUser·p0.9999: 10.797 ms/op
                 createUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372848
  mean =      2.572 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 176900 
    [ 2.500,  3.750) = 191143 
    [ 3.750,  5.000) = 3927 
    [ 5.000,  6.250) = 412 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.133 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      9.269 ms/op
     p(99.9900) =     13.119 ms/op
     p(99.9990) =     14.310 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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
# Warmup Iteration   1: 3.971 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.527 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
Iteration   1: 2.484 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.441 ms/op
                 existUser·p0.999:  5.084 ms/op
                 existUser·p0.9999: 13.830 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  7.453 ms/op
                 existUser·p0.9999: 13.337 ms/op
                 existUser·p1.00:   13.566 ms/op

Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.068 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  9.502 ms/op
                 existUser·p0.9999: 11.254 ms/op
                 existUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384704
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 189075 
    [ 2.500,  3.750) = 192703 
    [ 3.750,  5.000) = 2264 
    [ 5.000,  6.250) = 193 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      7.691 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     14.234 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 3.997 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.006 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  6.272 ms/op
                 getUser·p0.9999: 14.189 ms/op
                 getUser·p1.00:   14.713 ms/op

Iteration   2: 2.493 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  8.776 ms/op
                 getUser·p0.9999: 14.817 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  6.043 ms/op
                 getUser·p0.9999: 14.680 ms/op
                 getUser·p1.00:   15.008 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386648
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 191862 
    [ 2.500,  3.750) = 189802 
    [ 3.750,  5.000) = 3492 
    [ 5.000,  6.250) = 992 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 94 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      6.990 ms/op
     p(99.9900) =     14.495 ms/op
     p(99.9990) =     15.272 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 5.066 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.009 ms/op
Iteration   1: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.697 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.606 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 12.279 ms/op
                 listUser·p1.00:   12.632 ms/op

Iteration   2: 3.077 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 10.889 ms/op
                 listUser·p1.00:   11.485 ms/op

Iteration   3: 3.079 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.752 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 12.207 ms/op
                 listUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313011
  mean =      3.064 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 83417 
    [ 2.500,  3.750) = 186941 
    [ 3.750,  5.000) = 34892 
    [ 5.000,  6.250) = 6352 
    [ 6.250,  7.500) = 703 
    [ 7.500,  8.750) = 127 
    [ 8.750, 10.000) = 256 
    [10.000, 11.250) = 155 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.627 ms/op
     p(99.9000) =      9.617 ms/op
     p(99.9900) =     12.001 ms/op
     p(99.9990) =     12.581 ms/op
     p(99.9999) =     12.648 ms/op
    p(100.0000) =     12.648 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.685 ± 2.498  ops/ms
ClientPb.existUser                       thrpt       3  13.100 ± 0.295  ops/ms
ClientPb.getUser                         thrpt       3  12.541 ± 1.866  ops/ms
ClientPb.listUser                        thrpt       3  10.594 ± 0.938  ops/ms
ClientPb.createUser                       avgt       3   2.605 ± 0.389   ms/op
ClientPb.existUser                        avgt       3   2.458 ± 0.308   ms/op
ClientPb.getUser                          avgt       3   2.540 ± 0.102   ms/op
ClientPb.listUser                         avgt       3   3.062 ± 0.033   ms/op
ClientPb.createUser                     sample  372848   2.572 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.936           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.269           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.119           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.302           ms/op
ClientPb.existUser                      sample  384704   2.493 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.971           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.691           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.337           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.320           ms/op
ClientPb.getUser                        sample  386648   2.481 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.760           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.990           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.495           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.401           ms/op
ClientPb.listUser                       sample  313011   3.064 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.697           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.011           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.627           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.617           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.001           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.648           ms/op
