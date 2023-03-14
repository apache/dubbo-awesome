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
# Warmup Iteration   1: 4.470 ops/ms
# Warmup Iteration   2: 9.635 ops/ms
# Warmup Iteration   3: 10.569 ops/ms
Iteration   1: 10.816 ops/ms
Iteration   2: 10.899 ops/ms
Iteration   3: 10.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.796 ±(99.9%) 2.090 ops/ms [Average]
  (min, avg, max) = (10.673, 10.796, 10.899), stdev = 0.115
  CI (99.9%): [8.705, 12.886] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.004 ops/ms
# Warmup Iteration   2: 11.267 ops/ms
# Warmup Iteration   3: 11.414 ops/ms
Iteration   1: 11.497 ops/ms
Iteration   2: 11.495 ops/ms
Iteration   3: 11.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.500 ±(99.9%) 0.132 ops/ms [Average]
  (min, avg, max) = (11.495, 11.500, 11.508), stdev = 0.007
  CI (99.9%): [11.369, 11.632] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.527 ops/ms
# Warmup Iteration   2: 10.515 ops/ms
# Warmup Iteration   3: 10.935 ops/ms
Iteration   1: 10.783 ops/ms
Iteration   2: 11.004 ops/ms
Iteration   3: 11.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.966 ±(99.9%) 3.034 ops/ms [Average]
  (min, avg, max) = (10.783, 10.966, 11.109), stdev = 0.166
  CI (99.9%): [7.931, 14.000] (assumes normal distribution)


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
# Warmup Iteration   1: 6.453 ops/ms
# Warmup Iteration   2: 8.138 ops/ms
# Warmup Iteration   3: 8.301 ops/ms
Iteration   1: 8.370 ops/ms
Iteration   2: 8.341 ops/ms
Iteration   3: 8.387 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.366 ±(99.9%) 0.421 ops/ms [Average]
  (min, avg, max) = (8.341, 8.366, 8.387), stdev = 0.023
  CI (99.9%): [7.945, 8.787] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.668 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.968 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.909 ±(99.9%) 0.003 ms/op
Iteration   1: 3.011 ±(99.9%) 0.010 ms/op
Iteration   2: 2.961 ±(99.9%) 0.002 ms/op
Iteration   3: 2.938 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.970 ±(99.9%) 0.684 ms/op [Average]
  (min, avg, max) = (2.938, 2.970, 3.011), stdev = 0.037
  CI (99.9%): [2.286, 3.654] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.609 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.833 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.877 ±(99.9%) 0.003 ms/op
Iteration   1: 2.815 ±(99.9%) 0.003 ms/op
Iteration   2: 2.847 ±(99.9%) 0.005 ms/op
Iteration   3: 2.846 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.836 ±(99.9%) 0.334 ms/op [Average]
  (min, avg, max) = (2.815, 2.836, 2.847), stdev = 0.018
  CI (99.9%): [2.502, 3.169] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.950 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.868 ±(99.9%) 0.003 ms/op
Iteration   1: 2.909 ±(99.9%) 0.002 ms/op
Iteration   2: 2.895 ±(99.9%) 0.002 ms/op
Iteration   3: 2.892 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.899 ±(99.9%) 0.167 ms/op [Average]
  (min, avg, max) = (2.892, 2.899, 2.909), stdev = 0.009
  CI (99.9%): [2.731, 3.066] (assumes normal distribution)


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
# Warmup Iteration   1: 5.062 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.739 ±(99.9%) 0.008 ms/op
Iteration   1: 3.847 ±(99.9%) 0.021 ms/op
Iteration   2: 3.790 ±(99.9%) 0.015 ms/op
Iteration   3: 3.761 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.800 ±(99.9%) 0.803 ms/op [Average]
  (min, avg, max) = (3.761, 3.800, 3.847), stdev = 0.044
  CI (99.9%): [2.996, 4.603] (assumes normal distribution)


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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.008 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.008 ms/op
Iteration   1: 2.940 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  6.731 ms/op
                 createUser·p0.9999: 17.695 ms/op
                 createUser·p1.00:   17.990 ms/op

Iteration   2: 2.932 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   2.916 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.555 ms/op
                 createUser·p0.99:   4.174 ms/op
                 createUser·p0.999:  8.248 ms/op
                 createUser·p0.9999: 18.877 ms/op
                 createUser·p1.00:   19.759 ms/op

Iteration   3: 2.993 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  10.158 ms/op
                 createUser·p0.9999: 33.308 ms/op
                 createUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325050
  mean =      2.955 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34902 
    [ 2.500,  5.000) = 289045 
    [ 5.000,  7.500) = 725 
    [ 7.500, 10.000) = 120 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      8.060 ms/op
     p(99.9900) =     26.744 ms/op
     p(99.9990) =     34.504 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.931 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.816 ±(99.9%) 0.006 ms/op
Iteration   1: 2.834 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  5.398 ms/op
                 existUser·p0.9999: 11.923 ms/op
                 existUser·p1.00:   12.190 ms/op

Iteration   2: 2.847 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  5.169 ms/op
                 existUser·p0.9999: 12.776 ms/op
                 existUser·p1.00:   12.894 ms/op

Iteration   3: 2.834 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.865 ms/op
                 existUser·p0.9999: 15.271 ms/op
                 existUser·p1.00:   15.663 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 338444
  mean =      2.838 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2247 
    [ 1.250,  2.500) = 47610 
    [ 2.500,  3.750) = 280334 
    [ 3.750,  5.000) = 7591 
    [ 5.000,  6.250) = 342 
    [ 6.250,  7.500) = 119 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.281 ms/op
     p(95.0000) =      3.498 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      6.157 ms/op
     p(99.9900) =     13.978 ms/op
     p(99.9990) =     15.585 ms/op
     p(99.9999) =     15.663 ms/op
    p(100.0000) =     15.663 ms/op


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.020 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.891 ±(99.9%) 0.006 ms/op
Iteration   1: 2.967 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.721 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  7.659 ms/op
                 getUser·p0.9999: 15.044 ms/op
                 getUser·p1.00:   15.843 ms/op

Iteration   2: 2.947 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.523 ms/op
                 getUser·p0.99:   4.055 ms/op
                 getUser·p0.999:  7.089 ms/op
                 getUser·p0.9999: 13.325 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   3: 2.912 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   2.920 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.550 ms/op
                 getUser·p0.9999: 24.871 ms/op
                 getUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 326133
  mean =      2.942 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31160 
    [ 2.500,  5.000) = 293813 
    [ 5.000,  7.500) = 878 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.158 ms/op
     p(99.9900) =     19.475 ms/op
     p(99.9990) =     25.083 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 4.840 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.936 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.010 ms/op
Iteration   1: 3.709 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   6.357 ms/op
                 listUser·p0.999:  12.141 ms/op
                 listUser·p0.9999: 16.855 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   2: 3.789 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.662 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  13.706 ms/op
                 listUser·p0.9999: 19.337 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   3: 3.617 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   3.531 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  12.088 ms/op
                 listUser·p0.9999: 15.836 ms/op
                 listUser·p1.00:   16.400 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 259355
  mean =      3.703 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 5844 
    [ 2.500,  3.750) = 160043 
    [ 3.750,  5.000) = 77472 
    [ 5.000,  6.250) = 12398 
    [ 6.250,  7.500) = 2630 
    [ 7.500,  8.750) = 439 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 137 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     12.599 ms/op
     p(99.9900) =     18.164 ms/op
     p(99.9990) =     19.753 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.796 ± 2.090  ops/ms
ClientGrpc.existUser                       thrpt       3  11.500 ± 0.132  ops/ms
ClientGrpc.getUser                         thrpt       3  10.966 ± 3.034  ops/ms
ClientGrpc.listUser                        thrpt       3   8.366 ± 0.421  ops/ms
ClientGrpc.createUser                       avgt       3   2.970 ± 0.684   ms/op
ClientGrpc.existUser                        avgt       3   2.836 ± 0.334   ms/op
ClientGrpc.getUser                          avgt       3   2.899 ± 0.167   ms/op
ClientGrpc.listUser                         avgt       3   3.800 ± 0.803   ms/op
ClientGrpc.createUser                     sample  325050   2.955 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.643           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.933           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.473           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.060           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.744           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.800           ms/op
ClientGrpc.existUser                      sample  338444   2.838 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.540           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.834           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.281           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.157           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.978           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.663           ms/op
ClientGrpc.getUser                        sample  326133   2.942 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.642           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.937           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.428           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.158           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.475           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.199           ms/op
ClientGrpc.listUser                       sample  259355   3.703 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.662           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.596           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.563           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.496           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.599           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.164           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.890           ms/op
