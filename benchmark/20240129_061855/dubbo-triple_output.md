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
# Warmup Iteration   1: 4.953 ops/ms
# Warmup Iteration   2: 11.825 ops/ms
# Warmup Iteration   3: 12.455 ops/ms
Iteration   1: 12.497 ops/ms
Iteration   2: 12.661 ops/ms
Iteration   3: 12.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.659 ±(99.9%) 2.948 ops/ms [Average]
  (min, avg, max) = (12.497, 12.659, 12.820), stdev = 0.162
  CI (99.9%): [9.711, 15.608] (assumes normal distribution)


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
# Warmup Iteration   1: 8.094 ops/ms
# Warmup Iteration   2: 12.959 ops/ms
# Warmup Iteration   3: 13.186 ops/ms
Iteration   1: 13.049 ops/ms
Iteration   2: 13.102 ops/ms
Iteration   3: 12.997 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.049 ±(99.9%) 0.954 ops/ms [Average]
  (min, avg, max) = (12.997, 13.049, 13.102), stdev = 0.052
  CI (99.9%): [12.095, 14.004] (assumes normal distribution)


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
# Warmup Iteration   1: 7.922 ops/ms
# Warmup Iteration   2: 12.578 ops/ms
# Warmup Iteration   3: 12.703 ops/ms
Iteration   1: 12.759 ops/ms
Iteration   2: 12.659 ops/ms
Iteration   3: 12.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.732 ±(99.9%) 1.174 ops/ms [Average]
  (min, avg, max) = (12.659, 12.732, 12.779), stdev = 0.064
  CI (99.9%): [11.558, 13.906] (assumes normal distribution)


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
# Warmup Iteration   1: 6.735 ops/ms
# Warmup Iteration   2: 10.532 ops/ms
# Warmup Iteration   3: 11.048 ops/ms
Iteration   1: 10.755 ops/ms
Iteration   2: 10.783 ops/ms
Iteration   3: 10.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.776 ±(99.9%) 0.332 ops/ms [Average]
  (min, avg, max) = (10.755, 10.776, 10.789), stdev = 0.018
  CI (99.9%): [10.444, 11.107] (assumes normal distribution)


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
Iteration   3: 2.513 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.514 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (2.502, 2.514, 2.527), stdev = 0.012
  CI (99.9%): [2.288, 2.740] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.709 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.004 ms/op
Iteration   1: 2.453 ±(99.9%) 0.005 ms/op
Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
Iteration   3: 2.423 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.450 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (2.423, 2.450, 2.473), stdev = 0.025
  CI (99.9%): [1.995, 2.904] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.787 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.004 ms/op
Iteration   1: 2.549 ±(99.9%) 0.004 ms/op
Iteration   2: 2.554 ±(99.9%) 0.004 ms/op
Iteration   3: 2.549 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.551 ±(99.9%) 0.056 ms/op [Average]
  (min, avg, max) = (2.549, 2.551, 2.554), stdev = 0.003
  CI (99.9%): [2.494, 2.607] (assumes normal distribution)


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
# Warmup Iteration   1: 4.809 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.004 ms/op
Iteration   1: 3.001 ±(99.9%) 0.006 ms/op
Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
Iteration   3: 3.035 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.010 ±(99.9%) 0.405 ms/op [Average]
  (min, avg, max) = (2.993, 3.010, 3.035), stdev = 0.022
  CI (99.9%): [2.605, 3.415] (assumes normal distribution)


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
# Warmup Iteration   1: 4.092 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.658 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.006 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.609 ms/op
                 createUser·p0.999:  10.532 ms/op
                 createUser·p0.9999: 13.569 ms/op
                 createUser·p1.00:   13.877 ms/op

Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  6.076 ms/op
                 createUser·p0.9999: 12.009 ms/op
                 createUser·p1.00:   12.386 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.812 ms/op
                 createUser·p0.999:  8.782 ms/op
                 createUser·p0.9999: 10.783 ms/op
                 createUser·p1.00:   16.122 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386159
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 189244 
    [ 2.500,  3.750) = 193477 
    [ 3.750,  5.000) = 2608 
    [ 5.000,  6.250) = 303 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 163 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      8.779 ms/op
     p(99.9900) =     13.107 ms/op
     p(99.9990) =     13.812 ms/op
     p(99.9999) =     16.122 ms/op
    p(100.0000) =     16.122 ms/op


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
# Warmup Iteration   1: 3.564 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.466 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
Iteration   1: 2.417 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.007 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.396 ms/op
                 existUser·p0.999:  6.543 ms/op
                 existUser·p0.9999: 14.410 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   2: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.424 ms/op
                 existUser·p0.999:  5.693 ms/op
                 existUser·p0.9999: 12.665 ms/op
                 existUser·p1.00:   14.434 ms/op

Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.020 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  8.086 ms/op
                 existUser·p0.9999: 11.747 ms/op
                 existUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394816
  mean =      2.429 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 195274 
    [ 2.500,  3.750) = 195810 
    [ 3.750,  5.000) = 2591 
    [ 5.000,  6.250) = 711 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      6.341 ms/op
     p(99.9900) =     12.952 ms/op
     p(99.9990) =     15.057 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


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
# Warmup Iteration   1: 3.888 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.006 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  9.629 ms/op
                 getUser·p0.9999: 14.010 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   2: 2.472 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.981 ms/op
                 getUser·p0.999:  8.236 ms/op
                 getUser·p0.9999: 19.104 ms/op
                 getUser·p1.00:   20.120 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.981 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  9.006 ms/op
                 getUser·p0.9999: 13.918 ms/op
                 getUser·p1.00:   14.238 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387042
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 193080 
    [ 2.500,  5.000) = 192914 
    [ 5.000,  7.500) = 613 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      9.043 ms/op
     p(99.9900) =     14.161 ms/op
     p(99.9990) =     19.334 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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
# Warmup Iteration   1: 4.694 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.008 ms/op
Iteration   1: 2.965 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.844 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.390 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 12.718 ms/op
                 listUser·p1.00:   12.911 ms/op

Iteration   2: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.819 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.315 ms/op
                 listUser·p0.9999: 11.229 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   3: 2.967 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  9.282 ms/op
                 listUser·p0.9999: 10.519 ms/op
                 listUser·p1.00:   10.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322042
  mean =      2.978 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 96288 
    [ 2.500,  3.750) = 188224 
    [ 3.750,  5.000) = 31033 
    [ 5.000,  6.250) = 5170 
    [ 6.250,  7.500) = 521 
    [ 7.500,  8.750) = 279 
    [ 8.750, 10.000) = 254 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     11.138 ms/op
     p(99.9990) =     12.871 ms/op
     p(99.9999) =     12.911 ms/op
    p(100.0000) =     12.911 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.659 ± 2.948  ops/ms
ClientPb.existUser                       thrpt       3  13.049 ± 0.954  ops/ms
ClientPb.getUser                         thrpt       3  12.732 ± 1.174  ops/ms
ClientPb.listUser                        thrpt       3  10.776 ± 0.332  ops/ms
ClientPb.createUser                       avgt       3   2.514 ± 0.226   ms/op
ClientPb.existUser                        avgt       3   2.450 ± 0.454   ms/op
ClientPb.getUser                          avgt       3   2.551 ± 0.056   ms/op
ClientPb.listUser                         avgt       3   3.010 ± 0.405   ms/op
ClientPb.createUser                     sample  386159   2.484 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.758           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.015           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.678           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.779           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.107           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.122           ms/op
ClientPb.existUser                      sample  394816   2.429 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.957           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.341           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.952           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.385           ms/op
ClientPb.getUser                        sample  387042   2.479 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.730           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.043           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.161           ms/op
ClientPb.getUser:getUser·p1.00          sample          20.120           ms/op
ClientPb.listUser                       sample  322042   2.978 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.819           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.175           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.138           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.911           ms/op
