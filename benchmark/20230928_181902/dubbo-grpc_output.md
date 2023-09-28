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
# Warmup Iteration   1: 3.851 ops/ms
# Warmup Iteration   2: 8.862 ops/ms
# Warmup Iteration   3: 9.748 ops/ms
Iteration   1: 10.237 ops/ms
Iteration   2: 10.218 ops/ms
Iteration   3: 10.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.224 ±(99.9%) 0.211 ops/ms [Average]
  (min, avg, max) = (10.217, 10.224, 10.237), stdev = 0.012
  CI (99.9%): [10.013, 10.435] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.593 ops/ms
# Warmup Iteration   2: 10.156 ops/ms
# Warmup Iteration   3: 11.020 ops/ms
Iteration   1: 10.894 ops/ms
Iteration   2: 10.707 ops/ms
Iteration   3: 10.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.818 ±(99.9%) 1.801 ops/ms [Average]
  (min, avg, max) = (10.707, 10.818, 10.894), stdev = 0.099
  CI (99.9%): [9.017, 12.619] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.795 ops/ms
# Warmup Iteration   2: 9.740 ops/ms
# Warmup Iteration   3: 10.212 ops/ms
Iteration   1: 10.254 ops/ms
Iteration   2: 10.093 ops/ms
Iteration   3: 10.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.185 ±(99.9%) 1.509 ops/ms [Average]
  (min, avg, max) = (10.093, 10.185, 10.254), stdev = 0.083
  CI (99.9%): [8.676, 11.694] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.986 ops/ms
# Warmup Iteration   2: 7.977 ops/ms
# Warmup Iteration   3: 8.113 ops/ms
Iteration   1: 8.361 ops/ms
Iteration   2: 8.305 ops/ms
Iteration   3: 8.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.291 ±(99.9%) 1.425 ops/ms [Average]
  (min, avg, max) = (8.207, 8.291, 8.361), stdev = 0.078
  CI (99.9%): [6.866, 9.715] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.310 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.004 ms/op
Iteration   1: 3.106 ±(99.9%) 0.008 ms/op
Iteration   2: 3.076 ±(99.9%) 0.004 ms/op
Iteration   3: 3.098 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.093 ±(99.9%) 0.290 ms/op [Average]
  (min, avg, max) = (3.076, 3.093, 3.106), stdev = 0.016
  CI (99.9%): [2.803, 3.384] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.045 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.004 ms/op
Iteration   1: 3.005 ±(99.9%) 0.003 ms/op
Iteration   2: 2.940 ±(99.9%) 0.003 ms/op
Iteration   3: 3.059 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.001 ±(99.9%) 1.091 ms/op [Average]
  (min, avg, max) = (2.940, 3.001, 3.059), stdev = 0.060
  CI (99.9%): [1.910, 4.092] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.356 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.003 ms/op
Iteration   1: 3.134 ±(99.9%) 0.003 ms/op
Iteration   2: 3.156 ±(99.9%) 0.005 ms/op
Iteration   3: 3.123 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.137 ±(99.9%) 0.308 ms/op [Average]
  (min, avg, max) = (3.123, 3.137, 3.156), stdev = 0.017
  CI (99.9%): [2.829, 3.445] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.411 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.015 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.952 ±(99.9%) 0.018 ms/op
Iteration   1: 3.911 ±(99.9%) 0.030 ms/op
Iteration   2: 3.852 ±(99.9%) 0.017 ms/op
Iteration   3: 3.901 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.888 ±(99.9%) 0.577 ms/op [Average]
  (min, avg, max) = (3.852, 3.888, 3.911), stdev = 0.032
  CI (99.9%): [3.312, 4.465] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.239 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
Iteration   1: 3.227 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  8.778 ms/op
                 createUser·p0.9999: 18.055 ms/op
                 createUser·p1.00:   19.005 ms/op

Iteration   2: 3.137 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  8.281 ms/op
                 createUser·p0.9999: 15.260 ms/op
                 createUser·p1.00:   16.318 ms/op

Iteration   3: 3.112 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  10.258 ms/op
                 createUser·p0.9999: 21.675 ms/op
                 createUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304011
  mean =      3.158 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11044 
    [ 2.500,  5.000) = 291065 
    [ 5.000,  7.500) = 1379 
    [ 7.500, 10.000) = 254 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     17.734 ms/op
     p(99.9990) =     21.888 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.854 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.007 ms/op
Iteration   1: 3.027 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  12.465 ms/op
                 existUser·p0.9999: 20.120 ms/op
                 existUser·p1.00:   22.118 ms/op

Iteration   2: 2.987 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.582 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.963 ms/op
                 existUser·p0.9999: 14.749 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  11.338 ms/op
                 existUser·p0.9999: 15.729 ms/op
                 existUser·p1.00:   16.237 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320130
  mean =      2.997 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25677 
    [ 2.500,  5.000) = 293015 
    [ 5.000,  7.500) = 1006 
    [ 7.500, 10.000) = 114 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      9.718 ms/op
     p(99.9900) =     18.579 ms/op
     p(99.9990) =     22.079 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 4.366 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
Iteration   1: 3.125 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.752 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.405 ms/op
                 getUser·p0.999:  7.250 ms/op
                 getUser·p0.9999: 16.318 ms/op
                 getUser·p1.00:   16.876 ms/op

Iteration   2: 3.118 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.664 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  10.699 ms/op
                 getUser·p0.9999: 29.131 ms/op
                 getUser·p1.00:   29.196 ms/op

Iteration   3: 3.129 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  9.124 ms/op
                 getUser·p0.9999: 21.496 ms/op
                 getUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307499
  mean =      3.124 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11560 
    [ 2.500,  5.000) = 293948 
    [ 5.000,  7.500) = 1507 
    [ 7.500, 10.000) = 214 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     27.730 ms/op
     p(99.9990) =     29.196 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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
# Warmup Iteration   1: 5.461 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.010 ms/op
Iteration   1: 3.937 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.487 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  15.204 ms/op
                 listUser·p0.9999: 25.289 ms/op
                 listUser·p1.00:   28.049 ms/op

Iteration   2: 3.898 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  20.249 ms/op
                 listUser·p0.9999: 49.991 ms/op
                 listUser·p1.00:   50.135 ms/op

Iteration   3: 3.859 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.719 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   6.949 ms/op
                 listUser·p0.999:  15.434 ms/op
                 listUser·p0.9999: 21.083 ms/op
                 listUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246250
  mean =      3.898 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 230808 
    [ 5.000, 10.000) = 14677 
    [10.000, 15.000) = 458 
    [15.000, 20.000) = 189 
    [20.000, 25.000) = 63 
    [25.000, 30.000) = 23 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 12 
    [45.000, 50.000) = 12 
    [50.000, 55.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     42.099 ms/op
     p(99.9990) =     50.105 ms/op
     p(99.9999) =     50.135 ms/op
    p(100.0000) =     50.135 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.224 ± 0.211  ops/ms
ClientGrpc.existUser                       thrpt       3  10.818 ± 1.801  ops/ms
ClientGrpc.getUser                         thrpt       3  10.185 ± 1.509  ops/ms
ClientGrpc.listUser                        thrpt       3   8.291 ± 1.425  ops/ms
ClientGrpc.createUser                       avgt       3   3.093 ± 0.290   ms/op
ClientGrpc.existUser                        avgt       3   3.001 ± 1.091   ms/op
ClientGrpc.getUser                          avgt       3   3.137 ± 0.308   ms/op
ClientGrpc.listUser                         avgt       3   3.888 ± 0.577   ms/op
ClientGrpc.createUser                     sample  304011   3.158 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.749           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.109           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.568           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.734           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.053           ms/op
ClientGrpc.existUser                      sample  320130   2.997 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.582           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.718           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.579           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.118           ms/op
ClientGrpc.getUser                        sample  307499   3.124 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.664           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.962           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.730           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.196           ms/op
ClientGrpc.listUser                       sample  246250   3.898 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.719           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.415           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.431           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.816           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.745           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          42.099           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          50.135           ms/op
