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
# Warmup Iteration   1: 4.450 ops/ms
# Warmup Iteration   2: 11.720 ops/ms
# Warmup Iteration   3: 12.288 ops/ms
Iteration   1: 12.352 ops/ms
Iteration   2: 12.438 ops/ms
Iteration   3: 12.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.414 ±(99.9%) 0.995 ops/ms [Average]
  (min, avg, max) = (12.352, 12.414, 12.452), stdev = 0.055
  CI (99.9%): [11.419, 13.409] (assumes normal distribution)


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
# Warmup Iteration   1: 8.169 ops/ms
# Warmup Iteration   2: 12.957 ops/ms
# Warmup Iteration   3: 13.025 ops/ms
Iteration   1: 12.996 ops/ms
Iteration   2: 13.041 ops/ms
Iteration   3: 13.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.040 ±(99.9%) 0.808 ops/ms [Average]
  (min, avg, max) = (12.996, 13.040, 13.084), stdev = 0.044
  CI (99.9%): [12.233, 13.848] (assumes normal distribution)


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
# Warmup Iteration   1: 7.516 ops/ms
# Warmup Iteration   2: 12.425 ops/ms
# Warmup Iteration   3: 12.644 ops/ms
Iteration   1: 12.685 ops/ms
Iteration   2: 12.665 ops/ms
Iteration   3: 12.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.625 ±(99.9%) 1.584 ops/ms [Average]
  (min, avg, max) = (12.525, 12.625, 12.685), stdev = 0.087
  CI (99.9%): [11.041, 14.209] (assumes normal distribution)


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
# Warmup Iteration   1: 6.573 ops/ms
# Warmup Iteration   2: 10.469 ops/ms
# Warmup Iteration   3: 10.513 ops/ms
Iteration   1: 10.538 ops/ms
Iteration   2: 10.490 ops/ms
Iteration   3: 10.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.538 ±(99.9%) 0.897 ops/ms [Average]
  (min, avg, max) = (10.490, 10.538, 10.588), stdev = 0.049
  CI (99.9%): [9.641, 11.436] (assumes normal distribution)


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.004 ms/op
Iteration   1: 2.493 ±(99.9%) 0.003 ms/op
Iteration   2: 2.612 ±(99.9%) 0.003 ms/op
Iteration   3: 2.515 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.540 ±(99.9%) 1.150 ms/op [Average]
  (min, avg, max) = (2.493, 2.540, 2.612), stdev = 0.063
  CI (99.9%): [1.390, 3.690] (assumes normal distribution)


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.466 ±(99.9%) 0.004 ms/op
Iteration   3: 2.465 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.474 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (2.465, 2.474, 2.492), stdev = 0.016
  CI (99.9%): [2.187, 2.762] (assumes normal distribution)


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.004 ms/op
Iteration   1: 2.542 ±(99.9%) 0.004 ms/op
Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
Iteration   3: 2.504 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.518 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (2.504, 2.518, 2.542), stdev = 0.021
  CI (99.9%): [2.127, 2.908] (assumes normal distribution)


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
# Warmup Iteration   1: 4.613 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 3.045 ±(99.9%) 0.006 ms/op
Iteration   2: 3.018 ±(99.9%) 0.006 ms/op
Iteration   3: 3.048 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.037 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (3.018, 3.037, 3.048), stdev = 0.017
  CI (99.9%): [2.735, 3.339] (assumes normal distribution)


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
# Warmup Iteration   1: 4.224 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.679 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.006 ms/op
Iteration   1: 2.526 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  11.545 ms/op
                 createUser·p0.9999: 17.564 ms/op
                 createUser·p1.00:   18.579 ms/op

Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.879 ms/op
                 createUser·p0.999:  10.469 ms/op
                 createUser·p0.9999: 13.517 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   4.255 ms/op
                 createUser·p0.999:  9.093 ms/op
                 createUser·p0.9999: 10.263 ms/op
                 createUser·p1.00:   10.519 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380023
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 183215 
    [ 2.500,  3.750) = 191519 
    [ 3.750,  5.000) = 4046 
    [ 5.000,  6.250) = 614 
    [ 6.250,  7.500) = 110 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 125 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      4.002 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     14.664 ms/op
     p(99.9990) =     18.357 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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
# Warmup Iteration   1: 3.687 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  7.694 ms/op
                 existUser·p0.9999: 17.270 ms/op
                 existUser·p1.00:   17.596 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.036 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  6.373 ms/op
                 existUser·p0.9999: 12.780 ms/op
                 existUser·p1.00:   13.058 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.027 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  8.201 ms/op
                 existUser·p0.9999: 11.849 ms/op
                 existUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387651
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 189092 
    [ 2.500,  3.750) = 194092 
    [ 3.750,  5.000) = 3441 
    [ 5.000,  6.250) = 520 
    [ 6.250,  7.500) = 94 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      7.207 ms/op
     p(99.9900) =     14.114 ms/op
     p(99.9990) =     17.437 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 4.135 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.006 ms/op
Iteration   1: 2.497 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  12.354 ms/op
                 getUser·p0.9999: 13.884 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.764 ms/op
                 getUser·p0.999:  9.814 ms/op
                 getUser·p0.9999: 12.603 ms/op
                 getUser·p1.00:   13.304 ms/op

Iteration   3: 2.508 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  8.602 ms/op
                 getUser·p0.9999: 10.121 ms/op
                 getUser·p1.00:   12.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383342
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 189896 
    [ 2.500,  3.750) = 188323 
    [ 3.750,  5.000) = 3770 
    [ 5.000,  6.250) = 727 
    [ 6.250,  7.500) = 86 
    [ 7.500,  8.750) = 79 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      8.809 ms/op
     p(99.9900) =     13.544 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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
# Warmup Iteration   1: 4.872 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.009 ms/op
Iteration   1: 3.034 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.795 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  8.815 ms/op
                 listUser·p0.9999: 10.394 ms/op
                 listUser·p1.00:   11.895 ms/op

Iteration   2: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  11.054 ms/op
                 listUser·p0.9999: 11.952 ms/op
                 listUser·p1.00:   13.255 ms/op

Iteration   3: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 12.461 ms/op
                 listUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315262
  mean =      3.042 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 87220 
    [ 2.500,  3.750) = 186518 
    [ 3.750,  5.000) = 33102 
    [ 5.000,  6.250) = 6942 
    [ 6.250,  7.500) = 690 
    [ 7.500,  8.750) = 183 
    [ 8.750, 10.000) = 191 
    [10.000, 11.250) = 177 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.880 ms/op
     p(99.9900) =     11.878 ms/op
     p(99.9990) =     12.627 ms/op
     p(99.9999) =     13.255 ms/op
    p(100.0000) =     13.255 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.414 ± 0.995  ops/ms
ClientPb.existUser                       thrpt       3  13.040 ± 0.808  ops/ms
ClientPb.getUser                         thrpt       3  12.625 ± 1.584  ops/ms
ClientPb.listUser                        thrpt       3  10.538 ± 0.897  ops/ms
ClientPb.createUser                       avgt       3   2.540 ± 1.150   ms/op
ClientPb.existUser                        avgt       3   2.474 ± 0.288   ms/op
ClientPb.getUser                          avgt       3   2.518 ± 0.390   ms/op
ClientPb.listUser                         avgt       3   3.037 ± 0.302   ms/op
ClientPb.createUser                     sample  380023   2.524 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.880           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.372           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.664           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.579           ms/op
ClientPb.existUser                      sample  387651   2.474 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.934           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.207           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.114           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.596           ms/op
ClientPb.getUser                        sample  383342   2.502 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.927           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.809           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.544           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.418           ms/op
ClientPb.listUser                       sample  315262   3.042 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.795           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.880           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.878           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.255           ms/op
