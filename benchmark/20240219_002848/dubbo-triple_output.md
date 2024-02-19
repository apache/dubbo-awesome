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
# Warmup Iteration   1: 4.608 ops/ms
# Warmup Iteration   2: 11.923 ops/ms
# Warmup Iteration   3: 12.203 ops/ms
Iteration   1: 12.421 ops/ms
Iteration   2: 12.562 ops/ms
Iteration   3: 12.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.565 ±(99.9%) 2.665 ops/ms [Average]
  (min, avg, max) = (12.421, 12.565, 12.713), stdev = 0.146
  CI (99.9%): [9.900, 15.230] (assumes normal distribution)


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
# Warmup Iteration   1: 8.341 ops/ms
# Warmup Iteration   2: 13.073 ops/ms
# Warmup Iteration   3: 12.978 ops/ms
Iteration   1: 13.100 ops/ms
Iteration   2: 13.132 ops/ms
Iteration   3: 13.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.098 ±(99.9%) 0.656 ops/ms [Average]
  (min, avg, max) = (13.061, 13.098, 13.132), stdev = 0.036
  CI (99.9%): [12.442, 13.753] (assumes normal distribution)


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
# Warmup Iteration   1: 7.710 ops/ms
# Warmup Iteration   2: 12.517 ops/ms
# Warmup Iteration   3: 12.675 ops/ms
Iteration   1: 12.865 ops/ms
Iteration   2: 12.671 ops/ms
Iteration   3: 12.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.723 ±(99.9%) 2.269 ops/ms [Average]
  (min, avg, max) = (12.634, 12.723, 12.865), stdev = 0.124
  CI (99.9%): [10.454, 14.992] (assumes normal distribution)


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
# Warmup Iteration   1: 6.998 ops/ms
# Warmup Iteration   2: 10.478 ops/ms
# Warmup Iteration   3: 10.678 ops/ms
Iteration   1: 10.815 ops/ms
Iteration   2: 10.806 ops/ms
Iteration   3: 10.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.799 ±(99.9%) 0.363 ops/ms [Average]
  (min, avg, max) = (10.777, 10.799, 10.815), stdev = 0.020
  CI (99.9%): [10.436, 11.162] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.055 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
Iteration   1: 2.478 ±(99.9%) 0.004 ms/op
Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
Iteration   3: 2.456 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.471 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (2.456, 2.471, 2.478), stdev = 0.013
  CI (99.9%): [2.234, 2.708] (assumes normal distribution)


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
# Warmup Iteration   1: 3.508 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.410 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.003 ms/op
Iteration   1: 2.422 ±(99.9%) 0.004 ms/op
Iteration   2: 2.405 ±(99.9%) 0.004 ms/op
Iteration   3: 2.425 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.417 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.405, 2.417, 2.425), stdev = 0.010
  CI (99.9%): [2.226, 2.609] (assumes normal distribution)


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
# Warmup Iteration   1: 3.800 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.004 ms/op
Iteration   1: 2.469 ±(99.9%) 0.003 ms/op
Iteration   2: 2.463 ±(99.9%) 0.002 ms/op
Iteration   3: 2.489 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.473 ±(99.9%) 0.249 ms/op [Average]
  (min, avg, max) = (2.463, 2.473, 2.489), stdev = 0.014
  CI (99.9%): [2.225, 2.722] (assumes normal distribution)


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
# Warmup Iteration   1: 4.630 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.005 ms/op
Iteration   1: 2.951 ±(99.9%) 0.006 ms/op
Iteration   2: 2.965 ±(99.9%) 0.005 ms/op
Iteration   3: 2.985 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.967 ±(99.9%) 0.312 ms/op [Average]
  (min, avg, max) = (2.951, 2.967, 2.985), stdev = 0.017
  CI (99.9%): [2.655, 3.279] (assumes normal distribution)


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
# Warmup Iteration   1: 4.206 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.006 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.614 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  11.249 ms/op
                 createUser·p0.9999: 13.730 ms/op
                 createUser·p1.00:   14.942 ms/op

Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.621 ms/op
                 createUser·p0.999:  9.383 ms/op
                 createUser·p0.9999: 12.448 ms/op
                 createUser·p1.00:   13.025 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.810 ms/op
                 createUser·p0.999:  8.391 ms/op
                 createUser·p0.9999: 12.991 ms/op
                 createUser·p1.00:   15.745 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381963
  mean =      2.511 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 184528 
    [ 2.500,  3.750) = 194078 
    [ 3.750,  5.000) = 2545 
    [ 5.000,  6.250) = 330 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 145 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      8.406 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     14.373 ms/op
     p(99.9999) =     15.745 ms/op
    p(100.0000) =     15.745 ms/op


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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
Iteration   1: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.371 ms/op
                 existUser·p0.999:  5.538 ms/op
                 existUser·p0.9999: 13.795 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   2: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.695 ms/op
                 existUser·p0.999:  7.471 ms/op
                 existUser·p0.9999: 12.008 ms/op
                 existUser·p1.00:   13.222 ms/op

Iteration   3: 2.484 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.954 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  8.180 ms/op
                 existUser·p0.9999: 12.069 ms/op
                 existUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390250
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 191275 
    [ 2.500,  3.750) = 194295 
    [ 3.750,  5.000) = 3378 
    [ 5.000,  6.250) = 733 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 133 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      8.083 ms/op
     p(99.9900) =     13.221 ms/op
     p(99.9990) =     13.947 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 3.826 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.520 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  6.784 ms/op
                 getUser·p0.9999: 14.354 ms/op
                 getUser·p1.00:   15.237 ms/op

Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  6.848 ms/op
                 getUser·p0.9999: 12.503 ms/op
                 getUser·p1.00:   13.255 ms/op

Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  6.381 ms/op
                 getUser·p0.9999: 11.026 ms/op
                 getUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388944
  mean =      2.466 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 195074 
    [ 2.500,  3.750) = 189416 
    [ 3.750,  5.000) = 3697 
    [ 5.000,  6.250) = 252 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      6.793 ms/op
     p(99.9900) =     13.404 ms/op
     p(99.9990) =     15.144 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


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
# Warmup Iteration   1: 4.697 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.009 ms/op
Iteration   1: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 10.869 ms/op
                 listUser·p1.00:   12.255 ms/op

Iteration   2: 3.044 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  9.585 ms/op
                 listUser·p0.9999: 12.583 ms/op
                 listUser·p1.00:   13.337 ms/op

Iteration   3: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.982 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.142 ms/op
                 listUser·p0.9999: 11.108 ms/op
                 listUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317693
  mean =      3.019 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 91225 
    [ 2.500,  3.750) = 187254 
    [ 3.750,  5.000) = 31760 
    [ 5.000,  6.250) = 5920 
    [ 6.250,  7.500) = 711 
    [ 7.500,  8.750) = 247 
    [ 8.750, 10.000) = 336 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     11.189 ms/op
     p(99.9990) =     13.216 ms/op
     p(99.9999) =     13.337 ms/op
    p(100.0000) =     13.337 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.565 ± 2.665  ops/ms
ClientPb.existUser                       thrpt       3  13.098 ± 0.656  ops/ms
ClientPb.getUser                         thrpt       3  12.723 ± 2.269  ops/ms
ClientPb.listUser                        thrpt       3  10.799 ± 0.363  ops/ms
ClientPb.createUser                       avgt       3   2.471 ± 0.237   ms/op
ClientPb.existUser                        avgt       3   2.417 ± 0.191   ms/op
ClientPb.getUser                          avgt       3   2.473 ± 0.249   ms/op
ClientPb.listUser                         avgt       3   2.967 ± 0.312   ms/op
ClientPb.createUser                     sample  381963   2.511 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.614           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.406           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.337           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.745           ms/op
ClientPb.existUser                      sample  390250   2.458 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.922           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.883           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.083           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.221           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.189           ms/op
ClientPb.getUser                        sample  388944   2.466 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.520           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.793           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.404           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.237           ms/op
ClientPb.listUser                       sample  317693   3.019 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.904           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.355           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.189           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.337           ms/op
