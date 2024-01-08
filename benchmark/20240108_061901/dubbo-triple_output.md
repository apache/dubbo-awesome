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
# Warmup Iteration   1: 4.403 ops/ms
# Warmup Iteration   2: 11.723 ops/ms
# Warmup Iteration   3: 12.012 ops/ms
Iteration   1: 12.618 ops/ms
Iteration   2: 12.293 ops/ms
Iteration   3: 12.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.523 ±(99.9%) 3.665 ops/ms [Average]
  (min, avg, max) = (12.293, 12.523, 12.659), stdev = 0.201
  CI (99.9%): [8.859, 16.188] (assumes normal distribution)


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
# Warmup Iteration   1: 7.915 ops/ms
# Warmup Iteration   2: 12.581 ops/ms
# Warmup Iteration   3: 12.676 ops/ms
Iteration   1: 12.770 ops/ms
Iteration   2: 12.835 ops/ms
Iteration   3: 12.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.743 ±(99.9%) 1.988 ops/ms [Average]
  (min, avg, max) = (12.623, 12.743, 12.835), stdev = 0.109
  CI (99.9%): [10.755, 14.730] (assumes normal distribution)


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
# Warmup Iteration   1: 7.291 ops/ms
# Warmup Iteration   2: 12.436 ops/ms
# Warmup Iteration   3: 12.633 ops/ms
Iteration   1: 12.626 ops/ms
Iteration   2: 12.693 ops/ms
Iteration   3: 12.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.643 ±(99.9%) 0.805 ops/ms [Average]
  (min, avg, max) = (12.610, 12.643, 12.693), stdev = 0.044
  CI (99.9%): [11.838, 13.448] (assumes normal distribution)


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
# Warmup Iteration   1: 6.865 ops/ms
# Warmup Iteration   2: 10.253 ops/ms
# Warmup Iteration   3: 10.365 ops/ms
Iteration   1: 10.608 ops/ms
Iteration   2: 10.494 ops/ms
Iteration   3: 10.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.532 ±(99.9%) 1.206 ops/ms [Average]
  (min, avg, max) = (10.493, 10.532, 10.608), stdev = 0.066
  CI (99.9%): [9.325, 11.738] (assumes normal distribution)


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
# Warmup Iteration   1: 4.030 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.665 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.605 ±(99.9%) 0.004 ms/op
Iteration   1: 2.590 ±(99.9%) 0.004 ms/op
Iteration   2: 2.572 ±(99.9%) 0.005 ms/op
Iteration   3: 2.539 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.567 ±(99.9%) 0.475 ms/op [Average]
  (min, avg, max) = (2.539, 2.567, 2.590), stdev = 0.026
  CI (99.9%): [2.092, 3.042] (assumes normal distribution)


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
# Warmup Iteration   1: 3.871 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.004 ms/op
Iteration   1: 2.521 ±(99.9%) 0.004 ms/op
Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
Iteration   3: 2.493 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.506 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (2.493, 2.506, 2.521), stdev = 0.014
  CI (99.9%): [2.244, 2.767] (assumes normal distribution)


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.663 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.578 ±(99.9%) 0.004 ms/op
Iteration   1: 2.562 ±(99.9%) 0.005 ms/op
Iteration   2: 2.589 ±(99.9%) 0.005 ms/op
Iteration   3: 2.570 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.574 ±(99.9%) 0.256 ms/op [Average]
  (min, avg, max) = (2.562, 2.574, 2.589), stdev = 0.014
  CI (99.9%): [2.317, 2.830] (assumes normal distribution)


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
# Warmup Iteration   1: 4.955 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.005 ms/op
Iteration   1: 3.068 ±(99.9%) 0.006 ms/op
Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
Iteration   3: 3.106 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.081 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (3.068, 3.081, 3.106), stdev = 0.021
  CI (99.9%): [2.694, 3.468] (assumes normal distribution)


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
# Warmup Iteration   1: 4.458 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.734 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.588 ±(99.9%) 0.006 ms/op
Iteration   1: 2.568 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.697 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  11.664 ms/op
                 createUser·p0.9999: 14.549 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.609 ms/op
                 createUser·p0.999:  9.726 ms/op
                 createUser·p0.9999: 14.981 ms/op
                 createUser·p1.00:   16.155 ms/op

Iteration   3: 2.579 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.675 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  9.880 ms/op
                 createUser·p0.9999: 12.865 ms/op
                 createUser·p1.00:   15.925 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374904
  mean =      2.559 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 179626 
    [ 2.500,  3.750) = 191490 
    [ 3.750,  5.000) = 2964 
    [ 5.000,  6.250) = 357 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      9.766 ms/op
     p(99.9900) =     14.549 ms/op
     p(99.9990) =     15.876 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  7.134 ms/op
                 existUser·p0.9999: 14.008 ms/op
                 existUser·p1.00:   14.762 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  7.409 ms/op
                 existUser·p0.9999: 13.942 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.648 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.805 ms/op
                 existUser·p0.999:  8.645 ms/op
                 existUser·p0.9999: 12.550 ms/op
                 existUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389606
  mean =      2.461 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 196105 
    [ 2.500,  3.750) = 189951 
    [ 3.750,  5.000) = 2600 
    [ 5.000,  6.250) = 408 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 115 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      8.084 ms/op
     p(99.9900) =     13.862 ms/op
     p(99.9990) =     14.665 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 3.922 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.046 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.767 ms/op
                 getUser·p0.999:  5.472 ms/op
                 getUser·p0.9999: 14.638 ms/op
                 getUser·p1.00:   15.237 ms/op

Iteration   2: 2.613 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   2.658 ms/op
                 getUser·p0.90:   3.170 ms/op
                 getUser·p0.95:   3.367 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  9.142 ms/op
                 getUser·p0.9999: 14.889 ms/op
                 getUser·p1.00:   15.712 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  8.503 ms/op
                 getUser·p0.9999: 11.972 ms/op
                 getUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376746
  mean =      2.546 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 182974 
    [ 2.500,  3.750) = 186919 
    [ 3.750,  5.000) = 5299 
    [ 5.000,  6.250) = 935 
    [ 6.250,  7.500) = 137 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      4.153 ms/op
     p(99.9000) =      7.922 ms/op
     p(99.9900) =     14.461 ms/op
     p(99.9990) =     15.433 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


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
# Warmup Iteration   1: 4.712 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.009 ms/op
Iteration   1: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.834 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.432 ms/op
                 listUser·p0.9999: 11.542 ms/op
                 listUser·p1.00:   11.895 ms/op

Iteration   2: 3.045 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.026 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 10.854 ms/op
                 listUser·p1.00:   11.534 ms/op

Iteration   3: 3.080 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.775 ms/op
                 listUser·p0.999:  10.325 ms/op
                 listUser·p0.9999: 13.091 ms/op
                 listUser·p1.00:   13.697 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314125
  mean =      3.053 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 82531 
    [ 2.500,  3.750) = 189465 
    [ 3.750,  5.000) = 34045 
    [ 5.000,  6.250) = 6506 
    [ 6.250,  7.500) = 810 
    [ 7.500,  8.750) = 163 
    [ 8.750, 10.000) = 242 
    [10.000, 11.250) = 210 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.748 ms/op
     p(99.9900) =     11.514 ms/op
     p(99.9990) =     13.370 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.523 ± 3.665  ops/ms
ClientPb.existUser                       thrpt       3  12.743 ± 1.988  ops/ms
ClientPb.getUser                         thrpt       3  12.643 ± 0.805  ops/ms
ClientPb.listUser                        thrpt       3  10.532 ± 1.206  ops/ms
ClientPb.createUser                       avgt       3   2.567 ± 0.475   ms/op
ClientPb.existUser                        avgt       3   2.506 ± 0.262   ms/op
ClientPb.getUser                          avgt       3   2.574 ± 0.256   ms/op
ClientPb.listUser                         avgt       3   3.081 ± 0.387   ms/op
ClientPb.createUser                     sample  374904   2.559 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.697           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.634           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.766           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.549           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.155           ms/op
ClientPb.existUser                      sample  389606   2.461 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.648           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.084           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.862           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.762           ms/op
ClientPb.getUser                        sample  376746   2.546 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.813           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.153           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.922           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.461           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.712           ms/op
ClientPb.listUser                       sample  314125   3.053 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.834           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.982           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.748           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.514           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.697           ms/op
