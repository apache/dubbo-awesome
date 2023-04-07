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
# Warmup Iteration   1: 1.423 ops/ms
# Warmup Iteration   2: 3.711 ops/ms
# Warmup Iteration   3: 7.123 ops/ms
Iteration   1: 7.312 ops/ms
Iteration   2: 7.677 ops/ms
Iteration   3: 8.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.666 ±(99.9%) 6.339 ops/ms [Average]
  (min, avg, max) = (7.312, 7.666, 8.007), stdev = 0.347
  CI (99.9%): [1.327, 14.004] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.290 ops/ms
# Warmup Iteration   2: 6.337 ops/ms
# Warmup Iteration   3: 7.673 ops/ms
Iteration   1: 8.086 ops/ms
Iteration   2: 8.084 ops/ms
Iteration   3: 8.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.248 ±(99.9%) 5.163 ops/ms [Average]
  (min, avg, max) = (8.084, 8.248, 8.575), stdev = 0.283
  CI (99.9%): [3.086, 13.411] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.258 ops/ms
# Warmup Iteration   2: 5.976 ops/ms
# Warmup Iteration   3: 7.486 ops/ms
Iteration   1: 7.853 ops/ms
Iteration   2: 8.161 ops/ms
Iteration   3: 8.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.082 ±(99.9%) 3.669 ops/ms [Average]
  (min, avg, max) = (7.853, 8.082, 8.231), stdev = 0.201
  CI (99.9%): [4.413, 11.750] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.239 ops/ms
# Warmup Iteration   2: 5.549 ops/ms
# Warmup Iteration   3: 6.660 ops/ms
Iteration   1: 7.019 ops/ms
Iteration   2: 6.932 ops/ms
Iteration   3: 6.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.974 ±(99.9%) 0.790 ops/ms [Average]
  (min, avg, max) = (6.932, 6.974, 7.019), stdev = 0.043
  CI (99.9%): [6.184, 7.764] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 12.860 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.688 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.238 ±(99.9%) 0.006 ms/op
Iteration   1: 3.899 ±(99.9%) 0.013 ms/op
Iteration   2: 3.910 ±(99.9%) 0.008 ms/op
Iteration   3: 4.044 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.951 ±(99.9%) 1.476 ms/op [Average]
  (min, avg, max) = (3.899, 3.951, 4.044), stdev = 0.081
  CI (99.9%): [2.475, 5.427] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.029 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.277 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.046 ±(99.9%) 0.008 ms/op
Iteration   1: 3.780 ±(99.9%) 0.008 ms/op
Iteration   2: 3.845 ±(99.9%) 0.004 ms/op
Iteration   3: 3.924 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.850 ±(99.9%) 1.319 ms/op [Average]
  (min, avg, max) = (3.780, 3.850, 3.924), stdev = 0.072
  CI (99.9%): [2.531, 5.168] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 13.370 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.425 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.009 ms/op
Iteration   1: 3.982 ±(99.9%) 0.010 ms/op
Iteration   2: 3.974 ±(99.9%) 0.012 ms/op
Iteration   3: 3.935 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.964 ±(99.9%) 0.462 ms/op [Average]
  (min, avg, max) = (3.935, 3.964, 3.982), stdev = 0.025
  CI (99.9%): [3.501, 4.426] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.832 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 5.593 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.730 ±(99.9%) 0.016 ms/op
Iteration   1: 4.680 ±(99.9%) 0.008 ms/op
Iteration   2: 4.651 ±(99.9%) 0.011 ms/op
Iteration   3: 4.690 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.674 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (4.651, 4.674, 4.690), stdev = 0.020
  CI (99.9%): [4.302, 5.045] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 12.293 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 5.141 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.740 ±(99.9%) 0.024 ms/op
Iteration   1: 4.387 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.356 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   6.423 ms/op
                 createUser·p0.95:   8.086 ms/op
                 createUser·p0.99:   10.879 ms/op
                 createUser·p0.999:  22.220 ms/op
                 createUser·p0.9999: 23.850 ms/op
                 createUser·p1.00:   24.478 ms/op

Iteration   2: 3.995 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.251 ms/op
                 createUser·p0.50:   3.801 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   7.366 ms/op
                 createUser·p0.999:  12.912 ms/op
                 createUser·p0.9999: 25.988 ms/op
                 createUser·p1.00:   27.263 ms/op

Iteration   3: 4.078 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.962 ms/op
                 createUser·p0.50:   3.916 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.218 ms/op
                 createUser·p0.99:   8.077 ms/op
                 createUser·p0.999:  27.493 ms/op
                 createUser·p0.9999: 30.788 ms/op
                 createUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 231297
  mean =      4.147 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 476 
    [ 2.500,  5.000) = 211210 
    [ 5.000,  7.500) = 13167 
    [ 7.500, 10.000) = 4737 
    [10.000, 12.500) = 1042 
    [12.500, 15.000) = 284 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      6.316 ms/op
     p(99.0000) =      9.355 ms/op
     p(99.9000) =     22.535 ms/op
     p(99.9900) =     30.171 ms/op
     p(99.9990) =     31.211 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.175 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.303 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.013 ms/op
Iteration   1: 4.101 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.013 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   5.374 ms/op
                 existUser·p0.95:   6.103 ms/op
                 existUser·p0.99:   8.233 ms/op
                 existUser·p0.999:  15.685 ms/op
                 existUser·p0.9999: 23.724 ms/op
                 existUser·p1.00:   24.281 ms/op

Iteration   2: 3.949 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.841 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   5.145 ms/op
                 existUser·p0.99:   7.438 ms/op
                 existUser·p0.999:  10.911 ms/op
                 existUser·p0.9999: 25.919 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   3: 3.774 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.341 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   7.414 ms/op
                 existUser·p0.999:  23.797 ms/op
                 existUser·p0.9999: 42.382 ms/op
                 existUser·p1.00:   44.958 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243691
  mean =      3.937 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 226383 
    [ 5.000, 10.000) = 16469 
    [10.000, 15.000) = 559 
    [15.000, 20.000) = 49 
    [20.000, 25.000) = 152 
    [25.000, 30.000) = 47 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      7.881 ms/op
     p(99.9000) =     15.968 ms/op
     p(99.9900) =     40.477 ms/op
     p(99.9990) =     44.696 ms/op
     p(99.9999) =     44.958 ms/op
    p(100.0000) =     44.958 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.156 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.884 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.315 ±(99.9%) 0.020 ms/op
Iteration   1: 3.982 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.536 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   8.192 ms/op
                 getUser·p0.999:  20.558 ms/op
                 getUser·p0.9999: 23.887 ms/op
                 getUser·p1.00:   26.903 ms/op

Iteration   2: 4.219 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.091 ms/op
                 getUser·p0.50:   4.018 ms/op
                 getUser·p0.90:   4.981 ms/op
                 getUser·p0.95:   5.538 ms/op
                 getUser·p0.99:   7.725 ms/op
                 getUser·p0.999:  11.583 ms/op
                 getUser·p0.9999: 26.700 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   3: 4.015 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.077 ms/op
                 getUser·p0.50:   3.867 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   7.365 ms/op
                 getUser·p0.999:  11.540 ms/op
                 getUser·p0.9999: 30.510 ms/op
                 getUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235854
  mean =      4.069 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 85 
    [ 2.500,  5.000) = 220856 
    [ 5.000,  7.500) = 11861 
    [ 7.500, 10.000) = 2383 
    [10.000, 12.500) = 369 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     19.005 ms/op
     p(99.9900) =     29.262 ms/op
     p(99.9990) =     31.190 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.933 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 5.893 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 4.910 ±(99.9%) 0.020 ms/op
Iteration   1: 4.615 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.009 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  26.693 ms/op
                 listUser·p0.9999: 37.683 ms/op
                 listUser·p1.00:   38.273 ms/op

Iteration   2: 4.755 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.483 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   6.226 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  21.517 ms/op
                 listUser·p0.9999: 25.905 ms/op
                 listUser·p1.00:   27.984 ms/op

Iteration   3: 4.501 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.630 ms/op
                 listUser·p0.50:   4.334 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   8.298 ms/op
                 listUser·p0.999:  16.433 ms/op
                 listUser·p0.9999: 17.331 ms/op
                 listUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 207665
  mean =      4.621 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 182465 
    [ 5.000,  7.500) = 20531 
    [ 7.500, 10.000) = 3605 
    [10.000, 12.500) = 460 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.483 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     20.982 ms/op
     p(99.9900) =     36.912 ms/op
     p(99.9990) =     37.814 ms/op
     p(99.9999) =     38.273 ms/op
    p(100.0000) =     38.273 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.666 ± 6.339  ops/ms
ClientPb.existUser                       thrpt       3   8.248 ± 5.163  ops/ms
ClientPb.getUser                         thrpt       3   8.082 ± 3.669  ops/ms
ClientPb.listUser                        thrpt       3   6.974 ± 0.790  ops/ms
ClientPb.createUser                       avgt       3   3.951 ± 1.476   ms/op
ClientPb.existUser                        avgt       3   3.850 ± 1.319   ms/op
ClientPb.getUser                          avgt       3   3.964 ± 0.462   ms/op
ClientPb.listUser                         avgt       3   4.674 ± 0.371   ms/op
ClientPb.createUser                     sample  231297   4.147 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.251           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.809           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.316           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.355           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.535           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.171           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.047           ms/op
ClientPb.existUser                      sample  243691   3.937 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.341           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.547           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.448           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.881           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.968           ms/op
ClientPb.existUser:existUser·p0.9999    sample          40.477           ms/op
ClientPb.existUser:existUser·p1.00      sample          44.958           ms/op
ClientPb.getUser                        sample  235854   4.069 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.536           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.686           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.218           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.799           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.005           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.262           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.359           ms/op
ClientPb.listUser                       sample  207665   4.621 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.483           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.087           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.716           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.982           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.912           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.273           ms/op
