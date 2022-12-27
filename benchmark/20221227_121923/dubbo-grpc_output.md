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
# Warmup Iteration   1: 3.890 ops/ms
# Warmup Iteration   2: 8.541 ops/ms
# Warmup Iteration   3: 10.003 ops/ms
Iteration   1: 10.117 ops/ms
Iteration   2: 9.992 ops/ms
Iteration   3: 9.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.017 ±(99.9%) 1.654 ops/ms [Average]
  (min, avg, max) = (9.940, 10.017, 10.117), stdev = 0.091
  CI (99.9%): [8.363, 11.671] (assumes normal distribution)


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
# Warmup Iteration   1: 7.568 ops/ms
# Warmup Iteration   2: 10.261 ops/ms
# Warmup Iteration   3: 10.861 ops/ms
Iteration   1: 10.289 ops/ms
Iteration   2: 10.308 ops/ms
Iteration   3: 10.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.426 ±(99.9%) 4.021 ops/ms [Average]
  (min, avg, max) = (10.289, 10.426, 10.680), stdev = 0.220
  CI (99.9%): [6.405, 14.447] (assumes normal distribution)


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
# Warmup Iteration   1: 6.613 ops/ms
# Warmup Iteration   2: 9.698 ops/ms
# Warmup Iteration   3: 9.852 ops/ms
Iteration   1: 9.953 ops/ms
Iteration   2: 9.958 ops/ms
Iteration   3: 10.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.994 ±(99.9%) 1.193 ops/ms [Average]
  (min, avg, max) = (9.953, 9.994, 10.069), stdev = 0.065
  CI (99.9%): [8.800, 11.187] (assumes normal distribution)


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
# Warmup Iteration   1: 5.090 ops/ms
# Warmup Iteration   2: 7.572 ops/ms
# Warmup Iteration   3: 7.781 ops/ms
Iteration   1: 7.798 ops/ms
Iteration   2: 8.289 ops/ms
Iteration   3: 7.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.969 ±(99.9%) 5.069 ops/ms [Average]
  (min, avg, max) = (7.798, 7.969, 8.289), stdev = 0.278
  CI (99.9%): [2.900, 13.038] (assumes normal distribution)


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
# Warmup Iteration   1: 4.249 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.002 ms/op
Iteration   1: 3.244 ±(99.9%) 0.011 ms/op
Iteration   2: 3.250 ±(99.9%) 0.002 ms/op
Iteration   3: 3.273 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.255 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (3.244, 3.255, 3.273), stdev = 0.015
  CI (99.9%): [2.975, 3.535] (assumes normal distribution)


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.002 ms/op
Iteration   1: 3.106 ±(99.9%) 0.002 ms/op
Iteration   2: 3.045 ±(99.9%) 0.002 ms/op
Iteration   3: 3.100 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.084 ±(99.9%) 0.611 ms/op [Average]
  (min, avg, max) = (3.045, 3.084, 3.106), stdev = 0.033
  CI (99.9%): [2.473, 3.694] (assumes normal distribution)


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
# Warmup Iteration   1: 4.212 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.282 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.002 ms/op
Iteration   1: 3.196 ±(99.9%) 0.002 ms/op
Iteration   2: 3.258 ±(99.9%) 0.002 ms/op
Iteration   3: 3.214 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.222 ±(99.9%) 0.584 ms/op [Average]
  (min, avg, max) = (3.196, 3.222, 3.258), stdev = 0.032
  CI (99.9%): [2.638, 3.807] (assumes normal distribution)


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
# Warmup Iteration   1: 6.030 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.352 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.166 ±(99.9%) 0.040 ms/op
Iteration   1: 4.084 ±(99.9%) 0.014 ms/op
Iteration   2: 4.150 ±(99.9%) 0.019 ms/op
Iteration   3: 4.113 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.116 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (4.084, 4.116, 4.150), stdev = 0.033
  CI (99.9%): [3.516, 4.715] (assumes normal distribution)


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
# Warmup Iteration   1: 4.484 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.316 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.007 ms/op
Iteration   1: 3.159 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  8.232 ms/op
                 createUser·p0.9999: 14.085 ms/op
                 createUser·p1.00:   14.598 ms/op

Iteration   2: 3.227 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  8.386 ms/op
                 createUser·p0.9999: 14.893 ms/op
                 createUser·p1.00:   15.254 ms/op

Iteration   3: 3.256 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  16.796 ms/op
                 createUser·p0.9999: 24.391 ms/op
                 createUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298590
  mean =      3.213 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15369 
    [ 2.500,  5.000) = 281897 
    [ 5.000,  7.500) = 815 
    [ 7.500, 10.000) = 194 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =     10.263 ms/op
     p(99.9900) =     22.922 ms/op
     p(99.9990) =     24.774 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.230 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.006 ms/op
Iteration   1: 3.111 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  7.105 ms/op
                 existUser·p0.9999: 19.422 ms/op
                 existUser·p1.00:   19.923 ms/op

Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  7.224 ms/op
                 existUser·p0.9999: 20.546 ms/op
                 existUser·p1.00:   20.808 ms/op

Iteration   3: 3.098 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.773 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.933 ms/op
                 existUser·p0.9999: 20.786 ms/op
                 existUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311225
  mean =      3.084 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30627 
    [ 2.500,  5.000) = 279698 
    [ 5.000,  7.500) = 660 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.094 ms/op
     p(99.9900) =     20.443 ms/op
     p(99.9990) =     21.128 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 4.370 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.280 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.008 ms/op
Iteration   1: 3.229 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  9.551 ms/op
                 getUser·p0.9999: 14.210 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   2: 3.205 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  6.595 ms/op
                 getUser·p0.9999: 17.597 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   3: 3.285 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.605 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  8.414 ms/op
                 getUser·p0.9999: 19.005 ms/op
                 getUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 296378
  mean =      3.239 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 318 
    [ 1.250,  2.500) = 16039 
    [ 2.500,  3.750) = 228003 
    [ 3.750,  5.000) = 50897 
    [ 5.000,  6.250) = 464 
    [ 6.250,  7.500) = 269 
    [ 7.500,  8.750) = 130 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      8.246 ms/op
     p(99.9900) =     17.751 ms/op
     p(99.9990) =     19.203 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 5.955 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.240 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.208 ±(99.9%) 0.013 ms/op
Iteration   1: 4.103 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.124 ms/op
                 listUser·p0.999:  13.421 ms/op
                 listUser·p0.9999: 19.399 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   2: 4.094 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  16.349 ms/op
                 listUser·p0.9999: 22.851 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   3: 4.122 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.681 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  17.118 ms/op
                 listUser·p0.9999: 22.348 ms/op
                 listUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233694
  mean =      4.106 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1956 
    [ 2.500,  5.000) = 204764 
    [ 5.000,  7.500) = 25162 
    [ 7.500, 10.000) = 1301 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     16.438 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     23.440 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.017 ± 1.654  ops/ms
ClientGrpc.existUser                       thrpt       3  10.426 ± 4.021  ops/ms
ClientGrpc.getUser                         thrpt       3   9.994 ± 1.193  ops/ms
ClientGrpc.listUser                        thrpt       3   7.969 ± 5.069  ops/ms
ClientGrpc.createUser                       avgt       3   3.255 ± 0.280   ms/op
ClientGrpc.existUser                        avgt       3   3.084 ± 0.611   ms/op
ClientGrpc.getUser                          avgt       3   3.222 ± 0.584   ms/op
ClientGrpc.listUser                         avgt       3   4.116 ± 0.599   ms/op
ClientGrpc.createUser                     sample  298590   3.213 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.710           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.178           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.850           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.055           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.263           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.922           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.936           ms/op
ClientGrpc.existUser                      sample  311225   3.084 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.606           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.060           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.736           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.916           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.094           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.443           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.234           ms/op
ClientGrpc.getUser                        sample  296378   3.239 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.605           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.203           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.965           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.145           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.246           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.751           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.366           ms/op
ClientGrpc.listUser                       sample  233694   4.106 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.681           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.940           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.225           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.438           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.348           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.593           ms/op
