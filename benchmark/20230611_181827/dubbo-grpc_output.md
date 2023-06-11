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
# Warmup Iteration   1: 4.251 ops/ms
# Warmup Iteration   2: 8.810 ops/ms
# Warmup Iteration   3: 9.932 ops/ms
Iteration   1: 10.393 ops/ms
Iteration   2: 10.287 ops/ms
Iteration   3: 10.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.448 ±(99.9%) 3.551 ops/ms [Average]
  (min, avg, max) = (10.287, 10.448, 10.664), stdev = 0.195
  CI (99.9%): [6.897, 13.999] (assumes normal distribution)


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
# Warmup Iteration   1: 7.436 ops/ms
# Warmup Iteration   2: 10.298 ops/ms
# Warmup Iteration   3: 10.576 ops/ms
Iteration   1: 10.840 ops/ms
Iteration   2: 10.959 ops/ms
Iteration   3: 10.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.865 ±(99.9%) 1.535 ops/ms [Average]
  (min, avg, max) = (10.796, 10.865, 10.959), stdev = 0.084
  CI (99.9%): [9.331, 12.400] (assumes normal distribution)


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
# Warmup Iteration   1: 7.521 ops/ms
# Warmup Iteration   2: 9.917 ops/ms
# Warmup Iteration   3: 10.217 ops/ms
Iteration   1: 10.186 ops/ms
Iteration   2: 10.301 ops/ms
Iteration   3: 10.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.353 ±(99.9%) 3.624 ops/ms [Average]
  (min, avg, max) = (10.186, 10.353, 10.573), stdev = 0.199
  CI (99.9%): [6.729, 13.977] (assumes normal distribution)


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
# Warmup Iteration   1: 6.584 ops/ms
# Warmup Iteration   2: 7.492 ops/ms
# Warmup Iteration   3: 7.869 ops/ms
Iteration   1: 7.890 ops/ms
Iteration   2: 8.115 ops/ms
Iteration   3: 8.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.064 ±(99.9%) 2.828 ops/ms [Average]
  (min, avg, max) = (7.890, 8.064, 8.187), stdev = 0.155
  CI (99.9%): [5.236, 10.892] (assumes normal distribution)


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
# Warmup Iteration   1: 4.420 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.003 ms/op
Iteration   1: 3.088 ±(99.9%) 0.002 ms/op
Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
Iteration   3: 2.988 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.020 ±(99.9%) 1.062 ms/op [Average]
  (min, avg, max) = (2.985, 3.020, 3.088), stdev = 0.058
  CI (99.9%): [1.959, 4.082] (assumes normal distribution)


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
# Warmup Iteration   1: 3.676 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.940 ±(99.9%) 0.003 ms/op
Iteration   1: 2.900 ±(99.9%) 0.003 ms/op
Iteration   2: 2.886 ±(99.9%) 0.003 ms/op
Iteration   3: 2.907 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.898 ±(99.9%) 0.197 ms/op [Average]
  (min, avg, max) = (2.886, 2.898, 2.907), stdev = 0.011
  CI (99.9%): [2.700, 3.095] (assumes normal distribution)


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
# Warmup Iteration   1: 4.304 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.004 ms/op
Iteration   1: 3.070 ±(99.9%) 0.002 ms/op
Iteration   2: 3.022 ±(99.9%) 0.003 ms/op
Iteration   3: 3.036 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.043 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (3.022, 3.043, 3.070), stdev = 0.025
  CI (99.9%): [2.584, 3.501] (assumes normal distribution)


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
# Warmup Iteration   1: 5.497 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.193 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.013 ms/op
Iteration   1: 4.033 ±(99.9%) 0.017 ms/op
Iteration   2: 3.946 ±(99.9%) 0.009 ms/op
Iteration   3: 4.011 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.997 ±(99.9%) 0.820 ms/op [Average]
  (min, avg, max) = (3.946, 3.997, 4.033), stdev = 0.045
  CI (99.9%): [3.177, 4.816] (assumes normal distribution)


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
# Warmup Iteration   1: 4.343 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.007 ms/op
Iteration   1: 3.027 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.719 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  6.596 ms/op
                 createUser·p0.9999: 19.674 ms/op
                 createUser·p1.00:   20.152 ms/op

Iteration   2: 2.991 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  7.417 ms/op
                 createUser·p0.9999: 19.671 ms/op
                 createUser·p1.00:   20.218 ms/op

Iteration   3: 3.059 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  9.175 ms/op
                 createUser·p0.9999: 28.347 ms/op
                 createUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317380
  mean =      3.025 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29780 
    [ 2.500,  5.000) = 286248 
    [ 5.000,  7.500) = 950 
    [ 7.500, 10.000) = 146 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      9.021 ms/op
     p(99.9900) =     28.017 ms/op
     p(99.9990) =     28.742 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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
# Warmup Iteration   1: 3.883 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.917 ±(99.9%) 0.005 ms/op
Iteration   1: 2.825 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.937 ms/op
                 existUser·p0.9999: 12.184 ms/op
                 existUser·p1.00:   12.468 ms/op

Iteration   2: 2.896 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   3.977 ms/op
                 existUser·p0.999:  6.570 ms/op
                 existUser·p0.9999: 14.417 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   3: 2.954 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.624 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.143 ms/op
                 existUser·p0.999:  7.061 ms/op
                 existUser·p0.9999: 26.711 ms/op
                 existUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331945
  mean =      2.891 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37055 
    [ 2.500,  5.000) = 293979 
    [ 5.000,  7.500) = 668 
    [ 7.500, 10.000) = 55 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.555 ms/op
     p(99.0000) =      4.133 ms/op
     p(99.9000) =      6.701 ms/op
     p(99.9900) =     26.142 ms/op
     p(99.9990) =     26.892 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 3.987 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
Iteration   1: 3.010 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  7.370 ms/op
                 getUser·p0.9999: 14.574 ms/op
                 getUser·p1.00:   15.041 ms/op

Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.650 ms/op
                 getUser·p0.9999: 15.705 ms/op
                 getUser·p1.00:   15.925 ms/op

Iteration   3: 3.011 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  7.575 ms/op
                 getUser·p0.9999: 28.443 ms/op
                 getUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317045
  mean =      3.026 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20965 
    [ 2.500,  5.000) = 294390 
    [ 5.000,  7.500) = 1370 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      7.552 ms/op
     p(99.9900) =     27.807 ms/op
     p(99.9990) =     28.601 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 5.428 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.049 ±(99.9%) 0.010 ms/op
Iteration   1: 4.037 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.550 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  13.788 ms/op
                 listUser·p0.9999: 22.252 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   2: 4.067 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.499 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  14.505 ms/op
                 listUser·p0.9999: 16.374 ms/op
                 listUser·p1.00:   17.334 ms/op

Iteration   3: 3.868 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.785 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  16.024 ms/op
                 listUser·p0.9999: 18.987 ms/op
                 listUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240702
  mean =      3.989 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2434 
    [ 2.500,  5.000) = 216398 
    [ 5.000,  7.500) = 20473 
    [ 7.500, 10.000) = 952 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     14.739 ms/op
     p(99.9900) =     21.590 ms/op
     p(99.9990) =     22.381 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.448 ± 3.551  ops/ms
ClientGrpc.existUser                       thrpt       3  10.865 ± 1.535  ops/ms
ClientGrpc.getUser                         thrpt       3  10.353 ± 3.624  ops/ms
ClientGrpc.listUser                        thrpt       3   8.064 ± 2.828  ops/ms
ClientGrpc.createUser                       avgt       3   3.020 ± 1.062   ms/op
ClientGrpc.existUser                        avgt       3   2.898 ± 0.197   ms/op
ClientGrpc.getUser                          avgt       3   3.043 ± 0.458   ms/op
ClientGrpc.listUser                         avgt       3   3.997 ± 0.820   ms/op
ClientGrpc.createUser                     sample  317380   3.025 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.719           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.021           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.017           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.474           ms/op
ClientGrpc.existUser                      sample  331945   2.891 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.624           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.701           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.142           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.001           ms/op
ClientGrpc.getUser                        sample  317045   3.026 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.753           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.552           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.807           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.672           ms/op
ClientGrpc.listUser                       sample  240702   3.989 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.785           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.004           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.739           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.590           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.413           ms/op
