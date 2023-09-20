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
# Warmup Iteration   1: 3.816 ops/ms
# Warmup Iteration   2: 8.475 ops/ms
# Warmup Iteration   3: 9.591 ops/ms
Iteration   1: 9.756 ops/ms
Iteration   2: 9.923 ops/ms
Iteration   3: 10.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.901 ±(99.9%) 2.489 ops/ms [Average]
  (min, avg, max) = (9.756, 9.901, 10.026), stdev = 0.136
  CI (99.9%): [7.412, 12.390] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.906 ops/ms
# Warmup Iteration   2: 10.114 ops/ms
# Warmup Iteration   3: 10.498 ops/ms
Iteration   1: 10.638 ops/ms
Iteration   2: 10.583 ops/ms
Iteration   3: 10.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.621 ±(99.9%) 0.605 ops/ms [Average]
  (min, avg, max) = (10.583, 10.621, 10.643), stdev = 0.033
  CI (99.9%): [10.016, 11.227] (assumes normal distribution)


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
# Warmup Iteration   1: 6.520 ops/ms
# Warmup Iteration   2: 9.979 ops/ms
# Warmup Iteration   3: 10.061 ops/ms
Iteration   1: 10.131 ops/ms
Iteration   2: 10.114 ops/ms
Iteration   3: 10.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.203 ±(99.9%) 2.564 ops/ms [Average]
  (min, avg, max) = (10.114, 10.203, 10.365), stdev = 0.141
  CI (99.9%): [7.640, 12.767] (assumes normal distribution)


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
# Warmup Iteration   1: 5.753 ops/ms
# Warmup Iteration   2: 8.108 ops/ms
# Warmup Iteration   3: 8.171 ops/ms
Iteration   1: 8.175 ops/ms
Iteration   2: 8.173 ops/ms
Iteration   3: 8.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.172 ±(99.9%) 0.067 ops/ms [Average]
  (min, avg, max) = (8.168, 8.172, 8.175), stdev = 0.004
  CI (99.9%): [8.104, 8.239] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.274 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.318 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.005 ms/op
Iteration   1: 3.142 ±(99.9%) 0.009 ms/op
Iteration   2: 3.097 ±(99.9%) 0.003 ms/op
Iteration   3: 3.260 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.166 ±(99.9%) 1.536 ms/op [Average]
  (min, avg, max) = (3.097, 3.166, 3.260), stdev = 0.084
  CI (99.9%): [1.630, 4.702] (assumes normal distribution)


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
# Warmup Iteration   1: 4.228 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.002 ms/op
Iteration   1: 2.986 ±(99.9%) 0.002 ms/op
Iteration   2: 3.054 ±(99.9%) 0.002 ms/op
Iteration   3: 3.077 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.039 ±(99.9%) 0.860 ms/op [Average]
  (min, avg, max) = (2.986, 3.039, 3.077), stdev = 0.047
  CI (99.9%): [2.179, 3.899] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.349 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.004 ms/op
Iteration   1: 3.175 ±(99.9%) 0.002 ms/op
Iteration   2: 3.159 ±(99.9%) 0.001 ms/op
Iteration   3: 3.188 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.174 ±(99.9%) 0.264 ms/op [Average]
  (min, avg, max) = (3.159, 3.174, 3.188), stdev = 0.014
  CI (99.9%): [2.910, 3.438] (assumes normal distribution)


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
# Warmup Iteration   1: 5.344 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.011 ms/op
Iteration   1: 3.741 ±(99.9%) 0.023 ms/op
Iteration   2: 3.887 ±(99.9%) 0.022 ms/op
Iteration   3: 3.882 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.836 ±(99.9%) 1.512 ms/op [Average]
  (min, avg, max) = (3.741, 3.836, 3.887), stdev = 0.083
  CI (99.9%): [2.324, 5.348] (assumes normal distribution)


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
# Warmup Iteration   1: 4.528 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.266 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.006 ms/op
Iteration   1: 3.173 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  7.619 ms/op
                 createUser·p0.9999: 12.205 ms/op
                 createUser·p1.00:   12.763 ms/op

Iteration   2: 3.106 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.833 ms/op
                 createUser·p0.999:  10.435 ms/op
                 createUser·p0.9999: 14.282 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   3: 3.211 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.828 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.577 ms/op
                 createUser·p0.999:  8.757 ms/op
                 createUser·p0.9999: 16.419 ms/op
                 createUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303364
  mean =      3.163 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 429 
    [ 1.250,  2.500) = 14043 
    [ 2.500,  3.750) = 254270 
    [ 3.750,  5.000) = 32427 
    [ 5.000,  6.250) = 1279 
    [ 6.250,  7.500) = 468 
    [ 7.500,  8.750) = 139 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      8.858 ms/op
     p(99.9900) =     15.991 ms/op
     p(99.9990) =     16.776 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 4.228 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.005 ms/op
Iteration   1: 3.044 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.484 ms/op
                 existUser·p0.999:  9.158 ms/op
                 existUser·p0.9999: 12.263 ms/op
                 existUser·p1.00:   12.747 ms/op

Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  6.931 ms/op
                 existUser·p0.9999: 13.573 ms/op
                 existUser·p1.00:   14.844 ms/op

Iteration   3: 3.061 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  7.065 ms/op
                 existUser·p0.9999: 26.971 ms/op
                 existUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315648
  mean =      3.042 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23703 
    [ 2.500,  5.000) = 290219 
    [ 5.000,  7.500) = 1326 
    [ 7.500, 10.000) = 204 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      8.118 ms/op
     p(99.9900) =     26.360 ms/op
     p(99.9990) =     27.285 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 4.463 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.006 ms/op
Iteration   1: 3.124 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  9.634 ms/op
                 getUser·p0.9999: 20.514 ms/op
                 getUser·p1.00:   21.266 ms/op

Iteration   2: 3.130 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  8.208 ms/op
                 getUser·p0.9999: 15.532 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   3: 3.175 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  8.815 ms/op
                 getUser·p0.9999: 15.807 ms/op
                 getUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305390
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8037 
    [ 2.500,  5.000) = 295312 
    [ 5.000,  7.500) = 1413 
    [ 7.500, 10.000) = 415 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     19.479 ms/op
     p(99.9990) =     20.740 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


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
# Warmup Iteration   1: 5.583 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.961 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.011 ms/op
Iteration   1: 3.911 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.479 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  12.976 ms/op
                 listUser·p0.9999: 16.638 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   2: 3.871 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   6.423 ms/op
                 listUser·p0.999:  14.262 ms/op
                 listUser·p0.9999: 16.055 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   3: 3.857 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  14.045 ms/op
                 listUser·p0.9999: 16.758 ms/op
                 listUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247474
  mean =      3.880 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1625 
    [ 2.500,  3.750) = 108123 
    [ 3.750,  5.000) = 125923 
    [ 5.000,  6.250) = 8021 
    [ 6.250,  7.500) = 3004 
    [ 7.500,  8.750) = 277 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 153 
    [13.750, 15.000) = 112 
    [15.000, 16.250) = 95 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     13.591 ms/op
     p(99.9900) =     16.507 ms/op
     p(99.9990) =     17.698 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.901 ± 2.489  ops/ms
ClientGrpc.existUser                       thrpt       3  10.621 ± 0.605  ops/ms
ClientGrpc.getUser                         thrpt       3  10.203 ± 2.564  ops/ms
ClientGrpc.listUser                        thrpt       3   8.172 ± 0.067  ops/ms
ClientGrpc.createUser                       avgt       3   3.166 ± 1.536   ms/op
ClientGrpc.existUser                        avgt       3   3.039 ± 0.860   ms/op
ClientGrpc.getUser                          avgt       3   3.174 ± 0.264   ms/op
ClientGrpc.listUser                         avgt       3   3.836 ± 1.512   ms/op
ClientGrpc.createUser                     sample  303364   3.163 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.748           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.109           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.981           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.858           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.991           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.907           ms/op
ClientGrpc.existUser                      sample  315648   3.042 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.717           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.777           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.118           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.360           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.394           ms/op
ClientGrpc.getUser                        sample  305390   3.143 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.751           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.864           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.479           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.266           ms/op
ClientGrpc.listUser                       sample  247474   3.880 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.300           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.325           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.488           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.591           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.507           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          17.793           ms/op
