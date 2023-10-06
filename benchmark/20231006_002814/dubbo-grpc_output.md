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
# Warmup Iteration   1: 3.618 ops/ms
# Warmup Iteration   2: 8.125 ops/ms
# Warmup Iteration   3: 9.373 ops/ms
Iteration   1: 9.504 ops/ms
Iteration   2: 9.519 ops/ms
Iteration   3: 9.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.478 ±(99.9%) 1.047 ops/ms [Average]
  (min, avg, max) = (9.413, 9.478, 9.519), stdev = 0.057
  CI (99.9%): [8.432, 10.525] (assumes normal distribution)


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
# Warmup Iteration   1: 7.666 ops/ms
# Warmup Iteration   2: 9.673 ops/ms
# Warmup Iteration   3: 9.692 ops/ms
Iteration   1: 10.217 ops/ms
Iteration   2: 10.274 ops/ms
Iteration   3: 10.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.226 ±(99.9%) 0.811 ops/ms [Average]
  (min, avg, max) = (10.186, 10.226, 10.274), stdev = 0.044
  CI (99.9%): [9.415, 11.036] (assumes normal distribution)


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
# Warmup Iteration   1: 5.768 ops/ms
# Warmup Iteration   2: 9.206 ops/ms
# Warmup Iteration   3: 9.456 ops/ms
Iteration   1: 9.670 ops/ms
Iteration   2: 9.513 ops/ms
Iteration   3: 9.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.603 ±(99.9%) 1.482 ops/ms [Average]
  (min, avg, max) = (9.513, 9.603, 9.670), stdev = 0.081
  CI (99.9%): [8.121, 11.085] (assumes normal distribution)


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
# Warmup Iteration   1: 4.869 ops/ms
# Warmup Iteration   2: 7.344 ops/ms
# Warmup Iteration   3: 7.762 ops/ms
Iteration   1: 7.586 ops/ms
Iteration   2: 7.606 ops/ms
Iteration   3: 7.322 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.505 ±(99.9%) 2.891 ops/ms [Average]
  (min, avg, max) = (7.322, 7.505, 7.606), stdev = 0.158
  CI (99.9%): [4.614, 10.396] (assumes normal distribution)


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
# Warmup Iteration   1: 4.892 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.003 ms/op
Iteration   1: 3.490 ±(99.9%) 0.002 ms/op
Iteration   2: 3.281 ±(99.9%) 0.001 ms/op
Iteration   3: 3.386 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.385 ±(99.9%) 1.911 ms/op [Average]
  (min, avg, max) = (3.281, 3.385, 3.490), stdev = 0.105
  CI (99.9%): [1.474, 5.297] (assumes normal distribution)


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
# Warmup Iteration   1: 4.444 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.002 ms/op
Iteration   1: 3.135 ±(99.9%) 0.001 ms/op
Iteration   2: 3.138 ±(99.9%) 0.001 ms/op
Iteration   3: 3.173 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.148 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (3.135, 3.148, 3.173), stdev = 0.021
  CI (99.9%): [2.764, 3.533] (assumes normal distribution)


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
# Warmup Iteration   1: 4.377 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.002 ms/op
Iteration   1: 3.444 ±(99.9%) 0.002 ms/op
Iteration   2: 3.346 ±(99.9%) 0.004 ms/op
Iteration   3: 3.517 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.436 ±(99.9%) 1.566 ms/op [Average]
  (min, avg, max) = (3.346, 3.436, 3.517), stdev = 0.086
  CI (99.9%): [1.870, 5.002] (assumes normal distribution)


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
# Warmup Iteration   1: 5.796 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.381 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.228 ±(99.9%) 0.012 ms/op
Iteration   1: 4.226 ±(99.9%) 0.014 ms/op
Iteration   2: 4.169 ±(99.9%) 0.014 ms/op
Iteration   3: 4.224 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.206 ±(99.9%) 0.592 ms/op [Average]
  (min, avg, max) = (4.169, 4.206, 4.226), stdev = 0.032
  CI (99.9%): [3.614, 4.799] (assumes normal distribution)


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
# Warmup Iteration   1: 5.070 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.529 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.417 ±(99.9%) 0.008 ms/op
Iteration   1: 3.377 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  9.306 ms/op
                 createUser·p0.9999: 26.103 ms/op
                 createUser·p1.00:   29.393 ms/op

Iteration   2: 3.347 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.346 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   4.145 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  13.176 ms/op
                 createUser·p0.9999: 20.181 ms/op
                 createUser·p1.00:   20.808 ms/op

Iteration   3: 3.413 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  17.891 ms/op
                 createUser·p0.9999: 35.300 ms/op
                 createUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 283987
  mean =      3.379 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16427 
    [ 2.500,  5.000) = 262835 
    [ 5.000,  7.500) = 3740 
    [ 7.500, 10.000) = 615 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     12.386 ms/op
     p(99.9900) =     34.577 ms/op
     p(99.9990) =     35.652 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


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
# Warmup Iteration   1: 4.576 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.007 ms/op
Iteration   1: 3.189 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   4.964 ms/op
                 existUser·p0.999:  6.939 ms/op
                 existUser·p0.9999: 18.898 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   2: 3.133 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.617 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   4.956 ms/op
                 existUser·p0.999:  8.434 ms/op
                 existUser·p0.9999: 19.777 ms/op
                 existUser·p1.00:   20.283 ms/op

Iteration   3: 3.036 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   4.973 ms/op
                 existUser·p0.999:  8.098 ms/op
                 existUser·p0.9999: 22.166 ms/op
                 existUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 307937
  mean =      3.118 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32768 
    [ 2.500,  5.000) = 272216 
    [ 5.000,  7.500) = 2583 
    [ 7.500, 10.000) = 207 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      4.964 ms/op
     p(99.9000) =      7.881 ms/op
     p(99.9900) =     21.070 ms/op
     p(99.9990) =     22.738 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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
# Warmup Iteration   1: 4.617 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.526 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.009 ms/op
Iteration   1: 3.531 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  12.078 ms/op
                 getUser·p0.9999: 13.843 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   2: 3.393 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   4.125 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   5.128 ms/op
                 getUser·p0.999:  7.613 ms/op
                 getUser·p0.9999: 15.984 ms/op
                 getUser·p1.00:   16.679 ms/op

Iteration   3: 3.369 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   5.267 ms/op
                 getUser·p0.999:  9.667 ms/op
                 getUser·p0.9999: 17.826 ms/op
                 getUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 279720
  mean =      3.430 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 6549 
    [ 2.500,  3.750) = 204019 
    [ 3.750,  5.000) = 63943 
    [ 5.000,  6.250) = 3391 
    [ 6.250,  7.500) = 882 
    [ 7.500,  8.750) = 417 
    [ 8.750, 10.000) = 179 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.961 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     18.042 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 6.107 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.518 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.522 ±(99.9%) 0.017 ms/op
Iteration   1: 4.470 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   4.186 ms/op
                 listUser·p0.90:   6.103 ms/op
                 listUser·p0.95:   7.004 ms/op
                 listUser·p0.99:   8.598 ms/op
                 listUser·p0.999:  20.120 ms/op
                 listUser·p0.9999: 25.019 ms/op
                 listUser·p1.00:   25.362 ms/op

Iteration   2: 4.429 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   4.137 ms/op
                 listUser·p0.90:   6.062 ms/op
                 listUser·p0.95:   6.898 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  17.530 ms/op
                 listUser·p0.9999: 22.874 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   3: 4.297 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   4.104 ms/op
                 listUser·p0.90:   5.396 ms/op
                 listUser·p0.95:   6.332 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  16.993 ms/op
                 listUser·p0.9999: 20.171 ms/op
                 listUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 218378
  mean =      4.397 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 852 
    [ 2.500,  5.000) = 178043 
    [ 5.000,  7.500) = 34306 
    [ 7.500, 10.000) = 4309 
    [10.000, 12.500) = 387 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      4.141 ms/op
     p(90.0000) =      5.857 ms/op
     p(95.0000) =      6.791 ms/op
     p(99.0000) =      8.364 ms/op
     p(99.9000) =     18.252 ms/op
     p(99.9900) =     23.964 ms/op
     p(99.9990) =     25.273 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.478 ± 1.047  ops/ms
ClientGrpc.existUser                       thrpt       3  10.226 ± 0.811  ops/ms
ClientGrpc.getUser                         thrpt       3   9.603 ± 1.482  ops/ms
ClientGrpc.listUser                        thrpt       3   7.505 ± 2.891  ops/ms
ClientGrpc.createUser                       avgt       3   3.385 ± 1.911   ms/op
ClientGrpc.existUser                        avgt       3   3.148 ± 0.385   ms/op
ClientGrpc.getUser                          avgt       3   3.436 ± 1.566   ms/op
ClientGrpc.listUser                         avgt       3   4.206 ± 0.592   ms/op
ClientGrpc.createUser                     sample  283987   3.379 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.346           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.293           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.178           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.386           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.577           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.717           ms/op
ClientGrpc.existUser                      sample  307937   3.118 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.617           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.056           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.838           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.104           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.964           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.881           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.070           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.839           ms/op
ClientGrpc.getUser                        sample  279720   3.430 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.958           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.346           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.166           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.961           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.302           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.153           ms/op
ClientGrpc.listUser                       sample  218378   4.397 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.870           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.141           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.364           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.252           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.964           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.362           ms/op
