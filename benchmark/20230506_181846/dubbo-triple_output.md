# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.997 ops/ms
# Warmup Iteration   2: 5.444 ops/ms
# Warmup Iteration   3: 8.448 ops/ms
Iteration   1: 9.121 ops/ms
Iteration   2: 9.170 ops/ms
Iteration   3: 8.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.088 ±(99.9%) 1.859 ops/ms [Average]
  (min, avg, max) = (8.974, 9.088, 9.170), stdev = 0.102
  CI (99.9%): [7.229, 10.948] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.207 ops/ms
# Warmup Iteration   2: 8.967 ops/ms
# Warmup Iteration   3: 9.318 ops/ms
Iteration   1: 9.820 ops/ms
Iteration   2: 9.740 ops/ms
Iteration   3: 9.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.710 ±(99.9%) 2.331 ops/ms [Average]
  (min, avg, max) = (9.570, 9.710, 9.820), stdev = 0.128
  CI (99.9%): [7.379, 12.041] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.838 ops/ms
# Warmup Iteration   2: 8.390 ops/ms
# Warmup Iteration   3: 8.696 ops/ms
Iteration   1: 9.548 ops/ms
Iteration   2: 9.257 ops/ms
Iteration   3: 8.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.261 ±(99.9%) 5.193 ops/ms [Average]
  (min, avg, max) = (8.979, 9.261, 9.548), stdev = 0.285
  CI (99.9%): [4.068, 14.454] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.160 ops/ms
# Warmup Iteration   2: 7.043 ops/ms
# Warmup Iteration   3: 7.511 ops/ms
Iteration   1: 7.972 ops/ms
Iteration   2: 7.735 ops/ms
Iteration   3: 8.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.930 ±(99.9%) 3.254 ops/ms [Average]
  (min, avg, max) = (7.735, 7.930, 8.085), stdev = 0.178
  CI (99.9%): [4.676, 11.185] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.405 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.594 ±(99.9%) 0.003 ms/op
Iteration   1: 3.429 ±(99.9%) 0.015 ms/op
Iteration   2: 3.378 ±(99.9%) 0.012 ms/op
Iteration   3: 3.503 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.437 ±(99.9%) 1.147 ms/op [Average]
  (min, avg, max) = (3.378, 3.437, 3.503), stdev = 0.063
  CI (99.9%): [2.289, 4.584] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.767 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.005 ms/op
Iteration   1: 3.389 ±(99.9%) 0.004 ms/op
Iteration   2: 3.367 ±(99.9%) 0.006 ms/op
Iteration   3: 3.353 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.370 ±(99.9%) 0.337 ms/op [Average]
  (min, avg, max) = (3.353, 3.370, 3.389), stdev = 0.018
  CI (99.9%): [3.032, 3.707] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 10.452 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.913 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.499 ±(99.9%) 0.004 ms/op
Iteration   1: 3.520 ±(99.9%) 0.007 ms/op
Iteration   2: 3.581 ±(99.9%) 0.005 ms/op
Iteration   3: 3.450 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.517 ±(99.9%) 1.194 ms/op [Average]
  (min, avg, max) = (3.450, 3.517, 3.581), stdev = 0.065
  CI (99.9%): [2.323, 4.711] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 12.285 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.470 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.105 ±(99.9%) 0.009 ms/op
Iteration   1: 4.090 ±(99.9%) 0.005 ms/op
Iteration   2: 3.844 ±(99.9%) 0.017 ms/op
Iteration   3: 3.924 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.953 ±(99.9%) 2.286 ms/op [Average]
  (min, avg, max) = (3.844, 3.953, 4.090), stdev = 0.125
  CI (99.9%): [1.667, 6.239] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.184 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.467 ±(99.9%) 0.011 ms/op
Iteration   1: 3.798 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   6.070 ms/op
                 createUser·p0.99:   7.660 ms/op
                 createUser·p0.999:  20.742 ms/op
                 createUser·p0.9999: 29.852 ms/op
                 createUser·p1.00:   30.704 ms/op

Iteration   2: 3.560 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  21.826 ms/op
                 createUser·p0.9999: 24.642 ms/op
                 createUser·p1.00:   25.297 ms/op

Iteration   3: 3.476 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  19.174 ms/op
                 createUser·p0.9999: 29.675 ms/op
                 createUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 265998
  mean =      3.606 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5015 
    [ 2.500,  5.000) = 248704 
    [ 5.000,  7.500) = 10435 
    [ 7.500, 10.000) = 1435 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     20.480 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     30.573 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.833 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.655 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.009 ms/op
Iteration   1: 3.376 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  19.942 ms/op
                 existUser·p0.9999: 24.530 ms/op
                 existUser·p1.00:   25.919 ms/op

Iteration   2: 3.372 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.348 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   6.529 ms/op
                 existUser·p0.999:  22.577 ms/op
                 existUser·p0.9999: 32.114 ms/op
                 existUser·p1.00:   33.751 ms/op

Iteration   3: 3.346 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  11.330 ms/op
                 existUser·p0.9999: 24.361 ms/op
                 existUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285187
  mean =      3.364 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5448 
    [ 2.500,  5.000) = 274507 
    [ 5.000,  7.500) = 3961 
    [ 7.500, 10.000) = 753 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 160 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     15.221 ms/op
     p(99.9900) =     30.440 ms/op
     p(99.9990) =     32.609 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.872 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.012 ms/op
Iteration   1: 3.577 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   7.168 ms/op
                 getUser·p0.999:  21.332 ms/op
                 getUser·p0.9999: 26.153 ms/op
                 getUser·p1.00:   26.739 ms/op

Iteration   2: 3.441 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.626 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  20.908 ms/op
                 getUser·p0.9999: 29.655 ms/op
                 getUser·p1.00:   34.144 ms/op

Iteration   3: 3.436 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.393 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  18.055 ms/op
                 getUser·p0.9999: 27.820 ms/op
                 getUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275332
  mean =      3.483 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7715 
    [ 2.500,  5.000) = 259389 
    [ 5.000,  7.500) = 6878 
    [ 7.500, 10.000) = 831 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     18.929 ms/op
     p(99.9900) =     28.410 ms/op
     p(99.9990) =     29.958 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.801 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.456 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.275 ±(99.9%) 0.013 ms/op
Iteration   1: 4.123 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.651 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  21.019 ms/op
                 listUser·p0.9999: 30.531 ms/op
                 listUser·p1.00:   43.385 ms/op

Iteration   2: 4.138 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.544 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.937 ms/op
                 listUser·p0.999:  17.762 ms/op
                 listUser·p0.9999: 21.758 ms/op
                 listUser·p1.00:   22.970 ms/op

Iteration   3: 3.943 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  15.466 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235968
  mean =      4.066 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 226364 
    [ 5.000, 10.000) = 8704 
    [10.000, 15.000) = 476 
    [15.000, 20.000) = 305 
    [20.000, 25.000) = 87 
    [25.000, 30.000) = 17 
    [30.000, 35.000) = 11 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.651 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.741 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     29.433 ms/op
     p(99.9990) =     42.724 ms/op
     p(99.9999) =     43.385 ms/op
    p(100.0000) =     43.385 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.088 ± 1.859  ops/ms
ClientPb.existUser                       thrpt       3   9.710 ± 2.331  ops/ms
ClientPb.getUser                         thrpt       3   9.261 ± 5.193  ops/ms
ClientPb.listUser                        thrpt       3   7.930 ± 3.254  ops/ms
ClientPb.createUser                       avgt       3   3.437 ± 1.147   ms/op
ClientPb.existUser                        avgt       3   3.370 ± 0.337   ms/op
ClientPb.getUser                          avgt       3   3.517 ± 1.194   ms/op
ClientPb.listUser                         avgt       3   3.953 ± 2.286   ms/op
ClientPb.createUser                     sample  265998   3.606 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.114           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.396           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.227           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.850           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.168           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.480           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.426           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.704           ms/op
ClientPb.existUser                      sample  285187   3.364 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.920           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.985           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.767           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.221           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.440           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.751           ms/op
ClientPb.getUser                        sample  275332   3.483 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.305           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.709           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.929           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.410           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.144           ms/op
ClientPb.listUser                       sample  235968   4.066 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.651           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.809           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.741           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.859           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.433           ms/op
ClientPb.listUser:listUser·p1.00        sample          43.385           ms/op
