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
# Warmup Iteration   1: 4.412 ops/ms
# Warmup Iteration   2: 8.926 ops/ms
# Warmup Iteration   3: 9.812 ops/ms
Iteration   1: 9.983 ops/ms
Iteration   2: 10.087 ops/ms
Iteration   3: 9.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.964 ±(99.9%) 2.450 ops/ms [Average]
  (min, avg, max) = (9.821, 9.964, 10.087), stdev = 0.134
  CI (99.9%): [7.514, 12.413] (assumes normal distribution)


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
# Warmup Iteration   1: 6.353 ops/ms
# Warmup Iteration   2: 9.992 ops/ms
# Warmup Iteration   3: 10.386 ops/ms
Iteration   1: 10.422 ops/ms
Iteration   2: 10.425 ops/ms
Iteration   3: 10.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.383 ±(99.9%) 1.283 ops/ms [Average]
  (min, avg, max) = (10.302, 10.383, 10.425), stdev = 0.070
  CI (99.9%): [9.100, 11.665] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.775 ops/ms
# Warmup Iteration   2: 9.743 ops/ms
# Warmup Iteration   3: 9.952 ops/ms
Iteration   1: 10.191 ops/ms
Iteration   2: 9.901 ops/ms
Iteration   3: 10.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.065 ±(99.9%) 2.711 ops/ms [Average]
  (min, avg, max) = (9.901, 10.065, 10.191), stdev = 0.149
  CI (99.9%): [7.354, 12.775] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.072 ops/ms
# Warmup Iteration   2: 7.093 ops/ms
# Warmup Iteration   3: 7.675 ops/ms
Iteration   1: 7.551 ops/ms
Iteration   2: 7.478 ops/ms
Iteration   3: 7.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.582 ±(99.9%) 2.213 ops/ms [Average]
  (min, avg, max) = (7.478, 7.582, 7.715), stdev = 0.121
  CI (99.9%): [5.368, 9.795] (assumes normal distribution)


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
# Warmup Iteration   1: 4.327 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.005 ms/op
Iteration   1: 3.193 ±(99.9%) 0.002 ms/op
Iteration   2: 3.240 ±(99.9%) 0.002 ms/op
Iteration   3: 3.142 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.192 ±(99.9%) 0.897 ms/op [Average]
  (min, avg, max) = (3.142, 3.192, 3.240), stdev = 0.049
  CI (99.9%): [2.295, 4.089] (assumes normal distribution)


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.003 ms/op
Iteration   1: 3.120 ±(99.9%) 0.002 ms/op
Iteration   2: 3.064 ±(99.9%) 0.003 ms/op
Iteration   3: 3.007 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.064 ±(99.9%) 1.035 ms/op [Average]
  (min, avg, max) = (3.007, 3.064, 3.120), stdev = 0.057
  CI (99.9%): [2.029, 4.098] (assumes normal distribution)


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
# Warmup Iteration   1: 4.498 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.002 ms/op
Iteration   1: 3.198 ±(99.9%) 0.002 ms/op
Iteration   2: 3.228 ±(99.9%) 0.002 ms/op
Iteration   3: 3.251 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.226 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (3.198, 3.226, 3.251), stdev = 0.027
  CI (99.9%): [2.742, 3.710] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.775 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.353 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.253 ±(99.9%) 0.012 ms/op
Iteration   1: 4.172 ±(99.9%) 0.015 ms/op
Iteration   2: 4.056 ±(99.9%) 0.010 ms/op
Iteration   3: 4.165 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.131 ±(99.9%) 1.182 ms/op [Average]
  (min, avg, max) = (4.056, 4.131, 4.172), stdev = 0.065
  CI (99.9%): [2.949, 5.313] (assumes normal distribution)


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
# Warmup Iteration   1: 4.626 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.344 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.007 ms/op
Iteration   1: 3.299 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  7.979 ms/op
                 createUser·p0.9999: 14.015 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   2: 3.236 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  8.054 ms/op
                 createUser·p0.9999: 15.812 ms/op
                 createUser·p1.00:   17.891 ms/op

Iteration   3: 3.165 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  11.276 ms/op
                 createUser·p0.9999: 22.901 ms/op
                 createUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 297267
  mean =      3.232 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15726 
    [ 2.500,  5.000) = 279601 
    [ 5.000,  7.500) = 1492 
    [ 7.500, 10.000) = 214 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      4.694 ms/op
     p(99.9000) =      8.413 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     23.170 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 4.198 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.313 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
Iteration   1: 3.124 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.723 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  7.907 ms/op
                 existUser·p0.9999: 14.255 ms/op
                 existUser·p1.00:   15.417 ms/op

Iteration   2: 3.098 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  7.479 ms/op
                 existUser·p0.9999: 15.287 ms/op
                 existUser·p1.00:   15.679 ms/op

Iteration   3: 3.113 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  9.978 ms/op
                 existUser·p0.9999: 17.924 ms/op
                 existUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 308286
  mean =      3.111 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 650 
    [ 1.250,  2.500) = 32707 
    [ 2.500,  3.750) = 238766 
    [ 3.750,  5.000) = 34786 
    [ 5.000,  6.250) = 643 
    [ 6.250,  7.500) = 364 
    [ 7.500,  8.750) = 79 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.171 ms/op
     p(99.9900) =     17.433 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 4.670 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.009 ms/op
Iteration   1: 3.196 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   4.572 ms/op
                 getUser·p0.999:  8.809 ms/op
                 getUser·p0.9999: 20.545 ms/op
                 getUser·p1.00:   21.004 ms/op

Iteration   2: 3.228 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.447 ms/op
                 getUser·p0.9999: 18.186 ms/op
                 getUser·p1.00:   20.414 ms/op

Iteration   3: 3.181 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  9.173 ms/op
                 getUser·p0.9999: 21.627 ms/op
                 getUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 299850
  mean =      3.201 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20399 
    [ 2.500,  5.000) = 277744 
    [ 5.000,  7.500) = 1293 
    [ 7.500, 10.000) = 209 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      7.987 ms/op
     p(99.9900) =     21.135 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 5.927 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.281 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.012 ms/op
Iteration   1: 4.177 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.681 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   6.110 ms/op
                 listUser·p0.99:   7.241 ms/op
                 listUser·p0.999:  14.215 ms/op
                 listUser·p0.9999: 20.578 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   2: 4.064 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.473 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  15.570 ms/op
                 listUser·p0.9999: 23.462 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   3: 4.303 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   4.059 ms/op
                 listUser·p0.90:   5.546 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  20.011 ms/op
                 listUser·p0.9999: 25.873 ms/op
                 listUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 229849
  mean =      4.179 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1452 
    [ 2.500,  5.000) = 195300 
    [ 5.000,  7.500) = 31191 
    [ 7.500, 10.000) = 1486 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     15.712 ms/op
     p(99.9900) =     24.642 ms/op
     p(99.9990) =     26.041 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.964 ± 2.450  ops/ms
ClientGrpc.existUser                       thrpt       3  10.383 ± 1.283  ops/ms
ClientGrpc.getUser                         thrpt       3  10.065 ± 2.711  ops/ms
ClientGrpc.listUser                        thrpt       3   7.582 ± 2.213  ops/ms
ClientGrpc.createUser                       avgt       3   3.192 ± 0.897   ms/op
ClientGrpc.existUser                        avgt       3   3.064 ± 1.035   ms/op
ClientGrpc.getUser                          avgt       3   3.226 ± 0.484   ms/op
ClientGrpc.listUser                         avgt       3   4.131 ± 1.182   ms/op
ClientGrpc.createUser                     sample  297267   3.232 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.826           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.195           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.141           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.694           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.413           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.741           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.364           ms/op
ClientGrpc.existUser                      sample  308286   3.111 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.708           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.076           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.797           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.985           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.171           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.433           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.957           ms/op
ClientGrpc.getUser                        sample  299850   3.201 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.732           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.174           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.063           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.987           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.135           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.626           ms/op
ClientGrpc.listUser                       sample  229849   4.179 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.206           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.990           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.374           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.964           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.307           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.712           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.642           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.116           ms/op
