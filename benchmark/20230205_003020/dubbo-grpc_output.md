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
# Warmup Iteration   1: 3.681 ops/ms
# Warmup Iteration   2: 8.532 ops/ms
# Warmup Iteration   3: 10.066 ops/ms
Iteration   1: 9.898 ops/ms
Iteration   2: 10.022 ops/ms
Iteration   3: 9.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.962 ±(99.9%) 1.138 ops/ms [Average]
  (min, avg, max) = (9.898, 9.962, 10.022), stdev = 0.062
  CI (99.9%): [8.824, 11.100] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.978 ops/ms
# Warmup Iteration   2: 10.073 ops/ms
# Warmup Iteration   3: 10.248 ops/ms
Iteration   1: 10.229 ops/ms
Iteration   2: 10.250 ops/ms
Iteration   3: 10.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.317 ±(99.9%) 2.432 ops/ms [Average]
  (min, avg, max) = (10.229, 10.317, 10.470), stdev = 0.133
  CI (99.9%): [7.884, 12.749] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.579 ops/ms
# Warmup Iteration   2: 9.983 ops/ms
# Warmup Iteration   3: 9.987 ops/ms
Iteration   1: 10.099 ops/ms
Iteration   2: 9.915 ops/ms
Iteration   3: 9.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.897 ±(99.9%) 3.835 ops/ms [Average]
  (min, avg, max) = (9.679, 9.897, 10.099), stdev = 0.210
  CI (99.9%): [6.063, 13.732] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.535 ops/ms
# Warmup Iteration   2: 7.438 ops/ms
# Warmup Iteration   3: 7.723 ops/ms
Iteration   1: 7.932 ops/ms
Iteration   2: 7.450 ops/ms
Iteration   3: 7.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.695 ±(99.9%) 4.405 ops/ms [Average]
  (min, avg, max) = (7.450, 7.695, 7.932), stdev = 0.241
  CI (99.9%): [3.290, 12.099] (assumes normal distribution)


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
# Warmup Iteration   1: 4.562 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.284 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.237 ±(99.9%) 0.002 ms/op
Iteration   1: 3.285 ±(99.9%) 0.002 ms/op
Iteration   2: 3.246 ±(99.9%) 0.002 ms/op
Iteration   3: 3.232 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.254 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (3.232, 3.254, 3.285), stdev = 0.028
  CI (99.9%): [2.748, 3.760] (assumes normal distribution)


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
# Warmup Iteration   1: 4.122 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.002 ms/op
Iteration   1: 3.103 ±(99.9%) 0.002 ms/op
Iteration   2: 3.215 ±(99.9%) 0.003 ms/op
Iteration   3: 3.188 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.168 ±(99.9%) 1.066 ms/op [Average]
  (min, avg, max) = (3.103, 3.168, 3.215), stdev = 0.058
  CI (99.9%): [2.102, 4.234] (assumes normal distribution)


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
# Warmup Iteration   1: 4.407 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.004 ms/op
Iteration   1: 3.307 ±(99.9%) 0.002 ms/op
Iteration   2: 3.280 ±(99.9%) 0.002 ms/op
Iteration   3: 3.269 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.285 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (3.269, 3.285, 3.307), stdev = 0.020
  CI (99.9%): [2.924, 3.647] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.705 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.200 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.009 ms/op
Iteration   1: 4.012 ±(99.9%) 0.005 ms/op
Iteration   2: 4.021 ±(99.9%) 0.014 ms/op
Iteration   3: 4.201 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.078 ±(99.9%) 1.941 ms/op [Average]
  (min, avg, max) = (4.012, 4.078, 4.201), stdev = 0.106
  CI (99.9%): [2.137, 6.019] (assumes normal distribution)


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
# Warmup Iteration   1: 4.566 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.322 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.007 ms/op
Iteration   1: 3.229 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  6.995 ms/op
                 createUser·p0.9999: 16.569 ms/op
                 createUser·p1.00:   17.203 ms/op

Iteration   2: 3.195 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  6.791 ms/op
                 createUser·p0.9999: 18.382 ms/op
                 createUser·p1.00:   18.579 ms/op

Iteration   3: 3.238 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  9.300 ms/op
                 createUser·p0.9999: 26.710 ms/op
                 createUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 297851
  mean =      3.220 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16729 
    [ 2.500,  5.000) = 280113 
    [ 5.000,  7.500) = 730 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.332 ms/op
     p(99.9900) =     26.327 ms/op
     p(99.9990) =     26.871 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.006 ms/op
Iteration   1: 3.132 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   4.559 ms/op
                 existUser·p0.999:  7.379 ms/op
                 existUser·p0.9999: 12.821 ms/op
                 existUser·p1.00:   13.222 ms/op

Iteration   2: 3.116 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.554 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.236 ms/op
                 existUser·p0.9999: 15.170 ms/op
                 existUser·p1.00:   15.630 ms/op

Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.971 ms/op
                 existUser·p0.9999: 16.941 ms/op
                 existUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 309848
  mean =      3.099 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1214 
    [ 1.250,  2.500) = 31153 
    [ 2.500,  3.750) = 240528 
    [ 3.750,  5.000) = 35886 
    [ 5.000,  6.250) = 534 
    [ 6.250,  7.500) = 265 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.120 ms/op
     p(99.9900) =     15.712 ms/op
     p(99.9990) =     17.102 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 4.470 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.378 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.007 ms/op
Iteration   1: 3.222 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  6.788 ms/op
                 getUser·p0.9999: 12.766 ms/op
                 getUser·p1.00:   13.304 ms/op

Iteration   2: 3.321 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   4.100 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  7.406 ms/op
                 getUser·p0.9999: 20.308 ms/op
                 getUser·p1.00:   20.840 ms/op

Iteration   3: 3.226 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  6.757 ms/op
                 getUser·p0.9999: 18.910 ms/op
                 getUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 294907
  mean =      3.256 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19329 
    [ 2.500,  5.000) = 274375 
    [ 5.000,  7.500) = 963 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      6.874 ms/op
     p(99.9900) =     19.776 ms/op
     p(99.9990) =     20.747 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 5.811 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.188 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.136 ±(99.9%) 0.012 ms/op
Iteration   1: 4.190 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.839 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 16.261 ms/op
                 listUser·p1.00:   16.908 ms/op

Iteration   2: 4.011 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  13.943 ms/op
                 listUser·p0.9999: 16.433 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   3: 4.046 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.141 ms/op
                 listUser·p0.999:  17.202 ms/op
                 listUser·p0.9999: 27.564 ms/op
                 listUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235064
  mean =      4.081 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1747 
    [ 2.500,  5.000) = 205280 
    [ 5.000,  7.500) = 26480 
    [ 7.500, 10.000) = 1138 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     14.809 ms/op
     p(99.9900) =     26.886 ms/op
     p(99.9990) =     29.531 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.962 ± 1.138  ops/ms
ClientGrpc.existUser                       thrpt       3  10.317 ± 2.432  ops/ms
ClientGrpc.getUser                         thrpt       3   9.897 ± 3.835  ops/ms
ClientGrpc.listUser                        thrpt       3   7.695 ± 4.405  ops/ms
ClientGrpc.createUser                       avgt       3   3.254 ± 0.506   ms/op
ClientGrpc.existUser                        avgt       3   3.168 ± 1.066   ms/op
ClientGrpc.getUser                          avgt       3   3.285 ± 0.362   ms/op
ClientGrpc.listUser                         avgt       3   4.078 ± 1.941   ms/op
ClientGrpc.createUser                     sample  297851   3.220 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.746           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.191           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.084           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.332           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.327           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.935           ms/op
ClientGrpc.existUser                      sample  309848   3.099 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.554           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.076           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.809           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.998           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.120           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.712           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.236           ms/op
ClientGrpc.getUser                        sample  294907   3.256 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.773           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.236           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.010           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.874           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.776           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.840           ms/op
ClientGrpc.listUser                       sample  235064   4.081 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.839           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.903           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.186           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.809           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.886           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.704           ms/op
