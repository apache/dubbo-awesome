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
# Warmup Iteration   1: 4.446 ops/ms
# Warmup Iteration   2: 11.936 ops/ms
# Warmup Iteration   3: 12.236 ops/ms
Iteration   1: 12.433 ops/ms
Iteration   2: 12.434 ops/ms
Iteration   3: 12.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.437 ±(99.9%) 0.128 ops/ms [Average]
  (min, avg, max) = (12.433, 12.437, 12.445), stdev = 0.007
  CI (99.9%): [12.309, 12.566] (assumes normal distribution)


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
# Warmup Iteration   1: 7.854 ops/ms
# Warmup Iteration   2: 12.861 ops/ms
# Warmup Iteration   3: 12.836 ops/ms
Iteration   1: 12.918 ops/ms
Iteration   2: 12.854 ops/ms
Iteration   3: 12.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.904 ±(99.9%) 0.819 ops/ms [Average]
  (min, avg, max) = (12.854, 12.904, 12.940), stdev = 0.045
  CI (99.9%): [12.085, 13.723] (assumes normal distribution)


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
# Warmup Iteration   1: 7.634 ops/ms
# Warmup Iteration   2: 12.348 ops/ms
# Warmup Iteration   3: 12.542 ops/ms
Iteration   1: 12.663 ops/ms
Iteration   2: 12.456 ops/ms
Iteration   3: 12.638 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.586 ±(99.9%) 2.062 ops/ms [Average]
  (min, avg, max) = (12.456, 12.586, 12.663), stdev = 0.113
  CI (99.9%): [10.523, 14.648] (assumes normal distribution)


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
# Warmup Iteration   1: 6.687 ops/ms
# Warmup Iteration   2: 10.374 ops/ms
# Warmup Iteration   3: 10.487 ops/ms
Iteration   1: 10.398 ops/ms
Iteration   2: 10.454 ops/ms
Iteration   3: 10.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.440 ±(99.9%) 0.674 ops/ms [Average]
  (min, avg, max) = (10.398, 10.440, 10.468), stdev = 0.037
  CI (99.9%): [9.766, 11.114] (assumes normal distribution)


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
# Warmup Iteration   1: 3.954 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.004 ms/op
Iteration   1: 2.582 ±(99.9%) 0.005 ms/op
Iteration   2: 2.552 ±(99.9%) 0.004 ms/op
Iteration   3: 2.570 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.568 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (2.552, 2.568, 2.582), stdev = 0.015
  CI (99.9%): [2.294, 2.842] (assumes normal distribution)


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.004 ms/op
Iteration   1: 2.480 ±(99.9%) 0.005 ms/op
Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
Iteration   3: 2.475 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.477 ±(99.9%) 0.043 ms/op [Average]
  (min, avg, max) = (2.475, 2.477, 2.480), stdev = 0.002
  CI (99.9%): [2.435, 2.520] (assumes normal distribution)


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
# Warmup Iteration   1: 4.054 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.561 ±(99.9%) 0.004 ms/op
Iteration   1: 2.530 ±(99.9%) 0.004 ms/op
Iteration   2: 2.539 ±(99.9%) 0.004 ms/op
Iteration   3: 2.557 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.542 ±(99.9%) 0.250 ms/op [Average]
  (min, avg, max) = (2.530, 2.542, 2.557), stdev = 0.014
  CI (99.9%): [2.292, 2.792] (assumes normal distribution)


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
# Warmup Iteration   1: 4.692 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
Iteration   1: 3.013 ±(99.9%) 0.007 ms/op
Iteration   2: 3.023 ±(99.9%) 0.005 ms/op
Iteration   3: 3.009 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.015 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (3.009, 3.015, 3.023), stdev = 0.007
  CI (99.9%): [2.887, 3.143] (assumes normal distribution)


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.701 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.601 ±(99.9%) 0.006 ms/op
Iteration   1: 2.574 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  12.452 ms/op
                 createUser·p0.9999: 13.952 ms/op
                 createUser·p1.00:   14.631 ms/op

Iteration   2: 2.566 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.699 ms/op
                 createUser·p0.999:  9.753 ms/op
                 createUser·p0.9999: 14.314 ms/op
                 createUser·p1.00:   15.221 ms/op

Iteration   3: 2.585 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.146 ms/op
                 createUser·p0.95:   3.289 ms/op
                 createUser·p0.99:   4.153 ms/op
                 createUser·p0.999:  8.375 ms/op
                 createUser·p0.9999: 11.709 ms/op
                 createUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372486
  mean =      2.575 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 176462 
    [ 2.500,  3.750) = 191270 
    [ 3.750,  5.000) = 3551 
    [ 5.000,  6.250) = 709 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 114 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.129 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      8.905 ms/op
     p(99.9900) =     13.959 ms/op
     p(99.9990) =     15.025 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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
# Warmup Iteration   1: 3.812 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.161 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  7.891 ms/op
                 existUser·p0.9999: 14.254 ms/op
                 existUser·p1.00:   14.565 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  5.156 ms/op
                 existUser·p0.9999: 14.337 ms/op
                 existUser·p1.00:   15.090 ms/op

Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.867 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  7.588 ms/op
                 existUser·p0.9999: 12.321 ms/op
                 existUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387848
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 193680 
    [ 2.500,  3.750) = 190768 
    [ 3.750,  5.000) = 2723 
    [ 5.000,  6.250) = 233 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      6.448 ms/op
     p(99.9900) =     14.012 ms/op
     p(99.9990) =     15.024 ms/op
     p(99.9999) =     15.090 ms/op
    p(100.0000) =     15.090 ms/op


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
# Warmup Iteration   1: 3.850 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.006 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.795 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  11.419 ms/op
                 getUser·p0.9999: 13.697 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  8.890 ms/op
                 getUser·p0.9999: 20.148 ms/op
                 getUser·p1.00:   22.249 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  6.215 ms/op
                 getUser·p0.9999: 12.338 ms/op
                 getUser·p1.00:   13.566 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384088
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 191376 
    [ 2.500,  5.000) = 191677 
    [ 5.000,  7.500) = 648 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      8.272 ms/op
     p(99.9900) =     13.936 ms/op
     p(99.9990) =     22.053 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 4.727 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.009 ms/op
Iteration   1: 3.091 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  10.584 ms/op
                 listUser·p0.9999: 14.237 ms/op
                 listUser·p1.00:   16.089 ms/op

Iteration   2: 3.075 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.829 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 10.745 ms/op
                 listUser·p1.00:   11.256 ms/op

Iteration   3: 3.071 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.366 ms/op
                 listUser·p0.9999: 13.500 ms/op
                 listUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311493
  mean =      3.079 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 80195 
    [ 2.500,  3.750) = 186815 
    [ 3.750,  5.000) = 36833 
    [ 5.000,  6.250) = 6154 
    [ 6.250,  7.500) = 743 
    [ 7.500,  8.750) = 149 
    [ 8.750, 10.000) = 253 
    [10.000, 11.250) = 153 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.724 ms/op
     p(99.9900) =     13.409 ms/op
     p(99.9990) =     15.901 ms/op
     p(99.9999) =     16.089 ms/op
    p(100.0000) =     16.089 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.437 ± 0.128  ops/ms
ClientPb.existUser                       thrpt       3  12.904 ± 0.819  ops/ms
ClientPb.getUser                         thrpt       3  12.586 ± 2.062  ops/ms
ClientPb.listUser                        thrpt       3  10.440 ± 0.674  ops/ms
ClientPb.createUser                       avgt       3   2.568 ± 0.274   ms/op
ClientPb.existUser                        avgt       3   2.477 ± 0.043   ms/op
ClientPb.getUser                          avgt       3   2.542 ± 0.250   ms/op
ClientPb.listUser                         avgt       3   3.015 ± 0.128   ms/op
ClientPb.createUser                     sample  372486   2.575 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.889           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.905           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.959           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.221           ms/op
ClientPb.existUser                      sample  387848   2.473 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.867           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.448           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.012           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.090           ms/op
ClientPb.getUser                        sample  384088   2.497 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.736           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.272           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.936           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.249           ms/op
ClientPb.listUser                       sample  311493   3.079 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.829           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.019           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.724           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.409           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.089           ms/op
