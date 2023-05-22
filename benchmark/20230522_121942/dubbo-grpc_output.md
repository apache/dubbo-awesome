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
# Warmup Iteration   1: 2.507 ops/ms
# Warmup Iteration   2: 6.155 ops/ms
# Warmup Iteration   3: 7.464 ops/ms
Iteration   1: 7.867 ops/ms
Iteration   2: 8.133 ops/ms
Iteration   3: 8.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.009 ±(99.9%) 2.439 ops/ms [Average]
  (min, avg, max) = (7.867, 8.009, 8.133), stdev = 0.134
  CI (99.9%): [5.569, 10.448] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.056 ops/ms
# Warmup Iteration   2: 7.753 ops/ms
# Warmup Iteration   3: 8.269 ops/ms
Iteration   1: 8.435 ops/ms
Iteration   2: 8.366 ops/ms
Iteration   3: 8.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.387 ±(99.9%) 0.764 ops/ms [Average]
  (min, avg, max) = (8.359, 8.387, 8.435), stdev = 0.042
  CI (99.9%): [7.623, 9.151] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.697 ops/ms
# Warmup Iteration   2: 7.070 ops/ms
# Warmup Iteration   3: 7.710 ops/ms
Iteration   1: 7.962 ops/ms
Iteration   2: 7.863 ops/ms
Iteration   3: 7.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.790 ±(99.9%) 3.973 ops/ms [Average]
  (min, avg, max) = (7.545, 7.790, 7.962), stdev = 0.218
  CI (99.9%): [3.817, 11.763] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.656 ops/ms
# Warmup Iteration   2: 5.203 ops/ms
# Warmup Iteration   3: 5.801 ops/ms
Iteration   1: 5.785 ops/ms
Iteration   2: 6.105 ops/ms
Iteration   3: 5.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.937 ±(99.9%) 2.931 ops/ms [Average]
  (min, avg, max) = (5.785, 5.937, 6.105), stdev = 0.161
  CI (99.9%): [3.006, 8.868] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.328 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.348 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.272 ±(99.9%) 0.002 ms/op
Iteration   1: 4.145 ±(99.9%) 0.004 ms/op
Iteration   2: 4.144 ±(99.9%) 0.003 ms/op
Iteration   3: 4.912 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.400 ±(99.9%) 8.084 ms/op [Average]
  (min, avg, max) = (4.144, 4.400, 4.912), stdev = 0.443
  CI (99.9%): [≈ 0, 12.485] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.664 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.122 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.961 ±(99.9%) 0.012 ms/op
Iteration   1: 4.409 ±(99.9%) 0.006 ms/op
Iteration   2: 3.867 ±(99.9%) 0.004 ms/op
Iteration   3: 3.835 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.037 ±(99.9%) 5.884 ms/op [Average]
  (min, avg, max) = (3.835, 4.037, 4.409), stdev = 0.322
  CI (99.9%): [≈ 0, 9.920] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.347 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.335 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.006 ms/op
Iteration   1: 3.993 ±(99.9%) 0.004 ms/op
Iteration   2: 3.838 ±(99.9%) 0.005 ms/op
Iteration   3: 4.091 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.974 ±(99.9%) 2.320 ms/op [Average]
  (min, avg, max) = (3.838, 3.974, 4.091), stdev = 0.127
  CI (99.9%): [1.654, 6.294] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.806 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.663 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.549 ±(99.9%) 0.013 ms/op
Iteration   1: 5.512 ±(99.9%) 0.018 ms/op
Iteration   2: 5.403 ±(99.9%) 0.016 ms/op
Iteration   3: 5.274 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.397 ±(99.9%) 2.169 ms/op [Average]
  (min, avg, max) = (5.274, 5.397, 5.512), stdev = 0.119
  CI (99.9%): [3.228, 7.565] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.431 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.466 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.133 ±(99.9%) 0.011 ms/op
Iteration   1: 4.009 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.438 ms/op
                 createUser·p0.50:   3.961 ms/op
                 createUser·p0.90:   5.046 ms/op
                 createUser·p0.95:   5.423 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  9.552 ms/op
                 createUser·p0.9999: 19.006 ms/op
                 createUser·p1.00:   21.234 ms/op

Iteration   2: 4.038 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.120 ms/op
                 createUser·p0.50:   3.981 ms/op
                 createUser·p0.90:   4.997 ms/op
                 createUser·p0.95:   5.366 ms/op
                 createUser·p0.99:   6.461 ms/op
                 createUser·p0.999:  10.399 ms/op
                 createUser·p0.9999: 21.534 ms/op
                 createUser·p1.00:   23.101 ms/op

Iteration   3: 4.152 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   4.043 ms/op
                 createUser·p0.90:   5.120 ms/op
                 createUser·p0.95:   5.472 ms/op
                 createUser·p0.99:   6.692 ms/op
                 createUser·p0.999:  13.532 ms/op
                 createUser·p0.9999: 23.999 ms/op
                 createUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 235922
  mean =      4.066 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7320 
    [ 2.500,  5.000) = 202592 
    [ 5.000,  7.500) = 24827 
    [ 7.500, 10.000) = 809 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.438 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     12.091 ms/op
     p(99.9900) =     23.195 ms/op
     p(99.9990) =     24.922 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.718 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.376 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.922 ±(99.9%) 0.010 ms/op
Iteration   1: 3.903 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.204 ms/op
                 existUser·p0.50:   3.801 ms/op
                 existUser·p0.90:   4.760 ms/op
                 existUser·p0.95:   5.145 ms/op
                 existUser·p0.99:   6.513 ms/op
                 existUser·p0.999:  11.682 ms/op
                 existUser·p0.9999: 15.791 ms/op
                 existUser·p1.00:   16.237 ms/op

Iteration   2: 4.006 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   3.924 ms/op
                 existUser·p0.90:   4.973 ms/op
                 existUser·p0.95:   5.292 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  9.621 ms/op
                 existUser·p0.9999: 16.604 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   3: 3.943 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.016 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.874 ms/op
                 existUser·p0.95:   5.276 ms/op
                 existUser·p0.99:   6.406 ms/op
                 existUser·p0.999:  13.590 ms/op
                 existUser·p0.9999: 18.419 ms/op
                 existUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 242867
  mean =      3.950 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 3696 
    [ 2.500,  3.750) = 102295 
    [ 3.750,  5.000) = 117434 
    [ 5.000,  6.250) = 16856 
    [ 6.250,  7.500) = 1446 
    [ 7.500,  8.750) = 457 
    [ 8.750, 10.000) = 284 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 59 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.999 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      6.291 ms/op
     p(99.9000) =     11.682 ms/op
     p(99.9900) =     17.161 ms/op
     p(99.9990) =     18.767 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.917 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.507 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.159 ±(99.9%) 0.011 ms/op
Iteration   1: 4.083 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.272 ms/op
                 getUser·p0.50:   4.014 ms/op
                 getUser·p0.90:   4.948 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  10.939 ms/op
                 getUser·p0.9999: 15.592 ms/op
                 getUser·p1.00:   15.892 ms/op

Iteration   2: 4.098 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   4.030 ms/op
                 getUser·p0.90:   5.005 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  9.500 ms/op
                 getUser·p0.9999: 18.710 ms/op
                 getUser·p1.00:   19.431 ms/op

Iteration   3: 4.050 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   3.969 ms/op
                 getUser·p0.90:   4.940 ms/op
                 getUser·p0.95:   5.341 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  10.272 ms/op
                 getUser·p0.9999: 19.611 ms/op
                 getUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 235444
  mean =      4.077 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4126 
    [ 2.500,  5.000) = 209262 
    [ 5.000,  7.500) = 20842 
    [ 7.500, 10.000) = 942 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      4.006 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     10.504 ms/op
     p(99.9900) =     18.693 ms/op
     p(99.9990) =     20.904 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.735 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.601 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.447 ±(99.9%) 0.017 ms/op
Iteration   1: 5.327 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.174 ms/op
                 listUser·p0.50:   5.120 ms/op
                 listUser·p0.90:   6.767 ms/op
                 listUser·p0.95:   7.676 ms/op
                 listUser·p0.99:   9.498 ms/op
                 listUser·p0.999:  18.643 ms/op
                 listUser·p0.9999: 22.512 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   2: 5.292 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.407 ms/op
                 listUser·p0.50:   5.063 ms/op
                 listUser·p0.90:   6.619 ms/op
                 listUser·p0.95:   7.741 ms/op
                 listUser·p0.99:   9.667 ms/op
                 listUser·p0.999:  17.335 ms/op
                 listUser·p0.9999: 29.454 ms/op
                 listUser·p1.00:   30.179 ms/op

Iteration   3: 5.387 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   5.194 ms/op
                 listUser·p0.90:   6.586 ms/op
                 listUser·p0.95:   7.561 ms/op
                 listUser·p0.99:   9.434 ms/op
                 listUser·p0.999:  20.565 ms/op
                 listUser·p0.9999: 22.747 ms/op
                 listUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 179932
  mean =      5.335 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 77857 
    [ 5.000,  7.500) = 91883 
    [ 7.500, 10.000) = 8845 
    [10.000, 12.500) = 828 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      5.128 ms/op
     p(90.0000) =      6.660 ms/op
     p(95.0000) =      7.660 ms/op
     p(99.0000) =      9.535 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     28.607 ms/op
     p(99.9990) =     30.153 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.009 ± 2.439  ops/ms
ClientGrpc.existUser                       thrpt       3   8.387 ± 0.764  ops/ms
ClientGrpc.getUser                         thrpt       3   7.790 ± 3.973  ops/ms
ClientGrpc.listUser                        thrpt       3   5.937 ± 2.931  ops/ms
ClientGrpc.createUser                       avgt       3   4.400 ± 8.084   ms/op
ClientGrpc.existUser                        avgt       3   4.037 ± 5.884   ms/op
ClientGrpc.getUser                          avgt       3   3.974 ± 2.320   ms/op
ClientGrpc.listUser                         avgt       3   5.397 ± 2.169   ms/op
ClientGrpc.createUser                     sample  235922   4.066 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.438           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.054           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.423           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.472           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.091           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.195           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.100           ms/op
ClientGrpc.existUser                      sample  242867   3.950 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.999           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.854           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.874           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.251           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.291           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.682           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.161           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.842           ms/op
ClientGrpc.getUser                        sample  235444   4.077 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.079           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.964           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.325           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.431           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.504           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.693           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.004           ms/op
ClientGrpc.listUser                       sample  179932   5.335 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.174           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.660           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.660           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.535           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.973           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.607           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.179           ms/op
