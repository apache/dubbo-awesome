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
# Warmup Iteration   1: 3.472 ops/ms
# Warmup Iteration   2: 8.156 ops/ms
# Warmup Iteration   3: 9.621 ops/ms
Iteration   1: 9.900 ops/ms
Iteration   2: 9.993 ops/ms
Iteration   3: 10.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.060 ±(99.9%) 3.679 ops/ms [Average]
  (min, avg, max) = (9.900, 10.060, 10.286), stdev = 0.202
  CI (99.9%): [6.381, 13.739] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 6.715 ops/ms
# Warmup Iteration   2: 9.902 ops/ms
# Warmup Iteration   3: 10.617 ops/ms
Iteration   1: 10.240 ops/ms
Iteration   2: 10.511 ops/ms
Iteration   3: 10.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.371 ±(99.9%) 2.479 ops/ms [Average]
  (min, avg, max) = (10.240, 10.371, 10.511), stdev = 0.136
  CI (99.9%): [7.892, 12.850] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.507 ops/ms
# Warmup Iteration   2: 9.920 ops/ms
# Warmup Iteration   3: 9.990 ops/ms
Iteration   1: 10.129 ops/ms
Iteration   2: 10.223 ops/ms
Iteration   3: 10.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.185 ±(99.9%) 0.903 ops/ms [Average]
  (min, avg, max) = (10.129, 10.185, 10.223), stdev = 0.049
  CI (99.9%): [9.282, 11.088] (assumes normal distribution)


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
# Warmup Iteration   1: 4.808 ops/ms
# Warmup Iteration   2: 7.247 ops/ms
# Warmup Iteration   3: 7.808 ops/ms
Iteration   1: 7.768 ops/ms
Iteration   2: 7.758 ops/ms
Iteration   3: 7.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.765 ±(99.9%) 0.114 ops/ms [Average]
  (min, avg, max) = (7.758, 7.765, 7.769), stdev = 0.006
  CI (99.9%): [7.651, 7.879] (assumes normal distribution)


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
# Warmup Iteration   1: 4.852 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.018 ms/op
Iteration   1: 3.226 ±(99.9%) 0.006 ms/op
Iteration   2: 3.238 ±(99.9%) 0.006 ms/op
Iteration   3: 3.169 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.211 ±(99.9%) 0.673 ms/op [Average]
  (min, avg, max) = (3.169, 3.211, 3.238), stdev = 0.037
  CI (99.9%): [2.538, 3.884] (assumes normal distribution)


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
# Warmup Iteration   1: 4.284 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.190 ±(99.9%) 0.003 ms/op
Iteration   1: 3.313 ±(99.9%) 0.002 ms/op
Iteration   2: 3.186 ±(99.9%) 0.002 ms/op
Iteration   3: 3.129 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.210 ±(99.9%) 1.720 ms/op [Average]
  (min, avg, max) = (3.129, 3.210, 3.313), stdev = 0.094
  CI (99.9%): [1.490, 4.929] (assumes normal distribution)


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
# Warmup Iteration   1: 4.735 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.324 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.245 ±(99.9%) 0.002 ms/op
Iteration   1: 3.180 ±(99.9%) 0.003 ms/op
Iteration   2: 3.195 ±(99.9%) 0.003 ms/op
Iteration   3: 3.272 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.216 ±(99.9%) 0.896 ms/op [Average]
  (min, avg, max) = (3.180, 3.216, 3.272), stdev = 0.049
  CI (99.9%): [2.320, 4.112] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.666 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.449 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.191 ±(99.9%) 0.020 ms/op
Iteration   1: 4.220 ±(99.9%) 0.031 ms/op
Iteration   2: 4.110 ±(99.9%) 0.010 ms/op
Iteration   3: 4.138 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.156 ±(99.9%) 1.038 ms/op [Average]
  (min, avg, max) = (4.110, 4.156, 4.220), stdev = 0.057
  CI (99.9%): [3.118, 5.194] (assumes normal distribution)


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
# Warmup Iteration   1: 4.961 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.431 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.007 ms/op
Iteration   1: 3.161 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  13.147 ms/op
                 createUser·p0.9999: 19.100 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   2: 3.204 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   5.206 ms/op
                 createUser·p0.999:  11.031 ms/op
                 createUser·p0.9999: 20.055 ms/op
                 createUser·p1.00:   20.677 ms/op

Iteration   3: 3.142 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.610 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  9.404 ms/op
                 createUser·p0.9999: 21.234 ms/op
                 createUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302890
  mean =      3.169 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9018 
    [ 2.500,  5.000) = 291257 
    [ 5.000,  7.500) = 2038 
    [ 7.500, 10.000) = 212 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.841 ms/op
     p(99.9000) =     12.522 ms/op
     p(99.9900) =     20.700 ms/op
     p(99.9990) =     21.299 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 4.270 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.429 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.006 ms/op
Iteration   1: 3.125 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  8.477 ms/op
                 existUser·p0.9999: 13.919 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   2: 3.137 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  13.863 ms/op
                 existUser·p0.9999: 16.765 ms/op
                 existUser·p1.00:   17.203 ms/op

Iteration   3: 3.128 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  13.327 ms/op
                 existUser·p0.9999: 18.605 ms/op
                 existUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 306529
  mean =      3.130 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 452 
    [ 1.250,  2.500) = 18755 
    [ 2.500,  3.750) = 259712 
    [ 3.750,  5.000) = 23857 
    [ 5.000,  6.250) = 2054 
    [ 6.250,  7.500) = 656 
    [ 7.500,  8.750) = 342 
    [ 8.750, 10.000) = 168 
    [10.000, 11.250) = 206 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 91 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     12.065 ms/op
     p(99.9900) =     17.837 ms/op
     p(99.9990) =     19.591 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.009 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.494 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.008 ms/op
Iteration   1: 3.229 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.015 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   4.956 ms/op
                 getUser·p0.999:  9.196 ms/op
                 getUser·p0.9999: 20.349 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   2: 3.223 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   4.948 ms/op
                 getUser·p0.999:  11.464 ms/op
                 getUser·p0.9999: 25.231 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   3: 3.267 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   5.300 ms/op
                 getUser·p0.999:  12.337 ms/op
                 getUser·p0.9999: 25.868 ms/op
                 getUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 296320
  mean =      3.240 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9295 
    [ 2.500,  5.000) = 283646 
    [ 5.000,  7.500) = 2550 
    [ 7.500, 10.000) = 443 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.104 ms/op
     p(99.9000) =     11.796 ms/op
     p(99.9900) =     24.588 ms/op
     p(99.9990) =     26.478 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 6.024 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.178 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.012 ms/op
Iteration   1: 4.142 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  15.168 ms/op
                 listUser·p0.9999: 16.660 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   2: 4.115 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.438 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   7.627 ms/op
                 listUser·p0.999:  17.568 ms/op
                 listUser·p0.9999: 21.051 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   3: 4.015 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  17.377 ms/op
                 listUser·p0.9999: 22.545 ms/op
                 listUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234767
  mean =      4.090 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1582 
    [ 2.500,  5.000) = 215635 
    [ 5.000,  7.500) = 15427 
    [ 7.500, 10.000) = 1388 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 269 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     16.761 ms/op
     p(99.9900) =     21.638 ms/op
     p(99.9990) =     25.448 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.060 ± 3.679  ops/ms
ClientGrpc.existUser                       thrpt       3  10.371 ± 2.479  ops/ms
ClientGrpc.getUser                         thrpt       3  10.185 ± 0.903  ops/ms
ClientGrpc.listUser                        thrpt       3   7.765 ± 0.114  ops/ms
ClientGrpc.createUser                       avgt       3   3.211 ± 0.673   ms/op
ClientGrpc.existUser                        avgt       3   3.210 ± 1.720   ms/op
ClientGrpc.getUser                          avgt       3   3.216 ± 0.896   ms/op
ClientGrpc.listUser                         avgt       3   4.156 ± 1.038   ms/op
ClientGrpc.createUser                     sample  302890   3.169 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.610           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.109           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.953           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.841           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.522           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.700           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.332           ms/op
ClientGrpc.existUser                      sample  306529   3.130 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.618           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.056           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.961           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.267           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.065           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.837           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.726           ms/op
ClientGrpc.getUser                        sample  296320   3.240 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.805           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.174           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.076           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.104           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.796           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.588           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.509           ms/op
ClientGrpc.listUser                       sample  234767   4.090 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.233           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.969           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.653           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.373           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.761           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.638           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.280           ms/op
