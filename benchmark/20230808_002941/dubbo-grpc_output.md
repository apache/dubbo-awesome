# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.893 ops/ms
# Warmup Iteration   2: 9.553 ops/ms
# Warmup Iteration   3: 10.000 ops/ms
Iteration   1: 10.641 ops/ms
Iteration   2: 10.796 ops/ms
Iteration   3: 10.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.780 ±(99.9%) 2.406 ops/ms [Average]
  (min, avg, max) = (10.641, 10.780, 10.903), stdev = 0.132
  CI (99.9%): [8.374, 13.186] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.908 ops/ms
# Warmup Iteration   2: 10.794 ops/ms
# Warmup Iteration   3: 11.270 ops/ms
Iteration   1: 11.247 ops/ms
Iteration   2: 11.152 ops/ms
Iteration   3: 11.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.165 ±(99.9%) 1.389 ops/ms [Average]
  (min, avg, max) = (11.096, 11.165, 11.247), stdev = 0.076
  CI (99.9%): [9.776, 12.554] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.461 ops/ms
# Warmup Iteration   2: 10.315 ops/ms
# Warmup Iteration   3: 10.566 ops/ms
Iteration   1: 10.892 ops/ms
Iteration   2: 10.755 ops/ms
Iteration   3: 10.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.811 ±(99.9%) 1.316 ops/ms [Average]
  (min, avg, max) = (10.755, 10.811, 10.892), stdev = 0.072
  CI (99.9%): [9.494, 12.127] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.884 ops/ms
# Warmup Iteration   2: 7.809 ops/ms
# Warmup Iteration   3: 8.173 ops/ms
Iteration   1: 8.343 ops/ms
Iteration   2: 8.212 ops/ms
Iteration   3: 8.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.242 ±(99.9%) 1.635 ops/ms [Average]
  (min, avg, max) = (8.171, 8.242, 8.343), stdev = 0.090
  CI (99.9%): [6.606, 9.877] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.062 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.002 ms/op
Iteration   2: 2.993 ±(99.9%) 0.003 ms/op
Iteration   3: 3.009 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.997 ±(99.9%) 0.197 ms/op [Average]
  (min, avg, max) = (2.988, 2.997, 3.009), stdev = 0.011
  CI (99.9%): [2.799, 3.194] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.860 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.960 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.872 ±(99.9%) 0.004 ms/op
Iteration   1: 2.913 ±(99.9%) 0.003 ms/op
Iteration   2: 2.854 ±(99.9%) 0.003 ms/op
Iteration   3: 2.912 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.893 ±(99.9%) 0.613 ms/op [Average]
  (min, avg, max) = (2.854, 2.893, 2.913), stdev = 0.034
  CI (99.9%): [2.280, 3.506] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.921 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.002 ms/op
Iteration   1: 3.021 ±(99.9%) 0.003 ms/op
Iteration   2: 3.016 ±(99.9%) 0.003 ms/op
Iteration   3: 3.007 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.015 ±(99.9%) 0.131 ms/op [Average]
  (min, avg, max) = (3.007, 3.015, 3.021), stdev = 0.007
  CI (99.9%): [2.884, 3.145] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.826 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.954 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.022 ms/op
Iteration   1: 3.918 ±(99.9%) 0.019 ms/op
Iteration   2: 3.918 ±(99.9%) 0.018 ms/op
Iteration   3: 3.841 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.892 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (3.841, 3.892, 3.918), stdev = 0.044
  CI (99.9%): [3.086, 4.699] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.880 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
Iteration   1: 2.975 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.527 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  7.836 ms/op
                 createUser·p0.9999: 16.122 ms/op
                 createUser·p1.00:   17.596 ms/op

Iteration   2: 2.921 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.632 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.604 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  10.644 ms/op
                 createUser·p0.9999: 28.346 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  14.451 ms/op
                 createUser·p0.9999: 22.358 ms/op
                 createUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322607
  mean =      2.974 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32390 
    [ 2.500,  5.000) = 288192 
    [ 5.000,  7.500) = 1470 
    [ 7.500, 10.000) = 235 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      9.932 ms/op
     p(99.9900) =     25.806 ms/op
     p(99.9990) =     28.653 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.786 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.898 ±(99.9%) 0.006 ms/op
Iteration   1: 2.944 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  8.047 ms/op
                 existUser·p0.9999: 11.600 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   2: 2.876 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.557 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  6.985 ms/op
                 existUser·p0.9999: 19.296 ms/op
                 existUser·p1.00:   19.595 ms/op

Iteration   3: 2.825 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.531 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   4.395 ms/op
                 existUser·p0.999:  6.414 ms/op
                 existUser·p0.9999: 13.025 ms/op
                 existUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333383
  mean =      2.881 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4593 
    [ 1.250,  2.500) = 43121 
    [ 2.500,  3.750) = 272783 
    [ 3.750,  5.000) = 11467 
    [ 5.000,  6.250) = 721 
    [ 6.250,  7.500) = 407 
    [ 7.500,  8.750) = 130 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.255 ms/op
     p(99.9900) =     14.844 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.920 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.006 ms/op
Iteration   1: 3.024 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.500 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  8.111 ms/op
                 getUser·p0.9999: 22.689 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   2: 3.073 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  8.028 ms/op
                 getUser·p0.9999: 13.032 ms/op
                 getUser·p1.00:   13.468 ms/op

Iteration   3: 2.965 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.571 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.559 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.930 ms/op
                 getUser·p0.9999: 18.095 ms/op
                 getUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317713
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24937 
    [ 2.500,  5.000) = 290724 
    [ 5.000,  7.500) = 1531 
    [ 7.500, 10.000) = 361 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      7.981 ms/op
     p(99.9900) =     22.322 ms/op
     p(99.9990) =     22.899 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.018 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.011 ms/op
Iteration   1: 3.949 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.028 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  12.925 ms/op
                 listUser·p0.9999: 24.274 ms/op
                 listUser·p1.00:   25.035 ms/op

Iteration   2: 3.890 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  14.806 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   3: 3.933 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.734 ms/op
                 listUser·p0.9999: 16.155 ms/op
                 listUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244810
  mean =      3.924 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3757 
    [ 2.500,  5.000) = 218814 
    [ 5.000,  7.500) = 20721 
    [ 7.500, 10.000) = 949 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     14.487 ms/op
     p(99.9900) =     18.680 ms/op
     p(99.9990) =     24.860 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.780 ± 2.406  ops/ms
ClientGrpc.existUser                       thrpt       3  11.165 ± 1.389  ops/ms
ClientGrpc.getUser                         thrpt       3  10.811 ± 1.316  ops/ms
ClientGrpc.listUser                        thrpt       3   8.242 ± 1.635  ops/ms
ClientGrpc.createUser                       avgt       3   2.997 ± 0.197   ms/op
ClientGrpc.existUser                        avgt       3   2.893 ± 0.613   ms/op
ClientGrpc.getUser                          avgt       3   3.015 ± 0.131   ms/op
ClientGrpc.listUser                         avgt       3   3.892 ± 0.807   ms/op
ClientGrpc.createUser                     sample  322607   2.974 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.527           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.932           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.806           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.229           ms/op
ClientGrpc.existUser                      sample  333383   2.881 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.531           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.666           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.255           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.844           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.595           ms/op
ClientGrpc.getUser                        sample  317713   3.020 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.500           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.981           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.322           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.970           ms/op
ClientGrpc.listUser                       sample  244810   3.924 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.028           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.487           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.680           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.035           ms/op
