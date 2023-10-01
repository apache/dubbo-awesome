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
# Warmup Iteration   1: 4.120 ops/ms
# Warmup Iteration   2: 8.452 ops/ms
# Warmup Iteration   3: 9.603 ops/ms
Iteration   1: 10.101 ops/ms
Iteration   2: 10.158 ops/ms
Iteration   3: 10.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.108 ±(99.9%) 0.837 ops/ms [Average]
  (min, avg, max) = (10.067, 10.108, 10.158), stdev = 0.046
  CI (99.9%): [9.271, 10.946] (assumes normal distribution)


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
# Warmup Iteration   1: 6.723 ops/ms
# Warmup Iteration   2: 10.204 ops/ms
# Warmup Iteration   3: 10.549 ops/ms
Iteration   1: 10.417 ops/ms
Iteration   2: 10.614 ops/ms
Iteration   3: 10.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.527 ±(99.9%) 1.827 ops/ms [Average]
  (min, avg, max) = (10.417, 10.527, 10.614), stdev = 0.100
  CI (99.9%): [8.700, 12.354] (assumes normal distribution)


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
# Warmup Iteration   1: 6.618 ops/ms
# Warmup Iteration   2: 9.685 ops/ms
# Warmup Iteration   3: 10.044 ops/ms
Iteration   1: 10.329 ops/ms
Iteration   2: 10.023 ops/ms
Iteration   3: 9.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.074 ±(99.9%) 4.262 ops/ms [Average]
  (min, avg, max) = (9.870, 10.074, 10.329), stdev = 0.234
  CI (99.9%): [5.812, 14.336] (assumes normal distribution)


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
# Warmup Iteration   1: 6.211 ops/ms
# Warmup Iteration   2: 7.662 ops/ms
# Warmup Iteration   3: 7.714 ops/ms
Iteration   1: 7.771 ops/ms
Iteration   2: 7.893 ops/ms
Iteration   3: 7.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.812 ±(99.9%) 1.280 ops/ms [Average]
  (min, avg, max) = (7.771, 7.812, 7.893), stdev = 0.070
  CI (99.9%): [6.532, 9.092] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.474 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.003 ms/op
Iteration   1: 3.249 ±(99.9%) 0.001 ms/op
Iteration   2: 3.185 ±(99.9%) 0.001 ms/op
Iteration   3: 3.143 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.192 ±(99.9%) 0.970 ms/op [Average]
  (min, avg, max) = (3.143, 3.192, 3.249), stdev = 0.053
  CI (99.9%): [2.222, 4.163] (assumes normal distribution)


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
# Warmup Iteration   1: 3.896 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.001 ms/op
Iteration   1: 3.098 ±(99.9%) 0.001 ms/op
Iteration   2: 3.091 ±(99.9%) 0.001 ms/op
Iteration   3: 3.032 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.074 ±(99.9%) 0.658 ms/op [Average]
  (min, avg, max) = (3.032, 3.074, 3.098), stdev = 0.036
  CI (99.9%): [2.416, 3.732] (assumes normal distribution)


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
# Warmup Iteration   1: 4.130 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.002 ms/op
Iteration   1: 3.140 ±(99.9%) 0.004 ms/op
Iteration   2: 3.182 ±(99.9%) 0.002 ms/op
Iteration   3: 3.186 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.169 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (3.140, 3.169, 3.186), stdev = 0.026
  CI (99.9%): [2.701, 3.638] (assumes normal distribution)


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
# Warmup Iteration   1: 5.804 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.037 ms/op
Iteration   1: 4.097 ±(99.9%) 0.016 ms/op
Iteration   2: 4.019 ±(99.9%) 0.025 ms/op
Iteration   3: 3.912 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.009 ±(99.9%) 1.699 ms/op [Average]
  (min, avg, max) = (3.912, 4.009, 4.097), stdev = 0.093
  CI (99.9%): [2.311, 5.708] (assumes normal distribution)


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
# Warmup Iteration   1: 4.221 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.007 ms/op
Iteration   1: 3.187 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.385 ms/op
                 createUser·p0.999:  8.133 ms/op
                 createUser·p0.9999: 22.805 ms/op
                 createUser·p1.00:   23.560 ms/op

Iteration   2: 3.199 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.788 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  9.766 ms/op
                 createUser·p0.9999: 17.697 ms/op
                 createUser·p1.00:   18.940 ms/op

Iteration   3: 3.158 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.675 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.850 ms/op
                 createUser·p0.999:  14.933 ms/op
                 createUser·p0.9999: 20.177 ms/op
                 createUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301792
  mean =      3.181 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7795 
    [ 2.500,  5.000) = 291880 
    [ 5.000,  7.500) = 1641 
    [ 7.500, 10.000) = 193 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      9.329 ms/op
     p(99.9900) =     21.916 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 4.218 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
Iteration   1: 3.040 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.775 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.037 ms/op
                 existUser·p0.9999: 12.008 ms/op
                 existUser·p1.00:   12.354 ms/op

Iteration   2: 2.984 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  8.667 ms/op
                 existUser·p0.9999: 21.991 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   3: 3.057 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  8.618 ms/op
                 existUser·p0.9999: 16.926 ms/op
                 existUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317151
  mean =      3.026 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18210 
    [ 2.500,  5.000) = 297424 
    [ 5.000,  7.500) = 1057 
    [ 7.500, 10.000) = 265 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      8.379 ms/op
     p(99.9900) =     20.728 ms/op
     p(99.9990) =     22.233 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 4.447 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.267 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.007 ms/op
Iteration   1: 3.181 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.483 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  12.778 ms/op
                 getUser·p0.9999: 21.856 ms/op
                 getUser·p1.00:   22.151 ms/op

Iteration   2: 3.209 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  8.838 ms/op
                 getUser·p0.9999: 26.969 ms/op
                 getUser·p1.00:   28.180 ms/op

Iteration   3: 3.202 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.626 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.243 ms/op
                 getUser·p0.9999: 26.083 ms/op
                 getUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300262
  mean =      3.197 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5901 
    [ 2.500,  5.000) = 292499 
    [ 5.000,  7.500) = 1289 
    [ 7.500, 10.000) = 274 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      9.986 ms/op
     p(99.9900) =     26.180 ms/op
     p(99.9990) =     28.082 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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
# Warmup Iteration   1: 5.504 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.398 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.128 ±(99.9%) 0.010 ms/op
Iteration   1: 4.064 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.962 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  13.582 ms/op
                 listUser·p0.9999: 14.912 ms/op
                 listUser·p1.00:   15.188 ms/op

Iteration   2: 4.060 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.866 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  14.769 ms/op
                 listUser·p0.9999: 16.261 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   3: 4.057 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.002 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  16.356 ms/op
                 listUser·p0.9999: 18.518 ms/op
                 listUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236307
  mean =      4.060 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1390 
    [ 2.500,  3.750) = 66637 
    [ 3.750,  5.000) = 153006 
    [ 5.000,  6.250) = 8973 
    [ 6.250,  7.500) = 5082 
    [ 7.500,  8.750) = 651 
    [ 8.750, 10.000) = 124 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 118 
    [15.000, 16.250) = 78 
    [16.250, 17.500) = 50 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     14.331 ms/op
     p(99.9900) =     17.727 ms/op
     p(99.9990) =     18.884 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.108 ± 0.837  ops/ms
ClientGrpc.existUser                       thrpt       3  10.527 ± 1.827  ops/ms
ClientGrpc.getUser                         thrpt       3  10.074 ± 4.262  ops/ms
ClientGrpc.listUser                        thrpt       3   7.812 ± 1.280  ops/ms
ClientGrpc.createUser                       avgt       3   3.192 ± 0.970   ms/op
ClientGrpc.existUser                        avgt       3   3.074 ± 0.658   ms/op
ClientGrpc.getUser                          avgt       3   3.169 ± 0.468   ms/op
ClientGrpc.listUser                         avgt       3   4.009 ± 1.699   ms/op
ClientGrpc.createUser                     sample  301792   3.181 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.675           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.944           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.678           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.329           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.916           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.560           ms/op
ClientGrpc.existUser                      sample  317151   3.026 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.674           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.379           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.728           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.348           ms/op
ClientGrpc.getUser                        sample  300262   3.197 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.483           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.133           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.977           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.986           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.180           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.180           ms/op
ClientGrpc.listUser                       sample  236307   4.060 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.002           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.969           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.341           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.331           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.727           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.071           ms/op
