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
# Warmup Iteration   1: 4.488 ops/ms
# Warmup Iteration   2: 8.929 ops/ms
# Warmup Iteration   3: 10.498 ops/ms
Iteration   1: 10.400 ops/ms
Iteration   2: 10.531 ops/ms
Iteration   3: 10.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.545 ±(99.9%) 2.775 ops/ms [Average]
  (min, avg, max) = (10.400, 10.545, 10.703), stdev = 0.152
  CI (99.9%): [7.769, 13.320] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.820 ops/ms
# Warmup Iteration   2: 11.008 ops/ms
# Warmup Iteration   3: 11.084 ops/ms
Iteration   1: 11.134 ops/ms
Iteration   2: 11.330 ops/ms
Iteration   3: 11.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.292 ±(99.9%) 2.618 ops/ms [Average]
  (min, avg, max) = (11.134, 11.292, 11.413), stdev = 0.144
  CI (99.9%): [8.674, 13.910] (assumes normal distribution)


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
# Warmup Iteration   1: 6.814 ops/ms
# Warmup Iteration   2: 10.295 ops/ms
# Warmup Iteration   3: 10.497 ops/ms
Iteration   1: 10.531 ops/ms
Iteration   2: 10.480 ops/ms
Iteration   3: 10.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.559 ±(99.9%) 1.743 ops/ms [Average]
  (min, avg, max) = (10.480, 10.559, 10.665), stdev = 0.096
  CI (99.9%): [8.816, 12.302] (assumes normal distribution)


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
# Warmup Iteration   1: 5.446 ops/ms
# Warmup Iteration   2: 7.772 ops/ms
# Warmup Iteration   3: 7.979 ops/ms
Iteration   1: 8.207 ops/ms
Iteration   2: 8.005 ops/ms
Iteration   3: 8.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.167 ±(99.9%) 2.674 ops/ms [Average]
  (min, avg, max) = (8.005, 8.167, 8.289), stdev = 0.147
  CI (99.9%): [5.493, 10.841] (assumes normal distribution)


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
# Warmup Iteration   1: 4.208 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.968 ±(99.9%) 0.004 ms/op
Iteration   1: 3.003 ±(99.9%) 0.008 ms/op
Iteration   2: 2.986 ±(99.9%) 0.003 ms/op
Iteration   3: 3.026 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.005 ±(99.9%) 0.364 ms/op [Average]
  (min, avg, max) = (2.986, 3.005, 3.026), stdev = 0.020
  CI (99.9%): [2.641, 3.369] (assumes normal distribution)


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.974 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.815 ±(99.9%) 0.002 ms/op
Iteration   1: 2.892 ±(99.9%) 0.002 ms/op
Iteration   2: 2.892 ±(99.9%) 0.003 ms/op
Iteration   3: 2.854 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.879 ±(99.9%) 0.394 ms/op [Average]
  (min, avg, max) = (2.854, 2.879, 2.892), stdev = 0.022
  CI (99.9%): [2.485, 3.273] (assumes normal distribution)


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
# Warmup Iteration   1: 4.093 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.004 ms/op
Iteration   1: 3.001 ±(99.9%) 0.003 ms/op
Iteration   2: 2.981 ±(99.9%) 0.002 ms/op
Iteration   3: 2.952 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.978 ±(99.9%) 0.453 ms/op [Average]
  (min, avg, max) = (2.952, 2.978, 3.001), stdev = 0.025
  CI (99.9%): [2.525, 3.431] (assumes normal distribution)


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
# Warmup Iteration   1: 5.528 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.016 ms/op
Iteration   1: 3.719 ±(99.9%) 0.016 ms/op
Iteration   2: 3.963 ±(99.9%) 0.019 ms/op
Iteration   3: 3.911 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.864 ±(99.9%) 2.341 ms/op [Average]
  (min, avg, max) = (3.719, 3.864, 3.963), stdev = 0.128
  CI (99.9%): [1.523, 6.206] (assumes normal distribution)


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
# Warmup Iteration   1: 4.110 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  8.063 ms/op
                 createUser·p0.9999: 19.956 ms/op
                 createUser·p1.00:   20.283 ms/op

Iteration   2: 3.035 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  9.267 ms/op
                 createUser·p0.9999: 20.347 ms/op
                 createUser·p1.00:   21.561 ms/op

Iteration   3: 3.061 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  10.977 ms/op
                 createUser·p0.9999: 22.529 ms/op
                 createUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316592
  mean =      3.034 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26319 
    [ 2.500,  5.000) = 288758 
    [ 5.000,  7.500) = 953 
    [ 7.500, 10.000) = 228 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =     10.240 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     22.796 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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
# Warmup Iteration   1: 4.001 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.005 ms/op
Iteration   1: 2.890 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.583 ms/op
                 existUser·p0.9999: 12.402 ms/op
                 existUser·p1.00:   12.665 ms/op

Iteration   2: 2.965 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.002 ms/op
                 existUser·p0.999:  6.357 ms/op
                 existUser·p0.9999: 18.953 ms/op
                 existUser·p1.00:   19.759 ms/op

Iteration   3: 2.812 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  10.306 ms/op
                 existUser·p0.9999: 16.322 ms/op
                 existUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332626
  mean =      2.888 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3494 
    [ 1.250,  2.500) = 43750 
    [ 2.500,  3.750) = 276858 
    [ 3.750,  5.000) = 7466 
    [ 5.000,  6.250) = 425 
    [ 6.250,  7.500) = 196 
    [ 7.500,  8.750) = 209 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.190 ms/op
     p(99.9000) =      7.832 ms/op
     p(99.9900) =     16.645 ms/op
     p(99.9990) =     19.705 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 4.335 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
Iteration   1: 3.006 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.363 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.135 ms/op
                 getUser·p0.9999: 12.146 ms/op
                 getUser·p1.00:   12.370 ms/op

Iteration   2: 2.977 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.639 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.403 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.412 ms/op
                 getUser·p0.9999: 12.829 ms/op
                 getUser·p1.00:   13.074 ms/op

Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  6.455 ms/op
                 getUser·p0.9999: 25.264 ms/op
                 getUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320055
  mean =      2.998 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17778 
    [ 2.500,  5.000) = 300882 
    [ 5.000,  7.500) = 1146 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      6.930 ms/op
     p(99.9900) =     23.667 ms/op
     p(99.9990) =     25.520 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 5.235 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.010 ms/op
Iteration   1: 3.932 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  14.424 ms/op
                 listUser·p0.9999: 20.508 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   2: 3.777 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  14.617 ms/op
                 listUser·p0.9999: 18.711 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   3: 3.887 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  15.019 ms/op
                 listUser·p0.9999: 17.531 ms/op
                 listUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248505
  mean =      3.864 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3762 
    [ 2.500,  5.000) = 225306 
    [ 5.000,  7.500) = 18236 
    [ 7.500, 10.000) = 759 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     14.705 ms/op
     p(99.9900) =     19.164 ms/op
     p(99.9990) =     21.514 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.545 ± 2.775  ops/ms
ClientGrpc.existUser                       thrpt       3  11.292 ± 2.618  ops/ms
ClientGrpc.getUser                         thrpt       3  10.559 ± 1.743  ops/ms
ClientGrpc.listUser                        thrpt       3   8.167 ± 2.674  ops/ms
ClientGrpc.createUser                       avgt       3   3.005 ± 0.364   ms/op
ClientGrpc.existUser                        avgt       3   2.879 ± 0.394   ms/op
ClientGrpc.getUser                          avgt       3   2.978 ± 0.453   ms/op
ClientGrpc.listUser                         avgt       3   3.864 ± 2.341   ms/op
ClientGrpc.createUser                     sample  316592   3.034 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.695           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.240           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.987           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.938           ms/op
ClientGrpc.existUser                      sample  332626   2.888 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.667           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.832           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.645           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.759           ms/op
ClientGrpc.getUser                        sample  320055   2.998 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.639           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.404           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.930           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.667           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.821           ms/op
ClientGrpc.listUser                       sample  248505   3.864 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.882           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.751           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.816           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.705           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.164           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.561           ms/op
