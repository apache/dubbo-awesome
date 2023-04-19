# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.647 ops/ms
# Warmup Iteration   2: 4.137 ops/ms
# Warmup Iteration   3: 5.544 ops/ms
Iteration   1: 5.913 ops/ms
Iteration   2: 5.827 ops/ms
Iteration   3: 6.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.002 ±(99.9%) 4.231 ops/ms [Average]
  (min, avg, max) = (5.827, 6.002, 6.265), stdev = 0.232
  CI (99.9%): [1.771, 10.233] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 3.563 ops/ms
# Warmup Iteration   2: 5.750 ops/ms
# Warmup Iteration   3: 6.550 ops/ms
Iteration   1: 6.546 ops/ms
Iteration   2: 6.676 ops/ms
Iteration   3: 6.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.599 ±(99.9%) 1.242 ops/ms [Average]
  (min, avg, max) = (6.546, 6.599, 6.676), stdev = 0.068
  CI (99.9%): [5.358, 7.841] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 3.131 ops/ms
# Warmup Iteration   2: 5.310 ops/ms
# Warmup Iteration   3: 5.798 ops/ms
Iteration   1: 6.283 ops/ms
Iteration   2: 6.363 ops/ms
Iteration   3: 6.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.344 ±(99.9%) 0.982 ops/ms [Average]
  (min, avg, max) = (6.283, 6.344, 6.386), stdev = 0.054
  CI (99.9%): [5.362, 7.326] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.025 ops/ms
# Warmup Iteration   2: 4.693 ops/ms
# Warmup Iteration   3: 4.972 ops/ms
Iteration   1: 5.199 ops/ms
Iteration   2: 5.018 ops/ms
Iteration   3: 5.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.129 ±(99.9%) 1.766 ops/ms [Average]
  (min, avg, max) = (5.018, 5.129, 5.199), stdev = 0.097
  CI (99.9%): [3.363, 6.894] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.713 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.709 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.415 ±(99.9%) 0.003 ms/op
Iteration   1: 5.233 ±(99.9%) 0.004 ms/op
Iteration   2: 5.202 ±(99.9%) 0.003 ms/op
Iteration   3: 5.163 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  5.199 ±(99.9%) 0.638 ms/op [Average]
  (min, avg, max) = (5.163, 5.199, 5.233), stdev = 0.035
  CI (99.9%): [4.561, 5.838] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.527 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.803 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.018 ±(99.9%) 0.007 ms/op
Iteration   1: 4.970 ±(99.9%) 0.003 ms/op
Iteration   2: 4.997 ±(99.9%) 0.002 ms/op
Iteration   3: 4.967 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.978 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (4.967, 4.978, 4.997), stdev = 0.017
  CI (99.9%): [4.673, 5.283] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.397 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.868 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.450 ±(99.9%) 0.009 ms/op
Iteration   1: 5.411 ±(99.9%) 0.012 ms/op
Iteration   2: 5.368 ±(99.9%) 0.004 ms/op
Iteration   3: 5.284 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  5.354 ±(99.9%) 1.179 ms/op [Average]
  (min, avg, max) = (5.284, 5.354, 5.411), stdev = 0.065
  CI (99.9%): [4.175, 6.533] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.114 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 6.502 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 6.722 ±(99.9%) 0.012 ms/op
Iteration   1: 6.429 ±(99.9%) 0.015 ms/op
Iteration   2: 6.429 ±(99.9%) 0.018 ms/op
Iteration   3: 6.228 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.362 ±(99.9%) 2.115 ms/op [Average]
  (min, avg, max) = (6.228, 6.362, 6.429), stdev = 0.116
  CI (99.9%): [4.246, 8.477] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 7.728 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 5.779 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.526 ±(99.9%) 0.023 ms/op
Iteration   1: 4.866 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.931 ms/op
                 createUser·p0.50:   4.588 ms/op
                 createUser·p0.90:   6.185 ms/op
                 createUser·p0.95:   7.119 ms/op
                 createUser·p0.99:   10.060 ms/op
                 createUser·p0.999:  19.800 ms/op
                 createUser·p0.9999: 23.719 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   2: 4.683 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.282 ms/op
                 createUser·p0.50:   4.473 ms/op
                 createUser·p0.90:   5.710 ms/op
                 createUser·p0.95:   6.447 ms/op
                 createUser·p0.99:   9.781 ms/op
                 createUser·p0.999:  15.041 ms/op
                 createUser·p0.9999: 22.812 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   3: 4.688 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   4.497 ms/op
                 createUser·p0.90:   5.693 ms/op
                 createUser·p0.95:   6.283 ms/op
                 createUser·p0.99:   9.257 ms/op
                 createUser·p0.999:  17.524 ms/op
                 createUser·p0.9999: 27.477 ms/op
                 createUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 202286
  mean =      4.744 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1369 
    [ 2.500,  5.000) = 144112 
    [ 5.000,  7.500) = 50747 
    [ 7.500, 10.000) = 4309 
    [10.000, 12.500) = 1189 
    [12.500, 15.000) = 282 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.865 ms/op
     p(95.0000) =      6.636 ms/op
     p(99.0000) =      9.699 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     25.773 ms/op
     p(99.9990) =     27.851 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.366 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.769 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.336 ±(99.9%) 0.013 ms/op
Iteration   1: 3.987 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.895 ms/op
                 existUser·p0.90:   4.743 ms/op
                 existUser·p0.95:   5.095 ms/op
                 existUser·p0.99:   6.742 ms/op
                 existUser·p0.999:  11.826 ms/op
                 existUser·p0.9999: 15.155 ms/op
                 existUser·p1.00:   15.532 ms/op

Iteration   2: 3.783 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.505 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  12.556 ms/op
                 existUser·p0.9999: 19.862 ms/op
                 existUser·p1.00:   22.282 ms/op

Iteration   3: 4.201 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   4.112 ms/op
                 existUser·p0.90:   5.153 ms/op
                 existUser·p0.95:   5.571 ms/op
                 existUser·p0.99:   7.610 ms/op
                 existUser·p0.999:  13.786 ms/op
                 existUser·p0.9999: 19.043 ms/op
                 existUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 240983
  mean =      3.983 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5621 
    [ 2.500,  5.000) = 218311 
    [ 5.000,  7.500) = 15523 
    [ 7.500, 10.000) = 1073 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.505 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     12.681 ms/op
     p(99.9900) =     18.547 ms/op
     p(99.9990) =     21.016 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 6.492 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.951 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.012 ms/op
Iteration   1: 3.718 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.029 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  8.602 ms/op
                 getUser·p0.9999: 19.005 ms/op
                 getUser·p1.00:   20.447 ms/op

Iteration   2: 4.820 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.501 ms/op
                 getUser·p0.50:   4.473 ms/op
                 getUser·p0.90:   6.152 ms/op
                 getUser·p0.95:   7.807 ms/op
                 getUser·p0.99:   11.092 ms/op
                 getUser·p0.999:  14.926 ms/op
                 getUser·p0.9999: 25.833 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   3: 5.106 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   1.122 ms/op
                 getUser·p0.50:   4.571 ms/op
                 getUser·p0.90:   7.487 ms/op
                 getUser·p0.95:   9.388 ms/op
                 getUser·p0.99:   12.517 ms/op
                 getUser·p0.999:  17.605 ms/op
                 getUser·p0.9999: 27.975 ms/op
                 getUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 214967
  mean =      4.462 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3267 
    [ 2.500,  5.000) = 169206 
    [ 5.000,  7.500) = 32321 
    [ 7.500, 10.000) = 6518 
    [10.000, 12.500) = 2710 
    [12.500, 15.000) = 663 
    [15.000, 17.500) = 164 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      4.121 ms/op
     p(90.0000) =      5.743 ms/op
     p(95.0000) =      7.332 ms/op
     p(99.0000) =     10.994 ms/op
     p(99.9000) =     15.680 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     29.852 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.181 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 6.911 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.625 ±(99.9%) 0.042 ms/op
Iteration   1: 6.683 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   5.677 ms/op
                 listUser·p0.90:   10.371 ms/op
                 listUser·p0.95:   12.845 ms/op
                 listUser·p0.99:   18.224 ms/op
                 listUser·p0.999:  26.972 ms/op
                 listUser·p0.9999: 36.086 ms/op
                 listUser·p1.00:   36.569 ms/op

Iteration   2: 6.436 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   5.464 ms/op
                 listUser·p0.90:   9.798 ms/op
                 listUser·p0.95:   11.796 ms/op
                 listUser·p0.99:   16.999 ms/op
                 listUser·p0.999:  23.498 ms/op
                 listUser·p0.9999: 42.809 ms/op
                 listUser·p1.00:   44.892 ms/op

Iteration   3: 6.618 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.415 ms/op
                 listUser·p0.50:   5.603 ms/op
                 listUser·p0.90:   10.109 ms/op
                 listUser·p0.95:   12.632 ms/op
                 listUser·p0.99:   18.219 ms/op
                 listUser·p0.999:  27.996 ms/op
                 listUser·p0.9999: 32.937 ms/op
                 listUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 145921
  mean =      6.577 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 42353 
    [ 5.000, 10.000) = 88520 
    [10.000, 15.000) = 11597 
    [15.000, 20.000) = 2662 
    [20.000, 25.000) = 568 
    [25.000, 30.000) = 147 
    [30.000, 35.000) = 51 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      5.587 ms/op
     p(90.0000) =     10.093 ms/op
     p(95.0000) =     12.403 ms/op
     p(99.0000) =     17.851 ms/op
     p(99.9000) =     26.938 ms/op
     p(99.9900) =     37.531 ms/op
     p(99.9990) =     44.350 ms/op
     p(99.9999) =     44.892 ms/op
    p(100.0000) =     44.892 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.002 ± 4.231  ops/ms
ClientGrpc.existUser                       thrpt       3   6.599 ± 1.242  ops/ms
ClientGrpc.getUser                         thrpt       3   6.344 ± 0.982  ops/ms
ClientGrpc.listUser                        thrpt       3   5.129 ± 1.766  ops/ms
ClientGrpc.createUser                       avgt       3   5.199 ± 0.638   ms/op
ClientGrpc.existUser                        avgt       3   4.978 ± 0.305   ms/op
ClientGrpc.getUser                          avgt       3   5.354 ± 1.179   ms/op
ClientGrpc.listUser                         avgt       3   6.362 ± 2.115   ms/op
ClientGrpc.createUser                     sample  202286   4.744 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.931           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.865           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.636           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.699           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          16.876           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.773           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.918           ms/op
ClientGrpc.existUser                      sample  240983   3.983 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.505           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.887           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.809           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.202           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.742           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.681           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.547           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.282           ms/op
ClientGrpc.getUser                        sample  214967   4.462 ± 0.011   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.029           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.743           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           7.332           ms/op
ClientGrpc.getUser:getUser·p0.99          sample          10.994           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.680           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.214           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.310           ms/op
ClientGrpc.listUser                       sample  145921   6.577 ± 0.025   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.415           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.90        sample          10.093           ms/op
ClientGrpc.listUser:listUser·p0.95        sample          12.403           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          17.851           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          26.938           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          37.531           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          44.892           ms/op
