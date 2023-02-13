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
# Warmup Iteration   1: 1.952 ops/ms
# Warmup Iteration   2: 4.692 ops/ms
# Warmup Iteration   3: 6.598 ops/ms
Iteration   1: 6.498 ops/ms
Iteration   2: 6.535 ops/ms
Iteration   3: 6.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.572 ±(99.9%) 1.770 ops/ms [Average]
  (min, avg, max) = (6.498, 6.572, 6.682), stdev = 0.097
  CI (99.9%): [4.801, 8.342] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.272 ops/ms
# Warmup Iteration   2: 6.593 ops/ms
# Warmup Iteration   3: 6.911 ops/ms
Iteration   1: 6.973 ops/ms
Iteration   2: 6.833 ops/ms
Iteration   3: 7.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.977 ±(99.9%) 2.669 ops/ms [Average]
  (min, avg, max) = (6.833, 6.977, 7.125), stdev = 0.146
  CI (99.9%): [4.308, 9.646] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.947 ops/ms
# Warmup Iteration   2: 5.851 ops/ms
# Warmup Iteration   3: 6.494 ops/ms
Iteration   1: 6.631 ops/ms
Iteration   2: 6.514 ops/ms
Iteration   3: 6.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.588 ±(99.9%) 1.175 ops/ms [Average]
  (min, avg, max) = (6.514, 6.588, 6.631), stdev = 0.064
  CI (99.9%): [5.413, 7.762] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.611 ops/ms
# Warmup Iteration   2: 4.616 ops/ms
# Warmup Iteration   3: 5.251 ops/ms
Iteration   1: 5.130 ops/ms
Iteration   2: 5.296 ops/ms
Iteration   3: 5.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.212 ±(99.9%) 1.518 ops/ms [Average]
  (min, avg, max) = (5.130, 5.212, 5.296), stdev = 0.083
  CI (99.9%): [3.694, 6.730] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.401 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.100 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.835 ±(99.9%) 0.005 ms/op
Iteration   1: 5.118 ±(99.9%) 0.005 ms/op
Iteration   2: 5.027 ±(99.9%) 0.005 ms/op
Iteration   3: 5.196 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  5.114 ±(99.9%) 1.546 ms/op [Average]
  (min, avg, max) = (5.027, 5.114, 5.196), stdev = 0.085
  CI (99.9%): [3.567, 6.660] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.906 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.800 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.690 ±(99.9%) 0.003 ms/op
Iteration   1: 4.485 ±(99.9%) 0.003 ms/op
Iteration   2: 4.411 ±(99.9%) 0.003 ms/op
Iteration   3: 4.438 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.445 ±(99.9%) 0.683 ms/op [Average]
  (min, avg, max) = (4.411, 4.445, 4.485), stdev = 0.037
  CI (99.9%): [3.762, 5.128] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.406 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.353 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.862 ±(99.9%) 0.003 ms/op
Iteration   1: 4.579 ±(99.9%) 0.003 ms/op
Iteration   2: 4.545 ±(99.9%) 0.003 ms/op
Iteration   3: 4.591 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.572 ±(99.9%) 0.437 ms/op [Average]
  (min, avg, max) = (4.545, 4.572, 4.591), stdev = 0.024
  CI (99.9%): [4.135, 5.009] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.088 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 6.454 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.752 ±(99.9%) 0.016 ms/op
Iteration   1: 5.774 ±(99.9%) 0.014 ms/op
Iteration   2: 5.876 ±(99.9%) 0.011 ms/op
Iteration   3: 5.778 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.809 ±(99.9%) 1.055 ms/op [Average]
  (min, avg, max) = (5.774, 5.809, 5.876), stdev = 0.058
  CI (99.9%): [4.754, 6.864] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 6.744 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 5.009 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.886 ±(99.9%) 0.016 ms/op
Iteration   1: 4.788 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   4.702 ms/op
                 createUser·p0.90:   6.005 ms/op
                 createUser·p0.95:   6.390 ms/op
                 createUser·p0.99:   7.856 ms/op
                 createUser·p0.999:  12.598 ms/op
                 createUser·p0.9999: 18.054 ms/op
                 createUser·p1.00:   18.874 ms/op

Iteration   2: 4.763 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   4.686 ms/op
                 createUser·p0.90:   5.915 ms/op
                 createUser·p0.95:   6.272 ms/op
                 createUser·p0.99:   7.447 ms/op
                 createUser·p0.999:  10.498 ms/op
                 createUser·p0.9999: 19.169 ms/op
                 createUser·p1.00:   20.218 ms/op

Iteration   3: 4.842 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   4.735 ms/op
                 createUser·p0.90:   6.111 ms/op
                 createUser·p0.95:   6.595 ms/op
                 createUser·p0.99:   8.241 ms/op
                 createUser·p0.999:  16.400 ms/op
                 createUser·p0.9999: 21.955 ms/op
                 createUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 200095
  mean =      4.797 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2698 
    [ 2.500,  5.000) = 120612 
    [ 5.000,  7.500) = 74092 
    [ 7.500, 10.000) = 2175 
    [10.000, 12.500) = 291 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      6.013 ms/op
     p(95.0000) =      6.414 ms/op
     p(99.0000) =      7.897 ms/op
     p(99.9000) =     13.260 ms/op
     p(99.9900) =     21.201 ms/op
     p(99.9990) =     22.151 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.231 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.691 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.869 ±(99.9%) 0.020 ms/op
Iteration   1: 4.634 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.194 ms/op
                 existUser·p0.50:   4.563 ms/op
                 existUser·p0.90:   5.865 ms/op
                 existUser·p0.95:   6.324 ms/op
                 existUser·p0.99:   8.086 ms/op
                 existUser·p0.999:  10.993 ms/op
                 existUser·p0.9999: 17.603 ms/op
                 existUser·p1.00:   18.219 ms/op

Iteration   2: 4.518 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.567 ms/op
                 existUser·p0.50:   4.440 ms/op
                 existUser·p0.90:   5.808 ms/op
                 existUser·p0.95:   6.193 ms/op
                 existUser·p0.99:   7.840 ms/op
                 existUser·p0.999:  11.309 ms/op
                 existUser·p0.9999: 28.664 ms/op
                 existUser·p1.00:   32.276 ms/op

Iteration   3: 4.578 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   4.522 ms/op
                 existUser·p0.90:   5.808 ms/op
                 existUser·p0.95:   6.259 ms/op
                 existUser·p0.99:   8.061 ms/op
                 existUser·p0.999:  15.254 ms/op
                 existUser·p0.9999: 21.179 ms/op
                 existUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 209705
  mean =      4.576 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7422 
    [ 2.500,  5.000) = 136605 
    [ 5.000,  7.500) = 62683 
    [ 7.500, 10.000) = 2463 
    [10.000, 12.500) = 356 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.825 ms/op
     p(95.0000) =      6.259 ms/op
     p(99.0000) =      7.987 ms/op
     p(99.9000) =     11.795 ms/op
     p(99.9900) =     28.214 ms/op
     p(99.9990) =     31.768 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.863 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 5.173 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.699 ±(99.9%) 0.013 ms/op
Iteration   1: 4.756 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.235 ms/op
                 getUser·p0.50:   4.628 ms/op
                 getUser·p0.90:   5.980 ms/op
                 getUser·p0.95:   6.504 ms/op
                 getUser·p0.99:   8.220 ms/op
                 getUser·p0.999:  12.017 ms/op
                 getUser·p0.9999: 16.631 ms/op
                 getUser·p1.00:   16.941 ms/op

Iteration   2: 4.866 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   4.735 ms/op
                 getUser·p0.90:   6.193 ms/op
                 getUser·p0.95:   6.709 ms/op
                 getUser·p0.99:   8.634 ms/op
                 getUser·p0.999:  13.405 ms/op
                 getUser·p0.9999: 19.781 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   3: 4.868 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   4.784 ms/op
                 getUser·p0.90:   6.119 ms/op
                 getUser·p0.95:   6.562 ms/op
                 getUser·p0.99:   8.487 ms/op
                 getUser·p0.999:  16.082 ms/op
                 getUser·p0.9999: 21.833 ms/op
                 getUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 198752
  mean =      4.829 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3156 
    [ 2.500,  5.000) = 118627 
    [ 5.000,  7.500) = 72952 
    [ 7.500, 10.000) = 3275 
    [10.000, 12.500) = 459 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      6.103 ms/op
     p(95.0000) =      6.597 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     14.340 ms/op
     p(99.9900) =     20.283 ms/op
     p(99.9990) =     22.415 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 8.564 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 6.542 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 6.195 ±(99.9%) 0.026 ms/op
Iteration   1: 6.029 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.733 ms/op
                 listUser·p0.50:   5.685 ms/op
                 listUser·p0.90:   8.110 ms/op
                 listUser·p0.95:   9.060 ms/op
                 listUser·p0.99:   11.452 ms/op
                 listUser·p0.999:  16.695 ms/op
                 listUser·p0.9999: 20.963 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   2: 6.171 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   5.775 ms/op
                 listUser·p0.90:   8.307 ms/op
                 listUser·p0.95:   9.306 ms/op
                 listUser·p0.99:   11.895 ms/op
                 listUser·p0.999:  19.175 ms/op
                 listUser·p0.9999: 27.486 ms/op
                 listUser·p1.00:   28.049 ms/op

Iteration   3: 5.803 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   5.464 ms/op
                 listUser·p0.90:   7.889 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   11.387 ms/op
                 listUser·p0.999:  22.570 ms/op
                 listUser·p0.9999: 29.147 ms/op
                 listUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 160037
  mean =      5.997 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 114 
    [ 2.500,  5.000) = 41285 
    [ 5.000,  7.500) = 95130 
    [ 7.500, 10.000) = 19215 
    [10.000, 12.500) = 3375 
    [12.500, 15.000) = 519 
    [15.000, 17.500) = 168 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      5.644 ms/op
     p(90.0000) =      8.094 ms/op
     p(95.0000) =      9.077 ms/op
     p(99.0000) =     11.583 ms/op
     p(99.9000) =     18.906 ms/op
     p(99.9900) =     27.689 ms/op
     p(99.9990) =     29.583 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.572 ± 1.770  ops/ms
ClientGrpc.existUser                       thrpt       3   6.977 ± 2.669  ops/ms
ClientGrpc.getUser                         thrpt       3   6.588 ± 1.175  ops/ms
ClientGrpc.listUser                        thrpt       3   5.212 ± 1.518  ops/ms
ClientGrpc.createUser                       avgt       3   5.114 ± 1.546   ms/op
ClientGrpc.existUser                        avgt       3   4.445 ± 0.683   ms/op
ClientGrpc.getUser                          avgt       3   4.572 ± 0.437   ms/op
ClientGrpc.listUser                         avgt       3   5.809 ± 1.055   ms/op
ClientGrpc.createUser                     sample  200095   4.797 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.139           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.013           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.414           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.897           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.260           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.201           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.249           ms/op
ClientGrpc.existUser                      sample  209705   4.576 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.567           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.825           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.259           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.987           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.795           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.214           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.276           ms/op
ClientGrpc.getUser                        sample  198752   4.829 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.923           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.710           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.103           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.597           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.438           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.340           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.283           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.544           ms/op
ClientGrpc.listUser                       sample  160037   5.997 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.405           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.094           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.077           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.583           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.906           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.689           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.721           ms/op
