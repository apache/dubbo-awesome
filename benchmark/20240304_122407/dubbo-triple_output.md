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
# Warmup Iteration   1: 5.215 ops/ms
# Warmup Iteration   2: 12.137 ops/ms
# Warmup Iteration   3: 12.312 ops/ms
Iteration   1: 12.493 ops/ms
Iteration   2: 12.690 ops/ms
Iteration   3: 12.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.629 ±(99.9%) 2.151 ops/ms [Average]
  (min, avg, max) = (12.493, 12.629, 12.704), stdev = 0.118
  CI (99.9%): [10.477, 14.780] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.135 ops/ms
# Warmup Iteration   2: 13.123 ops/ms
# Warmup Iteration   3: 13.094 ops/ms
Iteration   1: 13.258 ops/ms
Iteration   2: 13.239 ops/ms
Iteration   3: 13.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.219 ±(99.9%) 0.972 ops/ms [Average]
  (min, avg, max) = (13.158, 13.219, 13.258), stdev = 0.053
  CI (99.9%): [12.247, 14.190] (assumes normal distribution)


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
# Warmup Iteration   1: 8.294 ops/ms
# Warmup Iteration   2: 12.757 ops/ms
# Warmup Iteration   3: 12.760 ops/ms
Iteration   1: 12.990 ops/ms
Iteration   2: 12.862 ops/ms
Iteration   3: 12.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.939 ±(99.9%) 1.234 ops/ms [Average]
  (min, avg, max) = (12.862, 12.939, 12.990), stdev = 0.068
  CI (99.9%): [11.704, 14.173] (assumes normal distribution)


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
# Warmup Iteration   1: 6.605 ops/ms
# Warmup Iteration   2: 10.477 ops/ms
# Warmup Iteration   3: 10.494 ops/ms
Iteration   1: 10.493 ops/ms
Iteration   2: 10.575 ops/ms
Iteration   3: 10.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.538 ±(99.9%) 0.752 ops/ms [Average]
  (min, avg, max) = (10.493, 10.538, 10.575), stdev = 0.041
  CI (99.9%): [9.786, 11.290] (assumes normal distribution)


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
# Warmup Iteration   1: 3.891 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.004 ms/op
Iteration   1: 2.530 ±(99.9%) 0.004 ms/op
Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
Iteration   3: 2.538 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.527 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (2.512, 2.527, 2.538), stdev = 0.013
  CI (99.9%): [2.282, 2.772] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.734 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.410 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.417 ±(99.9%) 0.004 ms/op
Iteration   1: 2.401 ±(99.9%) 0.003 ms/op
Iteration   2: 2.417 ±(99.9%) 0.004 ms/op
Iteration   3: 2.432 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.417 ±(99.9%) 0.275 ms/op [Average]
  (min, avg, max) = (2.401, 2.417, 2.432), stdev = 0.015
  CI (99.9%): [2.142, 2.691] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.886 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.004 ms/op
Iteration   1: 2.461 ±(99.9%) 0.004 ms/op
Iteration   2: 2.468 ±(99.9%) 0.003 ms/op
Iteration   3: 2.504 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.478 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (2.461, 2.478, 2.504), stdev = 0.023
  CI (99.9%): [2.055, 2.901] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.683 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
Iteration   1: 2.985 ±(99.9%) 0.004 ms/op
Iteration   2: 2.977 ±(99.9%) 0.006 ms/op
Iteration   3: 2.974 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.979 ±(99.9%) 0.110 ms/op [Average]
  (min, avg, max) = (2.974, 2.979, 2.985), stdev = 0.006
  CI (99.9%): [2.869, 3.088] (assumes normal distribution)


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
# Warmup Iteration   1: 4.040 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.685 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.006 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.008 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.555 ms/op
                 createUser·p0.999:  11.559 ms/op
                 createUser·p0.9999: 13.816 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.867 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  9.278 ms/op
                 createUser·p0.9999: 12.709 ms/op
                 createUser·p1.00:   13.173 ms/op

Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   4.105 ms/op
                 createUser·p0.999:  9.077 ms/op
                 createUser·p0.9999: 12.607 ms/op
                 createUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380825
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 184177 
    [ 2.500,  3.750) = 192519 
    [ 3.750,  5.000) = 3225 
    [ 5.000,  6.250) = 362 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      9.085 ms/op
     p(99.9900) =     13.302 ms/op
     p(99.9990) =     13.959 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 3.818 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.415 ±(99.9%) 0.005 ms/op
Iteration   1: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  6.094 ms/op
                 existUser·p0.9999: 13.812 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 2.427 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.668 ms/op
                 existUser·p0.999:  7.669 ms/op
                 existUser·p0.9999: 12.730 ms/op
                 existUser·p1.00:   13.877 ms/op

Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.995 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.777 ms/op
                 existUser·p0.999:  7.634 ms/op
                 existUser·p0.9999: 11.664 ms/op
                 existUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394035
  mean =      2.434 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 199843 
    [ 2.500,  3.750) = 190457 
    [ 3.750,  5.000) = 2851 
    [ 5.000,  6.250) = 376 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 115 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      7.519 ms/op
     p(99.9900) =     13.566 ms/op
     p(99.9990) =     14.288 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 3.795 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
Iteration   1: 2.501 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.226 ms/op
                 getUser·p0.999:  10.476 ms/op
                 getUser·p0.9999: 13.771 ms/op
                 getUser·p1.00:   14.713 ms/op

Iteration   2: 2.530 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  6.289 ms/op
                 getUser·p0.9999: 14.976 ms/op
                 getUser·p1.00:   15.221 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.789 ms/op
                 getUser·p0.999:  7.278 ms/op
                 getUser·p0.9999: 11.264 ms/op
                 getUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382584
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 100 
    [ 1.250,  2.500) = 188012 
    [ 2.500,  3.750) = 188121 
    [ 3.750,  5.000) = 4830 
    [ 5.000,  6.250) = 1094 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      4.149 ms/op
     p(99.9000) =      6.636 ms/op
     p(99.9900) =     13.656 ms/op
     p(99.9990) =     15.115 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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
# Warmup Iteration   1: 4.558 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.008 ms/op
Iteration   1: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  8.810 ms/op
                 listUser·p0.9999: 10.155 ms/op
                 listUser·p1.00:   10.486 ms/op

Iteration   2: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  10.174 ms/op
                 listUser·p0.9999: 14.821 ms/op
                 listUser·p1.00:   15.352 ms/op

Iteration   3: 2.963 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.730 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.366 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 10.781 ms/op
                 listUser·p1.00:   11.092 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321966
  mean =      2.979 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 97512 
    [ 2.500,  3.750) = 186588 
    [ 3.750,  5.000) = 31541 
    [ 5.000,  6.250) = 5161 
    [ 6.250,  7.500) = 437 
    [ 7.500,  8.750) = 167 
    [ 8.750, 10.000) = 264 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     12.885 ms/op
     p(99.9990) =     15.161 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.629 ± 2.151  ops/ms
ClientPb.existUser                       thrpt       3  13.219 ± 0.972  ops/ms
ClientPb.getUser                         thrpt       3  12.939 ± 1.234  ops/ms
ClientPb.listUser                        thrpt       3  10.538 ± 0.752  ops/ms
ClientPb.createUser                       avgt       3   2.527 ± 0.245   ms/op
ClientPb.existUser                        avgt       3   2.417 ± 0.275   ms/op
ClientPb.getUser                          avgt       3   2.478 ± 0.423   ms/op
ClientPb.listUser                         avgt       3   2.979 ± 0.110   ms/op
ClientPb.createUser                     sample  380825   2.518 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.867           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.085           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.302           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.336           ms/op
ClientPb.existUser                      sample  394035   2.434 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.694           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.474           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.519           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.566           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.303           ms/op
ClientPb.getUser                        sample  382584   2.507 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.804           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.149           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.636           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.656           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.221           ms/op
ClientPb.listUser                       sample  321966   2.979 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.730           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.448           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.241           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.885           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.352           ms/op
