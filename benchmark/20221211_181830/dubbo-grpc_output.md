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
# Warmup Iteration   1: 4.525 ops/ms
# Warmup Iteration   2: 9.566 ops/ms
# Warmup Iteration   3: 10.249 ops/ms
Iteration   1: 10.409 ops/ms
Iteration   2: 10.035 ops/ms
Iteration   3: 10.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.293 ±(99.9%) 4.086 ops/ms [Average]
  (min, avg, max) = (10.035, 10.293, 10.435), stdev = 0.224
  CI (99.9%): [6.207, 14.379] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.582 ops/ms
# Warmup Iteration   2: 10.518 ops/ms
# Warmup Iteration   3: 10.358 ops/ms
Iteration   1: 10.765 ops/ms
Iteration   2: 10.647 ops/ms
Iteration   3: 10.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.682 ±(99.9%) 1.318 ops/ms [Average]
  (min, avg, max) = (10.635, 10.682, 10.765), stdev = 0.072
  CI (99.9%): [9.364, 12.001] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.768 ops/ms
# Warmup Iteration   2: 10.315 ops/ms
# Warmup Iteration   3: 10.326 ops/ms
Iteration   1: 10.281 ops/ms
Iteration   2: 10.384 ops/ms
Iteration   3: 10.517 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.394 ±(99.9%) 2.158 ops/ms [Average]
  (min, avg, max) = (10.281, 10.394, 10.517), stdev = 0.118
  CI (99.9%): [8.236, 12.551] (assumes normal distribution)


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
# Warmup Iteration   1: 5.418 ops/ms
# Warmup Iteration   2: 7.803 ops/ms
# Warmup Iteration   3: 7.752 ops/ms
Iteration   1: 8.057 ops/ms
Iteration   2: 8.078 ops/ms
Iteration   3: 7.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.986 ±(99.9%) 2.578 ops/ms [Average]
  (min, avg, max) = (7.823, 7.986, 8.078), stdev = 0.141
  CI (99.9%): [5.409, 10.564] (assumes normal distribution)


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
# Warmup Iteration   1: 4.213 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.002 ms/op
Iteration   1: 3.155 ±(99.9%) 0.002 ms/op
Iteration   2: 3.094 ±(99.9%) 0.002 ms/op
Iteration   3: 3.124 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.125 ±(99.9%) 0.558 ms/op [Average]
  (min, avg, max) = (3.094, 3.125, 3.155), stdev = 0.031
  CI (99.9%): [2.566, 3.683] (assumes normal distribution)


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
# Warmup Iteration   1: 3.809 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.003 ms/op
Iteration   1: 3.044 ±(99.9%) 0.002 ms/op
Iteration   2: 3.033 ±(99.9%) 0.002 ms/op
Iteration   3: 3.007 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.028 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (3.007, 3.028, 3.044), stdev = 0.019
  CI (99.9%): [2.677, 3.378] (assumes normal distribution)


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
# Warmup Iteration   1: 3.918 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.004 ms/op
Iteration   1: 3.181 ±(99.9%) 0.003 ms/op
Iteration   2: 3.173 ±(99.9%) 0.002 ms/op
Iteration   3: 2.998 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.117 ±(99.9%) 1.888 ms/op [Average]
  (min, avg, max) = (2.998, 3.117, 3.181), stdev = 0.104
  CI (99.9%): [1.229, 5.006] (assumes normal distribution)


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
# Warmup Iteration   1: 4.481 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 4.237 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.024 ms/op
Iteration   1: 4.056 ±(99.9%) 0.063 ms/op
Iteration   2: 3.901 ±(99.9%) 0.006 ms/op
Iteration   3: 3.932 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.963 ±(99.9%) 1.493 ms/op [Average]
  (min, avg, max) = (3.901, 3.963, 4.056), stdev = 0.082
  CI (99.9%): [2.470, 5.456] (assumes normal distribution)


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
# Warmup Iteration   1: 4.200 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.006 ms/op
Iteration   1: 3.164 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  7.527 ms/op
                 createUser·p0.9999: 13.231 ms/op
                 createUser·p1.00:   13.582 ms/op

Iteration   2: 3.170 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  7.848 ms/op
                 createUser·p0.9999: 22.249 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  11.790 ms/op
                 createUser·p0.9999: 14.736 ms/op
                 createUser·p1.00:   15.598 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305015
  mean =      3.147 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24697 
    [ 2.500,  5.000) = 278864 
    [ 5.000,  7.500) = 1048 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      8.045 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     22.412 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 3.787 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
Iteration   1: 3.083 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.974 ms/op
                 existUser·p0.9999: 20.487 ms/op
                 existUser·p1.00:   20.906 ms/op

Iteration   2: 2.992 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.350 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.783 ms/op
                 existUser·p0.9999: 12.871 ms/op
                 existUser·p1.00:   13.222 ms/op

Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.542 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.585 ms/op
                 existUser·p0.9999: 13.472 ms/op
                 existUser·p1.00:   13.697 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317888
  mean =      3.021 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37316 
    [ 2.500,  5.000) = 279602 
    [ 5.000,  7.500) = 726 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.350 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.791 ms/op
     p(99.9900) =     19.262 ms/op
     p(99.9990) =     20.835 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.007 ms/op
Iteration   1: 3.096 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.876 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.347 ms/op
                 getUser·p0.9999: 11.693 ms/op
                 getUser·p1.00:   11.944 ms/op

Iteration   2: 3.147 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.299 ms/op
                 getUser·p0.9999: 12.758 ms/op
                 getUser·p1.00:   12.943 ms/op

Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.673 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.323 ms/op
                 getUser·p0.999:  8.236 ms/op
                 getUser·p0.9999: 18.514 ms/op
                 getUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308754
  mean =      3.108 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1192 
    [ 1.250,  2.500) = 19764 
    [ 2.500,  3.750) = 260053 
    [ 3.750,  5.000) = 26663 
    [ 5.000,  6.250) = 528 
    [ 6.250,  7.500) = 236 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.337 ms/op
     p(99.9000) =      7.637 ms/op
     p(99.9900) =     17.326 ms/op
     p(99.9990) =     18.612 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 5.291 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.830 ±(99.9%) 0.009 ms/op
Iteration   1: 3.831 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  12.396 ms/op
                 listUser·p0.9999: 18.240 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   2: 3.946 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.402 ms/op
                 listUser·p0.9999: 19.628 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   3: 3.991 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  18.673 ms/op
                 listUser·p0.9999: 25.297 ms/op
                 listUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244674
  mean =      3.921 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4672 
    [ 2.500,  5.000) = 216034 
    [ 5.000,  7.500) = 22733 
    [ 7.500, 10.000) = 679 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     14.341 ms/op
     p(99.9900) =     23.790 ms/op
     p(99.9990) =     25.413 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.293 ± 4.086  ops/ms
ClientGrpc.existUser                       thrpt       3  10.682 ± 1.318  ops/ms
ClientGrpc.getUser                         thrpt       3  10.394 ± 2.158  ops/ms
ClientGrpc.listUser                        thrpt       3   7.986 ± 2.578  ops/ms
ClientGrpc.createUser                       avgt       3   3.125 ± 0.558   ms/op
ClientGrpc.existUser                        avgt       3   3.028 ± 0.351   ms/op
ClientGrpc.getUser                          avgt       3   3.117 ± 1.888   ms/op
ClientGrpc.listUser                         avgt       3   3.963 ± 1.493   ms/op
ClientGrpc.createUser                     sample  305015   3.147 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.737           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.129           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.022           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.045           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.791           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.446           ms/op
ClientGrpc.existUser                      sample  317888   3.021 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.350           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.015           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.875           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.791           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.262           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.906           ms/op
ClientGrpc.getUser                        sample  308754   3.108 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.673           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.920           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.337           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.637           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.326           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.678           ms/op
ClientGrpc.listUser                       sample  244674   3.921 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.835           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.816           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.341           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.790           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.625           ms/op
