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
# Warmup Iteration   1: 4.289 ops/ms
# Warmup Iteration   2: 8.768 ops/ms
# Warmup Iteration   3: 10.074 ops/ms
Iteration   1: 10.252 ops/ms
Iteration   2: 10.409 ops/ms
Iteration   3: 10.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.294 ±(99.9%) 1.849 ops/ms [Average]
  (min, avg, max) = (10.220, 10.294, 10.409), stdev = 0.101
  CI (99.9%): [8.445, 12.142] (assumes normal distribution)


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
# Warmup Iteration   1: 8.756 ops/ms
# Warmup Iteration   2: 10.459 ops/ms
# Warmup Iteration   3: 10.660 ops/ms
Iteration   1: 10.779 ops/ms
Iteration   2: 10.946 ops/ms
Iteration   3: 11.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.913 ±(99.9%) 2.194 ops/ms [Average]
  (min, avg, max) = (10.779, 10.913, 11.012), stdev = 0.120
  CI (99.9%): [8.719, 13.106] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.190 ops/ms
# Warmup Iteration   2: 9.968 ops/ms
# Warmup Iteration   3: 10.296 ops/ms
Iteration   1: 10.540 ops/ms
Iteration   2: 10.436 ops/ms
Iteration   3: 10.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.441 ±(99.9%) 1.755 ops/ms [Average]
  (min, avg, max) = (10.348, 10.441, 10.540), stdev = 0.096
  CI (99.9%): [8.686, 12.197] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.498 ops/ms
# Warmup Iteration   2: 8.102 ops/ms
# Warmup Iteration   3: 8.239 ops/ms
Iteration   1: 8.036 ops/ms
Iteration   2: 8.382 ops/ms
Iteration   3: 8.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.218 ±(99.9%) 3.166 ops/ms [Average]
  (min, avg, max) = (8.036, 8.218, 8.382), stdev = 0.174
  CI (99.9%): [5.052, 11.384] (assumes normal distribution)


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.003 ms/op
Iteration   1: 3.125 ±(99.9%) 0.002 ms/op
Iteration   2: 3.093 ±(99.9%) 0.002 ms/op
Iteration   3: 3.113 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.110 ±(99.9%) 0.290 ms/op [Average]
  (min, avg, max) = (3.093, 3.110, 3.125), stdev = 0.016
  CI (99.9%): [2.821, 3.400] (assumes normal distribution)


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
# Warmup Iteration   1: 3.912 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.003 ms/op
Iteration   1: 3.029 ±(99.9%) 0.002 ms/op
Iteration   2: 2.943 ±(99.9%) 0.003 ms/op
Iteration   3: 3.028 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.000 ±(99.9%) 0.905 ms/op [Average]
  (min, avg, max) = (2.943, 3.000, 3.029), stdev = 0.050
  CI (99.9%): [2.095, 3.905] (assumes normal distribution)


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
# Warmup Iteration   1: 4.202 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.001 ms/op
Iteration   1: 3.209 ±(99.9%) 0.002 ms/op
Iteration   2: 3.241 ±(99.9%) 0.002 ms/op
Iteration   3: 3.107 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.186 ±(99.9%) 1.278 ms/op [Average]
  (min, avg, max) = (3.107, 3.186, 3.241), stdev = 0.070
  CI (99.9%): [1.908, 4.464] (assumes normal distribution)


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
# Warmup Iteration   1: 5.113 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.866 ±(99.9%) 0.028 ms/op
Iteration   1: 3.857 ±(99.9%) 0.014 ms/op
Iteration   2: 3.833 ±(99.9%) 0.007 ms/op
Iteration   3: 3.857 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.849 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (3.833, 3.849, 3.857), stdev = 0.014
  CI (99.9%): [3.592, 4.106] (assumes normal distribution)


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
# Warmup Iteration   1: 4.106 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.005 ms/op
Iteration   1: 3.199 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  11.518 ms/op
                 createUser·p0.9999: 16.009 ms/op
                 createUser·p1.00:   18.973 ms/op

Iteration   2: 3.094 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.119 ms/op
                 createUser·p0.9999: 12.485 ms/op
                 createUser·p1.00:   12.730 ms/op

Iteration   3: 3.091 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.562 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  14.270 ms/op
                 createUser·p0.9999: 26.400 ms/op
                 createUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306777
  mean =      3.127 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11118 
    [ 2.500,  5.000) = 294001 
    [ 5.000,  7.500) = 925 
    [ 7.500, 10.000) = 302 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =     11.354 ms/op
     p(99.9900) =     25.777 ms/op
     p(99.9990) =     26.804 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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
# Warmup Iteration   1: 4.029 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.006 ms/op
Iteration   1: 3.098 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.833 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  6.193 ms/op
                 existUser·p0.9999: 15.270 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   2: 3.085 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  7.448 ms/op
                 existUser·p0.9999: 13.301 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   3: 3.068 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  9.118 ms/op
                 existUser·p0.9999: 16.220 ms/op
                 existUser·p1.00:   16.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311287
  mean =      3.083 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1239 
    [ 1.250,  2.500) = 17061 
    [ 2.500,  3.750) = 267651 
    [ 3.750,  5.000) = 23618 
    [ 5.000,  6.250) = 892 
    [ 6.250,  7.500) = 423 
    [ 7.500,  8.750) = 154 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      8.067 ms/op
     p(99.9900) =     15.741 ms/op
     p(99.9990) =     16.462 ms/op
     p(99.9999) =     16.531 ms/op
    p(100.0000) =     16.531 ms/op


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
# Warmup Iteration   1: 4.157 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.007 ms/op
Iteration   1: 3.221 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.650 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.480 ms/op
                 getUser·p0.999:  9.050 ms/op
                 getUser·p0.9999: 16.567 ms/op
                 getUser·p1.00:   16.876 ms/op

Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.554 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.522 ms/op
                 getUser·p0.9999: 15.477 ms/op
                 getUser·p1.00:   17.203 ms/op

Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  8.750 ms/op
                 getUser·p0.9999: 22.020 ms/op
                 getUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305548
  mean =      3.142 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13043 
    [ 2.500,  5.000) = 290863 
    [ 5.000,  7.500) = 1180 
    [ 7.500, 10.000) = 270 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.543 ms/op
     p(99.9900) =     20.972 ms/op
     p(99.9990) =     23.263 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 4.673 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.009 ms/op
Iteration   1: 3.886 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  11.626 ms/op
                 listUser·p0.9999: 14.685 ms/op
                 listUser·p1.00:   15.008 ms/op

Iteration   2: 3.900 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  12.861 ms/op
                 listUser·p0.9999: 21.121 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   3: 3.832 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   6.414 ms/op
                 listUser·p0.999:  14.148 ms/op
                 listUser·p0.9999: 18.317 ms/op
                 listUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247880
  mean =      3.872 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3274 
    [ 2.500,  5.000) = 229920 
    [ 5.000,  7.500) = 13698 
    [ 7.500, 10.000) = 545 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     12.945 ms/op
     p(99.9900) =     17.971 ms/op
     p(99.9990) =     22.972 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.294 ± 1.849  ops/ms
ClientGrpc.existUser                       thrpt       3  10.913 ± 2.194  ops/ms
ClientGrpc.getUser                         thrpt       3  10.441 ± 1.755  ops/ms
ClientGrpc.listUser                        thrpt       3   8.218 ± 3.166  ops/ms
ClientGrpc.createUser                       avgt       3   3.110 ± 0.290   ms/op
ClientGrpc.existUser                        avgt       3   3.000 ± 0.905   ms/op
ClientGrpc.getUser                          avgt       3   3.186 ± 1.278   ms/op
ClientGrpc.listUser                         avgt       3   3.849 ± 0.257   ms/op
ClientGrpc.createUser                     sample  306777   3.127 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.562           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.354           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.777           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.837           ms/op
ClientGrpc.existUser                      sample  311287   3.083 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.736           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.047           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.875           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.067           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.741           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.531           ms/op
ClientGrpc.getUser                        sample  305548   3.142 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.554           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.932           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.543           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.972           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.396           ms/op
ClientGrpc.listUser                       sample  247880   3.872 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.862           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.334           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.529           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.945           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.971           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.364           ms/op
