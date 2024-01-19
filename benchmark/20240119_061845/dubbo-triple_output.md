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
# Warmup Iteration   1: 4.747 ops/ms
# Warmup Iteration   2: 12.183 ops/ms
# Warmup Iteration   3: 12.619 ops/ms
Iteration   1: 12.644 ops/ms
Iteration   2: 12.843 ops/ms
Iteration   3: 12.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.758 ±(99.9%) 1.876 ops/ms [Average]
  (min, avg, max) = (12.644, 12.758, 12.843), stdev = 0.103
  CI (99.9%): [10.882, 14.634] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.709 ops/ms
# Warmup Iteration   2: 13.224 ops/ms
# Warmup Iteration   3: 13.266 ops/ms
Iteration   1: 13.107 ops/ms
Iteration   2: 13.352 ops/ms
Iteration   3: 13.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.267 ±(99.9%) 2.525 ops/ms [Average]
  (min, avg, max) = (13.107, 13.267, 13.352), stdev = 0.138
  CI (99.9%): [10.742, 15.792] (assumes normal distribution)


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
# Warmup Iteration   1: 7.676 ops/ms
# Warmup Iteration   2: 12.752 ops/ms
# Warmup Iteration   3: 12.911 ops/ms
Iteration   1: 13.066 ops/ms
Iteration   2: 12.928 ops/ms
Iteration   3: 12.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.989 ±(99.9%) 1.286 ops/ms [Average]
  (min, avg, max) = (12.928, 12.989, 13.066), stdev = 0.070
  CI (99.9%): [11.704, 14.275] (assumes normal distribution)


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
# Warmup Iteration   1: 6.897 ops/ms
# Warmup Iteration   2: 10.621 ops/ms
# Warmup Iteration   3: 10.817 ops/ms
Iteration   1: 10.740 ops/ms
Iteration   2: 10.807 ops/ms
Iteration   3: 10.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.777 ±(99.9%) 0.616 ops/ms [Average]
  (min, avg, max) = (10.740, 10.777, 10.807), stdev = 0.034
  CI (99.9%): [10.161, 11.392] (assumes normal distribution)


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
# Warmup Iteration   1: 4.091 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.641 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.004 ms/op
Iteration   1: 2.556 ±(99.9%) 0.004 ms/op
Iteration   2: 2.599 ±(99.9%) 0.004 ms/op
Iteration   3: 2.538 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.564 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (2.538, 2.564, 2.599), stdev = 0.031
  CI (99.9%): [1.996, 3.133] (assumes normal distribution)


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
# Warmup Iteration   1: 3.582 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
Iteration   2: 2.471 ±(99.9%) 0.003 ms/op
Iteration   3: 2.460 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.471 ±(99.9%) 0.206 ms/op [Average]
  (min, avg, max) = (2.460, 2.471, 2.482), stdev = 0.011
  CI (99.9%): [2.265, 2.677] (assumes normal distribution)


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.004 ms/op
Iteration   1: 2.484 ±(99.9%) 0.004 ms/op
Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
Iteration   3: 2.463 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.474 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (2.463, 2.474, 2.484), stdev = 0.010
  CI (99.9%): [2.287, 2.661] (assumes normal distribution)


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
# Warmup Iteration   1: 4.756 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
Iteration   1: 2.968 ±(99.9%) 0.004 ms/op
Iteration   2: 2.957 ±(99.9%) 0.006 ms/op
Iteration   3: 2.980 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.968 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (2.957, 2.968, 2.980), stdev = 0.012
  CI (99.9%): [2.755, 3.182] (assumes normal distribution)


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
# Warmup Iteration   1: 4.078 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.006 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.592 ms/op
                 createUser·p0.999:  10.001 ms/op
                 createUser·p0.9999: 14.090 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.572 ms/op
                 createUser·p0.999:  10.095 ms/op
                 createUser·p0.9999: 12.426 ms/op
                 createUser·p1.00:   13.091 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  8.995 ms/op
                 createUser·p0.9999: 10.764 ms/op
                 createUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383939
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 187504 
    [ 2.500,  3.750) = 193204 
    [ 3.750,  5.000) = 2388 
    [ 5.000,  6.250) = 274 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 145 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     13.455 ms/op
     p(99.9990) =     14.322 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 3.717 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
Iteration   1: 2.461 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  6.213 ms/op
                 existUser·p0.9999: 16.728 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.940 ms/op
                 existUser·p0.999:  9.314 ms/op
                 existUser·p0.9999: 13.918 ms/op
                 existUser·p1.00:   15.041 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.762 ms/op
                 existUser·p0.999:  7.258 ms/op
                 existUser·p0.9999: 11.239 ms/op
                 existUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386036
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 189576 
    [ 2.500,  3.750) = 192504 
    [ 3.750,  5.000) = 3076 
    [ 5.000,  6.250) = 359 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      7.897 ms/op
     p(99.9900) =     15.876 ms/op
     p(99.9990) =     16.876 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 3.759 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.006 ms/op
Iteration   1: 2.441 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.966 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   3.564 ms/op
                 getUser·p0.999:  5.586 ms/op
                 getUser·p0.9999: 16.613 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.122 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.580 ms/op
                 getUser·p0.999:  6.045 ms/op
                 getUser·p0.9999: 13.054 ms/op
                 getUser·p1.00:   13.664 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.528 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.375 ms/op
                 getUser·p0.9999: 11.574 ms/op
                 getUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390841
  mean =      2.454 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 197540 
    [ 2.500,  3.750) = 189158 
    [ 3.750,  5.000) = 3177 
    [ 5.000,  6.250) = 491 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      6.554 ms/op
     p(99.9900) =     15.761 ms/op
     p(99.9990) =     16.977 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 4.705 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.008 ms/op
Iteration   1: 2.972 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.841 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.625 ms/op
                 listUser·p0.999:  9.674 ms/op
                 listUser·p0.9999: 13.640 ms/op
                 listUser·p1.00:   14.352 ms/op

Iteration   2: 2.955 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.394 ms/op
                 listUser·p0.9999: 11.108 ms/op
                 listUser·p1.00:   12.567 ms/op

Iteration   3: 2.944 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.772 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 11.700 ms/op
                 listUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324354
  mean =      2.957 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 146 
    [ 1.250,  2.500) = 103728 
    [ 2.500,  3.750) = 184975 
    [ 3.750,  5.000) = 28651 
    [ 5.000,  6.250) = 5466 
    [ 6.250,  7.500) = 689 
    [ 7.500,  8.750) = 218 
    [ 8.750, 10.000) = 301 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     11.707 ms/op
     p(99.9990) =     14.092 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.758 ± 1.876  ops/ms
ClientPb.existUser                       thrpt       3  13.267 ± 2.525  ops/ms
ClientPb.getUser                         thrpt       3  12.989 ± 1.286  ops/ms
ClientPb.listUser                        thrpt       3  10.777 ± 0.616  ops/ms
ClientPb.createUser                       avgt       3   2.564 ± 0.569   ms/op
ClientPb.existUser                        avgt       3   2.471 ± 0.206   ms/op
ClientPb.getUser                          avgt       3   2.474 ± 0.187   ms/op
ClientPb.listUser                         avgt       3   2.968 ± 0.213   ms/op
ClientPb.createUser                     sample  383939   2.497 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.811           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.650           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.372           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.455           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.402           ms/op
ClientPb.existUser                      sample  386036   2.484 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.858           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.897           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.876           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.908           ms/op
ClientPb.getUser                        sample  390841   2.454 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.528           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.478           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.986           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.554           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.761           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.138           ms/op
ClientPb.listUser                       sample  324354   2.957 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.841           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.809           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.707           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.352           ms/op
