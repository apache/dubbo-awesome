# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.364 ops/ms
# Warmup Iteration   2: 5.349 ops/ms
# Warmup Iteration   3: 8.781 ops/ms
Iteration   1: 9.134 ops/ms
Iteration   2: 9.813 ops/ms
Iteration   3: 9.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.570 ±(99.9%) 6.902 ops/ms [Average]
  (min, avg, max) = (9.134, 9.570, 9.813), stdev = 0.378
  CI (99.9%): [2.669, 16.472] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.213 ops/ms
# Warmup Iteration   2: 8.964 ops/ms
# Warmup Iteration   3: 9.313 ops/ms
Iteration   1: 10.388 ops/ms
Iteration   2: 10.200 ops/ms
Iteration   3: 10.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.305 ±(99.9%) 1.747 ops/ms [Average]
  (min, avg, max) = (10.200, 10.305, 10.388), stdev = 0.096
  CI (99.9%): [8.558, 12.052] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.357 ops/ms
# Warmup Iteration   2: 9.077 ops/ms
# Warmup Iteration   3: 9.864 ops/ms
Iteration   1: 9.788 ops/ms
Iteration   2: 10.301 ops/ms
Iteration   3: 10.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.159 ±(99.9%) 5.917 ops/ms [Average]
  (min, avg, max) = (9.788, 10.159, 10.388), stdev = 0.324
  CI (99.9%): [4.242, 16.076] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.020 ops/ms
# Warmup Iteration   2: 7.190 ops/ms
# Warmup Iteration   3: 8.276 ops/ms
Iteration   1: 8.493 ops/ms
Iteration   2: 8.471 ops/ms
Iteration   3: 8.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.583 ±(99.9%) 3.192 ops/ms [Average]
  (min, avg, max) = (8.471, 8.583, 8.784), stdev = 0.175
  CI (99.9%): [5.391, 11.774] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.479 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.003 ms/op
Iteration   1: 3.183 ±(99.9%) 0.004 ms/op
Iteration   2: 3.114 ±(99.9%) 0.002 ms/op
Iteration   3: 3.256 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.184 ±(99.9%) 1.296 ms/op [Average]
  (min, avg, max) = (3.114, 3.184, 3.256), stdev = 0.071
  CI (99.9%): [1.888, 4.480] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.838 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.002 ms/op
Iteration   1: 3.128 ±(99.9%) 0.010 ms/op
Iteration   2: 3.159 ±(99.9%) 0.009 ms/op
Iteration   3: 2.999 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.095 ±(99.9%) 1.548 ms/op [Average]
  (min, avg, max) = (2.999, 3.095, 3.159), stdev = 0.085
  CI (99.9%): [1.547, 4.643] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.119 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.511 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.211 ±(99.9%) 0.004 ms/op
Iteration   1: 3.278 ±(99.9%) 0.005 ms/op
Iteration   2: 3.158 ±(99.9%) 0.003 ms/op
Iteration   3: 3.096 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.177 ±(99.9%) 1.690 ms/op [Average]
  (min, avg, max) = (3.096, 3.177, 3.278), stdev = 0.093
  CI (99.9%): [1.488, 4.867] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.550 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.791 ±(99.9%) 0.011 ms/op
Iteration   1: 3.823 ±(99.9%) 0.007 ms/op
Iteration   2: 3.659 ±(99.9%) 0.003 ms/op
Iteration   3: 3.706 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.729 ±(99.9%) 1.544 ms/op [Average]
  (min, avg, max) = (3.659, 3.729, 3.823), stdev = 0.085
  CI (99.9%): [2.185, 5.273] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.745 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.718 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.010 ms/op
Iteration   1: 3.277 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.128 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  11.417 ms/op
                 createUser·p0.9999: 22.781 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   2: 3.130 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  19.525 ms/op
                 createUser·p0.9999: 23.298 ms/op
                 createUser·p1.00:   24.609 ms/op

Iteration   3: 3.170 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  17.859 ms/op
                 createUser·p0.9999: 19.756 ms/op
                 createUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300801
  mean =      3.191 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11644 
    [ 2.500,  5.000) = 283860 
    [ 5.000,  7.500) = 4169 
    [ 7.500, 10.000) = 603 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 176 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.019 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     22.837 ms/op
     p(99.9990) =     24.575 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.842 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.009 ms/op
Iteration   1: 3.085 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.187 ms/op
                 existUser·p0.95:   3.412 ms/op
                 existUser·p0.99:   6.010 ms/op
                 existUser·p0.999:  15.122 ms/op
                 existUser·p0.9999: 20.652 ms/op
                 existUser·p1.00:   22.413 ms/op

Iteration   2: 3.174 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.479 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  15.385 ms/op
                 existUser·p0.9999: 23.888 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   3: 3.192 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.952 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  13.861 ms/op
                 existUser·p0.9999: 22.970 ms/op
                 existUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304554
  mean =      3.150 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24845 
    [ 2.500,  5.000) = 272590 
    [ 5.000,  7.500) = 6294 
    [ 7.500, 10.000) = 327 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     14.048 ms/op
     p(99.9900) =     22.988 ms/op
     p(99.9990) =     24.378 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.205 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.365 ±(99.9%) 0.010 ms/op
Iteration   1: 3.210 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  16.683 ms/op
                 getUser·p0.9999: 19.990 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   2: 3.317 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  16.873 ms/op
                 getUser·p0.9999: 25.592 ms/op
                 getUser·p1.00:   27.034 ms/op

Iteration   3: 3.318 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  14.559 ms/op
                 getUser·p0.9999: 23.462 ms/op
                 getUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292382
  mean =      3.281 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13719 
    [ 2.500,  5.000) = 270157 
    [ 5.000,  7.500) = 7482 
    [ 7.500, 10.000) = 652 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     16.591 ms/op
     p(99.9900) =     23.560 ms/op
     p(99.9990) =     26.182 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.944 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.012 ms/op
Iteration   1: 3.752 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   7.312 ms/op
                 listUser·p0.999:  17.990 ms/op
                 listUser·p0.9999: 22.911 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   2: 3.791 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.859 ms/op
                 listUser·p0.999:  13.992 ms/op
                 listUser·p0.9999: 16.220 ms/op
                 listUser·p1.00:   17.334 ms/op

Iteration   3: 3.796 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  14.205 ms/op
                 listUser·p0.9999: 17.754 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253754
  mean =      3.779 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 246654 
    [ 5.000,  7.500) = 5253 
    [ 7.500, 10.000) = 1000 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 308 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     15.503 ms/op
     p(99.9900) =     20.877 ms/op
     p(99.9990) =     23.487 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.570 ± 6.902  ops/ms
ClientPb.existUser                       thrpt       3  10.305 ± 1.747  ops/ms
ClientPb.getUser                         thrpt       3  10.159 ± 5.917  ops/ms
ClientPb.listUser                        thrpt       3   8.583 ± 3.192  ops/ms
ClientPb.createUser                       avgt       3   3.184 ± 1.296   ms/op
ClientPb.existUser                        avgt       3   3.095 ± 1.548   ms/op
ClientPb.getUser                          avgt       3   3.177 ± 1.690   ms/op
ClientPb.listUser                         avgt       3   3.729 ± 1.544   ms/op
ClientPb.createUser                     sample  300801   3.191 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.019           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.609           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.579           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.547           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.837           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.609           ms/op
ClientPb.existUser                      sample  304554   3.150 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.952           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.432           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.734           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.048           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.988           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.854           ms/op
ClientPb.getUser                        sample  292382   3.281 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.090           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.654           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.182           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.029           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.591           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.560           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.034           ms/op
ClientPb.listUser                       sample  253754   3.779 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.217           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.711           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.037           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.877           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.117           ms/op
