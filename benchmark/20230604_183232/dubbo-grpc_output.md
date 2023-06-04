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
# Warmup Iteration   1: 2.172 ops/ms
# Warmup Iteration   2: 4.840 ops/ms
# Warmup Iteration   3: 6.560 ops/ms
Iteration   1: 7.290 ops/ms
Iteration   2: 7.345 ops/ms
Iteration   3: 7.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.312 ±(99.9%) 0.538 ops/ms [Average]
  (min, avg, max) = (7.290, 7.312, 7.345), stdev = 0.029
  CI (99.9%): [6.774, 7.850] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.938 ops/ms
# Warmup Iteration   2: 7.912 ops/ms
# Warmup Iteration   3: 8.198 ops/ms
Iteration   1: 8.206 ops/ms
Iteration   2: 8.267 ops/ms
Iteration   3: 8.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.242 ±(99.9%) 0.586 ops/ms [Average]
  (min, avg, max) = (8.206, 8.242, 8.267), stdev = 0.032
  CI (99.9%): [7.656, 8.829] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.226 ops/ms
# Warmup Iteration   2: 7.116 ops/ms
# Warmup Iteration   3: 7.738 ops/ms
Iteration   1: 7.895 ops/ms
Iteration   2: 7.945 ops/ms
Iteration   3: 7.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.936 ±(99.9%) 0.681 ops/ms [Average]
  (min, avg, max) = (7.895, 7.936, 7.968), stdev = 0.037
  CI (99.9%): [7.255, 8.617] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.714 ops/ms
# Warmup Iteration   2: 5.181 ops/ms
# Warmup Iteration   3: 5.606 ops/ms
Iteration   1: 5.721 ops/ms
Iteration   2: 5.965 ops/ms
Iteration   3: 5.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.826 ±(99.9%) 2.283 ops/ms [Average]
  (min, avg, max) = (5.721, 5.826, 5.965), stdev = 0.125
  CI (99.9%): [3.543, 8.109] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.335 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.680 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.393 ±(99.9%) 0.017 ms/op
Iteration   1: 4.273 ±(99.9%) 0.003 ms/op
Iteration   2: 4.291 ±(99.9%) 0.003 ms/op
Iteration   3: 4.454 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.339 ±(99.9%) 1.820 ms/op [Average]
  (min, avg, max) = (4.273, 4.339, 4.454), stdev = 0.100
  CI (99.9%): [2.519, 6.160] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.722 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.767 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.297 ±(99.9%) 0.004 ms/op
Iteration   1: 4.120 ±(99.9%) 0.003 ms/op
Iteration   2: 3.866 ±(99.9%) 0.004 ms/op
Iteration   3: 3.878 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.955 ±(99.9%) 2.608 ms/op [Average]
  (min, avg, max) = (3.866, 3.955, 4.120), stdev = 0.143
  CI (99.9%): [1.347, 6.563] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.196 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.515 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.402 ±(99.9%) 0.003 ms/op
Iteration   1: 4.259 ±(99.9%) 0.003 ms/op
Iteration   2: 4.218 ±(99.9%) 0.003 ms/op
Iteration   3: 4.206 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.228 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (4.206, 4.228, 4.259), stdev = 0.028
  CI (99.9%): [3.721, 4.734] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.387 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 6.129 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.590 ±(99.9%) 0.022 ms/op
Iteration   1: 5.441 ±(99.9%) 0.016 ms/op
Iteration   2: 5.458 ±(99.9%) 0.014 ms/op
Iteration   3: 5.478 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.459 ±(99.9%) 0.339 ms/op [Average]
  (min, avg, max) = (5.441, 5.459, 5.478), stdev = 0.019
  CI (99.9%): [5.120, 5.798] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.385 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.500 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.188 ±(99.9%) 0.015 ms/op
Iteration   1: 4.193 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   4.043 ms/op
                 createUser·p0.90:   5.276 ms/op
                 createUser·p0.95:   5.956 ms/op
                 createUser·p0.99:   8.339 ms/op
                 createUser·p0.999:  11.551 ms/op
                 createUser·p0.9999: 24.109 ms/op
                 createUser·p1.00:   28.901 ms/op

Iteration   2: 4.212 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   4.014 ms/op
                 createUser·p0.90:   5.374 ms/op
                 createUser·p0.95:   6.005 ms/op
                 createUser·p0.99:   8.135 ms/op
                 createUser·p0.999:  14.680 ms/op
                 createUser·p0.9999: 36.110 ms/op
                 createUser·p1.00:   38.142 ms/op

Iteration   3: 4.231 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   4.059 ms/op
                 createUser·p0.90:   5.448 ms/op
                 createUser·p0.95:   6.005 ms/op
                 createUser·p0.99:   7.971 ms/op
                 createUser·p0.999:  10.966 ms/op
                 createUser·p0.9999: 26.982 ms/op
                 createUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 227868
  mean =      4.212 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4843 
    [ 2.500,  5.000) = 187294 
    [ 5.000,  7.500) = 32194 
    [ 7.500, 10.000) = 2865 
    [10.000, 12.500) = 456 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      4.039 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      8.167 ms/op
     p(99.9000) =     12.213 ms/op
     p(99.9900) =     34.669 ms/op
     p(99.9990) =     37.872 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.650 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.263 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.012 ms/op
Iteration   1: 3.901 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.413 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.727 ms/op
                 existUser·p0.95:   5.464 ms/op
                 existUser·p0.99:   7.176 ms/op
                 existUser·p0.999:  9.979 ms/op
                 existUser·p0.9999: 21.405 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   2: 4.015 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   5.022 ms/op
                 existUser·p0.95:   5.620 ms/op
                 existUser·p0.99:   7.913 ms/op
                 existUser·p0.999:  12.878 ms/op
                 existUser·p0.9999: 18.055 ms/op
                 existUser·p1.00:   18.645 ms/op

Iteration   3: 3.943 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.792 ms/op
                 existUser·p0.95:   5.423 ms/op
                 existUser·p0.99:   7.086 ms/op
                 existUser·p0.999:  13.124 ms/op
                 existUser·p0.9999: 37.742 ms/op
                 existUser·p1.00:   38.142 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 242757
  mean =      3.952 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6385 
    [ 2.500,  5.000) = 215777 
    [ 5.000,  7.500) = 18465 
    [ 7.500, 10.000) = 1587 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.413 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     12.361 ms/op
     p(99.9900) =     36.027 ms/op
     p(99.9990) =     38.114 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.514 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.620 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.310 ±(99.9%) 0.014 ms/op
Iteration   1: 4.279 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   4.116 ms/op
                 getUser·p0.90:   5.415 ms/op
                 getUser·p0.95:   6.021 ms/op
                 getUser·p0.99:   8.149 ms/op
                 getUser·p0.999:  14.537 ms/op
                 getUser·p0.9999: 16.499 ms/op
                 getUser·p1.00:   18.743 ms/op

Iteration   2: 4.254 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.157 ms/op
                 getUser·p0.50:   4.108 ms/op
                 getUser·p0.90:   5.300 ms/op
                 getUser·p0.95:   5.882 ms/op
                 getUser·p0.99:   7.815 ms/op
                 getUser·p0.999:  11.015 ms/op
                 getUser·p0.9999: 19.333 ms/op
                 getUser·p1.00:   19.792 ms/op

Iteration   3: 4.150 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   4.002 ms/op
                 getUser·p0.90:   5.186 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   7.463 ms/op
                 getUser·p0.999:  10.452 ms/op
                 getUser·p0.9999: 30.690 ms/op
                 getUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 227017
  mean =      4.227 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3207 
    [ 2.500,  5.000) = 189923 
    [ 5.000,  7.500) = 31037 
    [ 7.500, 10.000) = 2376 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      4.071 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     11.485 ms/op
     p(99.9900) =     30.025 ms/op
     p(99.9990) =     31.070 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.667 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 6.053 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.482 ±(99.9%) 0.020 ms/op
Iteration   1: 5.432 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.843 ms/op
                 listUser·p0.50:   5.120 ms/op
                 listUser·p0.90:   7.249 ms/op
                 listUser·p0.95:   8.225 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  24.519 ms/op
                 listUser·p0.9999: 28.279 ms/op
                 listUser·p1.00:   28.475 ms/op

Iteration   2: 5.529 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.935 ms/op
                 listUser·p0.50:   5.210 ms/op
                 listUser·p0.90:   7.266 ms/op
                 listUser·p0.95:   8.274 ms/op
                 listUser·p0.99:   10.715 ms/op
                 listUser·p0.999:  18.612 ms/op
                 listUser·p0.9999: 30.940 ms/op
                 listUser·p1.00:   31.425 ms/op

Iteration   3: 5.593 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   5.259 ms/op
                 listUser·p0.90:   7.381 ms/op
                 listUser·p0.95:   8.339 ms/op
                 listUser·p0.99:   11.026 ms/op
                 listUser·p0.999:  19.661 ms/op
                 listUser·p0.9999: 31.766 ms/op
                 listUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 173871
  mean =      5.517 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 108 
    [ 2.500,  5.000) = 71190 
    [ 5.000,  7.500) = 87316 
    [ 7.500, 10.000) = 12386 
    [10.000, 12.500) = 2033 
    [12.500, 15.000) = 428 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.423 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      7.299 ms/op
     p(95.0000) =      8.282 ms/op
     p(99.0000) =     10.830 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     30.756 ms/op
     p(99.9990) =     32.164 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.312 ± 0.538  ops/ms
ClientGrpc.existUser                       thrpt       3   8.242 ± 0.586  ops/ms
ClientGrpc.getUser                         thrpt       3   7.936 ± 0.681  ops/ms
ClientGrpc.listUser                        thrpt       3   5.826 ± 2.283  ops/ms
ClientGrpc.createUser                       avgt       3   4.339 ± 1.820   ms/op
ClientGrpc.existUser                        avgt       3   3.955 ± 2.608   ms/op
ClientGrpc.getUser                          avgt       3   4.228 ± 0.506   ms/op
ClientGrpc.listUser                         avgt       3   5.459 ± 0.339   ms/op
ClientGrpc.createUser                     sample  227868   4.212 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.798           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.366           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.997           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.167           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.213           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.669           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          38.142           ms/op
ClientGrpc.existUser                      sample  242757   3.952 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.413           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.813           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.866           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.505           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.332           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.361           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          36.027           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          38.142           ms/op
ClientGrpc.getUser                        sample  227017   4.227 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.065           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.071           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.308           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.882           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.799           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.485           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.025           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.195           ms/op
ClientGrpc.listUser                       sample  173871   5.517 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.423           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.194           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.299           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.282           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.830           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.923           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.756           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.309           ms/op
