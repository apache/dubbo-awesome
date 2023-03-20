# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.458 ops/ms
# Warmup Iteration   2: 5.953 ops/ms
# Warmup Iteration   3: 8.935 ops/ms
Iteration   1: 9.639 ops/ms
Iteration   2: 9.884 ops/ms
Iteration   3: 9.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.777 ±(99.9%) 2.281 ops/ms [Average]
  (min, avg, max) = (9.639, 9.777, 9.884), stdev = 0.125
  CI (99.9%): [7.496, 12.057] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.734 ops/ms
# Warmup Iteration   2: 9.351 ops/ms
# Warmup Iteration   3: 10.365 ops/ms
Iteration   1: 9.815 ops/ms
Iteration   2: 9.866 ops/ms
Iteration   3: 10.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.102 ±(99.9%) 8.281 ops/ms [Average]
  (min, avg, max) = (9.815, 10.102, 10.625), stdev = 0.454
  CI (99.9%): [1.821, 18.384] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.722 ops/ms
# Warmup Iteration   2: 9.295 ops/ms
# Warmup Iteration   3: 9.575 ops/ms
Iteration   1: 9.716 ops/ms
Iteration   2: 9.643 ops/ms
Iteration   3: 10.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.847 ±(99.9%) 5.314 ops/ms [Average]
  (min, avg, max) = (9.643, 9.847, 10.180), stdev = 0.291
  CI (99.9%): [4.533, 15.161] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.493 ops/ms
# Warmup Iteration   2: 8.037 ops/ms
# Warmup Iteration   3: 8.290 ops/ms
Iteration   1: 8.413 ops/ms
Iteration   2: 8.585 ops/ms
Iteration   3: 8.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.520 ±(99.9%) 1.698 ops/ms [Average]
  (min, avg, max) = (8.413, 8.520, 8.585), stdev = 0.093
  CI (99.9%): [6.822, 10.218] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.109 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.003 ms/op
Iteration   1: 3.177 ±(99.9%) 0.002 ms/op
Iteration   2: 3.143 ±(99.9%) 0.009 ms/op
Iteration   3: 3.225 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.182 ±(99.9%) 0.750 ms/op [Average]
  (min, avg, max) = (3.143, 3.182, 3.225), stdev = 0.041
  CI (99.9%): [2.432, 3.932] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.926 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.356 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.004 ms/op
Iteration   1: 3.154 ±(99.9%) 0.007 ms/op
Iteration   2: 3.163 ±(99.9%) 0.009 ms/op
Iteration   3: 3.110 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.142 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (3.110, 3.142, 3.163), stdev = 0.029
  CI (99.9%): [2.622, 3.663] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.057 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.432 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.001 ms/op
Iteration   1: 3.239 ±(99.9%) 0.003 ms/op
Iteration   2: 3.295 ±(99.9%) 0.006 ms/op
Iteration   3: 3.277 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.270 ±(99.9%) 0.526 ms/op [Average]
  (min, avg, max) = (3.239, 3.270, 3.295), stdev = 0.029
  CI (99.9%): [2.745, 3.796] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.236 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.073 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.008 ms/op
Iteration   1: 3.768 ±(99.9%) 0.006 ms/op
Iteration   2: 3.690 ±(99.9%) 0.006 ms/op
Iteration   3: 3.725 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.728 ±(99.9%) 0.713 ms/op [Average]
  (min, avg, max) = (3.690, 3.728, 3.768), stdev = 0.039
  CI (99.9%): [3.014, 4.441] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.660 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.009 ms/op
Iteration   1: 3.137 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  18.219 ms/op
                 createUser·p0.9999: 22.473 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   2: 3.274 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.195 ms/op
                 createUser·p0.999:  14.871 ms/op
                 createUser·p0.9999: 22.935 ms/op
                 createUser·p1.00:   25.231 ms/op

Iteration   3: 3.180 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  11.698 ms/op
                 createUser·p0.9999: 22.443 ms/op
                 createUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300119
  mean =      3.196 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16912 
    [ 2.500,  5.000) = 277805 
    [ 5.000,  7.500) = 4517 
    [ 7.500, 10.000) = 487 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     15.073 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     24.772 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.944 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.368 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.009 ms/op
Iteration   1: 3.140 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  8.946 ms/op
                 existUser·p0.9999: 31.058 ms/op
                 existUser·p1.00:   31.982 ms/op

Iteration   2: 3.131 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.040 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  15.622 ms/op
                 existUser·p0.9999: 23.626 ms/op
                 existUser·p1.00:   24.510 ms/op

Iteration   3: 3.182 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   6.153 ms/op
                 existUser·p0.999:  15.327 ms/op
                 existUser·p0.9999: 25.261 ms/op
                 existUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304708
  mean =      3.151 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13165 
    [ 2.500,  5.000) = 284775 
    [ 5.000,  7.500) = 5974 
    [ 7.500, 10.000) = 339 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.040 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     15.335 ms/op
     p(99.9900) =     29.613 ms/op
     p(99.9990) =     31.685 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.200 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.010 ms/op
Iteration   1: 3.203 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  14.882 ms/op
                 getUser·p0.9999: 26.968 ms/op
                 getUser·p1.00:   27.394 ms/op

Iteration   2: 3.253 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.382 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   5.540 ms/op
                 getUser·p0.999:  8.634 ms/op
                 getUser·p0.9999: 26.401 ms/op
                 getUser·p1.00:   27.591 ms/op

Iteration   3: 3.210 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.681 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   4.190 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  11.174 ms/op
                 getUser·p0.9999: 22.057 ms/op
                 getUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297670
  mean =      3.222 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17562 
    [ 2.500,  5.000) = 271267 
    [ 5.000,  7.500) = 7991 
    [ 7.500, 10.000) = 485 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      0.979 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     11.375 ms/op
     p(99.9900) =     26.164 ms/op
     p(99.9990) =     27.526 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.926 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.042 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.845 ±(99.9%) 0.012 ms/op
Iteration   1: 3.859 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.791 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  16.547 ms/op
                 listUser·p0.9999: 22.938 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   2: 3.797 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   6.879 ms/op
                 listUser·p0.999:  13.222 ms/op
                 listUser·p0.9999: 15.511 ms/op
                 listUser·p1.00:   15.712 ms/op

Iteration   3: 3.745 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  13.959 ms/op
                 listUser·p0.9999: 16.351 ms/op
                 listUser·p1.00:   16.548 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252656
  mean =      3.800 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 243320 
    [ 5.000,  7.500) = 7466 
    [ 7.500, 10.000) = 1155 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 311 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     14.025 ms/op
     p(99.9900) =     22.289 ms/op
     p(99.9990) =     24.284 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.777 ± 2.281  ops/ms
ClientPb.existUser                       thrpt       3  10.102 ± 8.281  ops/ms
ClientPb.getUser                         thrpt       3   9.847 ± 5.314  ops/ms
ClientPb.listUser                        thrpt       3   8.520 ± 1.698  ops/ms
ClientPb.createUser                       avgt       3   3.182 ± 0.750   ms/op
ClientPb.existUser                        avgt       3   3.142 ± 0.520   ms/op
ClientPb.getUser                          avgt       3   3.270 ± 0.526   ms/op
ClientPb.listUser                         avgt       3   3.728 ± 0.713   ms/op
ClientPb.createUser                     sample  300119   3.196 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.783           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.678           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.145           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.073           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.544           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.231           ms/op
ClientPb.existUser                      sample  304708   3.151 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.040           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.490           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.932           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.718           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.335           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.613           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.982           ms/op
ClientPb.getUser                        sample  297670   3.222 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.979           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.617           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.923           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.375           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.164           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.591           ms/op
ClientPb.listUser                       sample  252656   3.800 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.791           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.980           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.025           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.289           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.609           ms/op
