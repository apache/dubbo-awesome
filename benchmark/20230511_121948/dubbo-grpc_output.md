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
# Warmup Iteration   1: 4.548 ops/ms
# Warmup Iteration   2: 9.252 ops/ms
# Warmup Iteration   3: 9.931 ops/ms
Iteration   1: 10.302 ops/ms
Iteration   2: 10.519 ops/ms
Iteration   3: 10.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.495 ±(99.9%) 3.326 ops/ms [Average]
  (min, avg, max) = (10.302, 10.495, 10.664), stdev = 0.182
  CI (99.9%): [7.169, 13.821] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.834 ops/ms
# Warmup Iteration   2: 10.692 ops/ms
# Warmup Iteration   3: 11.231 ops/ms
Iteration   1: 11.383 ops/ms
Iteration   2: 11.131 ops/ms
Iteration   3: 11.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.173 ±(99.9%) 3.501 ops/ms [Average]
  (min, avg, max) = (11.006, 11.173, 11.383), stdev = 0.192
  CI (99.9%): [7.672, 14.675] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.070 ops/ms
# Warmup Iteration   2: 10.095 ops/ms
# Warmup Iteration   3: 10.595 ops/ms
Iteration   1: 10.406 ops/ms
Iteration   2: 10.652 ops/ms
Iteration   3: 10.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.539 ±(99.9%) 2.263 ops/ms [Average]
  (min, avg, max) = (10.406, 10.539, 10.652), stdev = 0.124
  CI (99.9%): [8.276, 12.802] (assumes normal distribution)


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
# Warmup Iteration   1: 5.468 ops/ms
# Warmup Iteration   2: 7.660 ops/ms
# Warmup Iteration   3: 7.881 ops/ms
Iteration   1: 7.963 ops/ms
Iteration   2: 8.043 ops/ms
Iteration   3: 8.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.015 ±(99.9%) 0.817 ops/ms [Average]
  (min, avg, max) = (7.963, 8.015, 8.043), stdev = 0.045
  CI (99.9%): [7.197, 8.832] (assumes normal distribution)


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
# Warmup Iteration   1: 4.443 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.004 ms/op
Iteration   1: 3.043 ±(99.9%) 0.002 ms/op
Iteration   2: 3.047 ±(99.9%) 0.002 ms/op
Iteration   3: 3.029 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.039 ±(99.9%) 0.170 ms/op [Average]
  (min, avg, max) = (3.029, 3.039, 3.047), stdev = 0.009
  CI (99.9%): [2.869, 3.210] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.062 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.003 ms/op
Iteration   1: 2.862 ±(99.9%) 0.003 ms/op
Iteration   2: 2.922 ±(99.9%) 0.002 ms/op
Iteration   3: 2.894 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.893 ±(99.9%) 0.544 ms/op [Average]
  (min, avg, max) = (2.862, 2.893, 2.922), stdev = 0.030
  CI (99.9%): [2.348, 3.437] (assumes normal distribution)


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
# Warmup Iteration   1: 4.188 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.003 ms/op
Iteration   1: 3.027 ±(99.9%) 0.004 ms/op
Iteration   2: 3.046 ±(99.9%) 0.003 ms/op
Iteration   3: 3.048 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.040 ±(99.9%) 0.208 ms/op [Average]
  (min, avg, max) = (3.027, 3.040, 3.048), stdev = 0.011
  CI (99.9%): [2.832, 3.248] (assumes normal distribution)


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
# Warmup Iteration   1: 5.526 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.020 ms/op
Iteration   1: 4.057 ±(99.9%) 0.011 ms/op
Iteration   2: 4.033 ±(99.9%) 0.014 ms/op
Iteration   3: 3.965 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.018 ±(99.9%) 0.866 ms/op [Average]
  (min, avg, max) = (3.965, 4.018, 4.057), stdev = 0.047
  CI (99.9%): [3.152, 4.884] (assumes normal distribution)


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.007 ms/op
Iteration   1: 3.029 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  8.527 ms/op
                 createUser·p0.9999: 16.588 ms/op
                 createUser·p1.00:   17.367 ms/op

Iteration   2: 3.028 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  8.751 ms/op
                 createUser·p0.9999: 22.067 ms/op
                 createUser·p1.00:   22.872 ms/op

Iteration   3: 3.047 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.439 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  12.059 ms/op
                 createUser·p0.9999: 23.412 ms/op
                 createUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316436
  mean =      3.034 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26805 
    [ 2.500,  5.000) = 287903 
    [ 5.000,  7.500) = 1231 
    [ 7.500, 10.000) = 150 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.439 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =     11.076 ms/op
     p(99.9900) =     22.228 ms/op
     p(99.9990) =     23.784 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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
# Warmup Iteration   1: 4.065 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.872 ±(99.9%) 0.005 ms/op
Iteration   1: 2.861 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.119 ms/op
                 existUser·p0.9999: 12.665 ms/op
                 existUser·p1.00:   12.861 ms/op

Iteration   2: 2.878 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  6.828 ms/op
                 existUser·p0.9999: 14.400 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   3: 2.880 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.006 ms/op
                 existUser·p0.999:  6.569 ms/op
                 existUser·p0.9999: 16.118 ms/op
                 existUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334152
  mean =      2.873 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2504 
    [ 1.250,  2.500) = 43270 
    [ 2.500,  3.750) = 281184 
    [ 3.750,  5.000) = 6220 
    [ 5.000,  6.250) = 557 
    [ 6.250,  7.500) = 226 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.555 ms/op
     p(99.0000) =      4.084 ms/op
     p(99.9000) =      6.488 ms/op
     p(99.9900) =     14.529 ms/op
     p(99.9990) =     16.422 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 4.250 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.006 ms/op
Iteration   1: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  8.189 ms/op
                 getUser·p0.9999: 16.859 ms/op
                 getUser·p1.00:   17.203 ms/op

Iteration   2: 3.078 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.590 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.346 ms/op
                 getUser·p0.9999: 18.252 ms/op
                 getUser·p1.00:   18.514 ms/op

Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.627 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  6.504 ms/op
                 getUser·p0.9999: 15.489 ms/op
                 getUser·p1.00:   15.811 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315622
  mean =      3.041 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 870 
    [ 1.250,  2.500) = 18568 
    [ 2.500,  3.750) = 280582 
    [ 3.750,  5.000) = 14232 
    [ 5.000,  6.250) = 834 
    [ 6.250,  7.500) = 227 
    [ 7.500,  8.750) = 80 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.368 ms/op
     p(99.9900) =     17.185 ms/op
     p(99.9990) =     18.443 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 4.946 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.239 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.061 ±(99.9%) 0.012 ms/op
Iteration   1: 4.055 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.966 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.931 ms/op
                 listUser·p0.999:  12.583 ms/op
                 listUser·p0.9999: 15.278 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   2: 4.043 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  17.724 ms/op
                 listUser·p0.9999: 26.777 ms/op
                 listUser·p1.00:   27.263 ms/op

Iteration   3: 4.089 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  15.417 ms/op
                 listUser·p0.9999: 17.638 ms/op
                 listUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236313
  mean =      4.062 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2937 
    [ 2.500,  5.000) = 206876 
    [ 5.000,  7.500) = 25096 
    [ 7.500, 10.000) = 958 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     25.833 ms/op
     p(99.9990) =     27.174 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.495 ± 3.326  ops/ms
ClientGrpc.existUser                       thrpt       3  11.173 ± 3.501  ops/ms
ClientGrpc.getUser                         thrpt       3  10.539 ± 2.263  ops/ms
ClientGrpc.listUser                        thrpt       3   8.015 ± 0.817  ops/ms
ClientGrpc.createUser                       avgt       3   3.039 ± 0.170   ms/op
ClientGrpc.existUser                        avgt       3   2.893 ± 0.544   ms/op
ClientGrpc.getUser                          avgt       3   3.040 ± 0.208   ms/op
ClientGrpc.listUser                         avgt       3   4.018 ± 0.866   ms/op
ClientGrpc.createUser                     sample  316436   3.034 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.439           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.637           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.076           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.228           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.921           ms/op
ClientGrpc.existUser                      sample  334152   2.873 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.606           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.084           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.488           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.529           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.072           ms/op
ClientGrpc.getUser                        sample  315622   3.041 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.590           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.368           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.185           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.514           ms/op
ClientGrpc.listUser                       sample  236313   4.062 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.966           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.942           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.833           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.263           ms/op
