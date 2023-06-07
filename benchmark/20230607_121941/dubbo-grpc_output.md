# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.529 ops/ms
# Warmup Iteration   2: 8.641 ops/ms
# Warmup Iteration   3: 10.080 ops/ms
Iteration   1: 10.633 ops/ms
Iteration   2: 10.681 ops/ms
Iteration   3: 10.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.573 ±(99.9%) 2.684 ops/ms [Average]
  (min, avg, max) = (10.406, 10.573, 10.681), stdev = 0.147
  CI (99.9%): [7.889, 13.258] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.709 ops/ms
# Warmup Iteration   2: 10.913 ops/ms
# Warmup Iteration   3: 11.171 ops/ms
Iteration   1: 11.050 ops/ms
Iteration   2: 11.337 ops/ms
Iteration   3: 11.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.152 ±(99.9%) 2.935 ops/ms [Average]
  (min, avg, max) = (11.050, 11.152, 11.337), stdev = 0.161
  CI (99.9%): [8.217, 14.087] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.364 ops/ms
# Warmup Iteration   2: 10.111 ops/ms
# Warmup Iteration   3: 10.536 ops/ms
Iteration   1: 10.670 ops/ms
Iteration   2: 10.731 ops/ms
Iteration   3: 10.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.711 ±(99.9%) 0.657 ops/ms [Average]
  (min, avg, max) = (10.670, 10.711, 10.733), stdev = 0.036
  CI (99.9%): [10.054, 11.369] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.983 ops/ms
# Warmup Iteration   2: 7.794 ops/ms
# Warmup Iteration   3: 8.128 ops/ms
Iteration   1: 8.226 ops/ms
Iteration   2: 8.147 ops/ms
Iteration   3: 8.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.167 ±(99.9%) 0.934 ops/ms [Average]
  (min, avg, max) = (8.129, 8.167, 8.226), stdev = 0.051
  CI (99.9%): [7.233, 9.101] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.201 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.003 ms/op
Iteration   1: 3.005 ±(99.9%) 0.004 ms/op
Iteration   2: 3.056 ±(99.9%) 0.003 ms/op
Iteration   3: 3.013 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.025 ±(99.9%) 0.500 ms/op [Average]
  (min, avg, max) = (3.005, 3.025, 3.056), stdev = 0.027
  CI (99.9%): [2.525, 3.525] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.867 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.003 ms/op
Iteration   1: 2.887 ±(99.9%) 0.004 ms/op
Iteration   2: 2.929 ±(99.9%) 0.004 ms/op
Iteration   3: 2.949 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.922 ±(99.9%) 0.572 ms/op [Average]
  (min, avg, max) = (2.887, 2.922, 2.949), stdev = 0.031
  CI (99.9%): [2.350, 3.493] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.037 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.003 ms/op
Iteration   1: 3.020 ±(99.9%) 0.002 ms/op
Iteration   2: 2.991 ±(99.9%) 0.004 ms/op
Iteration   3: 2.999 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.003 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (2.991, 3.003, 3.020), stdev = 0.015
  CI (99.9%): [2.729, 3.278] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.091 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.017 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.034 ms/op
Iteration   1: 3.835 ±(99.9%) 0.017 ms/op
Iteration   2: 3.717 ±(99.9%) 0.007 ms/op
Iteration   3: 3.923 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.825 ±(99.9%) 1.889 ms/op [Average]
  (min, avg, max) = (3.717, 3.825, 3.923), stdev = 0.104
  CI (99.9%): [1.936, 5.714] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.323 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
Iteration   1: 3.014 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.584 ms/op
                 createUser·p0.9999: 11.269 ms/op
                 createUser·p1.00:   11.583 ms/op

Iteration   2: 2.984 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.601 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  7.059 ms/op
                 createUser·p0.9999: 12.960 ms/op
                 createUser·p1.00:   13.173 ms/op

Iteration   3: 3.009 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  10.256 ms/op
                 createUser·p0.9999: 22.983 ms/op
                 createUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319720
  mean =      3.002 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28723 
    [ 2.500,  5.000) = 289543 
    [ 5.000,  7.500) = 1129 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.564 ms/op
     p(99.9900) =     22.185 ms/op
     p(99.9990) =     23.298 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.856 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.945 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.881 ±(99.9%) 0.006 ms/op
Iteration   1: 2.922 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  6.871 ms/op
                 existUser·p0.9999: 11.486 ms/op
                 existUser·p1.00:   11.813 ms/op

Iteration   2: 2.891 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  5.884 ms/op
                 existUser·p0.9999: 16.207 ms/op
                 existUser·p1.00:   16.581 ms/op

Iteration   3: 2.881 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  7.734 ms/op
                 existUser·p0.9999: 21.787 ms/op
                 existUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331206
  mean =      2.898 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41040 
    [ 2.500,  5.000) = 289235 
    [ 5.000,  7.500) = 686 
    [ 7.500, 10.000) = 78 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      6.884 ms/op
     p(99.9900) =     16.579 ms/op
     p(99.9990) =     22.010 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.008 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.007 ms/op
Iteration   1: 2.999 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.663 ms/op
                 getUser·p0.999:  8.903 ms/op
                 getUser·p0.9999: 13.763 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   2: 2.980 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.447 ms/op
                 getUser·p0.9999: 21.365 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.721 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  6.611 ms/op
                 getUser·p0.9999: 15.579 ms/op
                 getUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321103
  mean =      2.989 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29982 
    [ 2.500,  5.000) = 289923 
    [ 5.000,  7.500) = 922 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.011 ms/op
     p(99.9900) =     20.303 ms/op
     p(99.9990) =     21.548 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.833 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.978 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.871 ±(99.9%) 0.010 ms/op
Iteration   1: 3.958 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  12.916 ms/op
                 listUser·p0.9999: 20.021 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   2: 3.852 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.579 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  14.746 ms/op
                 listUser·p0.9999: 22.970 ms/op
                 listUser·p1.00:   24.805 ms/op

Iteration   3: 3.881 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  15.863 ms/op
                 listUser·p0.9999: 19.965 ms/op
                 listUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246260
  mean =      3.896 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4002 
    [ 2.500,  5.000) = 221381 
    [ 5.000,  7.500) = 19402 
    [ 7.500, 10.000) = 983 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     14.807 ms/op
     p(99.9900) =     22.524 ms/op
     p(99.9990) =     24.523 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.573 ± 2.684  ops/ms
ClientGrpc.existUser                       thrpt       3  11.152 ± 2.935  ops/ms
ClientGrpc.getUser                         thrpt       3  10.711 ± 0.657  ops/ms
ClientGrpc.listUser                        thrpt       3   8.167 ± 0.934  ops/ms
ClientGrpc.createUser                       avgt       3   3.025 ± 0.500   ms/op
ClientGrpc.existUser                        avgt       3   2.922 ± 0.572   ms/op
ClientGrpc.getUser                          avgt       3   3.003 ± 0.274   ms/op
ClientGrpc.listUser                         avgt       3   3.825 ± 1.889   ms/op
ClientGrpc.createUser                     sample  319720   3.002 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.601           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.564           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.185           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.364           ms/op
ClientGrpc.existUser                      sample  331206   2.898 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.715           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.884           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.579           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.184           ms/op
ClientGrpc.getUser                        sample  321103   2.989 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.721           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.011           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.303           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.627           ms/op
ClientGrpc.listUser                       sample  246260   3.896 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.579           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.807           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.524           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.805           ms/op
