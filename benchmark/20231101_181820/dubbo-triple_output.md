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
# Warmup Iteration   1: 4.408 ops/ms
# Warmup Iteration   2: 11.687 ops/ms
# Warmup Iteration   3: 11.839 ops/ms
Iteration   1: 12.113 ops/ms
Iteration   2: 12.147 ops/ms
Iteration   3: 12.188 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.149 ±(99.9%) 0.685 ops/ms [Average]
  (min, avg, max) = (12.113, 12.149, 12.188), stdev = 0.038
  CI (99.9%): [11.464, 12.835] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.389 ops/ms
# Warmup Iteration   2: 12.499 ops/ms
# Warmup Iteration   3: 12.645 ops/ms
Iteration   1: 12.588 ops/ms
Iteration   2: 12.644 ops/ms
Iteration   3: 12.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.637 ±(99.9%) 0.848 ops/ms [Average]
  (min, avg, max) = (12.588, 12.637, 12.680), stdev = 0.047
  CI (99.9%): [11.789, 13.486] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.365 ops/ms
# Warmup Iteration   2: 12.110 ops/ms
# Warmup Iteration   3: 12.490 ops/ms
Iteration   1: 12.324 ops/ms
Iteration   2: 12.568 ops/ms
Iteration   3: 12.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.443 ±(99.9%) 2.221 ops/ms [Average]
  (min, avg, max) = (12.324, 12.443, 12.568), stdev = 0.122
  CI (99.9%): [10.222, 14.663] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.155 ops/ms
# Warmup Iteration   2: 10.137 ops/ms
# Warmup Iteration   3: 10.044 ops/ms
Iteration   1: 10.138 ops/ms
Iteration   2: 10.147 ops/ms
Iteration   3: 10.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.127 ±(99.9%) 0.500 ops/ms [Average]
  (min, avg, max) = (10.096, 10.127, 10.147), stdev = 0.027
  CI (99.9%): [9.628, 10.627] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.334 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.689 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.602 ±(99.9%) 0.003 ms/op
Iteration   1: 2.614 ±(99.9%) 0.004 ms/op
Iteration   2: 2.652 ±(99.9%) 0.004 ms/op
Iteration   3: 2.571 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.612 ±(99.9%) 0.738 ms/op [Average]
  (min, avg, max) = (2.571, 2.612, 2.652), stdev = 0.040
  CI (99.9%): [1.874, 3.350] (assumes normal distribution)


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
# Warmup Iteration   1: 4.002 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.002 ms/op
Iteration   1: 2.523 ±(99.9%) 0.004 ms/op
Iteration   2: 2.526 ±(99.9%) 0.004 ms/op
Iteration   3: 2.505 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.518 ±(99.9%) 0.206 ms/op [Average]
  (min, avg, max) = (2.505, 2.518, 2.526), stdev = 0.011
  CI (99.9%): [2.312, 2.725] (assumes normal distribution)


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
# Warmup Iteration   1: 4.310 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.585 ±(99.9%) 0.005 ms/op
Iteration   1: 2.579 ±(99.9%) 0.004 ms/op
Iteration   2: 2.564 ±(99.9%) 0.004 ms/op
Iteration   3: 2.612 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.585 ±(99.9%) 0.450 ms/op [Average]
  (min, avg, max) = (2.564, 2.585, 2.612), stdev = 0.025
  CI (99.9%): [2.135, 3.035] (assumes normal distribution)


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
# Warmup Iteration   1: 5.204 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.005 ms/op
Iteration   1: 3.123 ±(99.9%) 0.005 ms/op
Iteration   2: 3.131 ±(99.9%) 0.006 ms/op
Iteration   3: 3.121 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.125 ±(99.9%) 0.102 ms/op [Average]
  (min, avg, max) = (3.121, 3.125, 3.131), stdev = 0.006
  CI (99.9%): [3.023, 3.227] (assumes normal distribution)


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
# Warmup Iteration   1: 4.417 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.742 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.603 ±(99.9%) 0.006 ms/op
Iteration   1: 2.589 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.017 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  12.149 ms/op
                 createUser·p0.9999: 13.653 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   2: 2.608 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   2.679 ms/op
                 createUser·p0.90:   3.166 ms/op
                 createUser·p0.95:   3.305 ms/op
                 createUser·p0.99:   4.170 ms/op
                 createUser·p0.999:  10.132 ms/op
                 createUser·p0.9999: 13.389 ms/op
                 createUser·p1.00:   13.763 ms/op

Iteration   3: 2.590 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   2.683 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  8.569 ms/op
                 createUser·p0.9999: 11.190 ms/op
                 createUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 369480
  mean =      2.595 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 174373 
    [ 2.500,  3.750) = 189518 
    [ 3.750,  5.000) = 3877 
    [ 5.000,  6.250) = 1213 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 134 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.666 ms/op
     p(90.0000) =      3.150 ms/op
     p(95.0000) =      3.277 ms/op
     p(99.0000) =      4.027 ms/op
     p(99.9000) =      8.634 ms/op
     p(99.9900) =     13.518 ms/op
     p(99.9990) =     13.849 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 3.842 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.006 ms/op
Iteration   1: 2.524 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.084 ms/op
                 existUser·p0.95:   3.244 ms/op
                 existUser·p0.99:   4.002 ms/op
                 existUser·p0.999:  5.792 ms/op
                 existUser·p0.9999: 13.976 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.080 ms/op
                 existUser·p0.95:   3.195 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  9.463 ms/op
                 existUser·p0.9999: 14.719 ms/op
                 existUser·p1.00:   15.188 ms/op

Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   2.630 ms/op
                 existUser·p0.90:   3.101 ms/op
                 existUser·p0.95:   3.224 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  6.984 ms/op
                 existUser·p0.9999: 12.148 ms/op
                 existUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 378809
  mean =      2.532 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 181454 
    [ 2.500,  3.750) = 192321 
    [ 3.750,  5.000) = 3981 
    [ 5.000,  6.250) = 623 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      6.444 ms/op
     p(99.9900) =     14.027 ms/op
     p(99.9990) =     14.949 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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
# Warmup Iteration   1: 4.286 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.706 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.634 ±(99.9%) 0.007 ms/op
Iteration   1: 2.642 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   2.662 ms/op
                 getUser·p0.90:   3.240 ms/op
                 getUser·p0.95:   3.416 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  13.255 ms/op
                 getUser·p0.9999: 14.929 ms/op
                 getUser·p1.00:   15.581 ms/op

Iteration   2: 2.608 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   2.642 ms/op
                 getUser·p0.90:   3.191 ms/op
                 getUser·p0.95:   3.355 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  10.722 ms/op
                 getUser·p0.9999: 14.725 ms/op
                 getUser·p1.00:   15.303 ms/op

Iteration   3: 2.572 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   2.605 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  6.989 ms/op
                 getUser·p0.9999: 10.783 ms/op
                 getUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 367821
  mean =      2.607 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 172425 
    [ 2.500,  3.750) = 188170 
    [ 3.750,  5.000) = 6098 
    [ 5.000,  6.250) = 641 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 95 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.187 ms/op
     p(95.0000) =      3.346 ms/op
     p(99.0000) =      4.133 ms/op
     p(99.9000) =      8.739 ms/op
     p(99.9900) =     14.647 ms/op
     p(99.9990) =     15.357 ms/op
     p(99.9999) =     15.581 ms/op
    p(100.0000) =     15.581 ms/op


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
# Warmup Iteration   1: 4.923 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.010 ms/op
Iteration   1: 3.147 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.935 ms/op
                 listUser·p0.50:   3.080 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   5.816 ms/op
                 listUser·p0.999:  9.182 ms/op
                 listUser·p0.9999: 11.925 ms/op
                 listUser·p1.00:   12.501 ms/op

Iteration   2: 3.162 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.004 ms/op
                 listUser·p0.50:   3.088 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   5.980 ms/op
                 listUser·p0.999:  9.632 ms/op
                 listUser·p0.9999: 11.385 ms/op
                 listUser·p1.00:   12.173 ms/op

Iteration   3: 3.122 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.808 ms/op
                 listUser·p0.50:   3.056 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.765 ms/op
                 listUser·p0.9999: 12.165 ms/op
                 listUser·p1.00:   13.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 305059
  mean =      3.144 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 69157 
    [ 2.500,  3.750) = 186272 
    [ 3.750,  5.000) = 40174 
    [ 5.000,  6.250) = 7680 
    [ 6.250,  7.500) = 1036 
    [ 7.500,  8.750) = 212 
    [ 8.750, 10.000) = 248 
    [10.000, 11.250) = 150 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     11.960 ms/op
     p(99.9990) =     13.087 ms/op
     p(99.9999) =     13.386 ms/op
    p(100.0000) =     13.386 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.149 ± 0.685  ops/ms
ClientPb.existUser                       thrpt       3  12.637 ± 0.848  ops/ms
ClientPb.getUser                         thrpt       3  12.443 ± 2.221  ops/ms
ClientPb.listUser                        thrpt       3  10.127 ± 0.500  ops/ms
ClientPb.createUser                       avgt       3   2.612 ± 0.738   ms/op
ClientPb.existUser                        avgt       3   2.518 ± 0.206   ms/op
ClientPb.getUser                          avgt       3   2.585 ± 0.450   ms/op
ClientPb.listUser                         avgt       3   3.125 ± 0.102   ms/op
ClientPb.createUser                     sample  369480   2.595 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.794           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.666           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.277           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.027           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.634           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.518           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.320           ms/op
ClientPb.existUser                      sample  378809   2.532 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.706           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.597           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.920           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.444           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.027           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.188           ms/op
ClientPb.getUser                        sample  367821   2.607 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.936           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.638           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.133           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.739           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.647           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.581           ms/op
ClientPb.listUser                       sample  305059   3.144 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.808           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.076           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.833           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.470           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.960           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.386           ms/op
