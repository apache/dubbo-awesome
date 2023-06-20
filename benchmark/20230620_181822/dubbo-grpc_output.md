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
# Warmup Iteration   1: 2.036 ops/ms
# Warmup Iteration   2: 4.998 ops/ms
# Warmup Iteration   3: 6.561 ops/ms
Iteration   1: 6.829 ops/ms
Iteration   2: 7.261 ops/ms
Iteration   3: 7.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.271 ±(99.9%) 8.157 ops/ms [Average]
  (min, avg, max) = (6.829, 7.271, 7.723), stdev = 0.447
  CI (99.9%): [≈ 0, 15.428] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.913 ops/ms
# Warmup Iteration   2: 7.837 ops/ms
# Warmup Iteration   3: 8.285 ops/ms
Iteration   1: 8.028 ops/ms
Iteration   2: 8.402 ops/ms
Iteration   3: 8.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.207 ±(99.9%) 3.426 ops/ms [Average]
  (min, avg, max) = (8.028, 8.207, 8.402), stdev = 0.188
  CI (99.9%): [4.781, 11.633] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.461 ops/ms
# Warmup Iteration   2: 6.744 ops/ms
# Warmup Iteration   3: 7.212 ops/ms
Iteration   1: 7.327 ops/ms
Iteration   2: 7.388 ops/ms
Iteration   3: 7.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.365 ±(99.9%) 0.608 ops/ms [Average]
  (min, avg, max) = (7.327, 7.365, 7.388), stdev = 0.033
  CI (99.9%): [6.757, 7.973] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.745 ops/ms
# Warmup Iteration   2: 5.218 ops/ms
# Warmup Iteration   3: 5.713 ops/ms
Iteration   1: 5.837 ops/ms
Iteration   2: 5.879 ops/ms
Iteration   3: 5.832 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.849 ±(99.9%) 0.472 ops/ms [Average]
  (min, avg, max) = (5.832, 5.849, 5.879), stdev = 0.026
  CI (99.9%): [5.377, 6.322] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.686 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.747 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.651 ±(99.9%) 0.005 ms/op
Iteration   1: 4.288 ±(99.9%) 0.005 ms/op
Iteration   2: 4.261 ±(99.9%) 0.003 ms/op
Iteration   3: 4.360 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.303 ±(99.9%) 0.932 ms/op [Average]
  (min, avg, max) = (4.261, 4.303, 4.360), stdev = 0.051
  CI (99.9%): [3.371, 5.235] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.124 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.011 ±(99.9%) 0.004 ms/op
Iteration   1: 4.300 ±(99.9%) 0.005 ms/op
Iteration   2: 4.343 ±(99.9%) 0.005 ms/op
Iteration   3: 4.323 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.322 ±(99.9%) 0.393 ms/op [Average]
  (min, avg, max) = (4.300, 4.322, 4.343), stdev = 0.022
  CI (99.9%): [3.929, 4.716] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.628 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.600 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.470 ±(99.9%) 0.007 ms/op
Iteration   1: 4.571 ±(99.9%) 0.004 ms/op
Iteration   2: 4.292 ±(99.9%) 0.004 ms/op
Iteration   3: 4.264 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.376 ±(99.9%) 3.097 ms/op [Average]
  (min, avg, max) = (4.264, 4.376, 4.571), stdev = 0.170
  CI (99.9%): [1.279, 7.473] (assumes normal distribution)


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
# Warmup Iteration   1: 8.201 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.592 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.315 ±(99.9%) 0.019 ms/op
Iteration   1: 5.406 ±(99.9%) 0.016 ms/op
Iteration   2: 5.531 ±(99.9%) 0.025 ms/op
Iteration   3: 5.700 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.545 ±(99.9%) 2.691 ms/op [Average]
  (min, avg, max) = (5.406, 5.545, 5.700), stdev = 0.147
  CI (99.9%): [2.855, 8.236] (assumes normal distribution)


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
# Warmup Iteration   1: 6.671 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.879 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.528 ±(99.9%) 0.016 ms/op
Iteration   1: 4.285 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   4.182 ms/op
                 createUser·p0.90:   5.497 ms/op
                 createUser·p0.95:   6.005 ms/op
                 createUser·p0.99:   7.709 ms/op
                 createUser·p0.999:  10.826 ms/op
                 createUser·p0.9999: 15.992 ms/op
                 createUser·p1.00:   16.302 ms/op

Iteration   2: 4.366 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   4.182 ms/op
                 createUser·p0.90:   5.636 ms/op
                 createUser·p0.95:   6.201 ms/op
                 createUser·p0.99:   8.337 ms/op
                 createUser·p0.999:  12.337 ms/op
                 createUser·p0.9999: 19.213 ms/op
                 createUser·p1.00:   20.021 ms/op

Iteration   3: 4.352 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   4.219 ms/op
                 createUser·p0.90:   5.636 ms/op
                 createUser·p0.95:   6.185 ms/op
                 createUser·p0.99:   8.221 ms/op
                 createUser·p0.999:  12.747 ms/op
                 createUser·p0.9999: 20.740 ms/op
                 createUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 221503
  mean =      4.334 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6420 
    [ 2.500,  5.000) = 167876 
    [ 5.000,  7.500) = 43928 
    [ 7.500, 10.000) = 2638 
    [10.000, 12.500) = 432 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.595 ms/op
     p(95.0000) =      6.128 ms/op
     p(99.0000) =      8.135 ms/op
     p(99.9000) =     12.394 ms/op
     p(99.9900) =     20.016 ms/op
     p(99.9990) =     21.081 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 5.929 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.437 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.143 ±(99.9%) 0.013 ms/op
Iteration   1: 4.101 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   3.957 ms/op
                 existUser·p0.90:   5.325 ms/op
                 existUser·p0.95:   5.898 ms/op
                 existUser·p0.99:   7.684 ms/op
                 existUser·p0.999:  9.829 ms/op
                 existUser·p0.9999: 14.921 ms/op
                 existUser·p1.00:   15.991 ms/op

Iteration   2: 4.010 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   3.850 ms/op
                 existUser·p0.90:   5.194 ms/op
                 existUser·p0.95:   5.775 ms/op
                 existUser·p0.99:   7.982 ms/op
                 existUser·p0.999:  11.181 ms/op
                 existUser·p0.9999: 22.249 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   3: 4.049 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.873 ms/op
                 existUser·p0.50:   3.887 ms/op
                 existUser·p0.90:   5.104 ms/op
                 existUser·p0.95:   5.669 ms/op
                 existUser·p0.99:   7.651 ms/op
                 existUser·p0.999:  9.781 ms/op
                 existUser·p0.9999: 23.763 ms/op
                 existUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 236836
  mean =      4.053 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8111 
    [ 2.500,  5.000) = 197945 
    [ 5.000,  7.500) = 27935 
    [ 7.500, 10.000) = 2511 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     10.551 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     25.054 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.527 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.589 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.296 ±(99.9%) 0.014 ms/op
Iteration   1: 4.347 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   4.186 ms/op
                 getUser·p0.90:   5.603 ms/op
                 getUser·p0.95:   6.218 ms/op
                 getUser·p0.99:   8.421 ms/op
                 getUser·p0.999:  13.426 ms/op
                 getUser·p0.9999: 18.818 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   2: 4.516 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.743 ms/op
                 getUser·p0.95:   6.444 ms/op
                 getUser·p0.99:   8.667 ms/op
                 getUser·p0.999:  13.977 ms/op
                 getUser·p0.9999: 20.480 ms/op
                 getUser·p1.00:   21.660 ms/op

Iteration   3: 4.568 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.192 ms/op
                 getUser·p0.50:   4.391 ms/op
                 getUser·p0.90:   5.833 ms/op
                 getUser·p0.95:   6.480 ms/op
                 getUser·p0.99:   8.372 ms/op
                 getUser·p0.999:  11.846 ms/op
                 getUser·p0.9999: 23.036 ms/op
                 getUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 214451
  mean =      4.475 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4516 
    [ 2.500,  5.000) = 159212 
    [ 5.000,  7.500) = 46540 
    [ 7.500, 10.000) = 3448 
    [10.000, 12.500) = 448 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.726 ms/op
     p(95.0000) =      6.382 ms/op
     p(99.0000) =      8.503 ms/op
     p(99.9000) =     13.223 ms/op
     p(99.9900) =     21.991 ms/op
     p(99.9990) =     24.103 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 7.455 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.668 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.836 ±(99.9%) 0.023 ms/op
Iteration   1: 5.439 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.853 ms/op
                 listUser·p0.50:   5.112 ms/op
                 listUser·p0.90:   7.340 ms/op
                 listUser·p0.95:   8.331 ms/op
                 listUser·p0.99:   10.666 ms/op
                 listUser·p0.999:  17.502 ms/op
                 listUser·p0.9999: 21.958 ms/op
                 listUser·p1.00:   25.297 ms/op

Iteration   2: 5.575 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   5.202 ms/op
                 listUser·p0.90:   7.594 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   11.239 ms/op
                 listUser·p0.999:  18.139 ms/op
                 listUser·p0.9999: 27.599 ms/op
                 listUser·p1.00:   27.820 ms/op

Iteration   3: 5.450 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.579 ms/op
                 listUser·p0.50:   5.095 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.552 ms/op
                 listUser·p0.99:   11.239 ms/op
                 listUser·p0.999:  19.366 ms/op
                 listUser·p0.9999: 24.019 ms/op
                 listUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 174987
  mean =      5.487 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 351 
    [ 2.500,  5.000) = 78368 
    [ 5.000,  7.500) = 79340 
    [ 7.500, 10.000) = 13628 
    [10.000, 12.500) = 2419 
    [12.500, 15.000) = 463 
    [15.000, 17.500) = 189 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      7.455 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     11.043 ms/op
     p(99.9000) =     18.383 ms/op
     p(99.9900) =     26.886 ms/op
     p(99.9990) =     27.795 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.271 ± 8.157  ops/ms
ClientGrpc.existUser                       thrpt       3   8.207 ± 3.426  ops/ms
ClientGrpc.getUser                         thrpt       3   7.365 ± 0.608  ops/ms
ClientGrpc.listUser                        thrpt       3   5.849 ± 0.472  ops/ms
ClientGrpc.createUser                       avgt       3   4.303 ± 0.932   ms/op
ClientGrpc.existUser                        avgt       3   4.322 ± 0.393   ms/op
ClientGrpc.getUser                          avgt       3   4.376 ± 3.097   ms/op
ClientGrpc.listUser                         avgt       3   5.545 ± 2.691   ms/op
ClientGrpc.createUser                     sample  221503   4.334 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.883           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.595           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.128           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.135           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.394           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.016           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.201           ms/op
ClientGrpc.existUser                      sample  236836   4.053 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.840           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.895           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.210           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.792           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.750           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.551           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.512           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.362           ms/op
ClientGrpc.getUser                        sample  214451   4.475 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.750           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.726           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.382           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.503           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.223           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.991           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.216           ms/op
ClientGrpc.listUser                       sample  174987   5.487 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.208           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.455           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.454           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.043           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.383           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.886           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.820           ms/op
