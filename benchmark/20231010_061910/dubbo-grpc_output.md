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
# Warmup Iteration   1: 4.310 ops/ms
# Warmup Iteration   2: 8.994 ops/ms
# Warmup Iteration   3: 10.151 ops/ms
Iteration   1: 10.317 ops/ms
Iteration   2: 10.383 ops/ms
Iteration   3: 10.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.370 ±(99.9%) 0.882 ops/ms [Average]
  (min, avg, max) = (10.317, 10.370, 10.411), stdev = 0.048
  CI (99.9%): [9.489, 11.252] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.458 ops/ms
# Warmup Iteration   2: 10.192 ops/ms
# Warmup Iteration   3: 10.681 ops/ms
Iteration   1: 10.684 ops/ms
Iteration   2: 10.758 ops/ms
Iteration   3: 10.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.813 ±(99.9%) 2.972 ops/ms [Average]
  (min, avg, max) = (10.684, 10.813, 10.996), stdev = 0.163
  CI (99.9%): [7.841, 13.785] (assumes normal distribution)


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
# Warmup Iteration   1: 7.392 ops/ms
# Warmup Iteration   2: 10.057 ops/ms
# Warmup Iteration   3: 10.155 ops/ms
Iteration   1: 10.230 ops/ms
Iteration   2: 10.292 ops/ms
Iteration   3: 10.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.308 ±(99.9%) 1.591 ops/ms [Average]
  (min, avg, max) = (10.230, 10.308, 10.402), stdev = 0.087
  CI (99.9%): [8.717, 11.898] (assumes normal distribution)


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
# Warmup Iteration   1: 5.883 ops/ms
# Warmup Iteration   2: 8.225 ops/ms
# Warmup Iteration   3: 8.313 ops/ms
Iteration   1: 8.139 ops/ms
Iteration   2: 8.368 ops/ms
Iteration   3: 8.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.247 ±(99.9%) 2.102 ops/ms [Average]
  (min, avg, max) = (8.139, 8.247, 8.368), stdev = 0.115
  CI (99.9%): [6.145, 10.348] (assumes normal distribution)


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
# Warmup Iteration   1: 3.949 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.173 ±(99.9%) 0.011 ms/op
Iteration   1: 3.157 ±(99.9%) 0.003 ms/op
Iteration   2: 3.095 ±(99.9%) 0.004 ms/op
Iteration   3: 3.115 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.123 ±(99.9%) 0.578 ms/op [Average]
  (min, avg, max) = (3.095, 3.123, 3.157), stdev = 0.032
  CI (99.9%): [2.544, 3.701] (assumes normal distribution)


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
# Warmup Iteration   1: 3.945 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.004 ms/op
Iteration   1: 3.048 ±(99.9%) 0.003 ms/op
Iteration   2: 3.041 ±(99.9%) 0.004 ms/op
Iteration   3: 2.992 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.027 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (2.992, 3.027, 3.048), stdev = 0.030
  CI (99.9%): [2.473, 3.581] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.153 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.005 ms/op
Iteration   1: 3.126 ±(99.9%) 0.003 ms/op
Iteration   2: 3.105 ±(99.9%) 0.003 ms/op
Iteration   3: 3.032 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.088 ±(99.9%) 0.906 ms/op [Average]
  (min, avg, max) = (3.032, 3.088, 3.126), stdev = 0.050
  CI (99.9%): [2.182, 3.993] (assumes normal distribution)


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
# Warmup Iteration   1: 5.124 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.973 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.849 ±(99.9%) 0.045 ms/op
Iteration   1: 3.924 ±(99.9%) 0.046 ms/op
Iteration   2: 3.816 ±(99.9%) 0.011 ms/op
Iteration   3: 3.855 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.865 ±(99.9%) 0.989 ms/op [Average]
  (min, avg, max) = (3.816, 3.865, 3.924), stdev = 0.054
  CI (99.9%): [2.876, 4.854] (assumes normal distribution)


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
# Warmup Iteration   1: 4.003 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.007 ms/op
Iteration   1: 3.132 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  8.065 ms/op
                 createUser·p0.9999: 19.523 ms/op
                 createUser·p1.00:   19.956 ms/op

Iteration   2: 3.138 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.511 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.991 ms/op
                 createUser·p0.999:  12.551 ms/op
                 createUser·p0.9999: 20.179 ms/op
                 createUser·p1.00:   20.414 ms/op

Iteration   3: 3.097 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.463 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  10.821 ms/op
                 createUser·p0.9999: 14.876 ms/op
                 createUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307650
  mean =      3.122 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17472 
    [ 2.500,  5.000) = 287576 
    [ 5.000,  7.500) = 1952 
    [ 7.500, 10.000) = 269 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.463 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =     11.294 ms/op
     p(99.9900) =     19.464 ms/op
     p(99.9990) =     20.377 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 4.076 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.880 ±(99.9%) 0.008 ms/op
Iteration   1: 2.908 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.646 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  7.709 ms/op
                 existUser·p0.9999: 15.106 ms/op
                 existUser·p1.00:   16.548 ms/op

Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.629 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.422 ms/op
                 existUser·p0.999:  6.875 ms/op
                 existUser·p0.9999: 21.321 ms/op
                 existUser·p1.00:   21.758 ms/op

Iteration   3: 2.998 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.719 ms/op
                 existUser·p0.999:  10.689 ms/op
                 existUser·p0.9999: 23.735 ms/op
                 existUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323463
  mean =      2.967 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32925 
    [ 2.500,  5.000) = 288618 
    [ 5.000,  7.500) = 1593 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      7.557 ms/op
     p(99.9900) =     21.255 ms/op
     p(99.9990) =     24.339 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 4.168 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.006 ms/op
Iteration   1: 3.119 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.539 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  12.730 ms/op
                 getUser·p0.9999: 21.553 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   2: 3.164 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.507 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  8.893 ms/op
                 getUser·p0.9999: 23.323 ms/op
                 getUser·p1.00:   24.642 ms/op

Iteration   3: 3.137 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  10.455 ms/op
                 getUser·p0.9999: 22.913 ms/op
                 getUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305755
  mean =      3.140 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14452 
    [ 2.500,  5.000) = 289175 
    [ 5.000,  7.500) = 1550 
    [ 7.500, 10.000) = 191 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =     11.788 ms/op
     p(99.9900) =     22.820 ms/op
     p(99.9990) =     24.166 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 5.366 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.010 ms/op
Iteration   1: 3.919 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  12.589 ms/op
                 listUser·p0.9999: 23.391 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   2: 3.878 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  12.634 ms/op
                 listUser·p0.9999: 24.683 ms/op
                 listUser·p1.00:   27.558 ms/op

Iteration   3: 3.931 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  15.461 ms/op
                 listUser·p0.9999: 19.029 ms/op
                 listUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245419
  mean =      3.909 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4080 
    [ 2.500,  5.000) = 223554 
    [ 5.000,  7.500) = 16377 
    [ 7.500, 10.000) = 844 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     22.965 ms/op
     p(99.9990) =     25.154 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.370 ± 0.882  ops/ms
ClientGrpc.existUser                       thrpt       3  10.813 ± 2.972  ops/ms
ClientGrpc.getUser                         thrpt       3  10.308 ± 1.591  ops/ms
ClientGrpc.listUser                        thrpt       3   8.247 ± 2.102  ops/ms
ClientGrpc.createUser                       avgt       3   3.123 ± 0.578   ms/op
ClientGrpc.existUser                        avgt       3   3.027 ± 0.554   ms/op
ClientGrpc.getUser                          avgt       3   3.088 ± 0.906   ms/op
ClientGrpc.listUser                         avgt       3   3.865 ± 0.989   ms/op
ClientGrpc.createUser                     sample  307650   3.122 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.463           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.920           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.833           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.294           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.464           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.414           ms/op
ClientGrpc.existUser                      sample  323463   2.967 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.623           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.571           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.557           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.255           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.478           ms/op
ClientGrpc.getUser                        sample  305755   3.140 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.507           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.105           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.895           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.788           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.820           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.642           ms/op
ClientGrpc.listUser                       sample  245419   3.909 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.871           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.555           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.599           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.965           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.558           ms/op
