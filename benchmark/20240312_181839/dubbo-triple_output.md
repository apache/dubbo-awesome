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
# Warmup Iteration   1: 5.238 ops/ms
# Warmup Iteration   2: 12.388 ops/ms
# Warmup Iteration   3: 12.723 ops/ms
Iteration   1: 12.844 ops/ms
Iteration   2: 12.897 ops/ms
Iteration   3: 13.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.921 ±(99.9%) 1.664 ops/ms [Average]
  (min, avg, max) = (12.844, 12.921, 13.022), stdev = 0.091
  CI (99.9%): [11.256, 14.585] (assumes normal distribution)


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
# Warmup Iteration   1: 8.351 ops/ms
# Warmup Iteration   2: 13.210 ops/ms
# Warmup Iteration   3: 13.025 ops/ms
Iteration   1: 13.116 ops/ms
Iteration   2: 13.238 ops/ms
Iteration   3: 13.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.118 ±(99.9%) 2.165 ops/ms [Average]
  (min, avg, max) = (13.000, 13.118, 13.238), stdev = 0.119
  CI (99.9%): [10.953, 15.283] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.250 ops/ms
# Warmup Iteration   2: 12.999 ops/ms
# Warmup Iteration   3: 13.183 ops/ms
Iteration   1: 13.191 ops/ms
Iteration   2: 13.108 ops/ms
Iteration   3: 13.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.112 ±(99.9%) 1.404 ops/ms [Average]
  (min, avg, max) = (13.038, 13.112, 13.191), stdev = 0.077
  CI (99.9%): [11.708, 14.516] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.874 ops/ms
# Warmup Iteration   2: 10.660 ops/ms
# Warmup Iteration   3: 10.769 ops/ms
Iteration   1: 10.802 ops/ms
Iteration   2: 10.907 ops/ms
Iteration   3: 10.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.872 ±(99.9%) 1.092 ops/ms [Average]
  (min, avg, max) = (10.802, 10.872, 10.907), stdev = 0.060
  CI (99.9%): [9.780, 11.963] (assumes normal distribution)


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
Iteration   1: 2.527 ±(99.9%) 0.004 ms/op
Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
Iteration   3: 2.519 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.522 ±(99.9%) 0.073 ms/op [Average]
  (min, avg, max) = (2.519, 2.522, 2.527), stdev = 0.004
  CI (99.9%): [2.449, 2.595] (assumes normal distribution)


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
# Warmup Iteration   1: 3.511 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.381 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.379 ±(99.9%) 0.004 ms/op
Iteration   1: 2.386 ±(99.9%) 0.004 ms/op
Iteration   2: 2.374 ±(99.9%) 0.003 ms/op
Iteration   3: 2.382 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.381 ±(99.9%) 0.110 ms/op [Average]
  (min, avg, max) = (2.374, 2.381, 2.386), stdev = 0.006
  CI (99.9%): [2.271, 2.491] (assumes normal distribution)


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.003 ms/op
Iteration   1: 2.444 ±(99.9%) 0.004 ms/op
Iteration   2: 2.418 ±(99.9%) 0.003 ms/op
Iteration   3: 2.427 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.430 ±(99.9%) 0.236 ms/op [Average]
  (min, avg, max) = (2.418, 2.430, 2.444), stdev = 0.013
  CI (99.9%): [2.194, 2.665] (assumes normal distribution)


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
# Warmup Iteration   1: 4.599 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.005 ms/op
Iteration   1: 2.970 ±(99.9%) 0.006 ms/op
Iteration   2: 3.000 ±(99.9%) 0.005 ms/op
Iteration   3: 3.013 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.995 ±(99.9%) 0.402 ms/op [Average]
  (min, avg, max) = (2.970, 2.995, 3.013), stdev = 0.022
  CI (99.9%): [2.593, 3.396] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.995 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  10.892 ms/op
                 createUser·p0.9999: 13.353 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   3.506 ms/op
                 createUser·p0.999:  6.276 ms/op
                 createUser·p0.9999: 13.982 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.038 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   4.174 ms/op
                 createUser·p0.999:  8.298 ms/op
                 createUser·p0.9999: 12.825 ms/op
                 createUser·p1.00:   14.090 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384392
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 185882 
    [ 2.500,  3.750) = 194609 
    [ 3.750,  5.000) = 2883 
    [ 5.000,  6.250) = 515 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 128 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      8.298 ms/op
     p(99.9900) =     13.664 ms/op
     p(99.9990) =     14.409 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 3.740 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
Iteration   1: 2.426 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.379 ms/op
                 existUser·p0.999:  5.935 ms/op
                 existUser·p0.9999: 13.451 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   2: 2.431 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  6.525 ms/op
                 existUser·p0.9999: 11.880 ms/op
                 existUser·p1.00:   12.747 ms/op

Iteration   3: 2.402 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.908 ms/op
                 existUser·p0.95:   2.998 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  5.792 ms/op
                 existUser·p0.9999: 11.480 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396300
  mean =      2.420 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 197246 
    [ 2.500,  3.750) = 196159 
    [ 3.750,  5.000) = 2266 
    [ 5.000,  6.250) = 183 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =      6.226 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     13.582 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


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
# Warmup Iteration   1: 3.798 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
Iteration   1: 2.436 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.537 ms/op
                 getUser·p0.50:   2.433 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  6.486 ms/op
                 getUser·p0.9999: 13.238 ms/op
                 getUser·p1.00:   13.664 ms/op

Iteration   2: 2.460 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.794 ms/op
                 getUser·p0.9999: 12.862 ms/op
                 getUser·p1.00:   13.271 ms/op

Iteration   3: 2.428 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   2.966 ms/op
                 getUser·p0.95:   3.076 ms/op
                 getUser·p0.99:   3.617 ms/op
                 getUser·p0.999:  5.661 ms/op
                 getUser·p0.9999: 10.972 ms/op
                 getUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 392912
  mean =      2.441 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 201749 
    [ 2.500,  3.750) = 186475 
    [ 3.750,  5.000) = 3451 
    [ 5.000,  6.250) = 628 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      2.445 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      7.294 ms/op
     p(99.9900) =     12.861 ms/op
     p(99.9990) =     13.551 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


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
# Warmup Iteration   1: 4.697 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.009 ms/op
Iteration   1: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.001 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.585 ms/op
                 listUser·p0.999:  9.585 ms/op
                 listUser·p0.9999: 12.294 ms/op
                 listUser·p1.00:   12.419 ms/op

Iteration   2: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.218 ms/op
                 listUser·p0.9999: 10.852 ms/op
                 listUser·p1.00:   11.272 ms/op

Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.776 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 10.474 ms/op
                 listUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319973
  mean =      2.998 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 95241 
    [ 2.500,  3.750) = 186280 
    [ 3.750,  5.000) = 31178 
    [ 5.000,  6.250) = 5951 
    [ 6.250,  7.500) = 535 
    [ 7.500,  8.750) = 201 
    [ 8.750, 10.000) = 320 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     11.223 ms/op
     p(99.9990) =     12.367 ms/op
     p(99.9999) =     12.419 ms/op
    p(100.0000) =     12.419 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.921 ± 1.664  ops/ms
ClientPb.existUser                       thrpt       3  13.118 ± 2.165  ops/ms
ClientPb.getUser                         thrpt       3  13.112 ± 1.404  ops/ms
ClientPb.listUser                        thrpt       3  10.872 ± 1.092  ops/ms
ClientPb.createUser                       avgt       3   2.522 ± 0.073   ms/op
ClientPb.existUser                        avgt       3   2.381 ± 0.110   ms/op
ClientPb.getUser                          avgt       3   2.430 ± 0.236   ms/op
ClientPb.listUser                         avgt       3   2.995 ± 0.402   ms/op
ClientPb.createUser                     sample  384392   2.495 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.860           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.298           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.664           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.516           ms/op
ClientPb.existUser                      sample  396300   2.420 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.719           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.929           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.226           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.238           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.681           ms/op
ClientPb.getUser                        sample  392912   2.441 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.537           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.445           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.982           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.294           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.861           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.664           ms/op
ClientPb.listUser                       sample  319973   2.998 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.776           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.421           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.223           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.419           ms/op
