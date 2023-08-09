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
# Warmup Iteration   1: 4.099 ops/ms
# Warmup Iteration   2: 9.088 ops/ms
# Warmup Iteration   3: 9.824 ops/ms
Iteration   1: 10.079 ops/ms
Iteration   2: 10.276 ops/ms
Iteration   3: 10.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.335 ±(99.9%) 5.284 ops/ms [Average]
  (min, avg, max) = (10.079, 10.335, 10.649), stdev = 0.290
  CI (99.9%): [5.050, 15.619] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.136 ops/ms
# Warmup Iteration   2: 10.497 ops/ms
# Warmup Iteration   3: 10.973 ops/ms
Iteration   1: 10.734 ops/ms
Iteration   2: 10.784 ops/ms
Iteration   3: 10.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.825 ±(99.9%) 2.125 ops/ms [Average]
  (min, avg, max) = (10.734, 10.825, 10.956), stdev = 0.116
  CI (99.9%): [8.700, 12.950] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.041 ops/ms
# Warmup Iteration   2: 9.639 ops/ms
# Warmup Iteration   3: 10.376 ops/ms
Iteration   1: 10.228 ops/ms
Iteration   2: 10.419 ops/ms
Iteration   3: 10.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.386 ±(99.9%) 2.633 ops/ms [Average]
  (min, avg, max) = (10.228, 10.386, 10.511), stdev = 0.144
  CI (99.9%): [7.754, 13.019] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.597 ops/ms
# Warmup Iteration   2: 7.447 ops/ms
# Warmup Iteration   3: 7.849 ops/ms
Iteration   1: 7.958 ops/ms
Iteration   2: 7.890 ops/ms
Iteration   3: 7.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.933 ±(99.9%) 0.678 ops/ms [Average]
  (min, avg, max) = (7.890, 7.933, 7.958), stdev = 0.037
  CI (99.9%): [7.255, 8.611] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.369 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.003 ms/op
Iteration   1: 3.057 ±(99.9%) 0.006 ms/op
Iteration   2: 3.112 ±(99.9%) 0.002 ms/op
Iteration   3: 3.049 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.073 ±(99.9%) 0.629 ms/op [Average]
  (min, avg, max) = (3.049, 3.073, 3.112), stdev = 0.035
  CI (99.9%): [2.443, 3.702] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.200 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.896 ±(99.9%) 0.003 ms/op
Iteration   1: 2.918 ±(99.9%) 0.003 ms/op
Iteration   2: 2.786 ±(99.9%) 0.003 ms/op
Iteration   3: 2.928 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.878 ±(99.9%) 1.447 ms/op [Average]
  (min, avg, max) = (2.786, 2.878, 2.928), stdev = 0.079
  CI (99.9%): [1.430, 4.325] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.322 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.003 ms/op
Iteration   1: 3.102 ±(99.9%) 0.004 ms/op
Iteration   2: 3.100 ±(99.9%) 0.003 ms/op
Iteration   3: 3.032 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.078 ±(99.9%) 0.727 ms/op [Average]
  (min, avg, max) = (3.032, 3.078, 3.102), stdev = 0.040
  CI (99.9%): [2.351, 3.805] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.891 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.044 ms/op
Iteration   1: 4.004 ±(99.9%) 0.022 ms/op
Iteration   2: 3.866 ±(99.9%) 0.010 ms/op
Iteration   3: 4.081 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.984 ±(99.9%) 1.993 ms/op [Average]
  (min, avg, max) = (3.866, 3.984, 4.081), stdev = 0.109
  CI (99.9%): [1.991, 5.977] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.544 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.276 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.006 ms/op
Iteration   1: 3.137 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.989 ms/op
                 createUser·p0.999:  8.734 ms/op
                 createUser·p0.9999: 20.926 ms/op
                 createUser·p1.00:   21.168 ms/op

Iteration   2: 3.104 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  10.370 ms/op
                 createUser·p0.9999: 14.577 ms/op
                 createUser·p1.00:   14.762 ms/op

Iteration   3: 3.101 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  10.676 ms/op
                 createUser·p0.9999: 20.011 ms/op
                 createUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308114
  mean =      3.114 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13051 
    [ 2.500,  5.000) = 292751 
    [ 5.000,  7.500) = 1518 
    [ 7.500, 10.000) = 484 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =     10.011 ms/op
     p(99.9900) =     20.546 ms/op
     p(99.9990) =     21.103 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.256 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.908 ±(99.9%) 0.007 ms/op
Iteration   1: 2.926 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  9.307 ms/op
                 existUser·p0.9999: 17.695 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   2: 3.120 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  57.672 ms/op
                 existUser·p0.9999: 72.975 ms/op
                 existUser·p1.00:   83.100 ms/op

Iteration   3: 3.452 ±(99.9%) 0.053 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   28.836 ms/op
                 existUser·p0.999:  66.511 ms/op
                 existUser·p0.9999: 85.029 ms/op
                 existUser·p1.00:   106.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 304719
  mean =      3.151 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 302676 
    [ 12.500,  25.000) = 595 
    [ 25.000,  37.500) = 530 
    [ 37.500,  50.000) = 400 
    [ 50.000,  62.500) = 312 
    [ 62.500,  75.000) = 156 
    [ 75.000,  87.500) = 47 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 3 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      5.757 ms/op
     p(99.9000) =     57.362 ms/op
     p(99.9900) =     80.354 ms/op
     p(99.9990) =     99.520 ms/op
     p(99.9999) =    106.037 ms/op
    p(100.0000) =    106.037 ms/op


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
# Warmup Iteration   1: 5.266 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 3.245 ±(99.9%) 0.030 ms/op
Iteration   1: 3.252 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   8.602 ms/op
                 getUser·p0.999:  38.580 ms/op
                 getUser·p0.9999: 63.526 ms/op
                 getUser·p1.00:   70.386 ms/op

Iteration   2: 3.309 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   8.306 ms/op
                 getUser·p0.999:  49.453 ms/op
                 getUser·p0.9999: 57.999 ms/op
                 getUser·p1.00:   60.097 ms/op

Iteration   3: 3.263 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   7.571 ms/op
                 getUser·p0.999:  48.550 ms/op
                 getUser·p0.9999: 61.836 ms/op
                 getUser·p1.00:   67.043 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 293205
  mean =      3.274 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 287325 
    [ 5.000, 10.000) = 3388 
    [10.000, 15.000) = 656 
    [15.000, 20.000) = 377 
    [20.000, 25.000) = 246 
    [25.000, 30.000) = 233 
    [30.000, 35.000) = 195 
    [35.000, 40.000) = 254 
    [40.000, 45.000) = 159 
    [45.000, 50.000) = 156 
    [50.000, 55.000) = 112 
    [55.000, 60.000) = 70 
    [60.000, 65.000) = 24 
    [65.000, 70.000) = 6 
    [70.000, 75.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      8.135 ms/op
     p(99.9000) =     47.448 ms/op
     p(99.9900) =     60.490 ms/op
     p(99.9990) =     70.255 ms/op
     p(99.9999) =     70.386 ms/op
    p(100.0000) =     70.386 ms/op


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
# Warmup Iteration   1: 6.180 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.633 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 4.357 ±(99.9%) 0.041 ms/op
Iteration   1: 4.446 ±(99.9%) 0.050 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.800 ms/op
                 listUser·p0.95:   6.455 ms/op
                 listUser·p0.99:   13.517 ms/op
                 listUser·p0.999:  67.507 ms/op
                 listUser·p0.9999: 138.417 ms/op
                 listUser·p1.00:   152.044 ms/op

Iteration   2: 4.428 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.759 ms/op
                 listUser·p0.95:   6.463 ms/op
                 listUser·p0.99:   16.754 ms/op
                 listUser·p0.999:  58.458 ms/op
                 listUser·p0.9999: 113.176 ms/op
                 listUser·p1.00:   118.489 ms/op

Iteration   3: 4.472 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   5.710 ms/op
                 listUser·p0.95:   6.423 ms/op
                 listUser·p0.99:   11.268 ms/op
                 listUser·p0.999:  58.720 ms/op
                 listUser·p0.9999: 88.297 ms/op
                 listUser·p1.00:   91.357 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 215870
  mean =      4.448 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 213524 
    [ 12.500,  25.000) = 1030 
    [ 25.000,  37.500) = 589 
    [ 37.500,  50.000) = 362 
    [ 50.000,  62.500) = 157 
    [ 62.500,  75.000) = 111 
    [ 75.000,  87.500) = 51 
    [ 87.500, 100.000) = 17 
    [100.000, 112.500) = 8 
    [112.500, 125.000) = 8 
    [125.000, 137.500) = 6 
    [137.500, 150.000) = 5 
    [150.000, 162.500) = 2 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      5.759 ms/op
     p(95.0000) =      6.447 ms/op
     p(99.0000) =     13.812 ms/op
     p(99.9000) =     61.686 ms/op
     p(99.9900) =    112.839 ms/op
     p(99.9990) =    149.210 ms/op
     p(99.9999) =    152.044 ms/op
    p(100.0000) =    152.044 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt    Score   Error   Units
ClientGrpc.createUser                      thrpt       3   10.335 ± 5.284  ops/ms
ClientGrpc.existUser                       thrpt       3   10.825 ± 2.125  ops/ms
ClientGrpc.getUser                         thrpt       3   10.386 ± 2.633  ops/ms
ClientGrpc.listUser                        thrpt       3    7.933 ± 0.678  ops/ms
ClientGrpc.createUser                       avgt       3    3.073 ± 0.629   ms/op
ClientGrpc.existUser                        avgt       3    2.878 ± 1.447   ms/op
ClientGrpc.getUser                          avgt       3    3.078 ± 0.727   ms/op
ClientGrpc.listUser                         avgt       3    3.984 ± 1.993   ms/op
ClientGrpc.createUser                     sample  308114    3.114 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample            0.727           ms/op
ClientGrpc.createUser:createUser·p0.50    sample            3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample            3.617           ms/op
ClientGrpc.createUser:createUser·p0.95    sample            3.863           ms/op
ClientGrpc.createUser:createUser·p0.99    sample            4.678           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           10.011           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample           20.546           ms/op
ClientGrpc.createUser:createUser·p1.00    sample           21.168           ms/op
ClientGrpc.existUser                      sample  304719    3.151 ± 0.019   ms/op
ClientGrpc.existUser:existUser·p0.00      sample            0.651           ms/op
ClientGrpc.existUser:existUser·p0.50      sample            2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample            3.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample            3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample            5.757           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           57.362           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample           80.354           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          106.037           ms/op
ClientGrpc.getUser                        sample  293205    3.274 ± 0.016   ms/op
ClientGrpc.getUser:getUser·p0.00          sample            0.740           ms/op
ClientGrpc.getUser:getUser·p0.50          sample            3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample            3.650           ms/op
ClientGrpc.getUser:getUser·p0.95          sample            4.035           ms/op
ClientGrpc.getUser:getUser·p0.99          sample            8.135           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           47.448           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample           60.490           ms/op
ClientGrpc.getUser:getUser·p1.00          sample           70.386           ms/op
ClientGrpc.listUser                       sample  215870    4.448 ± 0.027   ms/op
ClientGrpc.listUser:listUser·p0.00        sample            0.860           ms/op
ClientGrpc.listUser:listUser·p0.50        sample            3.903           ms/op
ClientGrpc.listUser:listUser·p0.90        sample            5.759           ms/op
ClientGrpc.listUser:listUser·p0.95        sample            6.447           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           13.812           ms/op
ClientGrpc.listUser:listUser·p0.999       sample           61.686           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          112.839           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          152.044           ms/op
