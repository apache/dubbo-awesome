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
# Warmup Iteration   1: 3.857 ops/ms
# Warmup Iteration   2: 8.009 ops/ms
# Warmup Iteration   3: 9.205 ops/ms
Iteration   1: 9.620 ops/ms
Iteration   2: 9.712 ops/ms
Iteration   3: 9.572 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.635 ±(99.9%) 1.298 ops/ms [Average]
  (min, avg, max) = (9.572, 9.635, 9.712), stdev = 0.071
  CI (99.9%): [8.337, 10.932] (assumes normal distribution)


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
# Warmup Iteration   1: 6.639 ops/ms
# Warmup Iteration   2: 9.813 ops/ms
# Warmup Iteration   3: 10.292 ops/ms
Iteration   1: 10.356 ops/ms
Iteration   2: 10.483 ops/ms
Iteration   3: 10.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.369 ±(99.9%) 1.960 ops/ms [Average]
  (min, avg, max) = (10.269, 10.369, 10.483), stdev = 0.107
  CI (99.9%): [8.409, 12.330] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.396 ops/ms
# Warmup Iteration   2: 9.804 ops/ms
# Warmup Iteration   3: 10.019 ops/ms
Iteration   1: 10.182 ops/ms
Iteration   2: 10.227 ops/ms
Iteration   3: 10.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.178 ±(99.9%) 0.937 ops/ms [Average]
  (min, avg, max) = (10.125, 10.178, 10.227), stdev = 0.051
  CI (99.9%): [9.241, 11.115] (assumes normal distribution)


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
# Warmup Iteration   1: 4.804 ops/ms
# Warmup Iteration   2: 7.664 ops/ms
# Warmup Iteration   3: 7.890 ops/ms
Iteration   1: 7.909 ops/ms
Iteration   2: 7.868 ops/ms
Iteration   3: 8.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.979 ±(99.9%) 2.898 ops/ms [Average]
  (min, avg, max) = (7.868, 7.979, 8.161), stdev = 0.159
  CI (99.9%): [5.081, 10.878] (assumes normal distribution)


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
# Warmup Iteration   1: 4.583 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.007 ms/op
Iteration   1: 3.176 ±(99.9%) 0.003 ms/op
Iteration   2: 3.154 ±(99.9%) 0.003 ms/op
Iteration   3: 3.187 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.172 ±(99.9%) 0.307 ms/op [Average]
  (min, avg, max) = (3.154, 3.172, 3.187), stdev = 0.017
  CI (99.9%): [2.865, 3.479] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.363 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.003 ms/op
Iteration   1: 2.959 ±(99.9%) 0.002 ms/op
Iteration   2: 3.053 ±(99.9%) 0.003 ms/op
Iteration   3: 2.980 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.998 ±(99.9%) 0.901 ms/op [Average]
  (min, avg, max) = (2.959, 2.998, 3.053), stdev = 0.049
  CI (99.9%): [2.097, 3.899] (assumes normal distribution)


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
# Warmup Iteration   1: 4.405 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.276 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.002 ms/op
Iteration   1: 3.195 ±(99.9%) 0.006 ms/op
Iteration   2: 3.116 ±(99.9%) 0.004 ms/op
Iteration   3: 3.170 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.160 ±(99.9%) 0.733 ms/op [Average]
  (min, avg, max) = (3.116, 3.160, 3.195), stdev = 0.040
  CI (99.9%): [2.427, 3.894] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.621 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.180 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.019 ms/op
Iteration   1: 4.034 ±(99.9%) 0.023 ms/op
Iteration   2: 4.025 ±(99.9%) 0.040 ms/op
Iteration   3: 4.079 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.046 ±(99.9%) 0.533 ms/op [Average]
  (min, avg, max) = (4.025, 4.046, 4.079), stdev = 0.029
  CI (99.9%): [3.513, 4.579] (assumes normal distribution)


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
# Warmup Iteration   1: 4.620 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.306 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.173 ±(99.9%) 0.007 ms/op
Iteration   1: 3.164 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  8.980 ms/op
                 createUser·p0.9999: 21.983 ms/op
                 createUser·p1.00:   22.675 ms/op

Iteration   2: 3.181 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  7.237 ms/op
                 createUser·p0.9999: 15.662 ms/op
                 createUser·p1.00:   16.564 ms/op

Iteration   3: 3.180 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  14.178 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302238
  mean =      3.175 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7672 
    [ 2.500,  5.000) = 293124 
    [ 5.000,  7.500) = 982 
    [ 7.500, 10.000) = 150 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =     11.742 ms/op
     p(99.9900) =     21.620 ms/op
     p(99.9990) =     22.477 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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
# Warmup Iteration   1: 4.183 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
Iteration   1: 2.977 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  7.804 ms/op
                 existUser·p0.9999: 13.923 ms/op
                 existUser·p1.00:   16.073 ms/op

Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  10.180 ms/op
                 existUser·p0.9999: 14.864 ms/op
                 existUser·p1.00:   16.089 ms/op

Iteration   3: 2.982 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  10.940 ms/op
                 existUser·p0.9999: 19.178 ms/op
                 existUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320653
  mean =      2.995 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26359 
    [ 2.500,  5.000) = 292482 
    [ 5.000,  7.500) = 1179 
    [ 7.500, 10.000) = 319 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      9.852 ms/op
     p(99.9900) =     17.752 ms/op
     p(99.9990) =     20.066 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.627 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.009 ms/op
Iteration   1: 3.230 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.639 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  12.322 ms/op
                 getUser·p0.9999: 26.519 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   2: 3.138 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.554 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  11.043 ms/op
                 getUser·p0.9999: 18.048 ms/op
                 getUser·p1.00:   19.038 ms/op

Iteration   3: 3.119 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  10.616 ms/op
                 getUser·p0.9999: 22.483 ms/op
                 getUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303780
  mean =      3.161 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10306 
    [ 2.500,  5.000) = 291270 
    [ 5.000,  7.500) = 1563 
    [ 7.500, 10.000) = 312 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =     11.010 ms/op
     p(99.9900) =     23.032 ms/op
     p(99.9990) =     26.966 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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
# Warmup Iteration   1: 5.685 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.302 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.012 ms/op
Iteration   1: 4.094 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  17.727 ms/op
                 listUser·p0.9999: 22.977 ms/op
                 listUser·p1.00:   23.101 ms/op

Iteration   2: 4.048 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  15.532 ms/op
                 listUser·p0.9999: 19.107 ms/op
                 listUser·p1.00:   19.562 ms/op

Iteration   3: 3.978 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.690 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  16.402 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237557
  mean =      4.039 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2264 
    [ 2.500,  5.000) = 217088 
    [ 5.000,  7.500) = 16679 
    [ 7.500, 10.000) = 947 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 199 
    [17.500, 20.000) = 158 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     16.956 ms/op
     p(99.9900) =     19.996 ms/op
     p(99.9990) =     23.069 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.635 ± 1.298  ops/ms
ClientGrpc.existUser                       thrpt       3  10.369 ± 1.960  ops/ms
ClientGrpc.getUser                         thrpt       3  10.178 ± 0.937  ops/ms
ClientGrpc.listUser                        thrpt       3   7.979 ± 2.898  ops/ms
ClientGrpc.createUser                       avgt       3   3.172 ± 0.307   ms/op
ClientGrpc.existUser                        avgt       3   2.998 ± 0.901   ms/op
ClientGrpc.getUser                          avgt       3   3.160 ± 0.733   ms/op
ClientGrpc.listUser                         avgt       3   4.046 ± 0.533   ms/op
ClientGrpc.createUser                     sample  302238   3.175 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.923           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.742           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.620           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.675           ms/op
ClientGrpc.existUser                      sample  320653   2.995 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.666           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.852           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.752           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.316           ms/op
ClientGrpc.getUser                        sample  303780   3.161 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.554           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.908           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.678           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.010           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.032           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.099           ms/op
ClientGrpc.listUser                       sample  237557   4.039 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.126           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.924           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.669           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.956           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.996           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.101           ms/op
