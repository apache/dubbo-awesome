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
# Warmup Iteration   1: 5.215 ops/ms
# Warmup Iteration   2: 9.703 ops/ms
# Warmup Iteration   3: 10.355 ops/ms
Iteration   1: 10.493 ops/ms
Iteration   2: 10.604 ops/ms
Iteration   3: 10.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.486 ±(99.9%) 2.227 ops/ms [Average]
  (min, avg, max) = (10.360, 10.486, 10.604), stdev = 0.122
  CI (99.9%): [8.259, 12.712] (assumes normal distribution)


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
# Warmup Iteration   1: 8.524 ops/ms
# Warmup Iteration   2: 10.832 ops/ms
# Warmup Iteration   3: 11.117 ops/ms
Iteration   1: 10.956 ops/ms
Iteration   2: 11.027 ops/ms
Iteration   3: 11.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.011 ±(99.9%) 0.891 ops/ms [Average]
  (min, avg, max) = (10.956, 11.011, 11.050), stdev = 0.049
  CI (99.9%): [10.120, 11.902] (assumes normal distribution)


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
# Warmup Iteration   1: 7.805 ops/ms
# Warmup Iteration   2: 10.537 ops/ms
# Warmup Iteration   3: 10.388 ops/ms
Iteration   1: 10.564 ops/ms
Iteration   2: 10.257 ops/ms
Iteration   3: 10.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.428 ±(99.9%) 2.850 ops/ms [Average]
  (min, avg, max) = (10.257, 10.428, 10.564), stdev = 0.156
  CI (99.9%): [7.578, 13.277] (assumes normal distribution)


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
# Warmup Iteration   1: 5.921 ops/ms
# Warmup Iteration   2: 7.991 ops/ms
# Warmup Iteration   3: 7.810 ops/ms
Iteration   1: 8.337 ops/ms
Iteration   2: 8.223 ops/ms
Iteration   3: 8.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.254 ±(99.9%) 1.323 ops/ms [Average]
  (min, avg, max) = (8.203, 8.254, 8.337), stdev = 0.073
  CI (99.9%): [6.931, 9.577] (assumes normal distribution)


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
# Warmup Iteration   1: 4.005 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.002 ms/op
Iteration   1: 3.058 ±(99.9%) 0.003 ms/op
Iteration   2: 3.059 ±(99.9%) 0.002 ms/op
Iteration   3: 3.042 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.053 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (3.042, 3.053, 3.059), stdev = 0.010
  CI (99.9%): [2.876, 3.230] (assumes normal distribution)


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
# Warmup Iteration   1: 3.495 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.885 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.858 ±(99.9%) 0.003 ms/op
Iteration   1: 2.943 ±(99.9%) 0.003 ms/op
Iteration   2: 2.964 ±(99.9%) 0.002 ms/op
Iteration   3: 2.859 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.922 ±(99.9%) 1.011 ms/op [Average]
  (min, avg, max) = (2.859, 2.922, 2.964), stdev = 0.055
  CI (99.9%): [1.911, 3.932] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.944 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.003 ms/op
Iteration   1: 2.974 ±(99.9%) 0.002 ms/op
Iteration   2: 3.043 ±(99.9%) 0.003 ms/op
Iteration   3: 3.010 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.009 ±(99.9%) 0.626 ms/op [Average]
  (min, avg, max) = (2.974, 3.009, 3.043), stdev = 0.034
  CI (99.9%): [2.383, 3.635] (assumes normal distribution)


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
# Warmup Iteration   1: 4.654 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.006 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.903 ±(99.9%) 0.036 ms/op
Iteration   1: 3.973 ±(99.9%) 0.022 ms/op
Iteration   2: 3.940 ±(99.9%) 0.023 ms/op
Iteration   3: 3.798 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.904 ±(99.9%) 1.695 ms/op [Average]
  (min, avg, max) = (3.798, 3.904, 3.973), stdev = 0.093
  CI (99.9%): [2.209, 5.598] (assumes normal distribution)


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
# Warmup Iteration   1: 4.109 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
Iteration   1: 3.108 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.648 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  8.078 ms/op
                 createUser·p0.9999: 16.714 ms/op
                 createUser·p1.00:   17.105 ms/op

Iteration   2: 3.031 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.759 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  6.459 ms/op
                 createUser·p0.9999: 12.279 ms/op
                 createUser·p1.00:   12.829 ms/op

Iteration   3: 3.137 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  13.944 ms/op
                 createUser·p0.9999: 20.736 ms/op
                 createUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310455
  mean =      3.091 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29324 
    [ 2.500,  5.000) = 280193 
    [ 5.000,  7.500) = 571 
    [ 7.500, 10.000) = 128 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      8.262 ms/op
     p(99.9900) =     19.920 ms/op
     p(99.9990) =     21.030 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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
# Warmup Iteration   1: 3.775 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.940 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.885 ±(99.9%) 0.006 ms/op
Iteration   1: 2.920 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.370 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  6.023 ms/op
                 existUser·p0.9999: 11.895 ms/op
                 existUser·p1.00:   12.206 ms/op

Iteration   2: 2.898 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.358 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.283 ms/op
                 existUser·p0.9999: 20.298 ms/op
                 existUser·p1.00:   20.939 ms/op

Iteration   3: 2.939 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.613 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  9.634 ms/op
                 existUser·p0.9999: 22.086 ms/op
                 existUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329125
  mean =      2.919 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58111 
    [ 2.500,  5.000) = 270087 
    [ 5.000,  7.500) = 618 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.358 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.283 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     22.469 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.006 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  9.159 ms/op
                 getUser·p0.9999: 15.137 ms/op
                 getUser·p1.00:   15.679 ms/op

Iteration   2: 2.972 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.496 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   4.014 ms/op
                 getUser·p0.999:  6.244 ms/op
                 getUser·p0.9999: 12.534 ms/op
                 getUser·p1.00:   12.698 ms/op

Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  5.497 ms/op
                 getUser·p0.9999: 26.310 ms/op
                 getUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318387
  mean =      3.014 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30751 
    [ 2.500,  5.000) = 286841 
    [ 5.000,  7.500) = 539 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      6.496 ms/op
     p(99.9900) =     25.471 ms/op
     p(99.9990) =     26.596 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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
# Warmup Iteration   1: 4.875 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.978 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.010 ms/op
Iteration   1: 3.935 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.929 ms/op
                 listUser·p0.9999: 17.859 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   2: 3.836 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  19.244 ms/op
                 listUser·p0.9999: 22.752 ms/op
                 listUser·p1.00:   25.690 ms/op

Iteration   3: 3.909 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.735 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 20.782 ms/op
                 listUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246707
  mean =      3.893 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4683 
    [ 2.500,  5.000) = 219948 
    [ 5.000,  7.500) = 21067 
    [ 7.500, 10.000) = 537 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     15.319 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     25.517 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.486 ± 2.227  ops/ms
ClientGrpc.existUser                       thrpt       3  11.011 ± 0.891  ops/ms
ClientGrpc.getUser                         thrpt       3  10.428 ± 2.850  ops/ms
ClientGrpc.listUser                        thrpt       3   8.254 ± 1.323  ops/ms
ClientGrpc.createUser                       avgt       3   3.053 ± 0.177   ms/op
ClientGrpc.existUser                        avgt       3   2.922 ± 1.011   ms/op
ClientGrpc.getUser                          avgt       3   3.009 ± 0.626   ms/op
ClientGrpc.listUser                         avgt       3   3.904 ± 1.695   ms/op
ClientGrpc.createUser                     sample  310455   3.091 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.648           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.262           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.920           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.922           ms/op
ClientGrpc.existUser                      sample  329125   2.919 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.358           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.772           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.283           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.627           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.807           ms/op
ClientGrpc.getUser                        sample  318387   3.014 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.496           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.496           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.471           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.739           ms/op
ClientGrpc.listUser                       sample  246707   3.893 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.735           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.595           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.319           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.053           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.690           ms/op
