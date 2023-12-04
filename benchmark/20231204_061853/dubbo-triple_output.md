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
# Warmup Iteration   1: 4.650 ops/ms
# Warmup Iteration   2: 11.763 ops/ms
# Warmup Iteration   3: 12.372 ops/ms
Iteration   1: 12.469 ops/ms
Iteration   2: 12.682 ops/ms
Iteration   3: 12.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.606 ±(99.9%) 2.162 ops/ms [Average]
  (min, avg, max) = (12.469, 12.606, 12.682), stdev = 0.118
  CI (99.9%): [10.444, 14.767] (assumes normal distribution)


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
# Warmup Iteration   1: 8.157 ops/ms
# Warmup Iteration   2: 12.962 ops/ms
# Warmup Iteration   3: 12.869 ops/ms
Iteration   1: 12.984 ops/ms
Iteration   2: 13.058 ops/ms
Iteration   3: 12.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.960 ±(99.9%) 2.038 ops/ms [Average]
  (min, avg, max) = (12.838, 12.960, 13.058), stdev = 0.112
  CI (99.9%): [10.922, 14.998] (assumes normal distribution)


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
# Warmup Iteration   1: 7.427 ops/ms
# Warmup Iteration   2: 12.451 ops/ms
# Warmup Iteration   3: 12.593 ops/ms
Iteration   1: 12.922 ops/ms
Iteration   2: 12.624 ops/ms
Iteration   3: 12.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.740 ±(99.9%) 2.910 ops/ms [Average]
  (min, avg, max) = (12.624, 12.740, 12.922), stdev = 0.160
  CI (99.9%): [9.830, 15.650] (assumes normal distribution)


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
# Warmup Iteration   1: 6.395 ops/ms
# Warmup Iteration   2: 10.007 ops/ms
# Warmup Iteration   3: 10.382 ops/ms
Iteration   1: 10.447 ops/ms
Iteration   2: 10.453 ops/ms
Iteration   3: 10.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.450 ±(99.9%) 0.057 ops/ms [Average]
  (min, avg, max) = (10.447, 10.450, 10.453), stdev = 0.003
  CI (99.9%): [10.393, 10.506] (assumes normal distribution)


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
# Warmup Iteration   1: 4.101 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.557 ±(99.9%) 0.005 ms/op
Iteration   1: 2.531 ±(99.9%) 0.004 ms/op
Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
Iteration   3: 2.540 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.542 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (2.531, 2.542, 2.556), stdev = 0.012
  CI (99.9%): [2.318, 2.767] (assumes normal distribution)


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
Iteration   3: 2.460 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.459 ±(99.9%) 0.088 ms/op [Average]
  (min, avg, max) = (2.454, 2.459, 2.463), stdev = 0.005
  CI (99.9%): [2.371, 2.547] (assumes normal distribution)


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
# Warmup Iteration   1: 4.084 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.570 ±(99.9%) 0.004 ms/op
Iteration   1: 2.570 ±(99.9%) 0.004 ms/op
Iteration   2: 2.579 ±(99.9%) 0.004 ms/op
Iteration   3: 2.514 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.554 ±(99.9%) 0.636 ms/op [Average]
  (min, avg, max) = (2.514, 2.554, 2.579), stdev = 0.035
  CI (99.9%): [1.918, 3.191] (assumes normal distribution)


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
# Warmup Iteration   1: 5.025 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
Iteration   1: 3.090 ±(99.9%) 0.005 ms/op
Iteration   2: 3.095 ±(99.9%) 0.005 ms/op
Iteration   3: 3.121 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.102 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (3.090, 3.102, 3.121), stdev = 0.017
  CI (99.9%): [2.793, 3.411] (assumes normal distribution)


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
# Warmup Iteration   1: 4.422 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.659 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.006 ms/op
Iteration   1: 2.546 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.940 ms/op
                 createUser·p0.999:  11.434 ms/op
                 createUser·p0.9999: 13.917 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  9.770 ms/op
                 createUser·p0.9999: 14.303 ms/op
                 createUser·p1.00:   15.073 ms/op

Iteration   3: 2.588 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.318 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  8.970 ms/op
                 createUser·p0.9999: 11.037 ms/op
                 createUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374605
  mean =      2.560 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 177443 
    [ 2.500,  3.750) = 191773 
    [ 3.750,  5.000) = 4177 
    [ 5.000,  6.250) = 694 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      9.001 ms/op
     p(99.9900) =     13.986 ms/op
     p(99.9990) =     14.893 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.046 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
Iteration   1: 2.532 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.996 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.097 ms/op
                 existUser·p0.95:   3.211 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  11.844 ms/op
                 existUser·p0.9999: 14.080 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   2: 2.550 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.113 ms/op
                 existUser·p0.95:   3.236 ms/op
                 existUser·p0.99:   3.895 ms/op
                 existUser·p0.999:  9.688 ms/op
                 existUser·p0.9999: 13.717 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.088 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  8.083 ms/op
                 existUser·p0.9999: 12.294 ms/op
                 existUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 377921
  mean =      2.538 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 186069 
    [ 2.500,  3.750) = 187782 
    [ 3.750,  5.000) = 3109 
    [ 5.000,  6.250) = 467 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 145 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.991 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      8.210 ms/op
     p(99.9900) =     13.812 ms/op
     p(99.9990) =     14.675 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.874 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.661 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.006 ms/op
Iteration   1: 2.540 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.863 ms/op
                 getUser·p0.999:  11.158 ms/op
                 getUser·p0.9999: 16.876 ms/op
                 getUser·p1.00:   17.465 ms/op

Iteration   2: 2.572 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.301 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  9.800 ms/op
                 getUser·p0.9999: 14.631 ms/op
                 getUser·p1.00:   16.630 ms/op

Iteration   3: 2.555 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  8.633 ms/op
                 getUser·p0.9999: 10.437 ms/op
                 getUser·p1.00:   10.633 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375324
  mean =      2.555 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 181486 
    [ 2.500,  3.750) = 188182 
    [ 3.750,  5.000) = 4561 
    [ 5.000,  6.250) = 543 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      4.010 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     15.499 ms/op
     p(99.9990) =     16.924 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 4.795 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.009 ms/op
Iteration   1: 3.051 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.965 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  8.847 ms/op
                 listUser·p0.9999: 11.797 ms/op
                 listUser·p1.00:   12.845 ms/op

Iteration   2: 3.041 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.553 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 11.665 ms/op
                 listUser·p1.00:   13.484 ms/op

Iteration   3: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.016 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 10.404 ms/op
                 listUser·p1.00:   10.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314624
  mean =      3.048 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 111 
    [ 1.250,  2.500) = 85635 
    [ 2.500,  3.750) = 185416 
    [ 3.750,  5.000) = 35307 
    [ 5.000,  6.250) = 6685 
    [ 6.250,  7.500) = 811 
    [ 7.500,  8.750) = 245 
    [ 8.750, 10.000) = 249 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     11.609 ms/op
     p(99.9990) =     12.581 ms/op
     p(99.9999) =     13.484 ms/op
    p(100.0000) =     13.484 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.606 ± 2.162  ops/ms
ClientPb.existUser                       thrpt       3  12.960 ± 2.038  ops/ms
ClientPb.getUser                         thrpt       3  12.740 ± 2.910  ops/ms
ClientPb.listUser                        thrpt       3  10.450 ± 0.057  ops/ms
ClientPb.createUser                       avgt       3   2.542 ± 0.225   ms/op
ClientPb.existUser                        avgt       3   2.459 ± 0.088   ms/op
ClientPb.getUser                          avgt       3   2.554 ± 0.636   ms/op
ClientPb.listUser                         avgt       3   3.102 ± 0.309   ms/op
ClientPb.createUser                     sample  374605   2.560 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.799           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.001           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.986           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.073           ms/op
ClientPb.existUser                      sample  377921   2.538 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.991           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.210           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.812           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.942           ms/op
ClientPb.getUser                        sample  375324   2.555 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.908           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.576           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.929           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.499           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.465           ms/op
ClientPb.listUser                       sample  314624   3.048 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.553           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.977           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.241           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.609           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.484           ms/op
