# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.045 ops/ms
# Warmup Iteration   2: 2.553 ops/ms
# Warmup Iteration   3: 5.402 ops/ms
Iteration   1: 5.763 ops/ms
Iteration   2: 5.749 ops/ms
Iteration   3: 6.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.882 ±(99.9%) 3.998 ops/ms [Average]
  (min, avg, max) = (5.749, 5.882, 6.135), stdev = 0.219
  CI (99.9%): [1.885, 9.880] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.507 ops/ms
# Warmup Iteration   2: 5.134 ops/ms
# Warmup Iteration   3: 5.802 ops/ms
Iteration   1: 6.109 ops/ms
Iteration   2: 6.042 ops/ms
Iteration   3: 6.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.099 ±(99.9%) 0.948 ops/ms [Average]
  (min, avg, max) = (6.042, 6.099, 6.145), stdev = 0.052
  CI (99.9%): [5.151, 7.046] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.616 ops/ms
# Warmup Iteration   2: 3.919 ops/ms
# Warmup Iteration   3: 5.671 ops/ms
Iteration   1: 5.605 ops/ms
Iteration   2: 5.716 ops/ms
Iteration   3: 5.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.737 ±(99.9%) 2.620 ops/ms [Average]
  (min, avg, max) = (5.605, 5.737, 5.890), stdev = 0.144
  CI (99.9%): [3.117, 8.356] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.409 ops/ms
# Warmup Iteration   2: 3.845 ops/ms
# Warmup Iteration   3: 4.817 ops/ms
Iteration   1: 4.738 ops/ms
Iteration   2: 4.797 ops/ms
Iteration   3: 4.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.810 ±(99.9%) 1.460 ops/ms [Average]
  (min, avg, max) = (4.738, 4.810, 4.896), stdev = 0.080
  CI (99.9%): [3.351, 6.270] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.455 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 7.835 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.749 ±(99.9%) 0.008 ms/op
Iteration   1: 5.660 ±(99.9%) 0.010 ms/op
Iteration   2: 5.507 ±(99.9%) 0.010 ms/op
Iteration   3: 5.611 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.593 ±(99.9%) 1.426 ms/op [Average]
  (min, avg, max) = (5.507, 5.593, 5.660), stdev = 0.078
  CI (99.9%): [4.167, 7.019] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 18.581 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.321 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.440 ±(99.9%) 0.008 ms/op
Iteration   1: 5.346 ±(99.9%) 0.014 ms/op
Iteration   2: 5.305 ±(99.9%) 0.010 ms/op
Iteration   3: 5.223 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.291 ±(99.9%) 1.142 ms/op [Average]
  (min, avg, max) = (5.223, 5.291, 5.346), stdev = 0.063
  CI (99.9%): [4.149, 6.433] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 17.731 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 7.636 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.818 ±(99.9%) 0.006 ms/op
Iteration   1: 5.568 ±(99.9%) 0.009 ms/op
Iteration   2: 5.483 ±(99.9%) 0.011 ms/op
Iteration   3: 5.592 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.548 ±(99.9%) 1.044 ms/op [Average]
  (min, avg, max) = (5.483, 5.548, 5.592), stdev = 0.057
  CI (99.9%): [4.504, 6.592] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 17.728 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 7.874 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.488 ±(99.9%) 0.009 ms/op
Iteration   1: 6.411 ±(99.9%) 0.008 ms/op
Iteration   2: 6.411 ±(99.9%) 0.008 ms/op
Iteration   3: 6.441 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.421 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (6.411, 6.421, 6.441), stdev = 0.017
  CI (99.9%): [6.105, 6.737] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 17.409 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 7.261 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 5.684 ±(99.9%) 0.025 ms/op
Iteration   1: 5.457 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.935 ms/op
                 createUser·p0.50:   5.145 ms/op
                 createUser·p0.90:   6.767 ms/op
                 createUser·p0.95:   7.537 ms/op
                 createUser·p0.99:   9.863 ms/op
                 createUser·p0.999:  20.362 ms/op
                 createUser·p0.9999: 29.266 ms/op
                 createUser·p1.00:   29.753 ms/op

Iteration   2: 5.455 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.372 ms/op
                 createUser·p0.50:   5.177 ms/op
                 createUser·p0.90:   6.627 ms/op
                 createUser·p0.95:   7.168 ms/op
                 createUser·p0.99:   9.519 ms/op
                 createUser·p0.999:  22.839 ms/op
                 createUser·p0.9999: 25.999 ms/op
                 createUser·p1.00:   28.279 ms/op

Iteration   3: 5.414 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.626 ms/op
                 createUser·p0.50:   5.054 ms/op
                 createUser·p0.90:   6.799 ms/op
                 createUser·p0.95:   7.979 ms/op
                 createUser·p0.99:   10.060 ms/op
                 createUser·p0.999:  23.484 ms/op
                 createUser·p0.9999: 29.426 ms/op
                 createUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176375
  mean =      5.442 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 72655 
    [ 5.000,  7.500) = 94399 
    [ 7.500, 10.000) = 7674 
    [10.000, 12.500) = 1023 
    [12.500, 15.000) = 305 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.935 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      6.701 ms/op
     p(95.0000) =      7.586 ms/op
     p(99.0000) =      9.880 ms/op
     p(99.9000) =     22.303 ms/op
     p(99.9900) =     29.262 ms/op
     p(99.9990) =     30.478 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.723 ±(99.9%) 0.267 ms/op
# Warmup Iteration   2: 6.451 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.501 ±(99.9%) 0.020 ms/op
Iteration   1: 5.415 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   5.169 ms/op
                 existUser·p0.90:   6.513 ms/op
                 existUser·p0.95:   7.168 ms/op
                 existUser·p0.99:   9.929 ms/op
                 existUser·p0.999:  18.540 ms/op
                 existUser·p0.9999: 27.626 ms/op
                 existUser·p1.00:   32.375 ms/op

Iteration   2: 5.320 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.490 ms/op
                 existUser·p0.50:   5.071 ms/op
                 existUser·p0.90:   6.439 ms/op
                 existUser·p0.95:   7.184 ms/op
                 existUser·p0.99:   9.322 ms/op
                 existUser·p0.999:  13.795 ms/op
                 existUser·p0.9999: 48.300 ms/op
                 existUser·p1.00:   50.594 ms/op

Iteration   3: 5.568 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.421 ms/op
                 existUser·p0.50:   5.284 ms/op
                 existUser·p0.90:   6.676 ms/op
                 existUser·p0.95:   7.529 ms/op
                 existUser·p0.99:   11.043 ms/op
                 existUser·p0.999:  29.688 ms/op
                 existUser·p0.9999: 40.552 ms/op
                 existUser·p1.00:   41.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 176508
  mean =      5.432 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 69570 
    [ 5.000, 10.000) = 105156 
    [10.000, 15.000) = 1415 
    [15.000, 20.000) = 162 
    [20.000, 25.000) = 28 
    [25.000, 30.000) = 108 
    [30.000, 35.000) = 12 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 9 
    [45.000, 50.000) = 23 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      6.554 ms/op
     p(95.0000) =      7.274 ms/op
     p(99.0000) =     10.027 ms/op
     p(99.9000) =     25.084 ms/op
     p(99.9900) =     47.690 ms/op
     p(99.9990) =     50.393 ms/op
     p(99.9999) =     50.594 ms/op
    p(100.0000) =     50.594 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.509 ±(99.9%) 0.266 ms/op
# Warmup Iteration   2: 6.585 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.634 ±(99.9%) 0.018 ms/op
Iteration   1: 5.511 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.781 ms/op
                 getUser·p0.50:   5.276 ms/op
                 getUser·p0.90:   6.455 ms/op
                 getUser·p0.95:   7.184 ms/op
                 getUser·p0.99:   9.748 ms/op
                 getUser·p0.999:  21.985 ms/op
                 getUser·p0.9999: 28.691 ms/op
                 getUser·p1.00:   29.721 ms/op

Iteration   2: 5.579 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.666 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   6.554 ms/op
                 getUser·p0.95:   7.873 ms/op
                 getUser·p0.99:   11.338 ms/op
                 getUser·p0.999:  25.646 ms/op
                 getUser·p0.9999: 31.795 ms/op
                 getUser·p1.00:   33.358 ms/op

Iteration   3: 5.800 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   3.015 ms/op
                 getUser·p0.50:   5.480 ms/op
                 getUser·p0.90:   7.307 ms/op
                 getUser·p0.95:   7.963 ms/op
                 getUser·p0.99:   10.486 ms/op
                 getUser·p0.999:  25.457 ms/op
                 getUser·p0.9999: 30.372 ms/op
                 getUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 170531
  mean =      5.628 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 49028 
    [ 5.000,  7.500) = 111141 
    [ 7.500, 10.000) = 7805 
    [10.000, 12.500) = 1705 
    [12.500, 15.000) = 402 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.666 ms/op
     p(50.0000) =      5.325 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      7.750 ms/op
     p(99.0000) =     10.781 ms/op
     p(99.9000) =     24.543 ms/op
     p(99.9900) =     30.930 ms/op
     p(99.9990) =     33.034 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.981 ±(99.9%) 0.346 ms/op
# Warmup Iteration   2: 8.283 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.723 ±(99.9%) 0.027 ms/op
Iteration   1: 6.530 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   3.236 ms/op
                 listUser·p0.50:   6.275 ms/op
                 listUser·p0.90:   7.512 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.518 ms/op
                 listUser·p0.999:  27.364 ms/op
                 listUser·p0.9999: 29.958 ms/op
                 listUser·p1.00:   31.621 ms/op

Iteration   2: 6.554 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.011 ms/op
                 listUser·p0.50:   6.210 ms/op
                 listUser·p0.90:   7.602 ms/op
                 listUser·p0.95:   8.729 ms/op
                 listUser·p0.99:   12.589 ms/op
                 listUser·p0.999:  33.948 ms/op
                 listUser·p0.9999: 39.977 ms/op
                 listUser·p1.00:   42.598 ms/op

Iteration   3: 6.476 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.814 ms/op
                 listUser·p0.50:   6.160 ms/op
                 listUser·p0.90:   7.569 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   11.731 ms/op
                 listUser·p0.999:  23.830 ms/op
                 listUser·p0.9999: 34.414 ms/op
                 listUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147109
  mean =      6.520 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2854 
    [ 5.000, 10.000) = 140569 
    [10.000, 15.000) = 3132 
    [15.000, 20.000) = 235 
    [20.000, 25.000) = 83 
    [25.000, 30.000) = 108 
    [30.000, 35.000) = 95 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.814 ms/op
     p(50.0000) =      6.210 ms/op
     p(90.0000) =      7.561 ms/op
     p(95.0000) =      8.569 ms/op
     p(99.0000) =     11.747 ms/op
     p(99.9000) =     29.156 ms/op
     p(99.9900) =     38.545 ms/op
     p(99.9990) =     41.703 ms/op
     p(99.9999) =     42.598 ms/op
    p(100.0000) =     42.598 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.882 ± 3.998  ops/ms
ClientPb.existUser                       thrpt       3   6.099 ± 0.948  ops/ms
ClientPb.getUser                         thrpt       3   5.737 ± 2.620  ops/ms
ClientPb.listUser                        thrpt       3   4.810 ± 1.460  ops/ms
ClientPb.createUser                       avgt       3   5.593 ± 1.426   ms/op
ClientPb.existUser                        avgt       3   5.291 ± 1.142   ms/op
ClientPb.getUser                          avgt       3   5.548 ± 1.044   ms/op
ClientPb.listUser                         avgt       3   6.421 ± 0.316   ms/op
ClientPb.createUser                     sample  176375   5.442 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.935           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.120           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.701           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.586           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.880           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.303           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.262           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.704           ms/op
ClientPb.existUser                      sample  176508   5.432 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.606           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.169           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.554           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.274           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.027           ms/op
ClientPb.existUser:existUser·p0.999     sample          25.084           ms/op
ClientPb.existUser:existUser·p0.9999    sample          47.690           ms/op
ClientPb.existUser:existUser·p1.00      sample          50.594           ms/op
ClientPb.getUser                        sample  170531   5.628 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.666           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.325           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.775           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.750           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.781           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.543           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.930           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.358           ms/op
ClientPb.listUser                       sample  147109   6.520 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.814           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.210           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.561           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.569           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.747           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.156           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.545           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.598           ms/op
