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
# Warmup Iteration   1: 4.845 ops/ms
# Warmup Iteration   2: 12.214 ops/ms
# Warmup Iteration   3: 12.232 ops/ms
Iteration   1: 12.474 ops/ms
Iteration   2: 12.716 ops/ms
Iteration   3: 12.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.572 ±(99.9%) 2.328 ops/ms [Average]
  (min, avg, max) = (12.474, 12.572, 12.716), stdev = 0.128
  CI (99.9%): [10.244, 14.900] (assumes normal distribution)


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
# Warmup Iteration   1: 8.336 ops/ms
# Warmup Iteration   2: 13.026 ops/ms
# Warmup Iteration   3: 13.043 ops/ms
Iteration   1: 13.052 ops/ms
Iteration   2: 13.144 ops/ms
Iteration   3: 13.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.087 ±(99.9%) 0.909 ops/ms [Average]
  (min, avg, max) = (13.052, 13.087, 13.144), stdev = 0.050
  CI (99.9%): [12.178, 13.997] (assumes normal distribution)


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
# Warmup Iteration   1: 7.852 ops/ms
# Warmup Iteration   2: 12.508 ops/ms
# Warmup Iteration   3: 12.688 ops/ms
Iteration   1: 12.760 ops/ms
Iteration   2: 12.656 ops/ms
Iteration   3: 12.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.744 ±(99.9%) 1.486 ops/ms [Average]
  (min, avg, max) = (12.656, 12.744, 12.817), stdev = 0.081
  CI (99.9%): [11.258, 14.231] (assumes normal distribution)


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
# Warmup Iteration   1: 6.535 ops/ms
# Warmup Iteration   2: 10.526 ops/ms
# Warmup Iteration   3: 10.574 ops/ms
Iteration   1: 10.503 ops/ms
Iteration   2: 10.439 ops/ms
Iteration   3: 10.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.430 ±(99.9%) 1.426 ops/ms [Average]
  (min, avg, max) = (10.348, 10.430, 10.503), stdev = 0.078
  CI (99.9%): [9.004, 11.857] (assumes normal distribution)


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
# Warmup Iteration   1: 4.147 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.004 ms/op
Iteration   1: 2.496 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.476 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.479 ±(99.9%) 0.307 ms/op [Average]
  (min, avg, max) = (2.463, 2.479, 2.496), stdev = 0.017
  CI (99.9%): [2.171, 2.786] (assumes normal distribution)


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.003 ms/op
Iteration   1: 2.439 ±(99.9%) 0.003 ms/op
Iteration   2: 2.455 ±(99.9%) 0.003 ms/op
Iteration   3: 2.431 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.442 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (2.431, 2.442, 2.455), stdev = 0.012
  CI (99.9%): [2.225, 2.658] (assumes normal distribution)


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
# Warmup Iteration   1: 3.971 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.005 ms/op
Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
Iteration   3: 2.515 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.504 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.495, 2.504, 2.515), stdev = 0.010
  CI (99.9%): [2.313, 2.695] (assumes normal distribution)


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
# Warmup Iteration   1: 4.638 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
Iteration   1: 3.033 ±(99.9%) 0.005 ms/op
Iteration   2: 3.040 ±(99.9%) 0.005 ms/op
Iteration   3: 3.026 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.033 ±(99.9%) 0.125 ms/op [Average]
  (min, avg, max) = (3.026, 3.033, 3.040), stdev = 0.007
  CI (99.9%): [2.908, 3.158] (assumes normal distribution)


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.629 ms/op
                 createUser·p0.999:  11.534 ms/op
                 createUser·p0.9999: 14.372 ms/op
                 createUser·p1.00:   14.991 ms/op

Iteration   2: 2.520 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.588 ms/op
                 createUser·p0.999:  8.260 ms/op
                 createUser·p0.9999: 21.320 ms/op
                 createUser·p1.00:   21.660 ms/op

Iteration   3: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.835 ms/op
                 createUser·p0.999:  8.166 ms/op
                 createUser·p0.9999: 9.895 ms/op
                 createUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380953
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 184367 
    [ 2.500,  5.000) = 195796 
    [ 5.000,  7.500) = 355 
    [ 7.500, 10.000) = 189 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      8.439 ms/op
     p(99.9900) =     14.897 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 3.764 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
Iteration   1: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.016 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.715 ms/op
                 existUser·p0.999:  7.026 ms/op
                 existUser·p0.9999: 12.893 ms/op
                 existUser·p1.00:   13.353 ms/op

Iteration   2: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  5.568 ms/op
                 existUser·p0.9999: 12.681 ms/op
                 existUser·p1.00:   13.353 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.872 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  8.198 ms/op
                 existUser·p0.9999: 11.698 ms/op
                 existUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389648
  mean =      2.461 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 193850 
    [ 2.500,  3.750) = 191495 
    [ 3.750,  5.000) = 3235 
    [ 5.000,  6.250) = 548 
    [ 6.250,  7.500) = 99 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      7.277 ms/op
     p(99.9900) =     12.665 ms/op
     p(99.9990) =     13.276 ms/op
     p(99.9999) =     13.353 ms/op
    p(100.0000) =     13.353 ms/op


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
# Warmup Iteration   1: 3.944 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
Iteration   1: 2.493 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.998 ms/op
                 getUser·p0.999:  9.810 ms/op
                 getUser·p0.9999: 13.023 ms/op
                 getUser·p1.00:   13.664 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  8.630 ms/op
                 getUser·p0.9999: 12.845 ms/op
                 getUser·p1.00:   13.664 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.867 ms/op
                 getUser·p0.999:  8.190 ms/op
                 getUser·p0.9999: 11.624 ms/op
                 getUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384850
  mean =      2.492 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 190954 
    [ 2.500,  3.750) = 187963 
    [ 3.750,  5.000) = 4633 
    [ 5.000,  6.250) = 719 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 153 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      4.067 ms/op
     p(99.9000) =      8.620 ms/op
     p(99.9900) =     12.861 ms/op
     p(99.9990) =     13.578 ms/op
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
# Warmup Iteration   1: 5.038 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.009 ms/op
Iteration   1: 3.055 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 11.363 ms/op
                 listUser·p1.00:   12.861 ms/op

Iteration   2: 3.026 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.732 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.013 ms/op
                 listUser·p0.9999: 11.949 ms/op
                 listUser·p1.00:   12.698 ms/op

Iteration   3: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.023 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.062 ms/op
                 listUser·p0.9999: 10.623 ms/op
                 listUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316276
  mean =      3.033 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 87733 
    [ 2.500,  3.750) = 187560 
    [ 3.750,  5.000) = 33303 
    [ 5.000,  6.250) = 6178 
    [ 6.250,  7.500) = 718 
    [ 7.500,  8.750) = 224 
    [ 8.750, 10.000) = 216 
    [10.000, 11.250) = 169 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.285 ms/op
     p(99.9900) =     11.600 ms/op
     p(99.9990) =     12.644 ms/op
     p(99.9999) =     12.861 ms/op
    p(100.0000) =     12.861 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.572 ± 2.328  ops/ms
ClientPb.existUser                       thrpt       3  13.087 ± 0.909  ops/ms
ClientPb.getUser                         thrpt       3  12.744 ± 1.486  ops/ms
ClientPb.listUser                        thrpt       3  10.430 ± 1.426  ops/ms
ClientPb.createUser                       avgt       3   2.479 ± 0.307   ms/op
ClientPb.existUser                        avgt       3   2.442 ± 0.217   ms/op
ClientPb.getUser                          avgt       3   2.504 ± 0.191   ms/op
ClientPb.listUser                         avgt       3   3.033 ± 0.125   ms/op
ClientPb.createUser                     sample  380953   2.518 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.924           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.439           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.897           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.660           ms/op
ClientPb.existUser                      sample  389648   2.461 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.872           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.277           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.665           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.353           ms/op
ClientPb.getUser                        sample  384850   2.492 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.778           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.067           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.620           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.861           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.664           ms/op
ClientPb.listUser                       sample  316276   3.033 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.732           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.285           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.600           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.861           ms/op
