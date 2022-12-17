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
# Warmup Iteration   1: 3.911 ops/ms
# Warmup Iteration   2: 8.860 ops/ms
# Warmup Iteration   3: 10.110 ops/ms
Iteration   1: 10.575 ops/ms
Iteration   2: 10.356 ops/ms
Iteration   3: 10.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.413 ±(99.9%) 2.597 ops/ms [Average]
  (min, avg, max) = (10.307, 10.413, 10.575), stdev = 0.142
  CI (99.9%): [7.816, 13.009] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.359 ops/ms
# Warmup Iteration   2: 10.202 ops/ms
# Warmup Iteration   3: 10.521 ops/ms
Iteration   1: 10.683 ops/ms
Iteration   2: 10.703 ops/ms
Iteration   3: 11.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.814 ±(99.9%) 3.853 ops/ms [Average]
  (min, avg, max) = (10.683, 10.814, 11.058), stdev = 0.211
  CI (99.9%): [6.961, 14.668] (assumes normal distribution)


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
# Warmup Iteration   1: 7.383 ops/ms
# Warmup Iteration   2: 10.011 ops/ms
# Warmup Iteration   3: 10.158 ops/ms
Iteration   1: 10.344 ops/ms
Iteration   2: 10.135 ops/ms
Iteration   3: 10.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.249 ±(99.9%) 1.923 ops/ms [Average]
  (min, avg, max) = (10.135, 10.249, 10.344), stdev = 0.105
  CI (99.9%): [8.326, 12.173] (assumes normal distribution)


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
# Warmup Iteration   1: 5.656 ops/ms
# Warmup Iteration   2: 7.658 ops/ms
# Warmup Iteration   3: 7.744 ops/ms
Iteration   1: 7.741 ops/ms
Iteration   2: 7.873 ops/ms
Iteration   3: 7.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.788 ±(99.9%) 1.334 ops/ms [Average]
  (min, avg, max) = (7.741, 7.788, 7.873), stdev = 0.073
  CI (99.9%): [6.454, 9.123] (assumes normal distribution)


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
# Warmup Iteration   1: 4.255 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.002 ms/op
Iteration   1: 3.091 ±(99.9%) 0.005 ms/op
Iteration   2: 3.094 ±(99.9%) 0.002 ms/op
Iteration   3: 3.150 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.112 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (3.091, 3.112, 3.150), stdev = 0.033
  CI (99.9%): [2.506, 3.718] (assumes normal distribution)


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
# Warmup Iteration   1: 4.046 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.002 ms/op
Iteration   1: 3.002 ±(99.9%) 0.002 ms/op
Iteration   2: 3.026 ±(99.9%) 0.002 ms/op
Iteration   3: 2.978 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.002 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (2.978, 3.002, 3.026), stdev = 0.024
  CI (99.9%): [2.571, 3.433] (assumes normal distribution)


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
# Warmup Iteration   1: 4.191 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.003 ms/op
Iteration   1: 3.103 ±(99.9%) 0.002 ms/op
Iteration   2: 3.153 ±(99.9%) 0.002 ms/op
Iteration   3: 3.090 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.115 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (3.090, 3.115, 3.153), stdev = 0.033
  CI (99.9%): [2.511, 3.719] (assumes normal distribution)


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
# Warmup Iteration   1: 5.495 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.011 ms/op
Iteration   1: 4.040 ±(99.9%) 0.036 ms/op
Iteration   2: 3.750 ±(99.9%) 0.004 ms/op
Iteration   3: 3.938 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.909 ±(99.9%) 2.688 ms/op [Average]
  (min, avg, max) = (3.750, 3.909, 4.040), stdev = 0.147
  CI (99.9%): [1.222, 6.597] (assumes normal distribution)


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
# Warmup Iteration   1: 4.544 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.008 ms/op
Iteration   1: 3.185 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  10.479 ms/op
                 createUser·p0.9999: 13.074 ms/op
                 createUser·p1.00:   13.222 ms/op

Iteration   2: 3.142 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.632 ms/op
                 createUser·p0.9999: 22.303 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   3: 3.219 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  10.912 ms/op
                 createUser·p0.9999: 16.531 ms/op
                 createUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301479
  mean =      3.182 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24013 
    [ 2.500,  5.000) = 276360 
    [ 5.000,  7.500) = 562 
    [ 7.500, 10.000) = 226 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =     10.306 ms/op
     p(99.9900) =     21.509 ms/op
     p(99.9990) =     22.576 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 4.254 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.007 ms/op
Iteration   1: 3.101 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   4.320 ms/op
                 existUser·p0.999:  6.717 ms/op
                 existUser·p0.9999: 13.255 ms/op
                 existUser·p1.00:   13.517 ms/op

Iteration   2: 3.074 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.668 ms/op
                 existUser·p0.9999: 23.298 ms/op
                 existUser·p1.00:   23.986 ms/op

Iteration   3: 3.159 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.597 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  8.980 ms/op
                 existUser·p0.9999: 26.116 ms/op
                 existUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 308394
  mean =      3.111 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39674 
    [ 2.500,  5.000) = 267867 
    [ 5.000,  7.500) = 572 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      4.367 ms/op
     p(99.9000) =      7.132 ms/op
     p(99.9900) =     25.018 ms/op
     p(99.9990) =     26.572 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 4.379 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.006 ms/op
Iteration   1: 3.117 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.540 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.676 ms/op
                 getUser·p0.9999: 14.008 ms/op
                 getUser·p1.00:   14.221 ms/op

Iteration   2: 3.173 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.324 ms/op
                 getUser·p0.9999: 14.499 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   3: 3.168 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.357 ms/op
                 getUser·p0.9999: 17.656 ms/op
                 getUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304507
  mean =      3.152 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 612 
    [ 1.250,  2.500) = 23739 
    [ 2.500,  3.750) = 240101 
    [ 3.750,  5.000) = 38960 
    [ 5.000,  6.250) = 578 
    [ 6.250,  7.500) = 303 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      6.996 ms/op
     p(99.9900) =     16.131 ms/op
     p(99.9990) =     18.019 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 5.826 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.203 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.094 ±(99.9%) 0.011 ms/op
Iteration   1: 3.980 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  14.924 ms/op
                 listUser·p0.9999: 21.026 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   2: 3.993 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  15.563 ms/op
                 listUser·p0.9999: 21.108 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   3: 3.934 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.674 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.787 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  16.543 ms/op
                 listUser·p0.9999: 23.359 ms/op
                 listUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241984
  mean =      3.969 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2736 
    [ 2.500,  5.000) = 214947 
    [ 5.000,  7.500) = 22991 
    [ 7.500, 10.000) = 885 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     16.024 ms/op
     p(99.9900) =     22.826 ms/op
     p(99.9990) =     23.767 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.413 ± 2.597  ops/ms
ClientGrpc.existUser                       thrpt       3  10.814 ± 3.853  ops/ms
ClientGrpc.getUser                         thrpt       3  10.249 ± 1.923  ops/ms
ClientGrpc.listUser                        thrpt       3   7.788 ± 1.334  ops/ms
ClientGrpc.createUser                       avgt       3   3.112 ± 0.606   ms/op
ClientGrpc.existUser                        avgt       3   3.002 ± 0.431   ms/op
ClientGrpc.getUser                          avgt       3   3.115 ± 0.604   ms/op
ClientGrpc.listUser                         avgt       3   3.909 ± 2.688   ms/op
ClientGrpc.createUser                     sample  301479   3.182 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.810           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.150           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.051           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.306           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.509           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.708           ms/op
ClientGrpc.existUser                      sample  308394   3.111 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.597           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.084           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.854           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.030           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.367           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.132           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.018           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.673           ms/op
ClientGrpc.getUser                        sample  304507   3.152 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.540           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.125           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.834           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.022           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.996           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.131           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.186           ms/op
ClientGrpc.listUser                       sample  241984   3.969 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.674           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.024           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.826           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.855           ms/op
