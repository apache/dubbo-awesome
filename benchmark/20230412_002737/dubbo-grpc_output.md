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
# Warmup Iteration   1: 4.106 ops/ms
# Warmup Iteration   2: 8.895 ops/ms
# Warmup Iteration   3: 10.299 ops/ms
Iteration   1: 10.310 ops/ms
Iteration   2: 10.655 ops/ms
Iteration   3: 10.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.509 ±(99.9%) 3.258 ops/ms [Average]
  (min, avg, max) = (10.310, 10.509, 10.655), stdev = 0.179
  CI (99.9%): [7.251, 13.766] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.533 ops/ms
# Warmup Iteration   2: 10.758 ops/ms
# Warmup Iteration   3: 11.022 ops/ms
Iteration   1: 11.140 ops/ms
Iteration   2: 11.095 ops/ms
Iteration   3: 11.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.180 ±(99.9%) 2.036 ops/ms [Average]
  (min, avg, max) = (11.095, 11.180, 11.307), stdev = 0.112
  CI (99.9%): [9.144, 13.217] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.176 ops/ms
# Warmup Iteration   2: 10.120 ops/ms
# Warmup Iteration   3: 10.679 ops/ms
Iteration   1: 10.557 ops/ms
Iteration   2: 10.579 ops/ms
Iteration   3: 10.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.566 ±(99.9%) 0.218 ops/ms [Average]
  (min, avg, max) = (10.557, 10.566, 10.579), stdev = 0.012
  CI (99.9%): [10.347, 10.784] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.135 ops/ms
# Warmup Iteration   2: 7.703 ops/ms
# Warmup Iteration   3: 8.134 ops/ms
Iteration   1: 8.382 ops/ms
Iteration   2: 8.239 ops/ms
Iteration   3: 8.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.357 ±(99.9%) 1.975 ops/ms [Average]
  (min, avg, max) = (8.239, 8.357, 8.451), stdev = 0.108
  CI (99.9%): [6.383, 10.332] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.416 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.002 ms/op
Iteration   1: 3.038 ±(99.9%) 0.002 ms/op
Iteration   2: 2.964 ±(99.9%) 0.004 ms/op
Iteration   3: 3.036 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.013 ±(99.9%) 0.775 ms/op [Average]
  (min, avg, max) = (2.964, 3.013, 3.038), stdev = 0.043
  CI (99.9%): [2.237, 3.788] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.131 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.020 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.005 ms/op
Iteration   1: 2.901 ±(99.9%) 0.002 ms/op
Iteration   2: 2.829 ±(99.9%) 0.002 ms/op
Iteration   3: 2.909 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.880 ±(99.9%) 0.802 ms/op [Average]
  (min, avg, max) = (2.829, 2.880, 2.909), stdev = 0.044
  CI (99.9%): [2.078, 3.682] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.489 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.004 ms/op
Iteration   1: 2.975 ±(99.9%) 0.002 ms/op
Iteration   2: 2.923 ±(99.9%) 0.003 ms/op
Iteration   3: 2.972 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.957 ±(99.9%) 0.531 ms/op [Average]
  (min, avg, max) = (2.923, 2.957, 2.975), stdev = 0.029
  CI (99.9%): [2.425, 3.488] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.845 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.010 ms/op
Iteration   1: 3.909 ±(99.9%) 0.012 ms/op
Iteration   2: 3.847 ±(99.9%) 0.016 ms/op
Iteration   3: 3.862 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.873 ±(99.9%) 0.587 ms/op [Average]
  (min, avg, max) = (3.847, 3.873, 3.909), stdev = 0.032
  CI (99.9%): [3.285, 4.460] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.484 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.006 ms/op
Iteration   1: 3.065 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  6.818 ms/op
                 createUser·p0.9999: 13.608 ms/op
                 createUser·p1.00:   14.057 ms/op

Iteration   2: 3.011 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  6.824 ms/op
                 createUser·p0.9999: 13.654 ms/op
                 createUser·p1.00:   14.090 ms/op

Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  8.096 ms/op
                 createUser·p0.9999: 17.259 ms/op
                 createUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313626
  mean =      3.060 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 322 
    [ 1.250,  2.500) = 24391 
    [ 2.500,  3.750) = 269978 
    [ 3.750,  5.000) = 17550 
    [ 5.000,  6.250) = 808 
    [ 6.250,  7.500) = 328 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.021 ms/op
     p(99.9900) =     16.777 ms/op
     p(99.9990) =     17.915 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.040 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.974 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.864 ±(99.9%) 0.006 ms/op
Iteration   1: 2.885 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   3.944 ms/op
                 existUser·p0.999:  6.055 ms/op
                 existUser·p0.9999: 13.532 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   2: 2.843 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.133 ms/op
                 existUser·p0.95:   3.224 ms/op
                 existUser·p0.99:   3.772 ms/op
                 existUser·p0.999:  6.435 ms/op
                 existUser·p0.9999: 21.389 ms/op
                 existUser·p1.00:   21.627 ms/op

Iteration   3: 2.901 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.749 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.087 ms/op
                 existUser·p0.999:  10.682 ms/op
                 existUser·p0.9999: 15.875 ms/op
                 existUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333536
  mean =      2.876 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39963 
    [ 2.500,  5.000) = 292685 
    [ 5.000,  7.500) = 458 
    [ 7.500, 10.000) = 171 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.269 ms/op
     p(95.0000) =      3.457 ms/op
     p(99.0000) =      3.940 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     16.759 ms/op
     p(99.9990) =     21.561 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.239 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.006 ms/op
Iteration   1: 2.983 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.111 ms/op
                 getUser·p0.9999: 13.607 ms/op
                 getUser·p1.00:   13.894 ms/op

Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.624 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  10.663 ms/op
                 getUser·p0.9999: 13.864 ms/op
                 getUser·p1.00:   15.565 ms/op

Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.739 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.508 ms/op
                 getUser·p0.9999: 17.947 ms/op
                 getUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319973
  mean =      3.002 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 544 
    [ 1.250,  2.500) = 23370 
    [ 2.500,  3.750) = 282654 
    [ 3.750,  5.000) = 11711 
    [ 5.000,  6.250) = 893 
    [ 6.250,  7.500) = 382 
    [ 7.500,  8.750) = 159 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      7.922 ms/op
     p(99.9900) =     16.269 ms/op
     p(99.9990) =     18.049 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.401 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.195 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.010 ms/op
Iteration   1: 3.853 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.456 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  14.304 ms/op
                 listUser·p0.9999: 22.852 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   2: 3.902 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 19.482 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   3: 3.821 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.815 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  15.761 ms/op
                 listUser·p0.9999: 24.597 ms/op
                 listUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248785
  mean =      3.858 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3102 
    [ 2.500,  5.000) = 226811 
    [ 5.000,  7.500) = 17776 
    [ 7.500, 10.000) = 654 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     16.368 ms/op
     p(99.9900) =     22.814 ms/op
     p(99.9990) =     24.888 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.509 ± 3.258  ops/ms
ClientGrpc.existUser                       thrpt       3  11.180 ± 2.036  ops/ms
ClientGrpc.getUser                         thrpt       3  10.566 ± 0.218  ops/ms
ClientGrpc.listUser                        thrpt       3   8.357 ± 1.975  ops/ms
ClientGrpc.createUser                       avgt       3   3.013 ± 0.775   ms/op
ClientGrpc.existUser                        avgt       3   2.880 ± 0.802   ms/op
ClientGrpc.getUser                          avgt       3   2.957 ± 0.531   ms/op
ClientGrpc.listUser                         avgt       3   3.873 ± 0.587   ms/op
ClientGrpc.createUser                     sample  313626   3.060 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.771           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.021           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.777           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.121           ms/op
ClientGrpc.existUser                      sample  333536   2.876 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.749           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.269           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           3.940           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.044           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.759           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.627           ms/op
ClientGrpc.getUser                        sample  319973   3.002 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.624           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.922           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.269           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.153           ms/op
ClientGrpc.listUser                       sample  248785   3.858 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.815           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.702           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.660           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.368           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.814           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.002           ms/op
