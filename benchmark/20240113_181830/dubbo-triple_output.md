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
# Warmup Iteration   1: 4.952 ops/ms
# Warmup Iteration   2: 11.899 ops/ms
# Warmup Iteration   3: 12.102 ops/ms
Iteration   1: 12.419 ops/ms
Iteration   2: 12.348 ops/ms
Iteration   3: 12.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.420 ±(99.9%) 1.335 ops/ms [Average]
  (min, avg, max) = (12.348, 12.420, 12.494), stdev = 0.073
  CI (99.9%): [11.086, 13.755] (assumes normal distribution)


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
# Warmup Iteration   1: 7.945 ops/ms
# Warmup Iteration   2: 12.680 ops/ms
# Warmup Iteration   3: 12.701 ops/ms
Iteration   1: 12.566 ops/ms
Iteration   2: 12.734 ops/ms
Iteration   3: 12.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.690 ±(99.9%) 1.985 ops/ms [Average]
  (min, avg, max) = (12.566, 12.690, 12.769), stdev = 0.109
  CI (99.9%): [10.704, 14.675] (assumes normal distribution)


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
# Warmup Iteration   1: 7.214 ops/ms
# Warmup Iteration   2: 12.067 ops/ms
# Warmup Iteration   3: 12.580 ops/ms
Iteration   1: 12.713 ops/ms
Iteration   2: 12.577 ops/ms
Iteration   3: 12.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.630 ±(99.9%) 1.320 ops/ms [Average]
  (min, avg, max) = (12.577, 12.630, 12.713), stdev = 0.072
  CI (99.9%): [11.310, 13.951] (assumes normal distribution)


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
# Warmup Iteration   1: 6.628 ops/ms
# Warmup Iteration   2: 10.214 ops/ms
# Warmup Iteration   3: 10.537 ops/ms
Iteration   1: 10.511 ops/ms
Iteration   2: 10.458 ops/ms
Iteration   3: 10.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.484 ±(99.9%) 0.484 ops/ms [Average]
  (min, avg, max) = (10.458, 10.484, 10.511), stdev = 0.027
  CI (99.9%): [10.000, 10.968] (assumes normal distribution)


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
# Warmup Iteration   1: 3.815 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.561 ±(99.9%) 0.004 ms/op
Iteration   1: 2.561 ±(99.9%) 0.004 ms/op
Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
Iteration   3: 2.573 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.558 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (2.540, 2.558, 2.573), stdev = 0.017
  CI (99.9%): [2.253, 2.863] (assumes normal distribution)


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
# Warmup Iteration   1: 3.828 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.005 ms/op
Iteration   1: 2.493 ±(99.9%) 0.004 ms/op
Iteration   2: 2.488 ±(99.9%) 0.003 ms/op
Iteration   3: 2.489 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.490 ±(99.9%) 0.046 ms/op [Average]
  (min, avg, max) = (2.488, 2.490, 2.493), stdev = 0.003
  CI (99.9%): [2.444, 2.536] (assumes normal distribution)


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
# Warmup Iteration   1: 3.901 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.003 ms/op
Iteration   1: 2.511 ±(99.9%) 0.004 ms/op
Iteration   2: 2.507 ±(99.9%) 0.004 ms/op
Iteration   3: 2.509 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.509 ±(99.9%) 0.038 ms/op [Average]
  (min, avg, max) = (2.507, 2.509, 2.511), stdev = 0.002
  CI (99.9%): [2.471, 2.547] (assumes normal distribution)


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
# Warmup Iteration   1: 4.631 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
Iteration   2: 3.032 ±(99.9%) 0.005 ms/op
Iteration   3: 3.042 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.035 ±(99.9%) 0.117 ms/op [Average]
  (min, avg, max) = (3.030, 3.035, 3.042), stdev = 0.006
  CI (99.9%): [2.918, 3.152] (assumes normal distribution)


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.741 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
Iteration   1: 2.577 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  12.075 ms/op
                 createUser·p0.9999: 13.428 ms/op
                 createUser·p1.00:   13.566 ms/op

Iteration   2: 2.567 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  10.426 ms/op
                 createUser·p0.9999: 14.046 ms/op
                 createUser·p1.00:   15.598 ms/op

Iteration   3: 2.559 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.928 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.966 ms/op
                 createUser·p0.999:  10.404 ms/op
                 createUser·p0.9999: 14.627 ms/op
                 createUser·p1.00:   15.614 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373498
  mean =      2.567 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 177588 
    [ 2.500,  3.750) = 191140 
    [ 3.750,  5.000) = 3683 
    [ 5.000,  6.250) = 462 
    [ 6.250,  7.500) = 114 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 130 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =     10.420 ms/op
     p(99.9900) =     14.270 ms/op
     p(99.9990) =     15.598 ms/op
     p(99.9999) =     15.614 ms/op
    p(100.0000) =     15.614 ms/op


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
# Warmup Iteration   1: 3.788 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  7.995 ms/op
                 existUser·p0.9999: 13.746 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  6.407 ms/op
                 existUser·p0.9999: 12.880 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.764 ms/op
                 existUser·p0.999:  6.867 ms/op
                 existUser·p0.9999: 12.586 ms/op
                 existUser·p1.00:   13.238 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388753
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 190864 
    [ 2.500,  3.750) = 194456 
    [ 3.750,  5.000) = 2675 
    [ 5.000,  6.250) = 265 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      7.522 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     14.112 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.560 ±(99.9%) 0.006 ms/op
Iteration   1: 2.556 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.084 ms/op
                 getUser·p0.999:  12.042 ms/op
                 getUser·p0.9999: 13.853 ms/op
                 getUser·p1.00:   14.238 ms/op

Iteration   2: 2.583 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   2.605 ms/op
                 getUser·p0.90:   3.154 ms/op
                 getUser·p0.95:   3.342 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  8.655 ms/op
                 getUser·p0.9999: 14.144 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.704 ms/op
                 getUser·p0.999:  8.163 ms/op
                 getUser·p0.9999: 11.457 ms/op
                 getUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375997
  mean =      2.551 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 182845 
    [ 2.500,  3.750) = 186691 
    [ 3.750,  5.000) = 5215 
    [ 5.000,  6.250) = 716 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      4.116 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     13.795 ms/op
     p(99.9990) =     14.782 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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
# Warmup Iteration   1: 4.889 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.009 ms/op
Iteration   1: 3.049 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.472 ms/op
                 listUser·p0.9999: 11.218 ms/op
                 listUser·p1.00:   11.633 ms/op

Iteration   2: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.978 ms/op
                 listUser·p0.9999: 12.231 ms/op
                 listUser·p1.00:   13.533 ms/op

Iteration   3: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.203 ms/op
                 listUser·p0.9999: 10.850 ms/op
                 listUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315224
  mean =      3.042 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 130 
    [ 1.250,  2.500) = 88025 
    [ 2.500,  3.750) = 185317 
    [ 3.750,  5.000) = 33788 
    [ 5.000,  6.250) = 6358 
    [ 6.250,  7.500) = 858 
    [ 7.500,  8.750) = 213 
    [ 8.750, 10.000) = 326 
    [10.000, 11.250) = 163 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.565 ms/op
     p(99.9900) =     11.640 ms/op
     p(99.9990) =     12.908 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.420 ± 1.335  ops/ms
ClientPb.existUser                       thrpt       3  12.690 ± 1.985  ops/ms
ClientPb.getUser                         thrpt       3  12.630 ± 1.320  ops/ms
ClientPb.listUser                        thrpt       3  10.484 ± 0.484  ops/ms
ClientPb.createUser                       avgt       3   2.558 ± 0.305   ms/op
ClientPb.existUser                        avgt       3   2.490 ± 0.046   ms/op
ClientPb.getUser                          avgt       3   2.509 ± 0.038   ms/op
ClientPb.listUser                         avgt       3   3.035 ± 0.117   ms/op
ClientPb.createUser                     sample  373498   2.567 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.928           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.642           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.999   sample          10.420           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.270           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.614           ms/op
ClientPb.existUser                      sample  388753   2.467 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.824           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.522           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.206           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.008           ms/op
ClientPb.getUser                        sample  375997   2.551 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.696           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.576           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.116           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.552           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.795           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.942           ms/op
ClientPb.listUser                       sample  315224   3.042 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.914           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.565           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.640           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.533           ms/op
