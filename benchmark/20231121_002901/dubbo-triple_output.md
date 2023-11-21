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
# Warmup Iteration   1: 4.308 ops/ms
# Warmup Iteration   2: 11.762 ops/ms
# Warmup Iteration   3: 12.015 ops/ms
Iteration   1: 12.356 ops/ms
Iteration   2: 12.462 ops/ms
Iteration   3: 12.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.451 ±(99.9%) 1.623 ops/ms [Average]
  (min, avg, max) = (12.356, 12.451, 12.533), stdev = 0.089
  CI (99.9%): [10.828, 14.073] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.191 ops/ms
# Warmup Iteration   2: 12.953 ops/ms
# Warmup Iteration   3: 13.052 ops/ms
Iteration   1: 13.128 ops/ms
Iteration   2: 13.210 ops/ms
Iteration   3: 13.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.202 ±(99.9%) 1.272 ops/ms [Average]
  (min, avg, max) = (13.128, 13.202, 13.267), stdev = 0.070
  CI (99.9%): [11.930, 14.473] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.887 ops/ms
# Warmup Iteration   2: 12.526 ops/ms
# Warmup Iteration   3: 12.850 ops/ms
Iteration   1: 12.926 ops/ms
Iteration   2: 12.839 ops/ms
Iteration   3: 12.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.851 ±(99.9%) 1.270 ops/ms [Average]
  (min, avg, max) = (12.789, 12.851, 12.926), stdev = 0.070
  CI (99.9%): [11.581, 14.121] (assumes normal distribution)


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
# Warmup Iteration   1: 6.843 ops/ms
# Warmup Iteration   2: 10.504 ops/ms
# Warmup Iteration   3: 10.530 ops/ms
Iteration   1: 10.640 ops/ms
Iteration   2: 10.594 ops/ms
Iteration   3: 10.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.616 ±(99.9%) 0.420 ops/ms [Average]
  (min, avg, max) = (10.594, 10.616, 10.640), stdev = 0.023
  CI (99.9%): [10.196, 11.037] (assumes normal distribution)


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
# Warmup Iteration   1: 3.974 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.004 ms/op
Iteration   1: 2.520 ±(99.9%) 0.005 ms/op
Iteration   2: 2.500 ±(99.9%) 0.003 ms/op
Iteration   3: 2.522 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.514 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (2.500, 2.514, 2.522), stdev = 0.012
  CI (99.9%): [2.288, 2.740] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.643 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.433 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.003 ms/op
Iteration   1: 2.430 ±(99.9%) 0.004 ms/op
Iteration   2: 2.416 ±(99.9%) 0.004 ms/op
Iteration   3: 2.420 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.422 ±(99.9%) 0.134 ms/op [Average]
  (min, avg, max) = (2.416, 2.422, 2.430), stdev = 0.007
  CI (99.9%): [2.288, 2.556] (assumes normal distribution)


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
# Warmup Iteration   1: 4.040 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.004 ms/op
Iteration   1: 2.471 ±(99.9%) 0.003 ms/op
Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
Iteration   3: 2.490 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.484 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (2.471, 2.484, 2.493), stdev = 0.012
  CI (99.9%): [2.267, 2.702] (assumes normal distribution)


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
# Warmup Iteration   1: 4.948 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.005 ms/op
Iteration   1: 3.001 ±(99.9%) 0.005 ms/op
Iteration   2: 2.982 ±(99.9%) 0.004 ms/op
Iteration   3: 2.989 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.991 ±(99.9%) 0.175 ms/op [Average]
  (min, avg, max) = (2.982, 2.991, 3.001), stdev = 0.010
  CI (99.9%): [2.815, 3.166] (assumes normal distribution)


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
# Warmup Iteration   1: 4.097 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.485 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.940 ms/op
                 createUser·p0.999:  8.279 ms/op
                 createUser·p0.9999: 13.828 ms/op
                 createUser·p1.00:   14.221 ms/op

Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   2.970 ms/op
                 createUser·p0.95:   3.064 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  6.621 ms/op
                 createUser·p0.9999: 11.681 ms/op
                 createUser·p1.00:   12.452 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.920 ms/op
                 createUser·p0.999:  8.215 ms/op
                 createUser·p0.9999: 11.370 ms/op
                 createUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 388048
  mean =      2.472 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 190547 
    [ 2.500,  3.750) = 193167 
    [ 3.750,  5.000) = 3330 
    [ 5.000,  6.250) = 462 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      8.084 ms/op
     p(99.9900) =     13.127 ms/op
     p(99.9990) =     14.025 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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
# Warmup Iteration   1: 3.718 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
Iteration   1: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  6.097 ms/op
                 existUser·p0.9999: 13.668 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   2: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  6.365 ms/op
                 existUser·p0.9999: 12.484 ms/op
                 existUser·p1.00:   12.648 ms/op

Iteration   3: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.694 ms/op
                 existUser·p0.999:  7.763 ms/op
                 existUser·p0.9999: 14.498 ms/op
                 existUser·p1.00:   15.450 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393069
  mean =      2.440 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 196202 
    [ 2.500,  3.750) = 193749 
    [ 3.750,  5.000) = 2135 
    [ 5.000,  6.250) = 478 
    [ 6.250,  7.500) = 100 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.592 ms/op
     p(99.9000) =      6.495 ms/op
     p(99.9900) =     13.802 ms/op
     p(99.9990) =     15.239 ms/op
     p(99.9999) =     15.450 ms/op
    p(100.0000) =     15.450 ms/op


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
# Warmup Iteration   1: 4.033 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.006 ms/op
Iteration   1: 2.489 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.965 ms/op
                 getUser·p0.999:  9.613 ms/op
                 getUser·p0.9999: 13.995 ms/op
                 getUser·p1.00:   15.090 ms/op

Iteration   2: 2.525 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.721 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  6.557 ms/op
                 getUser·p0.9999: 12.343 ms/op
                 getUser·p1.00:   12.780 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  7.847 ms/op
                 getUser·p0.9999: 12.780 ms/op
                 getUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383533
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 190288 
    [ 2.500,  3.750) = 186909 
    [ 3.750,  5.000) = 4456 
    [ 5.000,  6.250) = 1366 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.975 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     14.647 ms/op
     p(99.9999) =     15.090 ms/op
    p(100.0000) =     15.090 ms/op


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
# Warmup Iteration   1: 4.641 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
Iteration   1: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.723 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 10.650 ms/op
                 listUser·p1.00:   10.748 ms/op

Iteration   2: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.944 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.678 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 11.158 ms/op
                 listUser·p1.00:   11.420 ms/op

Iteration   3: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.762 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 11.220 ms/op
                 listUser·p1.00:   13.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317648
  mean =      3.019 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 199 
    [ 1.250,  2.500) = 92134 
    [ 2.500,  3.750) = 184249 
    [ 3.750,  5.000) = 32930 
    [ 5.000,  6.250) = 6506 
    [ 6.250,  7.500) = 955 
    [ 7.500,  8.750) = 210 
    [ 8.750, 10.000) = 276 
    [10.000, 11.250) = 176 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     11.010 ms/op
     p(99.9990) =     11.831 ms/op
     p(99.9999) =     13.304 ms/op
    p(100.0000) =     13.304 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.451 ± 1.623  ops/ms
ClientPb.existUser                       thrpt       3  13.202 ± 1.272  ops/ms
ClientPb.getUser                         thrpt       3  12.851 ± 1.270  ops/ms
ClientPb.listUser                        thrpt       3  10.616 ± 0.420  ops/ms
ClientPb.createUser                       avgt       3   2.514 ± 0.226   ms/op
ClientPb.existUser                        avgt       3   2.422 ± 0.134   ms/op
ClientPb.getUser                          avgt       3   2.484 ± 0.217   ms/op
ClientPb.listUser                         avgt       3   2.991 ± 0.175   ms/op
ClientPb.createUser                     sample  388048   2.472 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.883           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.544           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.994           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.084           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.127           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.221           ms/op
ClientPb.existUser                      sample  393069   2.440 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.852           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.495           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.802           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.450           ms/op
ClientPb.getUser                        sample  383533   2.501 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.721           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.975           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.337           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.090           ms/op
ClientPb.listUser                       sample  317648   3.019 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.762           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.010           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.304           ms/op
