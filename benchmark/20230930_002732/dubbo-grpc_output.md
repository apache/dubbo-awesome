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
# Warmup Iteration   1: 4.331 ops/ms
# Warmup Iteration   2: 8.748 ops/ms
# Warmup Iteration   3: 9.943 ops/ms
Iteration   1: 10.166 ops/ms
Iteration   2: 10.322 ops/ms
Iteration   3: 10.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.275 ±(99.9%) 1.724 ops/ms [Average]
  (min, avg, max) = (10.166, 10.275, 10.336), stdev = 0.094
  CI (99.9%): [8.551, 11.998] (assumes normal distribution)


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
# Warmup Iteration   1: 7.530 ops/ms
# Warmup Iteration   2: 10.380 ops/ms
# Warmup Iteration   3: 10.611 ops/ms
Iteration   1: 10.724 ops/ms
Iteration   2: 10.836 ops/ms
Iteration   3: 10.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.698 ±(99.9%) 2.798 ops/ms [Average]
  (min, avg, max) = (10.533, 10.698, 10.836), stdev = 0.153
  CI (99.9%): [7.900, 13.495] (assumes normal distribution)


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
# Warmup Iteration   1: 6.807 ops/ms
# Warmup Iteration   2: 9.992 ops/ms
# Warmup Iteration   3: 9.907 ops/ms
Iteration   1: 10.306 ops/ms
Iteration   2: 10.496 ops/ms
Iteration   3: 10.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.396 ±(99.9%) 1.742 ops/ms [Average]
  (min, avg, max) = (10.306, 10.396, 10.496), stdev = 0.096
  CI (99.9%): [8.654, 12.138] (assumes normal distribution)


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
# Warmup Iteration   1: 5.959 ops/ms
# Warmup Iteration   2: 7.968 ops/ms
# Warmup Iteration   3: 8.196 ops/ms
Iteration   1: 8.259 ops/ms
Iteration   2: 8.308 ops/ms
Iteration   3: 8.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.229 ±(99.9%) 1.765 ops/ms [Average]
  (min, avg, max) = (8.121, 8.229, 8.308), stdev = 0.097
  CI (99.9%): [6.464, 9.994] (assumes normal distribution)


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.003 ms/op
Iteration   1: 3.083 ±(99.9%) 0.006 ms/op
Iteration   2: 3.139 ±(99.9%) 0.002 ms/op
Iteration   3: 3.173 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.132 ±(99.9%) 0.830 ms/op [Average]
  (min, avg, max) = (3.083, 3.132, 3.173), stdev = 0.045
  CI (99.9%): [2.302, 3.962] (assumes normal distribution)


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.938 ±(99.9%) 0.005 ms/op
Iteration   1: 2.927 ±(99.9%) 0.003 ms/op
Iteration   2: 3.068 ±(99.9%) 0.002 ms/op
Iteration   3: 2.946 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.980 ±(99.9%) 1.401 ms/op [Average]
  (min, avg, max) = (2.927, 2.980, 3.068), stdev = 0.077
  CI (99.9%): [1.579, 4.381] (assumes normal distribution)


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.002 ms/op
Iteration   1: 3.133 ±(99.9%) 0.002 ms/op
Iteration   2: 3.106 ±(99.9%) 0.002 ms/op
Iteration   3: 3.145 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.128 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (3.106, 3.128, 3.145), stdev = 0.020
  CI (99.9%): [2.766, 3.491] (assumes normal distribution)


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
# Warmup Iteration   1: 5.007 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 3.883 ±(99.9%) 0.028 ms/op
Iteration   1: 3.881 ±(99.9%) 0.017 ms/op
Iteration   2: 3.872 ±(99.9%) 0.028 ms/op
Iteration   3: 3.798 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.850 ±(99.9%) 0.827 ms/op [Average]
  (min, avg, max) = (3.798, 3.850, 3.881), stdev = 0.045
  CI (99.9%): [3.023, 4.678] (assumes normal distribution)


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
# Warmup Iteration   1: 4.140 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.007 ms/op
Iteration   1: 3.091 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.426 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  9.306 ms/op
                 createUser·p0.9999: 12.073 ms/op
                 createUser·p1.00:   12.321 ms/op

Iteration   2: 3.113 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.762 ms/op
                 createUser·p0.999:  6.908 ms/op
                 createUser·p0.9999: 15.413 ms/op
                 createUser·p1.00:   15.909 ms/op

Iteration   3: 3.078 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  11.304 ms/op
                 createUser·p0.9999: 15.483 ms/op
                 createUser·p1.00:   15.794 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310458
  mean =      3.094 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 850 
    [ 1.250,  2.500) = 12830 
    [ 2.500,  3.750) = 276658 
    [ 3.750,  5.000) = 17979 
    [ 5.000,  6.250) = 1201 
    [ 6.250,  7.500) = 376 
    [ 7.500,  8.750) = 155 
    [ 8.750, 10.000) = 119 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      9.652 ms/op
     p(99.9900) =     15.268 ms/op
     p(99.9990) =     15.824 ms/op
     p(99.9999) =     15.909 ms/op
    p(100.0000) =     15.909 ms/op


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
# Warmup Iteration   1: 3.890 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.968 ±(99.9%) 0.006 ms/op
Iteration   1: 2.970 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.808 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  8.129 ms/op
                 existUser·p0.9999: 11.169 ms/op
                 existUser·p1.00:   11.436 ms/op

Iteration   2: 2.998 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.544 ms/op
                 existUser·p0.999:  10.224 ms/op
                 existUser·p0.9999: 13.926 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   3: 3.028 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.334 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  7.717 ms/op
                 existUser·p0.9999: 25.489 ms/op
                 existUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320143
  mean =      2.998 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26817 
    [ 2.500,  5.000) = 291381 
    [ 5.000,  7.500) = 1471 
    [ 7.500, 10.000) = 273 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.334 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      8.256 ms/op
     p(99.9900) =     22.456 ms/op
     p(99.9990) =     25.847 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 3.976 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.006 ms/op
Iteration   1: 3.092 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.716 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  7.377 ms/op
                 getUser·p0.9999: 12.774 ms/op
                 getUser·p1.00:   13.074 ms/op

Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.757 ms/op
                 getUser·p0.9999: 13.246 ms/op
                 getUser·p1.00:   13.615 ms/op

Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  7.072 ms/op
                 getUser·p0.9999: 24.036 ms/op
                 getUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313300
  mean =      3.065 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17803 
    [ 2.500,  5.000) = 293440 
    [ 5.000,  7.500) = 1763 
    [ 7.500, 10.000) = 134 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      7.411 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     24.178 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 4.252 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.299 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.008 ms/op
Iteration   1: 3.928 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.704 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  11.709 ms/op
                 listUser·p0.9999: 13.836 ms/op
                 listUser·p1.00:   16.204 ms/op

Iteration   2: 3.908 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  13.866 ms/op
                 listUser·p0.9999: 18.168 ms/op
                 listUser·p1.00:   18.547 ms/op

Iteration   3: 3.937 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  15.414 ms/op
                 listUser·p0.9999: 24.081 ms/op
                 listUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244395
  mean =      3.924 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2091 
    [ 2.500,  5.000) = 225998 
    [ 5.000,  7.500) = 15084 
    [ 7.500, 10.000) = 754 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     13.330 ms/op
     p(99.9900) =     23.593 ms/op
     p(99.9990) =     24.973 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.275 ± 1.724  ops/ms
ClientGrpc.existUser                       thrpt       3  10.698 ± 2.798  ops/ms
ClientGrpc.getUser                         thrpt       3  10.396 ± 1.742  ops/ms
ClientGrpc.listUser                        thrpt       3   8.229 ± 1.765  ops/ms
ClientGrpc.createUser                       avgt       3   3.132 ± 0.830   ms/op
ClientGrpc.existUser                        avgt       3   2.980 ± 1.401   ms/op
ClientGrpc.getUser                          avgt       3   3.128 ± 0.362   ms/op
ClientGrpc.listUser                         avgt       3   3.850 ± 0.827   ms/op
ClientGrpc.createUser                     sample  310458   3.094 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.426           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.637           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.652           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.268           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          15.909           ms/op
ClientGrpc.existUser                      sample  320143   2.998 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.334           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.752           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.596           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.256           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.456           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.887           ms/op
ClientGrpc.getUser                        sample  313300   3.065 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.716           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.411           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.200           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.248           ms/op
ClientGrpc.listUser                       sample  244395   3.924 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.171           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.292           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.330           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.593           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.068           ms/op
