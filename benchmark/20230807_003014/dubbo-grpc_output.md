# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.189 ops/ms
# Warmup Iteration   2: 9.008 ops/ms
# Warmup Iteration   3: 10.134 ops/ms
Iteration   1: 10.693 ops/ms
Iteration   2: 10.866 ops/ms
Iteration   3: 10.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.794 ±(99.9%) 1.642 ops/ms [Average]
  (min, avg, max) = (10.693, 10.794, 10.866), stdev = 0.090
  CI (99.9%): [9.152, 12.435] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.946 ops/ms
# Warmup Iteration   2: 10.614 ops/ms
# Warmup Iteration   3: 11.347 ops/ms
Iteration   1: 11.490 ops/ms
Iteration   2: 11.124 ops/ms
Iteration   3: 11.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.298 ±(99.9%) 3.349 ops/ms [Average]
  (min, avg, max) = (11.124, 11.298, 11.490), stdev = 0.184
  CI (99.9%): [7.949, 14.646] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.757 ops/ms
# Warmup Iteration   2: 10.320 ops/ms
# Warmup Iteration   3: 10.727 ops/ms
Iteration   1: 10.533 ops/ms
Iteration   2: 10.762 ops/ms
Iteration   3: 10.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.655 ±(99.9%) 2.097 ops/ms [Average]
  (min, avg, max) = (10.533, 10.655, 10.762), stdev = 0.115
  CI (99.9%): [8.558, 12.752] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.049 ops/ms
# Warmup Iteration   2: 7.846 ops/ms
# Warmup Iteration   3: 8.106 ops/ms
Iteration   1: 8.154 ops/ms
Iteration   2: 8.042 ops/ms
Iteration   3: 8.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.069 ±(99.9%) 1.379 ops/ms [Average]
  (min, avg, max) = (8.010, 8.069, 8.154), stdev = 0.076
  CI (99.9%): [6.690, 9.448] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.973 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.003 ms/op
Iteration   1: 2.965 ±(99.9%) 0.002 ms/op
Iteration   2: 3.034 ±(99.9%) 0.004 ms/op
Iteration   3: 2.971 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.990 ±(99.9%) 0.702 ms/op [Average]
  (min, avg, max) = (2.965, 2.990, 3.034), stdev = 0.039
  CI (99.9%): [2.288, 3.693] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.876 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.881 ±(99.9%) 0.003 ms/op
Iteration   1: 2.916 ±(99.9%) 0.003 ms/op
Iteration   2: 2.854 ±(99.9%) 0.004 ms/op
Iteration   3: 2.866 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.879 ±(99.9%) 0.596 ms/op [Average]
  (min, avg, max) = (2.854, 2.879, 2.916), stdev = 0.033
  CI (99.9%): [2.283, 3.474] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.050 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.003 ms/op
Iteration   1: 2.964 ±(99.9%) 0.003 ms/op
Iteration   2: 2.976 ±(99.9%) 0.002 ms/op
Iteration   3: 2.976 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.972 ±(99.9%) 0.125 ms/op [Average]
  (min, avg, max) = (2.964, 2.972, 2.976), stdev = 0.007
  CI (99.9%): [2.847, 3.097] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.801 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.007 ms/op
Iteration   1: 3.881 ±(99.9%) 0.035 ms/op
Iteration   2: 3.863 ±(99.9%) 0.015 ms/op
Iteration   3: 3.915 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.886 ±(99.9%) 0.480 ms/op [Average]
  (min, avg, max) = (3.863, 3.886, 3.915), stdev = 0.026
  CI (99.9%): [3.406, 4.367] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.126 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.007 ms/op
Iteration   1: 3.022 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.666 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  8.300 ms/op
                 createUser·p0.9999: 23.658 ms/op
                 createUser·p1.00:   24.019 ms/op

Iteration   2: 3.048 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  8.389 ms/op
                 createUser·p0.9999: 15.131 ms/op
                 createUser·p1.00:   16.253 ms/op

Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.621 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  8.897 ms/op
                 createUser·p0.9999: 18.429 ms/op
                 createUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316629
  mean =      3.031 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26930 
    [ 2.500,  5.000) = 287310 
    [ 5.000,  7.500) = 1853 
    [ 7.500, 10.000) = 316 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =      8.362 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     23.882 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.876 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.927 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.846 ±(99.9%) 0.006 ms/op
Iteration   1: 2.827 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  7.053 ms/op
                 existUser·p0.9999: 11.945 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   2: 2.786 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.574 ms/op
                 existUser·p0.50:   2.793 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  6.825 ms/op
                 existUser·p0.9999: 23.758 ms/op
                 existUser·p1.00:   25.035 ms/op

Iteration   3: 2.919 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.595 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.727 ms/op
                 existUser·p0.999:  10.699 ms/op
                 existUser·p0.9999: 15.140 ms/op
                 existUser·p1.00:   15.499 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337559
  mean =      2.843 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60385 
    [ 2.500,  5.000) = 275275 
    [ 5.000,  7.500) = 1425 
    [ 7.500, 10.000) = 161 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      2.830 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      8.862 ms/op
     p(99.9900) =     15.474 ms/op
     p(99.9990) =     24.859 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.004 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
Iteration   1: 3.041 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.763 ms/op
                 getUser·p0.9999: 13.476 ms/op
                 getUser·p1.00:   16.450 ms/op

Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.138 ms/op
                 getUser·p0.9999: 18.481 ms/op
                 getUser·p1.00:   18.612 ms/op

Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.739 ms/op
                 getUser·p0.9999: 15.709 ms/op
                 getUser·p1.00:   16.237 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319138
  mean =      3.006 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1379 
    [ 1.250,  2.500) = 24147 
    [ 2.500,  3.750) = 277928 
    [ 3.750,  5.000) = 13705 
    [ 5.000,  6.250) = 1054 
    [ 6.250,  7.500) = 578 
    [ 7.500,  8.750) = 183 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.594 ms/op
     p(99.9900) =     17.894 ms/op
     p(99.9990) =     18.573 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.636 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.012 ms/op
Iteration   1: 3.861 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.409 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  12.059 ms/op
                 listUser·p0.9999: 19.684 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   2: 3.890 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  14.360 ms/op
                 listUser·p0.9999: 15.856 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   3: 3.955 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  16.367 ms/op
                 listUser·p0.9999: 19.359 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246150
  mean =      3.902 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3380 
    [ 2.500,  5.000) = 223185 
    [ 5.000,  7.500) = 18112 
    [ 7.500, 10.000) = 978 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     14.544 ms/op
     p(99.9900) =     19.300 ms/op
     p(99.9990) =     21.196 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.794 ± 1.642  ops/ms
ClientGrpc.existUser                       thrpt       3  11.298 ± 3.349  ops/ms
ClientGrpc.getUser                         thrpt       3  10.655 ± 2.097  ops/ms
ClientGrpc.listUser                        thrpt       3   8.069 ± 1.379  ops/ms
ClientGrpc.createUser                       avgt       3   2.990 ± 0.702   ms/op
ClientGrpc.existUser                        avgt       3   2.879 ± 0.596   ms/op
ClientGrpc.getUser                          avgt       3   2.972 ± 0.125   ms/op
ClientGrpc.listUser                         avgt       3   3.886 ± 0.480   ms/op
ClientGrpc.createUser                     sample  316629   3.031 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.621           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.362           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.167           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.019           ms/op
ClientGrpc.existUser                      sample  337559   2.843 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.540           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.830           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.588           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.862           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.474           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.035           ms/op
ClientGrpc.getUser                        sample  319138   3.006 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.743           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.594           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.894           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.612           ms/op
ClientGrpc.listUser                       sample  246150   3.902 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.051           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.521           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.544           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.300           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.381           ms/op
