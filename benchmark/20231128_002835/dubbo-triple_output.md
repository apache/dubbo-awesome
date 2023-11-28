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
# Warmup Iteration   1: 5.001 ops/ms
# Warmup Iteration   2: 12.055 ops/ms
# Warmup Iteration   3: 12.250 ops/ms
Iteration   1: 12.515 ops/ms
Iteration   2: 12.542 ops/ms
Iteration   3: 12.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.545 ±(99.9%) 0.572 ops/ms [Average]
  (min, avg, max) = (12.515, 12.545, 12.577), stdev = 0.031
  CI (99.9%): [11.973, 13.116] (assumes normal distribution)


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
# Warmup Iteration   1: 7.661 ops/ms
# Warmup Iteration   2: 12.860 ops/ms
# Warmup Iteration   3: 12.913 ops/ms
Iteration   1: 12.732 ops/ms
Iteration   2: 12.820 ops/ms
Iteration   3: 12.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.687 ±(99.9%) 2.919 ops/ms [Average]
  (min, avg, max) = (12.509, 12.687, 12.820), stdev = 0.160
  CI (99.9%): [9.768, 15.606] (assumes normal distribution)


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
# Warmup Iteration   1: 7.546 ops/ms
# Warmup Iteration   2: 12.422 ops/ms
# Warmup Iteration   3: 12.651 ops/ms
Iteration   1: 12.654 ops/ms
Iteration   2: 12.671 ops/ms
Iteration   3: 12.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.700 ±(99.9%) 1.191 ops/ms [Average]
  (min, avg, max) = (12.654, 12.700, 12.775), stdev = 0.065
  CI (99.9%): [11.509, 13.890] (assumes normal distribution)


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
# Warmup Iteration   1: 6.739 ops/ms
# Warmup Iteration   2: 10.232 ops/ms
# Warmup Iteration   3: 10.407 ops/ms
Iteration   1: 10.329 ops/ms
Iteration   2: 10.398 ops/ms
Iteration   3: 10.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.384 ±(99.9%) 0.898 ops/ms [Average]
  (min, avg, max) = (10.329, 10.384, 10.425), stdev = 0.049
  CI (99.9%): [9.486, 11.282] (assumes normal distribution)


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
# Warmup Iteration   1: 3.953 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.005 ms/op
Iteration   1: 2.547 ±(99.9%) 0.003 ms/op
Iteration   2: 2.562 ±(99.9%) 0.003 ms/op
Iteration   3: 2.534 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.548 ±(99.9%) 0.251 ms/op [Average]
  (min, avg, max) = (2.534, 2.548, 2.562), stdev = 0.014
  CI (99.9%): [2.297, 2.798] (assumes normal distribution)


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
# Warmup Iteration   1: 3.841 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.003 ms/op
Iteration   1: 2.516 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.507 ±(99.9%) 0.178 ms/op [Average]
  (min, avg, max) = (2.497, 2.507, 2.516), stdev = 0.010
  CI (99.9%): [2.329, 2.685] (assumes normal distribution)


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
# Warmup Iteration   1: 3.872 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.004 ms/op
Iteration   1: 2.517 ±(99.9%) 0.004 ms/op
Iteration   2: 2.504 ±(99.9%) 0.004 ms/op
Iteration   3: 2.519 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.513 ±(99.9%) 0.146 ms/op [Average]
  (min, avg, max) = (2.504, 2.513, 2.519), stdev = 0.008
  CI (99.9%): [2.367, 2.659] (assumes normal distribution)


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
# Warmup Iteration   1: 4.578 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.005 ms/op
Iteration   1: 3.057 ±(99.9%) 0.006 ms/op
Iteration   2: 3.048 ±(99.9%) 0.005 ms/op
Iteration   3: 3.038 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.048 ±(99.9%) 0.172 ms/op [Average]
  (min, avg, max) = (3.038, 3.048, 3.057), stdev = 0.009
  CI (99.9%): [2.876, 3.220] (assumes normal distribution)


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
# Warmup Iteration   1: 4.212 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.699 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.565 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  12.376 ms/op
                 createUser·p0.9999: 14.263 ms/op
                 createUser·p1.00:   17.727 ms/op

Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  9.404 ms/op
                 createUser·p0.9999: 13.271 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  7.816 ms/op
                 createUser·p0.9999: 10.895 ms/op
                 createUser·p1.00:   11.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376321
  mean =      2.549 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 180444 
    [ 2.500,  3.750) = 191153 
    [ 3.750,  5.000) = 3372 
    [ 5.000,  6.250) = 731 
    [ 6.250,  7.500) = 102 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      8.913 ms/op
     p(99.9900) =     13.813 ms/op
     p(99.9990) =     14.553 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 3.584 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  8.996 ms/op
                 existUser·p0.9999: 13.369 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.195 ms/op
                 existUser·p0.99:   3.822 ms/op
                 existUser·p0.999:  9.766 ms/op
                 existUser·p0.9999: 12.183 ms/op
                 existUser·p1.00:   13.042 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.084 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   3.863 ms/op
                 existUser·p0.999:  7.674 ms/op
                 existUser·p0.9999: 12.553 ms/op
                 existUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 381879
  mean =      2.511 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 188830 
    [ 2.500,  3.750) = 188974 
    [ 3.750,  5.000) = 3227 
    [ 5.000,  6.250) = 387 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 147 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      7.720 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     14.110 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 4.239 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.644 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.006 ms/op
Iteration   1: 2.520 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.883 ms/op
                 getUser·p0.999:  11.978 ms/op
                 getUser·p0.9999: 23.734 ms/op
                 getUser·p1.00:   24.773 ms/op

Iteration   2: 2.526 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.809 ms/op
                 getUser·p0.999:  10.040 ms/op
                 getUser·p0.9999: 13.703 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   3: 2.622 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   2.646 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.403 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  9.586 ms/op
                 getUser·p0.9999: 11.096 ms/op
                 getUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375477
  mean =      2.555 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 182947 
    [ 2.500,  5.000) = 189410 
    [ 5.000,  7.500) = 2569 
    [ 7.500, 10.000) = 224 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =      9.635 ms/op
     p(99.9900) =     14.533 ms/op
     p(99.9990) =     24.060 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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
# Warmup Iteration   1: 4.917 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.008 ms/op
Iteration   1: 3.071 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  8.960 ms/op
                 listUser·p0.9999: 11.323 ms/op
                 listUser·p1.00:   12.501 ms/op

Iteration   2: 3.045 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.961 ms/op
                 listUser·p0.9999: 11.182 ms/op
                 listUser·p1.00:   11.780 ms/op

Iteration   3: 3.043 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.010 ms/op
                 listUser·p0.9999: 10.568 ms/op
                 listUser·p1.00:   10.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314149
  mean =      3.053 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 82426 
    [ 2.500,  3.750) = 190719 
    [ 3.750,  5.000) = 33631 
    [ 5.000,  6.250) = 5830 
    [ 6.250,  7.500) = 733 
    [ 7.500,  8.750) = 261 
    [ 8.750, 10.000) = 236 
    [10.000, 11.250) = 176 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.320 ms/op
     p(99.9900) =     11.069 ms/op
     p(99.9990) =     11.773 ms/op
     p(99.9999) =     12.501 ms/op
    p(100.0000) =     12.501 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.545 ± 0.572  ops/ms
ClientPb.existUser                       thrpt       3  12.687 ± 2.919  ops/ms
ClientPb.getUser                         thrpt       3  12.700 ± 1.191  ops/ms
ClientPb.listUser                        thrpt       3  10.384 ± 0.898  ops/ms
ClientPb.createUser                       avgt       3   2.548 ± 0.251   ms/op
ClientPb.existUser                        avgt       3   2.507 ± 0.178   ms/op
ClientPb.getUser                          avgt       3   2.513 ± 0.146   ms/op
ClientPb.listUser                         avgt       3   3.048 ± 0.172   ms/op
ClientPb.createUser                     sample  376321   2.549 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.895           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.913           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.813           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.727           ms/op
ClientPb.existUser                      sample  381879   2.511 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.899           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.720           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.206           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.205           ms/op
ClientPb.getUser                        sample  375477   2.555 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.949           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.576           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.760           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.635           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.533           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.773           ms/op
ClientPb.listUser                       sample  314149   3.053 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.922           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.320           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.069           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.501           ms/op
