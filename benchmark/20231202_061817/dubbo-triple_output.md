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
# Warmup Iteration   1: 5.152 ops/ms
# Warmup Iteration   2: 11.867 ops/ms
# Warmup Iteration   3: 12.071 ops/ms
Iteration   1: 12.413 ops/ms
Iteration   2: 12.284 ops/ms
Iteration   3: 12.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.334 ±(99.9%) 1.272 ops/ms [Average]
  (min, avg, max) = (12.284, 12.334, 12.413), stdev = 0.070
  CI (99.9%): [11.062, 13.606] (assumes normal distribution)


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
# Warmup Iteration   1: 8.547 ops/ms
# Warmup Iteration   2: 13.023 ops/ms
# Warmup Iteration   3: 13.008 ops/ms
Iteration   1: 12.925 ops/ms
Iteration   2: 13.070 ops/ms
Iteration   3: 13.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.024 ±(99.9%) 1.562 ops/ms [Average]
  (min, avg, max) = (12.925, 13.024, 13.077), stdev = 0.086
  CI (99.9%): [11.462, 14.586] (assumes normal distribution)


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
# Warmup Iteration   1: 7.737 ops/ms
# Warmup Iteration   2: 12.609 ops/ms
# Warmup Iteration   3: 12.556 ops/ms
Iteration   1: 12.647 ops/ms
Iteration   2: 12.801 ops/ms
Iteration   3: 12.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.741 ±(99.9%) 1.501 ops/ms [Average]
  (min, avg, max) = (12.647, 12.741, 12.801), stdev = 0.082
  CI (99.9%): [11.240, 14.242] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.795 ops/ms
# Warmup Iteration   2: 10.410 ops/ms
# Warmup Iteration   3: 10.409 ops/ms
Iteration   1: 10.435 ops/ms
Iteration   2: 10.498 ops/ms
Iteration   3: 10.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.458 ±(99.9%) 0.632 ops/ms [Average]
  (min, avg, max) = (10.435, 10.458, 10.498), stdev = 0.035
  CI (99.9%): [9.826, 11.090] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.076 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.628 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.582 ±(99.9%) 0.004 ms/op
Iteration   1: 2.549 ±(99.9%) 0.004 ms/op
Iteration   2: 2.592 ±(99.9%) 0.003 ms/op
Iteration   3: 2.554 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.565 ±(99.9%) 0.432 ms/op [Average]
  (min, avg, max) = (2.549, 2.565, 2.592), stdev = 0.024
  CI (99.9%): [2.133, 2.997] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.654 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.004 ms/op
Iteration   1: 2.455 ±(99.9%) 0.004 ms/op
Iteration   2: 2.469 ±(99.9%) 0.004 ms/op
Iteration   3: 2.510 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.478 ±(99.9%) 0.522 ms/op [Average]
  (min, avg, max) = (2.455, 2.478, 2.510), stdev = 0.029
  CI (99.9%): [1.956, 3.000] (assumes normal distribution)


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
# Warmup Iteration   1: 3.875 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.640 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.004 ms/op
Iteration   1: 2.528 ±(99.9%) 0.004 ms/op
Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
Iteration   3: 2.531 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.524 ±(99.9%) 0.176 ms/op [Average]
  (min, avg, max) = (2.513, 2.524, 2.531), stdev = 0.010
  CI (99.9%): [2.348, 2.700] (assumes normal distribution)


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
# Warmup Iteration   1: 4.554 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.005 ms/op
Iteration   1: 3.047 ±(99.9%) 0.005 ms/op
Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
Iteration   3: 3.045 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.047 ±(99.9%) 0.044 ms/op [Average]
  (min, avg, max) = (3.045, 3.047, 3.049), stdev = 0.002
  CI (99.9%): [3.003, 3.091] (assumes normal distribution)


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
# Warmup Iteration   1: 4.020 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.742 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.006 ms/op
Iteration   1: 2.552 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  11.888 ms/op
                 createUser·p0.9999: 14.344 ms/op
                 createUser·p1.00:   15.090 ms/op

Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  9.683 ms/op
                 createUser·p0.9999: 12.124 ms/op
                 createUser·p1.00:   13.599 ms/op

Iteration   3: 2.549 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  9.054 ms/op
                 createUser·p0.9999: 11.551 ms/op
                 createUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376335
  mean =      2.548 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 180172 
    [ 2.500,  3.750) = 192070 
    [ 3.750,  5.000) = 3218 
    [ 5.000,  6.250) = 320 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 137 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      9.186 ms/op
     p(99.9900) =     13.572 ms/op
     p(99.9990) =     14.946 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.845 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.015 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  10.549 ms/op
                 existUser·p0.9999: 14.309 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  5.407 ms/op
                 existUser·p0.9999: 13.812 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.952 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.834 ms/op
                 existUser·p0.999:  7.333 ms/op
                 existUser·p0.9999: 12.403 ms/op
                 existUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385344
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 187118 
    [ 2.500,  3.750) = 194786 
    [ 3.750,  5.000) = 2679 
    [ 5.000,  6.250) = 313 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 146 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      6.674 ms/op
     p(99.9900) =     13.721 ms/op
     p(99.9990) =     14.978 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


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
# Warmup Iteration   1: 3.835 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
Iteration   1: 2.529 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.018 ms/op
                 getUser·p0.999:  11.633 ms/op
                 getUser·p0.9999: 14.020 ms/op
                 getUser·p1.00:   14.434 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   4.006 ms/op
                 getUser·p0.999:  8.978 ms/op
                 getUser·p0.9999: 13.995 ms/op
                 getUser·p1.00:   14.647 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.525 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  8.585 ms/op
                 getUser·p0.9999: 11.947 ms/op
                 getUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382711
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 188484 
    [ 2.500,  3.750) = 188023 
    [ 3.750,  5.000) = 4865 
    [ 5.000,  6.250) = 847 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.525 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      4.047 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     13.812 ms/op
     p(99.9990) =     14.443 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.903 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.009 ms/op
Iteration   1: 3.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.693 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.626 ms/op
                 listUser·p0.9999: 11.031 ms/op
                 listUser·p1.00:   11.747 ms/op

Iteration   2: 3.054 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.754 ms/op
                 listUser·p0.9999: 16.212 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   3: 3.054 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.004 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  8.950 ms/op
                 listUser·p0.9999: 9.905 ms/op
                 listUser·p1.00:   10.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314885
  mean =      3.046 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 86665 
    [ 2.500,  3.750) = 185867 
    [ 3.750,  5.000) = 34818 
    [ 5.000,  6.250) = 6020 
    [ 6.250,  7.500) = 703 
    [ 7.500,  8.750) = 229 
    [ 8.750, 10.000) = 291 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     12.624 ms/op
     p(99.9990) =     16.660 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.334 ± 1.272  ops/ms
ClientPb.existUser                       thrpt       3  13.024 ± 1.562  ops/ms
ClientPb.getUser                         thrpt       3  12.741 ± 1.501  ops/ms
ClientPb.listUser                        thrpt       3  10.458 ± 0.632  ops/ms
ClientPb.createUser                       avgt       3   2.565 ± 0.432   ms/op
ClientPb.existUser                        avgt       3   2.478 ± 0.522   ms/op
ClientPb.getUser                          avgt       3   2.524 ± 0.176   ms/op
ClientPb.listUser                         avgt       3   3.047 ± 0.044   ms/op
ClientPb.createUser                     sample  376335   2.548 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.932           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.186           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.572           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.090           ms/op
ClientPb.existUser                      sample  385344   2.489 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.750           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.674           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.721           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.385           ms/op
ClientPb.getUser                        sample  382711   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.525           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.602           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.812           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.647           ms/op
ClientPb.listUser                       sample  314885   3.046 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.693           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.454           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.624           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.810           ms/op
