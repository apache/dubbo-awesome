# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.582 ops/ms
# Warmup Iteration   2: 9.265 ops/ms
# Warmup Iteration   3: 10.161 ops/ms
Iteration   1: 11.049 ops/ms
Iteration   2: 10.686 ops/ms
Iteration   3: 10.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.874 ±(99.9%) 3.319 ops/ms [Average]
  (min, avg, max) = (10.686, 10.874, 11.049), stdev = 0.182
  CI (99.9%): [7.555, 14.193] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.482 ops/ms
# Warmup Iteration   2: 10.795 ops/ms
# Warmup Iteration   3: 11.225 ops/ms
Iteration   1: 11.223 ops/ms
Iteration   2: 11.404 ops/ms
Iteration   3: 11.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.306 ±(99.9%) 1.663 ops/ms [Average]
  (min, avg, max) = (11.223, 11.306, 11.404), stdev = 0.091
  CI (99.9%): [9.642, 12.969] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.661 ops/ms
# Warmup Iteration   2: 10.292 ops/ms
# Warmup Iteration   3: 10.853 ops/ms
Iteration   1: 10.867 ops/ms
Iteration   2: 11.079 ops/ms
Iteration   3: 10.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.902 ±(99.9%) 2.967 ops/ms [Average]
  (min, avg, max) = (10.759, 10.902, 11.079), stdev = 0.163
  CI (99.9%): [7.935, 13.869] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.782 ops/ms
# Warmup Iteration   2: 8.561 ops/ms
# Warmup Iteration   3: 8.228 ops/ms
Iteration   1: 8.361 ops/ms
Iteration   2: 8.443 ops/ms
Iteration   3: 8.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.405 ±(99.9%) 0.761 ops/ms [Average]
  (min, avg, max) = (8.361, 8.405, 8.443), stdev = 0.042
  CI (99.9%): [7.643, 9.166] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.900 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.003 ms/op
Iteration   1: 2.975 ±(99.9%) 0.002 ms/op
Iteration   2: 2.964 ±(99.9%) 0.002 ms/op
Iteration   3: 2.976 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.972 ±(99.9%) 0.113 ms/op [Average]
  (min, avg, max) = (2.964, 2.972, 2.976), stdev = 0.006
  CI (99.9%): [2.859, 3.085] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.796 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 2.910 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.886 ±(99.9%) 0.003 ms/op
Iteration   1: 2.869 ±(99.9%) 0.002 ms/op
Iteration   2: 2.892 ±(99.9%) 0.004 ms/op
Iteration   3: 2.761 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.841 ±(99.9%) 1.279 ms/op [Average]
  (min, avg, max) = (2.761, 2.841, 2.892), stdev = 0.070
  CI (99.9%): [1.562, 4.120] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.871 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.003 ms/op
Iteration   1: 2.946 ±(99.9%) 0.003 ms/op
Iteration   2: 2.943 ±(99.9%) 0.002 ms/op
Iteration   3: 2.946 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.945 ±(99.9%) 0.028 ms/op [Average]
  (min, avg, max) = (2.943, 2.945, 2.946), stdev = 0.002
  CI (99.9%): [2.916, 2.973] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.281 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.845 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.665 ±(99.9%) 0.025 ms/op
Iteration   1: 3.805 ±(99.9%) 0.031 ms/op
Iteration   2: 3.738 ±(99.9%) 0.008 ms/op
Iteration   3: 3.804 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.782 ±(99.9%) 0.700 ms/op [Average]
  (min, avg, max) = (3.738, 3.782, 3.805), stdev = 0.038
  CI (99.9%): [3.082, 4.482] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.052 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.007 ms/op
Iteration   1: 2.965 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  7.291 ms/op
                 createUser·p0.9999: 17.216 ms/op
                 createUser·p1.00:   17.531 ms/op

Iteration   2: 2.966 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.642 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  7.364 ms/op
                 createUser·p0.9999: 26.771 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   3: 2.992 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.530 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  9.146 ms/op
                 createUser·p0.9999: 24.924 ms/op
                 createUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322908
  mean =      2.975 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36658 
    [ 2.500,  5.000) = 285167 
    [ 5.000,  7.500) = 697 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.258 ms/op
     p(99.9900) =     25.845 ms/op
     p(99.9990) =     26.993 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.761 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.914 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.005 ms/op
Iteration   1: 2.855 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.577 ms/op
                 existUser·p0.9999: 10.876 ms/op
                 existUser·p1.00:   11.256 ms/op

Iteration   2: 2.811 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  5.865 ms/op
                 existUser·p0.9999: 12.603 ms/op
                 existUser·p1.00:   12.993 ms/op

Iteration   3: 2.860 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.563 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  8.064 ms/op
                 existUser·p0.9999: 14.019 ms/op
                 existUser·p1.00:   14.418 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337615
  mean =      2.842 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4671 
    [ 1.250,  2.500) = 46476 
    [ 2.500,  3.750) = 276792 
    [ 3.750,  5.000) = 8864 
    [ 5.000,  6.250) = 424 
    [ 6.250,  7.500) = 130 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      6.532 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     14.311 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.467 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.903 ±(99.9%) 0.006 ms/op
Iteration   1: 2.949 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.476 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.103 ms/op
                 getUser·p0.9999: 12.045 ms/op
                 getUser·p1.00:   12.222 ms/op

Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.465 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.758 ms/op
                 getUser·p0.9999: 20.010 ms/op
                 getUser·p1.00:   20.906 ms/op

Iteration   3: 2.991 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.568 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.136 ms/op
                 getUser·p0.9999: 15.242 ms/op
                 getUser·p1.00:   15.565 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322266
  mean =      2.978 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23668 
    [ 2.500,  5.000) = 297255 
    [ 5.000,  7.500) = 1078 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.127 ms/op
     p(99.9900) =     18.352 ms/op
     p(99.9990) =     20.636 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 3.900 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.751 ±(99.9%) 0.011 ms/op
Iteration   1: 3.782 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.483 ms/op
                 listUser·p0.999:  13.852 ms/op
                 listUser·p0.9999: 26.217 ms/op
                 listUser·p1.00:   26.804 ms/op

Iteration   2: 3.728 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.737 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  13.802 ms/op
                 listUser·p0.9999: 23.077 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   3: 3.806 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  20.603 ms/op
                 listUser·p0.9999: 24.333 ms/op
                 listUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 254590
  mean =      3.772 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8034 
    [ 2.500,  5.000) = 227541 
    [ 5.000,  7.500) = 18091 
    [ 7.500, 10.000) = 420 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     15.778 ms/op
     p(99.9900) =     25.660 ms/op
     p(99.9990) =     26.682 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.874 ± 3.319  ops/ms
ClientGrpc.existUser                       thrpt       3  11.306 ± 1.663  ops/ms
ClientGrpc.getUser                         thrpt       3  10.902 ± 2.967  ops/ms
ClientGrpc.listUser                        thrpt       3   8.405 ± 0.761  ops/ms
ClientGrpc.createUser                       avgt       3   2.972 ± 0.113   ms/op
ClientGrpc.existUser                        avgt       3   2.841 ± 1.279   ms/op
ClientGrpc.getUser                          avgt       3   2.945 ± 0.028   ms/op
ClientGrpc.listUser                         avgt       3   3.782 ± 0.700   ms/op
ClientGrpc.createUser                     sample  322908   2.975 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.530           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.258           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.845           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.034           ms/op
ClientGrpc.existUser                      sample  337615   2.842 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.558           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.532           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.713           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.418           ms/op
ClientGrpc.getUser                        sample  322266   2.978 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.465           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.441           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.127           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.352           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.906           ms/op
ClientGrpc.listUser                       sample  254590   3.772 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.737           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.637           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.661           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.472           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.778           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.660           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.804           ms/op
