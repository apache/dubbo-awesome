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
# Warmup Iteration   1: 4.636 ops/ms
# Warmup Iteration   2: 8.912 ops/ms
# Warmup Iteration   3: 10.244 ops/ms
Iteration   1: 10.454 ops/ms
Iteration   2: 10.215 ops/ms
Iteration   3: 10.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.292 ±(99.9%) 2.560 ops/ms [Average]
  (min, avg, max) = (10.206, 10.292, 10.454), stdev = 0.140
  CI (99.9%): [7.731, 12.852] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.784 ops/ms
# Warmup Iteration   2: 10.884 ops/ms
# Warmup Iteration   3: 10.798 ops/ms
Iteration   1: 11.059 ops/ms
Iteration   2: 10.732 ops/ms
Iteration   3: 10.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.864 ±(99.9%) 3.139 ops/ms [Average]
  (min, avg, max) = (10.732, 10.864, 11.059), stdev = 0.172
  CI (99.9%): [7.725, 14.003] (assumes normal distribution)


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
# Warmup Iteration   1: 8.381 ops/ms
# Warmup Iteration   2: 10.447 ops/ms
# Warmup Iteration   3: 10.361 ops/ms
Iteration   1: 10.523 ops/ms
Iteration   2: 10.239 ops/ms
Iteration   3: 10.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.353 ±(99.9%) 2.742 ops/ms [Average]
  (min, avg, max) = (10.239, 10.353, 10.523), stdev = 0.150
  CI (99.9%): [7.610, 13.095] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.987 ops/ms
# Warmup Iteration   2: 7.602 ops/ms
# Warmup Iteration   3: 8.065 ops/ms
Iteration   1: 7.959 ops/ms
Iteration   2: 7.962 ops/ms
Iteration   3: 7.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.900 ±(99.9%) 1.916 ops/ms [Average]
  (min, avg, max) = (7.779, 7.900, 7.962), stdev = 0.105
  CI (99.9%): [5.983, 9.816] (assumes normal distribution)


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
# Warmup Iteration   1: 3.871 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.002 ms/op
Iteration   1: 3.061 ±(99.9%) 0.003 ms/op
Iteration   2: 3.185 ±(99.9%) 0.002 ms/op
Iteration   3: 3.132 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.126 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (3.061, 3.126, 3.185), stdev = 0.062
  CI (99.9%): [1.991, 4.261] (assumes normal distribution)


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
# Warmup Iteration   1: 3.706 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.003 ms/op
Iteration   1: 2.973 ±(99.9%) 0.002 ms/op
Iteration   2: 2.993 ±(99.9%) 0.002 ms/op
Iteration   3: 2.985 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.984 ±(99.9%) 0.185 ms/op [Average]
  (min, avg, max) = (2.973, 2.984, 2.993), stdev = 0.010
  CI (99.9%): [2.798, 3.169] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.089 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.002 ms/op
Iteration   1: 3.100 ±(99.9%) 0.002 ms/op
Iteration   2: 3.121 ±(99.9%) 0.002 ms/op
Iteration   3: 3.069 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.097 ±(99.9%) 0.485 ms/op [Average]
  (min, avg, max) = (3.069, 3.097, 3.121), stdev = 0.027
  CI (99.9%): [2.612, 3.582] (assumes normal distribution)


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
# Warmup Iteration   1: 4.714 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.197 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.122 ±(99.9%) 0.013 ms/op
Iteration   1: 4.099 ±(99.9%) 0.021 ms/op
Iteration   2: 3.933 ±(99.9%) 0.030 ms/op
Iteration   3: 4.129 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.054 ±(99.9%) 1.933 ms/op [Average]
  (min, avg, max) = (3.933, 4.054, 4.129), stdev = 0.106
  CI (99.9%): [2.120, 5.987] (assumes normal distribution)


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
# Warmup Iteration   1: 4.060 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.007 ms/op
Iteration   1: 3.145 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.757 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  6.880 ms/op
                 createUser·p0.9999: 27.159 ms/op
                 createUser·p1.00:   27.492 ms/op

Iteration   2: 3.230 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.925 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  8.618 ms/op
                 createUser·p0.9999: 16.174 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   3: 3.220 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  9.661 ms/op
                 createUser·p0.9999: 23.757 ms/op
                 createUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300243
  mean =      3.198 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15851 
    [ 2.500,  5.000) = 283310 
    [ 5.000,  7.500) = 708 
    [ 7.500, 10.000) = 118 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.075 ms/op
     p(99.9900) =     26.771 ms/op
     p(99.9990) =     27.394 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 3.893 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
Iteration   1: 3.059 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  5.742 ms/op
                 existUser·p0.9999: 12.955 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.602 ms/op
                 existUser·p0.9999: 14.976 ms/op
                 existUser·p1.00:   15.303 ms/op

Iteration   3: 2.896 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  8.015 ms/op
                 existUser·p0.9999: 26.014 ms/op
                 existUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321805
  mean =      2.986 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41709 
    [ 2.500,  5.000) = 279173 
    [ 5.000,  7.500) = 655 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.112 ms/op
     p(99.9900) =     23.143 ms/op
     p(99.9990) =     26.619 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 4.031 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.007 ms/op
Iteration   1: 3.076 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.514 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.551 ms/op
                 getUser·p0.9999: 20.158 ms/op
                 getUser·p1.00:   20.972 ms/op

Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.675 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  8.151 ms/op
                 getUser·p0.9999: 20.167 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   3: 3.092 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.635 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.965 ms/op
                 getUser·p0.9999: 22.435 ms/op
                 getUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313036
  mean =      3.066 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20097 
    [ 2.500,  5.000) = 291889 
    [ 5.000,  7.500) = 781 
    [ 7.500, 10.000) = 77 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.241 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     22.831 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 4.588 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.012 ms/op
Iteration   1: 4.154 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   5.810 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 19.628 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   2: 4.002 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.006 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  14.762 ms/op
                 listUser·p0.9999: 16.450 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   3: 4.047 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.838 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  15.799 ms/op
                 listUser·p0.9999: 22.118 ms/op
                 listUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236212
  mean =      4.067 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2970 
    [ 2.500,  5.000) = 202090 
    [ 5.000,  7.500) = 29753 
    [ 7.500, 10.000) = 987 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     14.808 ms/op
     p(99.9900) =     21.455 ms/op
     p(99.9990) =     22.410 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.292 ± 2.560  ops/ms
ClientGrpc.existUser                       thrpt       3  10.864 ± 3.139  ops/ms
ClientGrpc.getUser                         thrpt       3  10.353 ± 2.742  ops/ms
ClientGrpc.listUser                        thrpt       3   7.900 ± 1.916  ops/ms
ClientGrpc.createUser                       avgt       3   3.126 ± 1.135   ms/op
ClientGrpc.existUser                        avgt       3   2.984 ± 0.185   ms/op
ClientGrpc.getUser                          avgt       3   3.097 ± 0.485   ms/op
ClientGrpc.listUser                         avgt       3   4.054 ± 1.933   ms/op
ClientGrpc.createUser                     sample  300243   3.198 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.706           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.154           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.875           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.039           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.075           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.771           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.492           ms/op
ClientGrpc.existUser                      sample  321805   2.986 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.621           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.970           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.813           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.112           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.143           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.197           ms/op
ClientGrpc.getUser                        sample  313036   3.066 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.514           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.241           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.561           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.970           ms/op
ClientGrpc.listUser                       sample  236212   4.067 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.838           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.202           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.808           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.455           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.512           ms/op
