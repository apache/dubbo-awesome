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
# Warmup Iteration   1: 4.752 ops/ms
# Warmup Iteration   2: 11.784 ops/ms
# Warmup Iteration   3: 12.300 ops/ms
Iteration   1: 12.336 ops/ms
Iteration   2: 12.457 ops/ms
Iteration   3: 12.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.432 ±(99.9%) 1.584 ops/ms [Average]
  (min, avg, max) = (12.336, 12.432, 12.504), stdev = 0.087
  CI (99.9%): [10.849, 14.016] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 7.839 ops/ms
# Warmup Iteration   2: 12.818 ops/ms
# Warmup Iteration   3: 12.733 ops/ms
Iteration   1: 12.890 ops/ms
Iteration   2: 12.871 ops/ms
Iteration   3: 12.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.850 ±(99.9%) 1.005 ops/ms [Average]
  (min, avg, max) = (12.787, 12.850, 12.890), stdev = 0.055
  CI (99.9%): [11.844, 13.855] (assumes normal distribution)


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
# Warmup Iteration   1: 7.274 ops/ms
# Warmup Iteration   2: 12.496 ops/ms
# Warmup Iteration   3: 12.559 ops/ms
Iteration   1: 12.720 ops/ms
Iteration   2: 12.744 ops/ms
Iteration   3: 12.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.710 ±(99.9%) 0.727 ops/ms [Average]
  (min, avg, max) = (12.666, 12.710, 12.744), stdev = 0.040
  CI (99.9%): [11.983, 13.437] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.248 ops/ms
# Warmup Iteration   2: 10.257 ops/ms
# Warmup Iteration   3: 10.604 ops/ms
Iteration   1: 10.422 ops/ms
Iteration   2: 10.416 ops/ms
Iteration   3: 10.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.488 ±(99.9%) 2.164 ops/ms [Average]
  (min, avg, max) = (10.416, 10.488, 10.625), stdev = 0.119
  CI (99.9%): [8.324, 12.651] (assumes normal distribution)


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.005 ms/op
Iteration   1: 2.583 ±(99.9%) 0.004 ms/op
Iteration   2: 2.564 ±(99.9%) 0.004 ms/op
Iteration   3: 2.554 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.567 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (2.554, 2.567, 2.583), stdev = 0.015
  CI (99.9%): [2.297, 2.837] (assumes normal distribution)


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
# Warmup Iteration   1: 3.730 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.003 ms/op
Iteration   1: 2.519 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
Iteration   3: 2.503 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.500 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (2.479, 2.500, 2.519), stdev = 0.020
  CI (99.9%): [2.133, 2.868] (assumes normal distribution)


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
# Warmup Iteration   1: 3.937 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.570 ±(99.9%) 0.004 ms/op
Iteration   1: 2.561 ±(99.9%) 0.004 ms/op
Iteration   2: 2.573 ±(99.9%) 0.004 ms/op
Iteration   3: 2.565 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.566 ±(99.9%) 0.110 ms/op [Average]
  (min, avg, max) = (2.561, 2.566, 2.573), stdev = 0.006
  CI (99.9%): [2.456, 2.677] (assumes normal distribution)


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
# Warmup Iteration   1: 4.772 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.007 ms/op
Iteration   1: 3.005 ±(99.9%) 0.005 ms/op
Iteration   2: 3.026 ±(99.9%) 0.005 ms/op
Iteration   3: 3.041 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.024 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (3.005, 3.024, 3.041), stdev = 0.018
  CI (99.9%): [2.691, 3.357] (assumes normal distribution)


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
# Warmup Iteration   1: 4.241 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.698 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.590 ±(99.9%) 0.006 ms/op
Iteration   1: 2.559 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.895 ms/op
                 createUser·p0.999:  11.867 ms/op
                 createUser·p0.9999: 13.543 ms/op
                 createUser·p1.00:   14.057 ms/op

Iteration   2: 2.556 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  9.454 ms/op
                 createUser·p0.9999: 12.272 ms/op
                 createUser·p1.00:   12.419 ms/op

Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  8.192 ms/op
                 createUser·p0.9999: 9.958 ms/op
                 createUser·p1.00:   10.322 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375935
  mean =      2.551 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 178349 
    [ 2.500,  3.750) = 193317 
    [ 3.750,  5.000) = 3431 
    [ 5.000,  6.250) = 359 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 123 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      8.881 ms/op
     p(99.9900) =     13.078 ms/op
     p(99.9990) =     13.955 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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
# Warmup Iteration   1: 3.862 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
Iteration   1: 2.510 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   4.112 ms/op
                 existUser·p0.999:  5.669 ms/op
                 existUser·p0.9999: 13.555 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.186 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.824 ms/op
                 existUser·p0.999:  9.716 ms/op
                 existUser·p0.9999: 14.038 ms/op
                 existUser·p1.00:   15.024 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.576 ms/op
                 existUser·p0.999:  5.337 ms/op
                 existUser·p0.9999: 11.305 ms/op
                 existUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382549
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 186020 
    [ 2.500,  3.750) = 192281 
    [ 3.750,  5.000) = 3491 
    [ 5.000,  6.250) = 336 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      6.213 ms/op
     p(99.9900) =     13.562 ms/op
     p(99.9990) =     14.543 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


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
# Warmup Iteration   1: 4.047 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.651 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.589 ±(99.9%) 0.006 ms/op
Iteration   1: 2.559 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  12.114 ms/op
                 getUser·p0.9999: 13.910 ms/op
                 getUser·p1.00:   14.139 ms/op

Iteration   2: 2.565 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.981 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   3.899 ms/op
                 getUser·p0.999:  9.929 ms/op
                 getUser·p0.9999: 14.255 ms/op
                 getUser·p1.00:   15.073 ms/op

Iteration   3: 2.593 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.142 ms/op
                 getUser·p0.95:   3.326 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  9.290 ms/op
                 getUser·p0.9999: 11.267 ms/op
                 getUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 372848
  mean =      2.572 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 180945 
    [ 2.500,  3.750) = 186008 
    [ 3.750,  5.000) = 4487 
    [ 5.000,  6.250) = 828 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.129 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      4.121 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     13.863 ms/op
     p(99.9990) =     14.853 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


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
# Warmup Iteration   1: 4.820 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.009 ms/op
Iteration   1: 3.040 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  9.156 ms/op
                 listUser·p0.9999: 10.666 ms/op
                 listUser·p1.00:   10.977 ms/op

Iteration   2: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.735 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  10.065 ms/op
                 listUser·p0.9999: 12.009 ms/op
                 listUser·p1.00:   13.271 ms/op

Iteration   3: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.748 ms/op
                 listUser·p0.9999: 11.215 ms/op
                 listUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318066
  mean =      3.016 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 92494 
    [ 2.500,  3.750) = 185601 
    [ 3.750,  5.000) = 32359 
    [ 5.000,  6.250) = 5967 
    [ 6.250,  7.500) = 776 
    [ 7.500,  8.750) = 283 
    [ 8.750, 10.000) = 222 
    [10.000, 11.250) = 206 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.616 ms/op
     p(99.9900) =     11.557 ms/op
     p(99.9990) =     12.200 ms/op
     p(99.9999) =     13.271 ms/op
    p(100.0000) =     13.271 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.432 ± 1.584  ops/ms
ClientPb.existUser                       thrpt       3  12.850 ± 1.005  ops/ms
ClientPb.getUser                         thrpt       3  12.710 ± 0.727  ops/ms
ClientPb.listUser                        thrpt       3  10.488 ± 2.164  ops/ms
ClientPb.createUser                       avgt       3   2.567 ± 0.270   ms/op
ClientPb.existUser                        avgt       3   2.500 ± 0.368   ms/op
ClientPb.getUser                          avgt       3   2.566 ± 0.110   ms/op
ClientPb.listUser                         avgt       3   3.024 ± 0.333   ms/op
ClientPb.createUser                     sample  375935   2.551 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.929           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.881           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.078           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.057           ms/op
ClientPb.existUser                      sample  382549   2.507 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.912           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.213           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.562           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.024           ms/op
ClientPb.getUser                        sample  372848   2.572 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.815           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.597           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.121           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.339           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.863           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.073           ms/op
ClientPb.listUser                       sample  318066   3.016 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.735           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.616           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.557           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.271           ms/op
