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
# Warmup Iteration   1: 4.793 ops/ms
# Warmup Iteration   2: 11.764 ops/ms
# Warmup Iteration   3: 12.187 ops/ms
Iteration   1: 12.431 ops/ms
Iteration   2: 12.408 ops/ms
Iteration   3: 12.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.384 ±(99.9%) 1.122 ops/ms [Average]
  (min, avg, max) = (12.314, 12.384, 12.431), stdev = 0.061
  CI (99.9%): [11.262, 13.506] (assumes normal distribution)


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
# Warmup Iteration   1: 7.936 ops/ms
# Warmup Iteration   2: 12.977 ops/ms
# Warmup Iteration   3: 13.028 ops/ms
Iteration   1: 12.925 ops/ms
Iteration   2: 12.808 ops/ms
Iteration   3: 12.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.879 ±(99.9%) 1.139 ops/ms [Average]
  (min, avg, max) = (12.808, 12.879, 12.925), stdev = 0.062
  CI (99.9%): [11.741, 14.018] (assumes normal distribution)


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
# Warmup Iteration   1: 7.506 ops/ms
# Warmup Iteration   2: 12.613 ops/ms
# Warmup Iteration   3: 12.806 ops/ms
Iteration   1: 12.705 ops/ms
Iteration   2: 12.748 ops/ms
Iteration   3: 12.795 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.749 ±(99.9%) 0.818 ops/ms [Average]
  (min, avg, max) = (12.705, 12.749, 12.795), stdev = 0.045
  CI (99.9%): [11.931, 13.568] (assumes normal distribution)


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
# Warmup Iteration   1: 6.588 ops/ms
# Warmup Iteration   2: 10.568 ops/ms
# Warmup Iteration   3: 10.421 ops/ms
Iteration   1: 10.790 ops/ms
Iteration   2: 10.573 ops/ms
Iteration   3: 10.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.604 ±(99.9%) 3.155 ops/ms [Average]
  (min, avg, max) = (10.449, 10.604, 10.790), stdev = 0.173
  CI (99.9%): [7.449, 13.759] (assumes normal distribution)


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
# Warmup Iteration   1: 4.063 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.003 ms/op
Iteration   1: 2.560 ±(99.9%) 0.003 ms/op
Iteration   2: 2.584 ±(99.9%) 0.005 ms/op
Iteration   3: 2.540 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.561 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (2.540, 2.561, 2.584), stdev = 0.022
  CI (99.9%): [2.156, 2.967] (assumes normal distribution)


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
# Warmup Iteration   1: 3.696 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.003 ms/op
Iteration   1: 2.468 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.003 ms/op
Iteration   3: 2.459 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.471 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (2.459, 2.471, 2.485), stdev = 0.013
  CI (99.9%): [2.234, 2.708] (assumes normal distribution)


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
# Warmup Iteration   1: 3.965 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.582 ±(99.9%) 0.004 ms/op
Iteration   1: 2.542 ±(99.9%) 0.003 ms/op
Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
Iteration   3: 2.543 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.545 ±(99.9%) 0.070 ms/op [Average]
  (min, avg, max) = (2.542, 2.545, 2.549), stdev = 0.004
  CI (99.9%): [2.475, 2.615] (assumes normal distribution)


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
# Warmup Iteration   1: 5.017 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 3.014 ±(99.9%) 0.006 ms/op
Iteration   2: 2.999 ±(99.9%) 0.006 ms/op
Iteration   3: 3.009 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.007 ±(99.9%) 0.148 ms/op [Average]
  (min, avg, max) = (2.999, 3.007, 3.014), stdev = 0.008
  CI (99.9%): [2.860, 3.155] (assumes normal distribution)


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
# Warmup Iteration   1: 4.090 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.684 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.006 ms/op
Iteration   1: 2.580 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.971 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.953 ms/op
                 createUser·p0.999:  12.355 ms/op
                 createUser·p0.9999: 13.678 ms/op
                 createUser·p1.00:   14.090 ms/op

Iteration   2: 2.601 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   4.100 ms/op
                 createUser·p0.999:  9.929 ms/op
                 createUser·p0.9999: 12.583 ms/op
                 createUser·p1.00:   12.927 ms/op

Iteration   3: 2.587 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.745 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.912 ms/op
                 createUser·p0.999:  9.161 ms/op
                 createUser·p0.9999: 10.781 ms/op
                 createUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370405
  mean =      2.589 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 176461 
    [ 2.500,  3.750) = 188684 
    [ 3.750,  5.000) = 3884 
    [ 5.000,  6.250) = 849 
    [ 6.250,  7.500) = 96 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 129 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      2.650 ms/op
     p(90.0000) =      3.142 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      3.985 ms/op
     p(99.9000) =      9.332 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     13.891 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


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
# Warmup Iteration   1: 3.791 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.995 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.408 ms/op
                 existUser·p0.999:  5.602 ms/op
                 existUser·p0.9999: 14.467 ms/op
                 existUser·p1.00:   15.450 ms/op

Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  6.948 ms/op
                 existUser·p0.9999: 12.861 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.850 ms/op
                 existUser·p0.999:  6.750 ms/op
                 existUser·p0.9999: 12.386 ms/op
                 existUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390038
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 191691 
    [ 2.500,  3.750) = 194812 
    [ 3.750,  5.000) = 2706 
    [ 5.000,  6.250) = 370 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      6.750 ms/op
     p(99.9900) =     13.648 ms/op
     p(99.9990) =     15.388 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.053 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.006 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  5.554 ms/op
                 getUser·p0.9999: 13.976 ms/op
                 getUser·p1.00:   14.287 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.739 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.756 ms/op
                 getUser·p0.999:  8.465 ms/op
                 getUser·p0.9999: 14.860 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   3: 2.533 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.133 ms/op
                 getUser·p0.999:  9.042 ms/op
                 getUser·p0.9999: 14.015 ms/op
                 getUser·p1.00:   14.598 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382447
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 188609 
    [ 2.500,  3.750) = 188839 
    [ 3.750,  5.000) = 3771 
    [ 5.000,  6.250) = 747 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      6.681 ms/op
     p(99.9900) =     14.049 ms/op
     p(99.9990) =     15.178 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
# Warmup Iteration   1: 4.840 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.009 ms/op
Iteration   1: 3.062 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  9.748 ms/op
                 listUser·p0.9999: 11.583 ms/op
                 listUser·p1.00:   12.042 ms/op

Iteration   2: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.864 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.795 ms/op
                 listUser·p0.999:  10.045 ms/op
                 listUser·p0.9999: 12.379 ms/op
                 listUser·p1.00:   13.091 ms/op

Iteration   3: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.991 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 11.732 ms/op
                 listUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313581
  mean =      3.059 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 84959 
    [ 2.500,  3.750) = 186287 
    [ 3.750,  5.000) = 34237 
    [ 5.000,  6.250) = 6473 
    [ 6.250,  7.500) = 824 
    [ 7.500,  8.750) = 189 
    [ 8.750, 10.000) = 242 
    [10.000, 11.250) = 174 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.781 ms/op
     p(99.9900) =     11.926 ms/op
     p(99.9990) =     12.892 ms/op
     p(99.9999) =     13.091 ms/op
    p(100.0000) =     13.091 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.384 ± 1.122  ops/ms
ClientPb.existUser                       thrpt       3  12.879 ± 1.139  ops/ms
ClientPb.getUser                         thrpt       3  12.749 ± 0.818  ops/ms
ClientPb.listUser                        thrpt       3  10.604 ± 3.155  ops/ms
ClientPb.createUser                       avgt       3   2.561 ± 0.406   ms/op
ClientPb.existUser                        avgt       3   2.471 ± 0.237   ms/op
ClientPb.getUser                          avgt       3   2.545 ± 0.070   ms/op
ClientPb.listUser                         avgt       3   3.007 ± 0.148   ms/op
ClientPb.createUser                     sample  370405   2.589 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.745           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.650           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.332           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.500           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.090           ms/op
ClientPb.existUser                      sample  390038   2.459 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.864           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.750           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.648           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.450           ms/op
ClientPb.getUser                        sample  382447   2.508 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.739           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.681           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.049           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.516           ms/op
ClientPb.listUser                       sample  313581   3.059 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.864           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.781           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.926           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.091           ms/op
