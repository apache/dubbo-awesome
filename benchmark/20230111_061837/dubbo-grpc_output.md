# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.860 ops/ms
# Warmup Iteration   2: 9.456 ops/ms
# Warmup Iteration   3: 10.451 ops/ms
Iteration   1: 10.563 ops/ms
Iteration   2: 10.371 ops/ms
Iteration   3: 10.235 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.390 ±(99.9%) 3.008 ops/ms [Average]
  (min, avg, max) = (10.235, 10.390, 10.563), stdev = 0.165
  CI (99.9%): [7.382, 13.398] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.935 ops/ms
# Warmup Iteration   2: 10.373 ops/ms
# Warmup Iteration   3: 10.459 ops/ms
Iteration   1: 10.493 ops/ms
Iteration   2: 10.473 ops/ms
Iteration   3: 10.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.571 ±(99.9%) 2.777 ops/ms [Average]
  (min, avg, max) = (10.473, 10.571, 10.746), stdev = 0.152
  CI (99.9%): [7.794, 13.348] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.379 ops/ms
# Warmup Iteration   2: 10.015 ops/ms
# Warmup Iteration   3: 10.335 ops/ms
Iteration   1: 10.280 ops/ms
Iteration   2: 10.524 ops/ms
Iteration   3: 10.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.386 ±(99.9%) 2.281 ops/ms [Average]
  (min, avg, max) = (10.280, 10.386, 10.524), stdev = 0.125
  CI (99.9%): [8.105, 12.667] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.312 ops/ms
# Warmup Iteration   2: 7.656 ops/ms
# Warmup Iteration   3: 8.055 ops/ms
Iteration   1: 8.148 ops/ms
Iteration   2: 7.787 ops/ms
Iteration   3: 8.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.032 ±(99.9%) 3.875 ops/ms [Average]
  (min, avg, max) = (7.787, 8.032, 8.161), stdev = 0.212
  CI (99.9%): [4.157, 11.907] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.910 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.002 ms/op
Iteration   1: 3.144 ±(99.9%) 0.001 ms/op
Iteration   2: 3.173 ±(99.9%) 0.002 ms/op
Iteration   3: 3.228 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.182 ±(99.9%) 0.781 ms/op [Average]
  (min, avg, max) = (3.144, 3.182, 3.228), stdev = 0.043
  CI (99.9%): [2.401, 3.962] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.889 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.003 ms/op
Iteration   1: 2.983 ±(99.9%) 0.002 ms/op
Iteration   2: 3.028 ±(99.9%) 0.002 ms/op
Iteration   3: 2.973 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.995 ±(99.9%) 0.536 ms/op [Average]
  (min, avg, max) = (2.973, 2.995, 3.028), stdev = 0.029
  CI (99.9%): [2.459, 3.531] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.888 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.002 ms/op
Iteration   1: 3.212 ±(99.9%) 0.002 ms/op
Iteration   2: 3.187 ±(99.9%) 0.002 ms/op
Iteration   3: 3.157 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.185 ±(99.9%) 0.498 ms/op [Average]
  (min, avg, max) = (3.157, 3.185, 3.212), stdev = 0.027
  CI (99.9%): [2.687, 3.684] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.571 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.201 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.018 ms/op
Iteration   1: 3.996 ±(99.9%) 0.010 ms/op
Iteration   2: 3.975 ±(99.9%) 0.033 ms/op
Iteration   3: 4.042 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.005 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (3.975, 4.005, 4.042), stdev = 0.034
  CI (99.9%): [3.382, 4.627] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.835 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
Iteration   1: 3.123 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  7.467 ms/op
                 createUser·p0.9999: 15.118 ms/op
                 createUser·p1.00:   17.269 ms/op

Iteration   2: 2.909 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.514 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  9.226 ms/op
                 createUser·p0.9999: 12.419 ms/op
                 createUser·p1.00:   12.698 ms/op

Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  8.471 ms/op
                 createUser·p0.9999: 15.148 ms/op
                 createUser·p1.00:   15.499 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316737
  mean =      3.031 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3588 
    [ 1.250,  2.500) = 31523 
    [ 2.500,  3.750) = 256520 
    [ 3.750,  5.000) = 24156 
    [ 5.000,  6.250) = 337 
    [ 6.250,  7.500) = 252 
    [ 7.500,  8.750) = 95 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.954 ms/op
     p(99.9900) =     15.013 ms/op
     p(99.9990) =     15.497 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.656 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
Iteration   1: 2.984 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.597 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  7.045 ms/op
                 existUser·p0.9999: 11.080 ms/op
                 existUser·p1.00:   11.338 ms/op

Iteration   2: 2.961 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.577 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  6.242 ms/op
                 existUser·p0.9999: 12.095 ms/op
                 existUser·p1.00:   12.616 ms/op

Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  5.998 ms/op
                 existUser·p0.9999: 16.922 ms/op
                 existUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320900
  mean =      2.990 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1428 
    [ 1.250,  2.500) = 43535 
    [ 2.500,  3.750) = 254073 
    [ 3.750,  5.000) = 21149 
    [ 5.000,  6.250) = 387 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =      6.333 ms/op
     p(99.9900) =     15.806 ms/op
     p(99.9990) =     17.652 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.863 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.007 ms/op
Iteration   1: 3.024 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.524 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  6.611 ms/op
                 getUser·p0.9999: 20.441 ms/op
                 getUser·p1.00:   20.840 ms/op

Iteration   2: 3.013 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.481 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.068 ms/op
                 getUser·p0.9999: 16.105 ms/op
                 getUser·p1.00:   16.204 ms/op

Iteration   3: 2.937 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.625 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.543 ms/op
                 getUser·p0.99:   4.100 ms/op
                 getUser·p0.999:  7.286 ms/op
                 getUser·p0.9999: 18.419 ms/op
                 getUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320984
  mean =      2.991 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28578 
    [ 2.500,  5.000) = 291197 
    [ 5.000,  7.500) = 941 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.004 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     20.735 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.657 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.049 ±(99.9%) 0.011 ms/op
Iteration   1: 4.076 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.476 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  12.585 ms/op
                 listUser·p0.9999: 19.119 ms/op
                 listUser·p1.00:   20.349 ms/op

Iteration   2: 4.007 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.812 ms/op
                 listUser·p0.9999: 24.216 ms/op
                 listUser·p1.00:   24.445 ms/op

Iteration   3: 3.981 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.419 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  15.118 ms/op
                 listUser·p0.9999: 26.165 ms/op
                 listUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238842
  mean =      4.021 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4625 
    [ 2.500,  5.000) = 200570 
    [ 5.000,  7.500) = 32179 
    [ 7.500, 10.000) = 1030 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.419 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     14.210 ms/op
     p(99.9900) =     23.560 ms/op
     p(99.9990) =     26.708 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.390 ± 3.008  ops/ms
ClientGrpc.existUser                       thrpt       3  10.571 ± 2.777  ops/ms
ClientGrpc.getUser                         thrpt       3  10.386 ± 2.281  ops/ms
ClientGrpc.listUser                        thrpt       3   8.032 ± 3.875  ops/ms
ClientGrpc.createUser                       avgt       3   3.182 ± 0.781   ms/op
ClientGrpc.existUser                        avgt       3   2.995 ± 0.536   ms/op
ClientGrpc.getUser                          avgt       3   3.185 ± 0.498   ms/op
ClientGrpc.listUser                         avgt       3   4.005 ± 0.622   ms/op
ClientGrpc.createUser                     sample  316737   3.031 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.514           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.954           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.013           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.269           ms/op
ClientGrpc.existUser                      sample  320900   2.990 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.577           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.970           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.830           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.333           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.806           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.826           ms/op
ClientGrpc.getUser                        sample  320984   2.991 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.481           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.004           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.514           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.840           ms/op
ClientGrpc.listUser                       sample  238842   4.021 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.419           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.210           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.560           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.804           ms/op
