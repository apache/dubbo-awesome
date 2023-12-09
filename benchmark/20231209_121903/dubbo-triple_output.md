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
# Warmup Iteration   1: 5.112 ops/ms
# Warmup Iteration   2: 12.059 ops/ms
# Warmup Iteration   3: 12.322 ops/ms
Iteration   1: 12.699 ops/ms
Iteration   2: 12.522 ops/ms
Iteration   3: 12.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.572 ±(99.9%) 2.021 ops/ms [Average]
  (min, avg, max) = (12.495, 12.572, 12.699), stdev = 0.111
  CI (99.9%): [10.551, 14.593] (assumes normal distribution)


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
# Warmup Iteration   1: 7.932 ops/ms
# Warmup Iteration   2: 12.674 ops/ms
# Warmup Iteration   3: 12.853 ops/ms
Iteration   1: 12.793 ops/ms
Iteration   2: 12.766 ops/ms
Iteration   3: 12.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.819 ±(99.9%) 1.276 ops/ms [Average]
  (min, avg, max) = (12.766, 12.819, 12.898), stdev = 0.070
  CI (99.9%): [11.543, 14.095] (assumes normal distribution)


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
# Warmup Iteration   1: 7.715 ops/ms
# Warmup Iteration   2: 12.564 ops/ms
# Warmup Iteration   3: 12.676 ops/ms
Iteration   1: 12.756 ops/ms
Iteration   2: 12.463 ops/ms
Iteration   3: 12.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.660 ±(99.9%) 3.108 ops/ms [Average]
  (min, avg, max) = (12.463, 12.660, 12.760), stdev = 0.170
  CI (99.9%): [9.552, 15.768] (assumes normal distribution)


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
# Warmup Iteration   1: 6.661 ops/ms
# Warmup Iteration   2: 10.516 ops/ms
# Warmup Iteration   3: 10.532 ops/ms
Iteration   1: 10.634 ops/ms
Iteration   2: 10.764 ops/ms
Iteration   3: 10.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.705 ±(99.9%) 1.200 ops/ms [Average]
  (min, avg, max) = (10.634, 10.705, 10.764), stdev = 0.066
  CI (99.9%): [9.505, 11.905] (assumes normal distribution)


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
# Warmup Iteration   1: 4.078 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.596 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.004 ms/op
Iteration   1: 2.534 ±(99.9%) 0.004 ms/op
Iteration   2: 2.548 ±(99.9%) 0.005 ms/op
Iteration   3: 2.509 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.530 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (2.509, 2.530, 2.548), stdev = 0.020
  CI (99.9%): [2.170, 2.890] (assumes normal distribution)


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
# Warmup Iteration   1: 3.639 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.004 ms/op
Iteration   1: 2.446 ±(99.9%) 0.003 ms/op
Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
Iteration   3: 2.430 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.446 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (2.430, 2.446, 2.462), stdev = 0.016
  CI (99.9%): [2.158, 2.734] (assumes normal distribution)


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
# Warmup Iteration   1: 3.768 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.004 ms/op
Iteration   1: 2.451 ±(99.9%) 0.004 ms/op
Iteration   2: 2.466 ±(99.9%) 0.004 ms/op
Iteration   3: 2.476 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.464 ±(99.9%) 0.227 ms/op [Average]
  (min, avg, max) = (2.451, 2.464, 2.476), stdev = 0.012
  CI (99.9%): [2.237, 2.691] (assumes normal distribution)


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
# Warmup Iteration   1: 4.685 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.005 ms/op
Iteration   1: 2.966 ±(99.9%) 0.005 ms/op
Iteration   2: 2.981 ±(99.9%) 0.006 ms/op
Iteration   3: 2.976 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.975 ±(99.9%) 0.139 ms/op [Average]
  (min, avg, max) = (2.966, 2.975, 2.981), stdev = 0.008
  CI (99.9%): [2.836, 3.113] (assumes normal distribution)


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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.688 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.006 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  11.101 ms/op
                 createUser·p0.9999: 13.402 ms/op
                 createUser·p1.00:   14.041 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.145 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  9.462 ms/op
                 createUser·p0.9999: 12.328 ms/op
                 createUser·p1.00:   13.386 ms/op

Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.883 ms/op
                 createUser·p0.999:  8.388 ms/op
                 createUser·p0.9999: 11.065 ms/op
                 createUser·p1.00:   14.746 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382648
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 184965 
    [ 2.500,  3.750) = 193796 
    [ 3.750,  5.000) = 2949 
    [ 5.000,  6.250) = 385 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 90 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      8.454 ms/op
     p(99.9900) =     13.091 ms/op
     p(99.9990) =     13.954 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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
# Warmup Iteration   1: 3.661 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
Iteration   1: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.023 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.404 ms/op
                 existUser·p0.999:  5.128 ms/op
                 existUser·p0.9999: 13.337 ms/op
                 existUser·p1.00:   14.762 ms/op

Iteration   2: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.001 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  7.135 ms/op
                 existUser·p0.9999: 18.444 ms/op
                 existUser·p1.00:   18.940 ms/op

Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.650 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  7.284 ms/op
                 existUser·p0.9999: 11.977 ms/op
                 existUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391949
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 192464 
    [ 2.500,  3.750) = 196695 
    [ 3.750,  5.000) = 2107 
    [ 5.000,  6.250) = 248 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.551 ms/op
     p(99.9000) =      6.242 ms/op
     p(99.9900) =     14.090 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.006 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.650 ms/op
                 getUser·p0.999:  9.615 ms/op
                 getUser·p0.9999: 17.083 ms/op
                 getUser·p1.00:   18.350 ms/op

Iteration   2: 2.520 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.891 ms/op
                 getUser·p0.999:  9.781 ms/op
                 getUser·p0.9999: 15.212 ms/op
                 getUser·p1.00:   17.007 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   4.076 ms/op
                 getUser·p0.999:  8.145 ms/op
                 getUser·p0.9999: 12.348 ms/op
                 getUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382911
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 189150 
    [ 2.500,  3.750) = 189206 
    [ 3.750,  5.000) = 3557 
    [ 5.000,  6.250) = 472 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 69 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      8.193 ms/op
     p(99.9900) =     15.080 ms/op
     p(99.9990) =     17.635 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


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
# Warmup Iteration   1: 4.871 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.009 ms/op
Iteration   1: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.745 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  8.897 ms/op
                 listUser·p0.9999: 11.430 ms/op
                 listUser·p1.00:   11.993 ms/op

Iteration   2: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.809 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.625 ms/op
                 listUser·p0.9999: 10.858 ms/op
                 listUser·p1.00:   11.616 ms/op

Iteration   3: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.026 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.011 ms/op
                 listUser·p0.9999: 10.868 ms/op
                 listUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321112
  mean =      2.987 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 100513 
    [ 2.500,  3.750) = 181929 
    [ 3.750,  5.000) = 31069 
    [ 5.000,  6.250) = 6064 
    [ 6.250,  7.500) = 755 
    [ 7.500,  8.750) = 240 
    [ 8.750, 10.000) = 253 
    [10.000, 11.250) = 138 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.140 ms/op
     p(99.9900) =     11.010 ms/op
     p(99.9990) =     11.762 ms/op
     p(99.9999) =     11.993 ms/op
    p(100.0000) =     11.993 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.572 ± 2.021  ops/ms
ClientPb.existUser                       thrpt       3  12.819 ± 1.276  ops/ms
ClientPb.getUser                         thrpt       3  12.660 ± 3.108  ops/ms
ClientPb.listUser                        thrpt       3  10.705 ± 1.200  ops/ms
ClientPb.createUser                       avgt       3   2.530 ± 0.360   ms/op
ClientPb.existUser                        avgt       3   2.446 ± 0.288   ms/op
ClientPb.getUser                          avgt       3   2.464 ± 0.227   ms/op
ClientPb.listUser                         avgt       3   2.975 ± 0.139   ms/op
ClientPb.createUser                     sample  382648   2.506 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.798           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.454           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.091           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.746           ms/op
ClientPb.existUser                      sample  391949   2.447 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.650           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.242           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.090           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.940           ms/op
ClientPb.getUser                        sample  382911   2.505 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.568           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.193           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.080           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.350           ms/op
ClientPb.listUser                       sample  321112   2.987 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.745           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.140           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.010           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.993           ms/op
