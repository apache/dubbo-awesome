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
# Warmup Iteration   1: 4.189 ops/ms
# Warmup Iteration   2: 8.736 ops/ms
# Warmup Iteration   3: 9.935 ops/ms
Iteration   1: 10.313 ops/ms
Iteration   2: 10.436 ops/ms
Iteration   3: 10.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.393 ±(99.9%) 1.268 ops/ms [Average]
  (min, avg, max) = (10.313, 10.393, 10.436), stdev = 0.070
  CI (99.9%): [9.125, 11.661] (assumes normal distribution)


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
# Warmup Iteration   1: 7.294 ops/ms
# Warmup Iteration   2: 10.680 ops/ms
# Warmup Iteration   3: 11.062 ops/ms
Iteration   1: 10.975 ops/ms
Iteration   2: 11.289 ops/ms
Iteration   3: 11.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.210 ±(99.9%) 3.777 ops/ms [Average]
  (min, avg, max) = (10.975, 11.210, 11.365), stdev = 0.207
  CI (99.9%): [7.433, 14.986] (assumes normal distribution)


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
# Warmup Iteration   1: 7.059 ops/ms
# Warmup Iteration   2: 10.008 ops/ms
# Warmup Iteration   3: 10.396 ops/ms
Iteration   1: 10.416 ops/ms
Iteration   2: 10.375 ops/ms
Iteration   3: 10.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.406 ±(99.9%) 0.501 ops/ms [Average]
  (min, avg, max) = (10.375, 10.406, 10.427), stdev = 0.027
  CI (99.9%): [9.905, 10.907] (assumes normal distribution)


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
# Warmup Iteration   1: 5.351 ops/ms
# Warmup Iteration   2: 7.932 ops/ms
# Warmup Iteration   3: 8.262 ops/ms
Iteration   1: 8.102 ops/ms
Iteration   2: 8.084 ops/ms
Iteration   3: 8.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.124 ±(99.9%) 0.983 ops/ms [Average]
  (min, avg, max) = (8.084, 8.124, 8.185), stdev = 0.054
  CI (99.9%): [7.141, 9.107] (assumes normal distribution)


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
# Warmup Iteration   1: 4.229 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.003 ms/op
Iteration   1: 2.989 ±(99.9%) 0.005 ms/op
Iteration   2: 3.060 ±(99.9%) 0.004 ms/op
Iteration   3: 3.058 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.036 ±(99.9%) 0.735 ms/op [Average]
  (min, avg, max) = (2.989, 3.036, 3.060), stdev = 0.040
  CI (99.9%): [2.301, 3.771] (assumes normal distribution)


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
# Warmup Iteration   1: 3.998 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.004 ms/op
Iteration   1: 2.933 ±(99.9%) 0.001 ms/op
Iteration   2: 2.997 ±(99.9%) 0.002 ms/op
Iteration   3: 2.953 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.961 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (2.933, 2.961, 2.997), stdev = 0.033
  CI (99.9%): [2.362, 3.561] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.376 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.003 ms/op
Iteration   1: 3.032 ±(99.9%) 0.003 ms/op
Iteration   2: 3.034 ±(99.9%) 0.003 ms/op
Iteration   3: 3.067 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.044 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (3.032, 3.044, 3.067), stdev = 0.020
  CI (99.9%): [2.685, 3.403] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.205 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.012 ms/op
Iteration   1: 3.975 ±(99.9%) 0.028 ms/op
Iteration   2: 3.727 ±(99.9%) 0.004 ms/op
Iteration   3: 3.922 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.875 ±(99.9%) 2.379 ms/op [Average]
  (min, avg, max) = (3.727, 3.875, 3.975), stdev = 0.130
  CI (99.9%): [1.496, 6.254] (assumes normal distribution)


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
# Warmup Iteration   1: 4.266 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
Iteration   1: 3.041 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  6.567 ms/op
                 createUser·p0.9999: 15.999 ms/op
                 createUser·p1.00:   16.433 ms/op

Iteration   2: 3.085 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  9.017 ms/op
                 createUser·p0.9999: 19.944 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   3: 3.014 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.646 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.696 ms/op
                 createUser·p0.999:  9.534 ms/op
                 createUser·p0.9999: 28.587 ms/op
                 createUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314933
  mean =      3.046 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22065 
    [ 2.500,  5.000) = 291303 
    [ 5.000,  7.500) = 1137 
    [ 7.500, 10.000) = 208 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     27.296 ms/op
     p(99.9990) =     29.023 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.005 ms/op
Iteration   1: 2.936 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  7.537 ms/op
                 existUser·p0.9999: 18.088 ms/op
                 existUser·p1.00:   18.350 ms/op

Iteration   2: 2.965 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.613 ms/op
                 existUser·p0.9999: 18.626 ms/op
                 existUser·p1.00:   18.907 ms/op

Iteration   3: 2.965 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.836 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.436 ms/op
                 existUser·p0.999:  7.112 ms/op
                 existUser·p0.9999: 18.776 ms/op
                 existUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324709
  mean =      2.955 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 905 
    [ 1.250,  2.500) = 34427 
    [ 2.500,  3.750) = 276976 
    [ 3.750,  5.000) = 11127 
    [ 5.000,  6.250) = 766 
    [ 6.250,  7.500) = 259 
    [ 7.500,  8.750) = 82 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 66 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.447 ms/op
     p(99.9000) =      7.097 ms/op
     p(99.9900) =     18.400 ms/op
     p(99.9990) =     19.358 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 4.297 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.254 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
Iteration   1: 3.051 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.687 ms/op
                 getUser·p0.999:  7.742 ms/op
                 getUser·p0.9999: 13.369 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   2: 3.073 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.687 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  8.126 ms/op
                 getUser·p0.9999: 22.531 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   3: 3.071 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  6.674 ms/op
                 getUser·p0.9999: 19.084 ms/op
                 getUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313284
  mean =      3.065 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20244 
    [ 2.500,  5.000) = 291312 
    [ 5.000,  7.500) = 1432 
    [ 7.500, 10.000) = 157 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      7.387 ms/op
     p(99.9900) =     21.212 ms/op
     p(99.9990) =     22.986 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 5.584 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.953 ±(99.9%) 0.011 ms/op
Iteration   1: 3.922 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  14.425 ms/op
                 listUser·p0.9999: 16.524 ms/op
                 listUser·p1.00:   16.679 ms/op

Iteration   2: 3.746 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   6.859 ms/op
                 listUser·p0.999:  14.320 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   3: 3.971 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  18.153 ms/op
                 listUser·p0.9999: 26.999 ms/op
                 listUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247501
  mean =      3.877 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3375 
    [ 2.500,  5.000) = 224406 
    [ 5.000,  7.500) = 18348 
    [ 7.500, 10.000) = 857 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     14.598 ms/op
     p(99.9900) =     24.904 ms/op
     p(99.9990) =     27.575 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.393 ± 1.268  ops/ms
ClientGrpc.existUser                       thrpt       3  11.210 ± 3.777  ops/ms
ClientGrpc.getUser                         thrpt       3  10.406 ± 0.501  ops/ms
ClientGrpc.listUser                        thrpt       3   8.124 ± 0.983  ops/ms
ClientGrpc.createUser                       avgt       3   3.036 ± 0.735   ms/op
ClientGrpc.existUser                        avgt       3   2.961 ± 0.599   ms/op
ClientGrpc.getUser                          avgt       3   3.044 ± 0.359   ms/op
ClientGrpc.listUser                         avgt       3   3.875 ± 2.379   ms/op
ClientGrpc.createUser                     sample  314933   3.046 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.646           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.995           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.296           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.131           ms/op
ClientGrpc.existUser                      sample  324709   2.955 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.721           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.682           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.447           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.097           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.400           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.464           ms/op
ClientGrpc.getUser                        sample  313284   3.065 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.687           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.854           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.387           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.212           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.101           ms/op
ClientGrpc.listUser                       sample  247501   3.877 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.900           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.719           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.598           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.904           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.754           ms/op
