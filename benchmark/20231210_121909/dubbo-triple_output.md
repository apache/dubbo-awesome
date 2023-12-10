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
# Warmup Iteration   1: 4.916 ops/ms
# Warmup Iteration   2: 12.023 ops/ms
# Warmup Iteration   3: 12.218 ops/ms
Iteration   1: 12.477 ops/ms
Iteration   2: 12.688 ops/ms
Iteration   3: 12.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.555 ±(99.9%) 2.106 ops/ms [Average]
  (min, avg, max) = (12.477, 12.555, 12.688), stdev = 0.115
  CI (99.9%): [10.450, 14.661] (assumes normal distribution)


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
# Warmup Iteration   1: 8.354 ops/ms
# Warmup Iteration   2: 13.110 ops/ms
# Warmup Iteration   3: 13.065 ops/ms
Iteration   1: 13.118 ops/ms
Iteration   2: 13.199 ops/ms
Iteration   3: 13.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.178 ±(99.9%) 0.960 ops/ms [Average]
  (min, avg, max) = (13.118, 13.178, 13.216), stdev = 0.053
  CI (99.9%): [12.218, 14.138] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.415 ops/ms
# Warmup Iteration   2: 12.423 ops/ms
# Warmup Iteration   3: 12.697 ops/ms
Iteration   1: 12.924 ops/ms
Iteration   2: 12.735 ops/ms
Iteration   3: 12.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.831 ±(99.9%) 1.722 ops/ms [Average]
  (min, avg, max) = (12.735, 12.831, 12.924), stdev = 0.094
  CI (99.9%): [11.110, 14.553] (assumes normal distribution)


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
# Warmup Iteration   1: 6.128 ops/ms
# Warmup Iteration   2: 10.419 ops/ms
# Warmup Iteration   3: 10.679 ops/ms
Iteration   1: 10.669 ops/ms
Iteration   2: 10.664 ops/ms
Iteration   3: 10.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.673 ±(99.9%) 0.214 ops/ms [Average]
  (min, avg, max) = (10.664, 10.673, 10.686), stdev = 0.012
  CI (99.9%): [10.459, 10.887] (assumes normal distribution)


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
# Warmup Iteration   1: 4.087 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.004 ms/op
Iteration   1: 2.519 ±(99.9%) 0.004 ms/op
Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
Iteration   3: 2.530 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.523 ±(99.9%) 0.102 ms/op [Average]
  (min, avg, max) = (2.519, 2.523, 2.530), stdev = 0.006
  CI (99.9%): [2.422, 2.625] (assumes normal distribution)


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.004 ms/op
Iteration   1: 2.459 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.003 ms/op
Iteration   3: 2.459 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.460 ±(99.9%) 0.042 ms/op [Average]
  (min, avg, max) = (2.459, 2.460, 2.463), stdev = 0.002
  CI (99.9%): [2.418, 2.503] (assumes normal distribution)


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
# Warmup Iteration   1: 4.057 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.532 ±(99.9%) 0.005 ms/op
Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
Iteration   3: 2.517 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.515 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (2.495, 2.515, 2.532), stdev = 0.019
  CI (99.9%): [2.177, 2.853] (assumes normal distribution)


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
# Warmup Iteration   1: 4.552 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
Iteration   1: 3.009 ±(99.9%) 0.005 ms/op
Iteration   2: 2.987 ±(99.9%) 0.005 ms/op
Iteration   3: 3.010 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.002 ±(99.9%) 0.238 ms/op [Average]
  (min, avg, max) = (2.987, 3.002, 3.010), stdev = 0.013
  CI (99.9%): [2.764, 3.240] (assumes normal distribution)


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
# Warmup Iteration   1: 4.086 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.696 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
Iteration   1: 2.519 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.629 ms/op
                 createUser·p0.999:  11.880 ms/op
                 createUser·p0.9999: 14.008 ms/op
                 createUser·p1.00:   14.942 ms/op

Iteration   2: 2.533 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  8.910 ms/op
                 createUser·p0.9999: 22.184 ms/op
                 createUser·p1.00:   22.741 ms/op

Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.895 ms/op
                 createUser·p0.999:  8.285 ms/op
                 createUser·p0.9999: 10.876 ms/op
                 createUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378988
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 179343 
    [ 2.500,  5.000) = 198671 
    [ 5.000,  7.500) = 579 
    [ 7.500, 10.000) = 129 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      8.372 ms/op
     p(99.9900) =     14.729 ms/op
     p(99.9990) =     22.474 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 3.796 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.504 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.006 ms/op
Iteration   1: 2.507 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.695 ms/op
                 existUser·p0.999:  11.571 ms/op
                 existUser·p0.9999: 16.031 ms/op
                 existUser·p1.00:   16.548 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.191 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.615 ms/op
                 existUser·p0.9999: 12.911 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.042 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  9.371 ms/op
                 existUser·p0.9999: 12.157 ms/op
                 existUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383398
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 187920 
    [ 2.500,  3.750) = 191220 
    [ 3.750,  5.000) = 3125 
    [ 5.000,  6.250) = 597 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      7.902 ms/op
     p(99.9900) =     15.259 ms/op
     p(99.9990) =     16.217 ms/op
     p(99.9999) =     16.548 ms/op
    p(100.0000) =     16.548 ms/op


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
# Warmup Iteration   1: 3.941 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.633 ms/op
                 getUser·p0.999:  6.162 ms/op
                 getUser·p0.9999: 13.812 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   4.022 ms/op
                 getUser·p0.999:  5.857 ms/op
                 getUser·p0.9999: 14.185 ms/op
                 getUser·p1.00:   15.450 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.690 ms/op
                 getUser·p0.999:  6.683 ms/op
                 getUser·p0.9999: 11.193 ms/op
                 getUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386499
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 192023 
    [ 2.500,  3.750) = 190521 
    [ 3.750,  5.000) = 3236 
    [ 5.000,  6.250) = 304 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      6.050 ms/op
     p(99.9900) =     13.577 ms/op
     p(99.9990) =     15.223 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.668 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.009 ms/op
Iteration   1: 3.083 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.928 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.732 ms/op
                 listUser·p0.9999: 11.971 ms/op
                 listUser·p1.00:   13.107 ms/op

Iteration   2: 3.054 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.033 ms/op
                 listUser·p0.9999: 11.068 ms/op
                 listUser·p1.00:   13.517 ms/op

Iteration   3: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.035 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 10.837 ms/op
                 listUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313808
  mean =      3.056 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 82419 
    [ 2.500,  3.750) = 189762 
    [ 3.750,  5.000) = 34366 
    [ 5.000,  6.250) = 5710 
    [ 6.250,  7.500) = 770 
    [ 7.500,  8.750) = 241 
    [ 8.750, 10.000) = 283 
    [10.000, 11.250) = 143 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     11.233 ms/op
     p(99.9990) =     13.069 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.555 ± 2.106  ops/ms
ClientPb.existUser                       thrpt       3  13.178 ± 0.960  ops/ms
ClientPb.getUser                         thrpt       3  12.831 ± 1.722  ops/ms
ClientPb.listUser                        thrpt       3  10.673 ± 0.214  ops/ms
ClientPb.createUser                       avgt       3   2.523 ± 0.102   ms/op
ClientPb.existUser                        avgt       3   2.460 ± 0.042   ms/op
ClientPb.getUser                          avgt       3   2.515 ± 0.338   ms/op
ClientPb.listUser                         avgt       3   3.002 ± 0.238   ms/op
ClientPb.createUser                     sample  378988   2.530 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.918           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.372           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.729           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.741           ms/op
ClientPb.existUser                      sample  383398   2.502 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.717           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.902           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.259           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.548           ms/op
ClientPb.getUser                        sample  386499   2.482 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.674           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.050           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.577           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.450           ms/op
ClientPb.listUser                       sample  313808   3.056 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.835           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.355           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.233           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.517           ms/op
