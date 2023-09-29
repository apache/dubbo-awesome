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
# Warmup Iteration   1: 4.459 ops/ms
# Warmup Iteration   2: 8.859 ops/ms
# Warmup Iteration   3: 9.776 ops/ms
Iteration   1: 9.990 ops/ms
Iteration   2: 10.267 ops/ms
Iteration   3: 10.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.186 ±(99.9%) 3.114 ops/ms [Average]
  (min, avg, max) = (9.990, 10.186, 10.301), stdev = 0.171
  CI (99.9%): [7.072, 13.300] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.648 ops/ms
# Warmup Iteration   2: 10.128 ops/ms
# Warmup Iteration   3: 10.459 ops/ms
Iteration   1: 10.757 ops/ms
Iteration   2: 10.724 ops/ms
Iteration   3: 10.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.679 ±(99.9%) 1.957 ops/ms [Average]
  (min, avg, max) = (10.557, 10.679, 10.757), stdev = 0.107
  CI (99.9%): [8.722, 12.636] (assumes normal distribution)


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
# Warmup Iteration   1: 7.059 ops/ms
# Warmup Iteration   2: 9.847 ops/ms
# Warmup Iteration   3: 10.222 ops/ms
Iteration   1: 10.308 ops/ms
Iteration   2: 10.414 ops/ms
Iteration   3: 10.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.272 ±(99.9%) 2.957 ops/ms [Average]
  (min, avg, max) = (10.095, 10.272, 10.414), stdev = 0.162
  CI (99.9%): [7.316, 13.229] (assumes normal distribution)


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
# Warmup Iteration   1: 6.469 ops/ms
# Warmup Iteration   2: 7.984 ops/ms
# Warmup Iteration   3: 8.328 ops/ms
Iteration   1: 8.135 ops/ms
Iteration   2: 8.213 ops/ms
Iteration   3: 8.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.171 ±(99.9%) 0.715 ops/ms [Average]
  (min, avg, max) = (8.135, 8.171, 8.213), stdev = 0.039
  CI (99.9%): [7.456, 8.886] (assumes normal distribution)


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
# Warmup Iteration   1: 4.163 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.002 ms/op
Iteration   1: 3.141 ±(99.9%) 0.009 ms/op
Iteration   2: 3.101 ±(99.9%) 0.003 ms/op
Iteration   3: 3.109 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.117 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (3.101, 3.117, 3.141), stdev = 0.021
  CI (99.9%): [2.732, 3.502] (assumes normal distribution)


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
# Warmup Iteration   1: 4.061 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.002 ms/op
Iteration   1: 3.032 ±(99.9%) 0.001 ms/op
Iteration   2: 2.957 ±(99.9%) 0.002 ms/op
Iteration   3: 3.004 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.998 ±(99.9%) 0.696 ms/op [Average]
  (min, avg, max) = (2.957, 2.998, 3.032), stdev = 0.038
  CI (99.9%): [2.301, 3.694] (assumes normal distribution)


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
# Warmup Iteration   1: 4.048 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.002 ms/op
Iteration   1: 3.131 ±(99.9%) 0.002 ms/op
Iteration   2: 3.114 ±(99.9%) 0.002 ms/op
Iteration   3: 3.143 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.129 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (3.114, 3.129, 3.143), stdev = 0.015
  CI (99.9%): [2.860, 3.398] (assumes normal distribution)


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
# Warmup Iteration   1: 4.885 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.053 ms/op
Iteration   1: 3.905 ±(99.9%) 0.028 ms/op
Iteration   2: 3.870 ±(99.9%) 0.010 ms/op
Iteration   3: 3.891 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.889 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (3.870, 3.889, 3.905), stdev = 0.017
  CI (99.9%): [3.575, 4.202] (assumes normal distribution)


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
# Warmup Iteration   1: 4.139 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.006 ms/op
Iteration   1: 3.146 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  7.602 ms/op
                 createUser·p0.9999: 19.137 ms/op
                 createUser·p1.00:   19.628 ms/op

Iteration   2: 3.154 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.477 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  10.011 ms/op
                 createUser·p0.9999: 22.011 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   3: 3.158 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.588 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.671 ms/op
                 createUser·p0.999:  8.871 ms/op
                 createUser·p0.9999: 21.717 ms/op
                 createUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304207
  mean =      3.153 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5406 
    [ 2.500,  5.000) = 296987 
    [ 5.000,  7.500) = 1302 
    [ 7.500, 10.000) = 229 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      9.398 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     22.346 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 3.940 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.006 ms/op
Iteration   1: 2.985 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  7.846 ms/op
                 existUser·p0.9999: 17.179 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  11.804 ms/op
                 existUser·p0.9999: 13.304 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   3: 3.007 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  8.962 ms/op
                 existUser·p0.9999: 14.326 ms/op
                 existUser·p1.00:   14.565 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318182
  mean =      3.017 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 495 
    [ 1.250,  2.500) = 17668 
    [ 2.500,  3.750) = 288208 
    [ 3.750,  5.000) = 10187 
    [ 5.000,  6.250) = 862 
    [ 6.250,  7.500) = 271 
    [ 7.500,  8.750) = 138 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     14.516 ms/op
     p(99.9990) =     17.459 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 4.192 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.007 ms/op
Iteration   1: 3.172 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  8.638 ms/op
                 getUser·p0.9999: 14.596 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   2: 3.177 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.694 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  11.213 ms/op
                 getUser·p0.9999: 15.677 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   3: 3.135 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.563 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  6.841 ms/op
                 getUser·p0.9999: 18.186 ms/op
                 getUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303415
  mean =      3.161 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 423 
    [ 1.250,  2.500) = 7258 
    [ 2.500,  3.750) = 269797 
    [ 3.750,  5.000) = 24359 
    [ 5.000,  6.250) = 891 
    [ 6.250,  7.500) = 290 
    [ 7.500,  8.750) = 116 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 104 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      8.496 ms/op
     p(99.9900) =     17.703 ms/op
     p(99.9990) =     18.382 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 4.894 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.010 ms/op
Iteration   1: 3.937 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.501 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  12.587 ms/op
                 listUser·p0.9999: 15.118 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   2: 3.856 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.679 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   6.534 ms/op
                 listUser·p0.999:  12.927 ms/op
                 listUser·p0.9999: 14.508 ms/op
                 listUser·p1.00:   16.056 ms/op

Iteration   3: 3.871 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  13.654 ms/op
                 listUser·p0.9999: 18.562 ms/op
                 listUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246967
  mean =      3.888 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2465 
    [ 2.500,  5.000) = 231126 
    [ 5.000,  7.500) = 12470 
    [ 7.500, 10.000) = 371 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     13.042 ms/op
     p(99.9900) =     17.518 ms/op
     p(99.9990) =     22.364 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.186 ± 3.114  ops/ms
ClientGrpc.existUser                       thrpt       3  10.679 ± 1.957  ops/ms
ClientGrpc.getUser                         thrpt       3  10.272 ± 2.957  ops/ms
ClientGrpc.listUser                        thrpt       3   8.171 ± 0.715  ops/ms
ClientGrpc.createUser                       avgt       3   3.117 ± 0.385   ms/op
ClientGrpc.existUser                        avgt       3   2.998 ± 0.696   ms/op
ClientGrpc.getUser                          avgt       3   3.129 ± 0.269   ms/op
ClientGrpc.listUser                         avgt       3   3.889 ± 0.314   ms/op
ClientGrpc.createUser                     sample  304207   3.153 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.477           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.398           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.561           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.446           ms/op
ClientGrpc.existUser                      sample  318182   3.017 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.678           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.974           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.678           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.110           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.516           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.564           ms/op
ClientGrpc.getUser                        sample  303415   3.161 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.563           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.117           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.496           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.703           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.514           ms/op
ClientGrpc.listUser                       sample  246967   3.888 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.893           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.350           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.042           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.518           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.593           ms/op
