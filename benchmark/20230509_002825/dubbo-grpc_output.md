# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.242 ops/ms
# Warmup Iteration   2: 8.987 ops/ms
# Warmup Iteration   3: 9.890 ops/ms
Iteration   1: 10.546 ops/ms
Iteration   2: 10.642 ops/ms
Iteration   3: 11.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.735 ±(99.9%) 4.541 ops/ms [Average]
  (min, avg, max) = (10.546, 10.735, 11.017), stdev = 0.249
  CI (99.9%): [6.195, 15.276] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.667 ops/ms
# Warmup Iteration   2: 10.724 ops/ms
# Warmup Iteration   3: 10.860 ops/ms
Iteration   1: 11.112 ops/ms
Iteration   2: 11.147 ops/ms
Iteration   3: 11.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.117 ±(99.9%) 0.518 ops/ms [Average]
  (min, avg, max) = (11.091, 11.117, 11.147), stdev = 0.028
  CI (99.9%): [10.599, 11.634] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.738 ops/ms
# Warmup Iteration   2: 10.408 ops/ms
# Warmup Iteration   3: 10.504 ops/ms
Iteration   1: 10.699 ops/ms
Iteration   2: 10.761 ops/ms
Iteration   3: 10.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.746 ±(99.9%) 0.764 ops/ms [Average]
  (min, avg, max) = (10.699, 10.746, 10.779), stdev = 0.042
  CI (99.9%): [9.982, 11.510] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.783 ops/ms
# Warmup Iteration   2: 7.791 ops/ms
# Warmup Iteration   3: 7.949 ops/ms
Iteration   1: 8.009 ops/ms
Iteration   2: 8.119 ops/ms
Iteration   3: 7.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.038 ±(99.9%) 1.293 ops/ms [Average]
  (min, avg, max) = (7.986, 8.038, 8.119), stdev = 0.071
  CI (99.9%): [6.745, 9.331] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.268 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.003 ms/op
Iteration   1: 2.990 ±(99.9%) 0.010 ms/op
Iteration   2: 3.032 ±(99.9%) 0.003 ms/op
Iteration   3: 3.020 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.014 ±(99.9%) 0.394 ms/op [Average]
  (min, avg, max) = (2.990, 3.014, 3.032), stdev = 0.022
  CI (99.9%): [2.620, 3.408] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.991 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.860 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.003 ms/op
Iteration   1: 2.866 ±(99.9%) 0.002 ms/op
Iteration   2: 2.914 ±(99.9%) 0.001 ms/op
Iteration   3: 2.899 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.893 ±(99.9%) 0.452 ms/op [Average]
  (min, avg, max) = (2.866, 2.893, 2.914), stdev = 0.025
  CI (99.9%): [2.441, 3.345] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.108 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.038 ms/op
Iteration   1: 2.954 ±(99.9%) 0.002 ms/op
Iteration   2: 3.012 ±(99.9%) 0.002 ms/op
Iteration   3: 3.035 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.001 ±(99.9%) 0.759 ms/op [Average]
  (min, avg, max) = (2.954, 3.001, 3.035), stdev = 0.042
  CI (99.9%): [2.241, 3.760] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.593 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.985 ±(99.9%) 0.016 ms/op
Iteration   1: 3.995 ±(99.9%) 0.021 ms/op
Iteration   2: 3.895 ±(99.9%) 0.020 ms/op
Iteration   3: 3.975 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.955 ±(99.9%) 0.972 ms/op [Average]
  (min, avg, max) = (3.895, 3.955, 3.995), stdev = 0.053
  CI (99.9%): [2.983, 4.927] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.052 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
Iteration   1: 2.997 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.524 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  6.861 ms/op
                 createUser·p0.9999: 19.268 ms/op
                 createUser·p1.00:   19.497 ms/op

Iteration   2: 2.932 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   2.912 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   3.486 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  8.715 ms/op
                 createUser·p0.9999: 17.894 ms/op
                 createUser·p1.00:   18.186 ms/op

Iteration   3: 2.973 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  11.043 ms/op
                 createUser·p0.9999: 20.316 ms/op
                 createUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323878
  mean =      2.967 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31276 
    [ 2.500,  5.000) = 291102 
    [ 5.000,  7.500) = 1082 
    [ 7.500, 10.000) = 144 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.423 ms/op
     p(99.9900) =     19.799 ms/op
     p(99.9990) =     20.546 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.075 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.854 ±(99.9%) 0.005 ms/op
Iteration   1: 2.858 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  6.145 ms/op
                 existUser·p0.9999: 11.908 ms/op
                 existUser·p1.00:   12.239 ms/op

Iteration   2: 2.861 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   3.928 ms/op
                 existUser·p0.999:  8.891 ms/op
                 existUser·p0.9999: 13.713 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   3: 2.933 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.622 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.006 ms/op
                 existUser·p0.999:  6.660 ms/op
                 existUser·p0.9999: 15.335 ms/op
                 existUser·p1.00:   16.122 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332738
  mean =      2.883 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1312 
    [ 1.250,  2.500) = 37928 
    [ 2.500,  3.750) = 286732 
    [ 3.750,  5.000) = 5971 
    [ 5.000,  6.250) = 366 
    [ 6.250,  7.500) = 168 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =      4.018 ms/op
     p(99.9000) =      6.812 ms/op
     p(99.9900) =     14.938 ms/op
     p(99.9990) =     15.877 ms/op
     p(99.9999) =     16.122 ms/op
    p(100.0000) =     16.122 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.226 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
Iteration   1: 3.041 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  9.374 ms/op
                 getUser·p0.9999: 13.779 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   2: 2.948 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  7.954 ms/op
                 getUser·p0.9999: 22.413 ms/op
                 getUser·p1.00:   22.643 ms/op

Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  6.207 ms/op
                 getUser·p0.9999: 16.661 ms/op
                 getUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321061
  mean =      2.991 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30165 
    [ 2.500,  5.000) = 289392 
    [ 5.000,  7.500) = 1084 
    [ 7.500, 10.000) = 179 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.297 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     22.603 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.576 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.011 ms/op
Iteration   1: 3.983 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.739 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.835 ms/op
                 listUser·p0.999:  13.207 ms/op
                 listUser·p0.9999: 16.285 ms/op
                 listUser·p1.00:   16.482 ms/op

Iteration   2: 3.934 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  13.789 ms/op
                 listUser·p0.9999: 17.400 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   3: 3.809 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.746 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  15.745 ms/op
                 listUser·p0.9999: 20.218 ms/op
                 listUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245850
  mean =      3.907 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1916 
    [ 2.500,  5.000) = 225382 
    [ 5.000,  7.500) = 17294 
    [ 7.500, 10.000) = 745 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     13.814 ms/op
     p(99.9900) =     19.852 ms/op
     p(99.9990) =     20.304 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.735 ± 4.541  ops/ms
ClientGrpc.existUser                       thrpt       3  11.117 ± 0.518  ops/ms
ClientGrpc.getUser                         thrpt       3  10.746 ± 0.764  ops/ms
ClientGrpc.listUser                        thrpt       3   8.038 ± 1.293  ops/ms
ClientGrpc.createUser                       avgt       3   3.014 ± 0.394   ms/op
ClientGrpc.existUser                        avgt       3   2.893 ± 0.452   ms/op
ClientGrpc.getUser                          avgt       3   3.001 ± 0.759   ms/op
ClientGrpc.listUser                         avgt       3   3.955 ± 0.972   ms/op
ClientGrpc.createUser                     sample  323878   2.967 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.524           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.941           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.416           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.423           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.799           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.266           ms/op
ClientGrpc.existUser                      sample  332738   2.883 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.618           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.310           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.018           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.812           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.938           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.122           ms/op
ClientGrpc.getUser                        sample  321061   2.991 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.767           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.297           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.561           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.643           ms/op
ClientGrpc.listUser                       sample  245850   3.907 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.746           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.719           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.814           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.852           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.742           ms/op
