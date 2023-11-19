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
# Warmup Iteration   1: 4.766 ops/ms
# Warmup Iteration   2: 11.936 ops/ms
# Warmup Iteration   3: 12.476 ops/ms
Iteration   1: 12.724 ops/ms
Iteration   2: 12.751 ops/ms
Iteration   3: 12.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.785 ±(99.9%) 1.532 ops/ms [Average]
  (min, avg, max) = (12.724, 12.785, 12.881), stdev = 0.084
  CI (99.9%): [11.253, 14.317] (assumes normal distribution)


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
# Warmup Iteration   1: 7.974 ops/ms
# Warmup Iteration   2: 12.883 ops/ms
# Warmup Iteration   3: 13.144 ops/ms
Iteration   1: 13.032 ops/ms
Iteration   2: 12.976 ops/ms
Iteration   3: 12.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.995 ±(99.9%) 0.574 ops/ms [Average]
  (min, avg, max) = (12.976, 12.995, 13.032), stdev = 0.031
  CI (99.9%): [12.422, 13.569] (assumes normal distribution)


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
# Warmup Iteration   1: 7.931 ops/ms
# Warmup Iteration   2: 12.687 ops/ms
# Warmup Iteration   3: 12.908 ops/ms
Iteration   1: 13.070 ops/ms
Iteration   2: 13.041 ops/ms
Iteration   3: 12.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.033 ±(99.9%) 0.739 ops/ms [Average]
  (min, avg, max) = (12.990, 13.033, 13.070), stdev = 0.041
  CI (99.9%): [12.294, 13.772] (assumes normal distribution)


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
# Warmup Iteration   1: 6.679 ops/ms
# Warmup Iteration   2: 10.408 ops/ms
# Warmup Iteration   3: 10.604 ops/ms
Iteration   1: 10.709 ops/ms
Iteration   2: 10.634 ops/ms
Iteration   3: 10.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.706 ±(99.9%) 1.286 ops/ms [Average]
  (min, avg, max) = (10.634, 10.706, 10.774), stdev = 0.070
  CI (99.9%): [9.420, 11.992] (assumes normal distribution)


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
# Warmup Iteration   1: 3.973 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.004 ms/op
Iteration   1: 2.505 ±(99.9%) 0.004 ms/op
Iteration   2: 2.544 ±(99.9%) 0.004 ms/op
Iteration   3: 2.526 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.525 ±(99.9%) 0.361 ms/op [Average]
  (min, avg, max) = (2.505, 2.525, 2.544), stdev = 0.020
  CI (99.9%): [2.164, 2.887] (assumes normal distribution)


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
# Warmup Iteration   1: 3.781 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.445 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.003 ms/op
Iteration   1: 2.469 ±(99.9%) 0.004 ms/op
Iteration   2: 2.447 ±(99.9%) 0.003 ms/op
Iteration   3: 2.439 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.452 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (2.439, 2.452, 2.469), stdev = 0.016
  CI (99.9%): [2.164, 2.739] (assumes normal distribution)


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
# Warmup Iteration   1: 3.874 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.004 ms/op
Iteration   1: 2.488 ±(99.9%) 0.004 ms/op
Iteration   2: 2.518 ±(99.9%) 0.004 ms/op
Iteration   3: 2.475 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.494 ±(99.9%) 0.400 ms/op [Average]
  (min, avg, max) = (2.475, 2.494, 2.518), stdev = 0.022
  CI (99.9%): [2.094, 2.893] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.610 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.005 ms/op
Iteration   1: 3.000 ±(99.9%) 0.005 ms/op
Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
Iteration   3: 2.991 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.993 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (2.989, 2.993, 3.000), stdev = 0.005
  CI (99.9%): [2.893, 3.094] (assumes normal distribution)


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
# Warmup Iteration   1: 4.307 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.629 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.006 ms/op
Iteration   1: 2.497 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.953 ms/op
                 createUser·p0.999:  12.288 ms/op
                 createUser·p0.9999: 15.155 ms/op
                 createUser·p1.00:   17.302 ms/op

Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.008 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   3.459 ms/op
                 createUser·p0.999:  5.989 ms/op
                 createUser·p0.9999: 12.206 ms/op
                 createUser·p1.00:   12.943 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.922 ms/op
                 createUser·p0.999:  8.372 ms/op
                 createUser·p0.9999: 11.289 ms/op
                 createUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386774
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 187135 
    [ 2.500,  3.750) = 195410 
    [ 3.750,  5.000) = 3311 
    [ 5.000,  6.250) = 315 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     16.540 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 3.674 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.488 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  7.542 ms/op
                 existUser·p0.9999: 14.189 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  5.788 ms/op
                 existUser·p0.9999: 13.356 ms/op
                 existUser·p1.00:   13.877 ms/op

Iteration   3: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.703 ms/op
                 existUser·p0.999:  8.176 ms/op
                 existUser·p0.9999: 12.694 ms/op
                 existUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390838
  mean =      2.454 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 195133 
    [ 2.500,  3.750) = 192132 
    [ 3.750,  5.000) = 2586 
    [ 5.000,  6.250) = 520 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 117 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      7.176 ms/op
     p(99.9900) =     13.499 ms/op
     p(99.9990) =     14.303 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 4.049 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.006 ms/op
Iteration   1: 2.484 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  9.004 ms/op
                 getUser·p0.9999: 13.730 ms/op
                 getUser·p1.00:   15.860 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  10.034 ms/op
                 getUser·p0.9999: 14.208 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   3: 2.506 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.689 ms/op
                 getUser·p0.999:  8.310 ms/op
                 getUser·p0.9999: 11.452 ms/op
                 getUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384309
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 189644 
    [ 2.500,  3.750) = 188830 
    [ 3.750,  5.000) = 4192 
    [ 5.000,  6.250) = 1130 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      4.088 ms/op
     p(99.9000) =      8.302 ms/op
     p(99.9900) =     13.690 ms/op
     p(99.9990) =     14.390 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


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
# Warmup Iteration   1: 4.649 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.008 ms/op
Iteration   1: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.842 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.904 ms/op
                 listUser·p0.9999: 12.399 ms/op
                 listUser·p1.00:   13.435 ms/op

Iteration   2: 2.958 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.880 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.458 ms/op
                 listUser·p0.9999: 11.393 ms/op
                 listUser·p1.00:   11.665 ms/op

Iteration   3: 2.963 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.840 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.504 ms/op
                 listUser·p0.999:  9.112 ms/op
                 listUser·p0.9999: 10.456 ms/op
                 listUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323479
  mean =      2.965 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 173 
    [ 1.250,  2.500) = 100208 
    [ 2.500,  3.750) = 186433 
    [ 3.750,  5.000) = 29755 
    [ 5.000,  6.250) = 5634 
    [ 6.250,  7.500) = 605 
    [ 7.500,  8.750) = 202 
    [ 8.750, 10.000) = 248 
    [10.000, 11.250) = 173 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     11.370 ms/op
     p(99.9990) =     13.165 ms/op
     p(99.9999) =     13.435 ms/op
    p(100.0000) =     13.435 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.785 ± 1.532  ops/ms
ClientPb.existUser                       thrpt       3  12.995 ± 0.574  ops/ms
ClientPb.getUser                         thrpt       3  13.033 ± 0.739  ops/ms
ClientPb.listUser                        thrpt       3  10.706 ± 1.286  ops/ms
ClientPb.createUser                       avgt       3   2.525 ± 0.361   ms/op
ClientPb.existUser                        avgt       3   2.452 ± 0.287   ms/op
ClientPb.getUser                          avgt       3   2.494 ± 0.400   ms/op
ClientPb.listUser                         avgt       3   2.993 ± 0.100   ms/op
ClientPb.createUser                     sample  386774   2.480 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.915           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.995           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.730           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.302           ms/op
ClientPb.existUser                      sample  390838   2.454 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.868           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.176           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.499           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.336           ms/op
ClientPb.getUser                        sample  384309   2.496 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.769           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.088           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.302           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.690           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.860           ms/op
ClientPb.listUser                       sample  323479   2.965 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.840           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.486           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.370           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.435           ms/op
