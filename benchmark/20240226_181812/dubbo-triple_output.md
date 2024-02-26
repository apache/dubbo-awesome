# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.713 ops/ms
# Warmup Iteration   2: 12.423 ops/ms
# Warmup Iteration   3: 12.404 ops/ms
Iteration   1: 12.706 ops/ms
Iteration   2: 12.655 ops/ms
Iteration   3: 12.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.745 ±(99.9%) 2.086 ops/ms [Average]
  (min, avg, max) = (12.655, 12.745, 12.874), stdev = 0.114
  CI (99.9%): [10.659, 14.831] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.520 ops/ms
# Warmup Iteration   2: 13.030 ops/ms
# Warmup Iteration   3: 13.059 ops/ms
Iteration   1: 13.119 ops/ms
Iteration   2: 13.045 ops/ms
Iteration   3: 13.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.107 ±(99.9%) 1.044 ops/ms [Average]
  (min, avg, max) = (13.045, 13.107, 13.157), stdev = 0.057
  CI (99.9%): [12.063, 14.151] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.920 ops/ms
# Warmup Iteration   2: 12.816 ops/ms
# Warmup Iteration   3: 12.756 ops/ms
Iteration   1: 12.878 ops/ms
Iteration   2: 12.825 ops/ms
Iteration   3: 12.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.864 ±(99.9%) 0.627 ops/ms [Average]
  (min, avg, max) = (12.825, 12.864, 12.890), stdev = 0.034
  CI (99.9%): [12.237, 13.491] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.833 ops/ms
# Warmup Iteration   2: 10.627 ops/ms
# Warmup Iteration   3: 10.775 ops/ms
Iteration   1: 10.720 ops/ms
Iteration   2: 10.731 ops/ms
Iteration   3: 10.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.708 ±(99.9%) 0.559 ops/ms [Average]
  (min, avg, max) = (10.673, 10.708, 10.731), stdev = 0.031
  CI (99.9%): [10.149, 11.267] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.763 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
Iteration   1: 2.535 ±(99.9%) 0.004 ms/op
Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
Iteration   3: 2.513 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.518 ±(99.9%) 0.279 ms/op [Average]
  (min, avg, max) = (2.506, 2.518, 2.535), stdev = 0.015
  CI (99.9%): [2.239, 2.797] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.764 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.004 ms/op
Iteration   1: 2.458 ±(99.9%) 0.003 ms/op
Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
Iteration   3: 2.479 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.468 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (2.458, 2.468, 2.479), stdev = 0.010
  CI (99.9%): [2.279, 2.657] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.903 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.004 ms/op
Iteration   1: 2.482 ±(99.9%) 0.004 ms/op
Iteration   2: 2.487 ±(99.9%) 0.003 ms/op
Iteration   3: 2.481 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.483 ±(99.9%) 0.062 ms/op [Average]
  (min, avg, max) = (2.481, 2.483, 2.487), stdev = 0.003
  CI (99.9%): [2.421, 2.546] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.026 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.004 ms/op
Iteration   1: 3.071 ±(99.9%) 0.006 ms/op
Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
Iteration   3: 3.061 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.067 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (3.061, 3.067, 3.071), stdev = 0.005
  CI (99.9%): [2.968, 3.167] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.079 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.690 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.006 ms/op
Iteration   1: 2.529 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.735 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  11.180 ms/op
                 createUser·p0.9999: 13.967 ms/op
                 createUser·p1.00:   15.548 ms/op

Iteration   2: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.604 ms/op
                 createUser·p0.999:  9.287 ms/op
                 createUser·p0.9999: 12.933 ms/op
                 createUser·p1.00:   13.320 ms/op

Iteration   3: 2.572 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.875 ms/op
                 createUser·p0.999:  8.618 ms/op
                 createUser·p0.9999: 11.602 ms/op
                 createUser·p1.00:   13.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376654
  mean =      2.546 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 179944 
    [ 2.500,  3.750) = 192655 
    [ 3.750,  5.000) = 3233 
    [ 5.000,  6.250) = 316 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 112 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     13.309 ms/op
     p(99.9990) =     15.110 ms/op
     p(99.9999) =     15.548 ms/op
    p(100.0000) =     15.548 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.659 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
Iteration   1: 2.499 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.047 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  10.996 ms/op
                 existUser·p0.9999: 15.113 ms/op
                 existUser·p1.00:   15.712 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  7.195 ms/op
                 existUser·p0.9999: 12.354 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.863 ms/op
                 existUser·p0.999:  8.634 ms/op
                 existUser·p0.9999: 11.946 ms/op
                 existUser·p1.00:   13.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386219
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 190826 
    [ 2.500,  3.750) = 191764 
    [ 3.750,  5.000) = 2726 
    [ 5.000,  6.250) = 351 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      8.634 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     15.602 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.124 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.006 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  6.498 ms/op
                 getUser·p0.9999: 13.256 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   2: 2.503 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.043 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  9.655 ms/op
                 getUser·p0.9999: 14.769 ms/op
                 getUser·p1.00:   15.270 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.059 ms/op
                 getUser·p0.999:  8.140 ms/op
                 getUser·p0.9999: 11.187 ms/op
                 getUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385569
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 190176 
    [ 2.500,  3.750) = 189754 
    [ 3.750,  5.000) = 4306 
    [ 5.000,  6.250) = 769 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      4.002 ms/op
     p(99.9000) =      8.079 ms/op
     p(99.9900) =     13.304 ms/op
     p(99.9990) =     15.108 ms/op
     p(99.9999) =     15.270 ms/op
    p(100.0000) =     15.270 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.772 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.009 ms/op
Iteration   1: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.093 ms/op
                 listUser·p0.9999: 10.945 ms/op
                 listUser·p1.00:   11.256 ms/op

Iteration   2: 3.089 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.855 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  9.657 ms/op
                 listUser·p0.9999: 11.911 ms/op
                 listUser·p1.00:   12.911 ms/op

Iteration   3: 3.071 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.466 ms/op
                 listUser·p0.9999: 11.734 ms/op
                 listUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312083
  mean =      3.073 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 78080 
    [ 2.500,  3.750) = 191762 
    [ 3.750,  5.000) = 34555 
    [ 5.000,  6.250) = 6184 
    [ 6.250,  7.500) = 739 
    [ 7.500,  8.750) = 241 
    [ 8.750, 10.000) = 216 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     11.809 ms/op
     p(99.9990) =     12.646 ms/op
     p(99.9999) =     12.911 ms/op
    p(100.0000) =     12.911 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.745 ± 2.086  ops/ms
ClientPb.existUser                       thrpt       3  13.107 ± 1.044  ops/ms
ClientPb.getUser                         thrpt       3  12.864 ± 0.627  ops/ms
ClientPb.listUser                        thrpt       3  10.708 ± 0.559  ops/ms
ClientPb.createUser                       avgt       3   2.518 ± 0.279   ms/op
ClientPb.existUser                        avgt       3   2.468 ± 0.189   ms/op
ClientPb.getUser                          avgt       3   2.483 ± 0.062   ms/op
ClientPb.listUser                         avgt       3   3.067 ± 0.100   ms/op
ClientPb.createUser                     sample  376654   2.546 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.735           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.651           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.309           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.548           ms/op
ClientPb.existUser                      sample  386219   2.484 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.792           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.634           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.517           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.712           ms/op
ClientPb.getUser                        sample  385569   2.488 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.695           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.079           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.304           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.270           ms/op
ClientPb.listUser                       sample  312083   3.073 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.855           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.015           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.809           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.911           ms/op
