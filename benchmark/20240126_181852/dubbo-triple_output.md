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
# Warmup Iteration   1: 5.022 ops/ms
# Warmup Iteration   2: 11.881 ops/ms
# Warmup Iteration   3: 12.156 ops/ms
Iteration   1: 12.503 ops/ms
Iteration   2: 12.553 ops/ms
Iteration   3: 12.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.542 ±(99.9%) 0.625 ops/ms [Average]
  (min, avg, max) = (12.503, 12.542, 12.569), stdev = 0.034
  CI (99.9%): [11.917, 13.167] (assumes normal distribution)


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
# Warmup Iteration   1: 8.135 ops/ms
# Warmup Iteration   2: 12.752 ops/ms
# Warmup Iteration   3: 12.880 ops/ms
Iteration   1: 12.891 ops/ms
Iteration   2: 13.026 ops/ms
Iteration   3: 13.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.972 ±(99.9%) 1.311 ops/ms [Average]
  (min, avg, max) = (12.891, 12.972, 13.026), stdev = 0.072
  CI (99.9%): [11.661, 14.283] (assumes normal distribution)


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
# Warmup Iteration   1: 7.735 ops/ms
# Warmup Iteration   2: 12.461 ops/ms
# Warmup Iteration   3: 12.581 ops/ms
Iteration   1: 12.709 ops/ms
Iteration   2: 12.712 ops/ms
Iteration   3: 12.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.701 ±(99.9%) 0.310 ops/ms [Average]
  (min, avg, max) = (12.681, 12.701, 12.712), stdev = 0.017
  CI (99.9%): [12.391, 13.011] (assumes normal distribution)


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
# Warmup Iteration   1: 6.576 ops/ms
# Warmup Iteration   2: 10.448 ops/ms
# Warmup Iteration   3: 10.536 ops/ms
Iteration   1: 10.473 ops/ms
Iteration   2: 10.573 ops/ms
Iteration   3: 10.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.541 ±(99.9%) 1.072 ops/ms [Average]
  (min, avg, max) = (10.473, 10.541, 10.576), stdev = 0.059
  CI (99.9%): [9.468, 11.613] (assumes normal distribution)


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
# Warmup Iteration   1: 3.939 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.584 ±(99.9%) 0.005 ms/op
Iteration   1: 2.614 ±(99.9%) 0.004 ms/op
Iteration   2: 2.569 ±(99.9%) 0.004 ms/op
Iteration   3: 2.581 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.588 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (2.569, 2.588, 2.614), stdev = 0.023
  CI (99.9%): [2.162, 3.014] (assumes normal distribution)


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
# Warmup Iteration   1: 3.706 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.004 ms/op
Iteration   1: 2.510 ±(99.9%) 0.004 ms/op
Iteration   2: 2.510 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.506 ±(99.9%) 0.129 ms/op [Average]
  (min, avg, max) = (2.497, 2.506, 2.510), stdev = 0.007
  CI (99.9%): [2.377, 2.634] (assumes normal distribution)


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.004 ms/op
Iteration   1: 2.488 ±(99.9%) 0.005 ms/op
Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
Iteration   3: 2.509 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.493 ±(99.9%) 0.255 ms/op [Average]
  (min, avg, max) = (2.482, 2.493, 2.509), stdev = 0.014
  CI (99.9%): [2.238, 2.749] (assumes normal distribution)


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
# Warmup Iteration   1: 4.624 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
Iteration   1: 2.990 ±(99.9%) 0.004 ms/op
Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
Iteration   3: 3.028 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.011 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (2.990, 3.011, 3.028), stdev = 0.020
  CI (99.9%): [2.651, 3.372] (assumes normal distribution)


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
# Warmup Iteration   1: 4.171 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.626 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
Iteration   1: 2.504 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  11.850 ms/op
                 createUser·p0.9999: 14.209 ms/op
                 createUser·p1.00:   15.172 ms/op

Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  9.441 ms/op
                 createUser·p0.9999: 12.026 ms/op
                 createUser·p1.00:   12.796 ms/op

Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   4.104 ms/op
                 createUser·p0.999:  7.845 ms/op
                 createUser·p0.9999: 12.802 ms/op
                 createUser·p1.00:   14.713 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381910
  mean =      2.511 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 184324 
    [ 2.500,  3.750) = 193257 
    [ 3.750,  5.000) = 3401 
    [ 5.000,  6.250) = 440 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 128 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      8.734 ms/op
     p(99.9900) =     13.265 ms/op
     p(99.9990) =     15.057 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


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
# Warmup Iteration   1: 3.676 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
Iteration   1: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  6.317 ms/op
                 existUser·p0.9999: 14.701 ms/op
                 existUser·p1.00:   15.204 ms/op

Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  7.086 ms/op
                 existUser·p0.9999: 12.632 ms/op
                 existUser·p1.00:   13.664 ms/op

Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  5.398 ms/op
                 existUser·p0.9999: 12.337 ms/op
                 existUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389224
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 191976 
    [ 2.500,  3.750) = 193898 
    [ 3.750,  5.000) = 2583 
    [ 5.000,  6.250) = 338 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      6.348 ms/op
     p(99.9900) =     12.911 ms/op
     p(99.9990) =     15.011 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


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
# Warmup Iteration   1: 4.113 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
Iteration   1: 2.460 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.576 ms/op
                 getUser·p0.999:  11.012 ms/op
                 getUser·p0.9999: 16.548 ms/op
                 getUser·p1.00:   16.712 ms/op

Iteration   2: 2.485 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  9.328 ms/op
                 getUser·p0.9999: 14.172 ms/op
                 getUser·p1.00:   15.221 ms/op

Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.654 ms/op
                 getUser·p0.999:  5.930 ms/op
                 getUser·p0.9999: 11.239 ms/op
                 getUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389677
  mean =      2.461 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 194525 
    [ 2.500,  3.750) = 190941 
    [ 3.750,  5.000) = 2990 
    [ 5.000,  6.250) = 690 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      8.416 ms/op
     p(99.9900) =     15.876 ms/op
     p(99.9990) =     16.653 ms/op
     p(99.9999) =     16.712 ms/op
    p(100.0000) =     16.712 ms/op


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
# Warmup Iteration   1: 4.659 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.008 ms/op
Iteration   1: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.873 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  8.618 ms/op
                 listUser·p0.9999: 11.141 ms/op
                 listUser·p1.00:   11.616 ms/op

Iteration   2: 2.998 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.077 ms/op
                 listUser·p0.9999: 13.353 ms/op
                 listUser·p1.00:   15.778 ms/op

Iteration   3: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.844 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.650 ms/op
                 listUser·p0.9999: 11.590 ms/op
                 listUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320101
  mean =      2.996 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 92176 
    [ 2.500,  3.750) = 189840 
    [ 3.750,  5.000) = 31195 
    [ 5.000,  6.250) = 5609 
    [ 6.250,  7.500) = 492 
    [ 7.500,  8.750) = 257 
    [ 8.750, 10.000) = 235 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     12.075 ms/op
     p(99.9990) =     15.482 ms/op
     p(99.9999) =     15.778 ms/op
    p(100.0000) =     15.778 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.542 ± 0.625  ops/ms
ClientPb.existUser                       thrpt       3  12.972 ± 1.311  ops/ms
ClientPb.getUser                         thrpt       3  12.701 ± 0.310  ops/ms
ClientPb.listUser                        thrpt       3  10.541 ± 1.072  ops/ms
ClientPb.createUser                       avgt       3   2.588 ± 0.426   ms/op
ClientPb.existUser                        avgt       3   2.506 ± 0.129   ms/op
ClientPb.getUser                          avgt       3   2.493 ± 0.255   ms/op
ClientPb.listUser                         avgt       3   3.011 ± 0.360   ms/op
ClientPb.createUser                     sample  381910   2.511 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.821           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.734           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.265           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.172           ms/op
ClientPb.existUser                      sample  389224   2.464 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.899           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.348           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.911           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.204           ms/op
ClientPb.getUser                        sample  389677   2.461 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.735           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.416           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.876           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.712           ms/op
ClientPb.listUser                       sample  320101   2.996 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.844           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.126           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.075           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.778           ms/op
