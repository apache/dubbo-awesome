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
# Warmup Iteration   1: 3.254 ops/ms
# Warmup Iteration   2: 7.357 ops/ms
# Warmup Iteration   3: 9.053 ops/ms
Iteration   1: 9.880 ops/ms
Iteration   2: 10.028 ops/ms
Iteration   3: 9.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.952 ±(99.9%) 1.350 ops/ms [Average]
  (min, avg, max) = (9.880, 9.952, 10.028), stdev = 0.074
  CI (99.9%): [8.602, 11.302] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.982 ops/ms
# Warmup Iteration   2: 9.711 ops/ms
# Warmup Iteration   3: 10.004 ops/ms
Iteration   1: 10.426 ops/ms
Iteration   2: 10.526 ops/ms
Iteration   3: 10.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.447 ±(99.9%) 1.290 ops/ms [Average]
  (min, avg, max) = (10.389, 10.447, 10.526), stdev = 0.071
  CI (99.9%): [9.158, 11.737] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.481 ops/ms
# Warmup Iteration   2: 9.102 ops/ms
# Warmup Iteration   3: 9.986 ops/ms
Iteration   1: 9.844 ops/ms
Iteration   2: 10.129 ops/ms
Iteration   3: 10.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.022 ±(99.9%) 2.836 ops/ms [Average]
  (min, avg, max) = (9.844, 10.022, 10.129), stdev = 0.155
  CI (99.9%): [7.186, 12.859] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 5.056 ops/ms
# Warmup Iteration   2: 6.855 ops/ms
# Warmup Iteration   3: 7.555 ops/ms
Iteration   1: 7.510 ops/ms
Iteration   2: 7.633 ops/ms
Iteration   3: 7.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.592 ±(99.9%) 1.296 ops/ms [Average]
  (min, avg, max) = (7.510, 7.592, 7.633), stdev = 0.071
  CI (99.9%): [6.295, 8.888] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 4.940 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.471 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.002 ms/op
Iteration   1: 3.166 ±(99.9%) 0.002 ms/op
Iteration   2: 3.137 ±(99.9%) 0.003 ms/op
Iteration   3: 3.205 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.169 ±(99.9%) 0.619 ms/op [Average]
  (min, avg, max) = (3.137, 3.169, 3.205), stdev = 0.034
  CI (99.9%): [2.550, 3.788] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.911 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.285 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.002 ms/op
Iteration   1: 3.082 ±(99.9%) 0.001 ms/op
Iteration   2: 3.113 ±(99.9%) 0.001 ms/op
Iteration   3: 2.964 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.053 ±(99.9%) 1.432 ms/op [Average]
  (min, avg, max) = (2.964, 3.053, 3.113), stdev = 0.079
  CI (99.9%): [1.621, 4.485] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.659 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.002 ms/op
Iteration   1: 3.229 ±(99.9%) 0.002 ms/op
Iteration   2: 3.186 ±(99.9%) 0.003 ms/op
Iteration   3: 3.233 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.216 ±(99.9%) 0.470 ms/op [Average]
  (min, avg, max) = (3.186, 3.216, 3.233), stdev = 0.026
  CI (99.9%): [2.746, 3.686] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.572 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.508 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.346 ±(99.9%) 0.015 ms/op
Iteration   1: 4.225 ±(99.9%) 0.010 ms/op
Iteration   2: 4.179 ±(99.9%) 0.015 ms/op
Iteration   3: 4.187 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.197 ±(99.9%) 0.453 ms/op [Average]
  (min, avg, max) = (4.179, 4.197, 4.225), stdev = 0.025
  CI (99.9%): [3.744, 4.650] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.017 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.007 ms/op
Iteration   1: 3.175 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   4.964 ms/op
                 createUser·p0.999:  9.454 ms/op
                 createUser·p0.9999: 14.908 ms/op
                 createUser·p1.00:   15.204 ms/op

Iteration   2: 3.135 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.344 ms/op
                 createUser·p0.50:   3.103 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  7.635 ms/op
                 createUser·p0.9999: 16.974 ms/op
                 createUser·p1.00:   17.302 ms/op

Iteration   3: 3.175 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  14.418 ms/op
                 createUser·p0.9999: 20.969 ms/op
                 createUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303599
  mean =      3.162 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9166 
    [ 2.500,  5.000) = 292342 
    [ 5.000,  7.500) = 1534 
    [ 7.500, 10.000) = 279 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.344 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      9.493 ms/op
     p(99.9900) =     20.108 ms/op
     p(99.9990) =     21.427 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.509 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.007 ms/op
Iteration   1: 3.172 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  8.283 ms/op
                 existUser·p0.9999: 17.954 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   2: 2.963 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  11.270 ms/op
                 existUser·p0.9999: 33.397 ms/op
                 existUser·p1.00:   34.144 ms/op

Iteration   3: 3.021 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.783 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  12.382 ms/op
                 existUser·p0.9999: 22.668 ms/op
                 existUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315148
  mean =      3.049 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23250 
    [ 2.500,  5.000) = 290553 
    [ 5.000,  7.500) = 751 
    [ 7.500, 10.000) = 239 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =     11.043 ms/op
     p(99.9900) =     31.637 ms/op
     p(99.9990) =     33.741 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 4.614 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.445 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.007 ms/op
Iteration   1: 3.141 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.787 ms/op
                 getUser·p0.999:  8.440 ms/op
                 getUser·p0.9999: 21.758 ms/op
                 getUser·p1.00:   22.020 ms/op

Iteration   2: 3.136 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  7.881 ms/op
                 getUser·p0.9999: 16.462 ms/op
                 getUser·p1.00:   17.826 ms/op

Iteration   3: 3.137 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.347 ms/op
                 getUser·p0.9999: 19.333 ms/op
                 getUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306037
  mean =      3.138 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13288 
    [ 2.500,  5.000) = 290886 
    [ 5.000,  7.500) = 1411 
    [ 7.500, 10.000) = 292 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      8.004 ms/op
     p(99.9900) =     20.892 ms/op
     p(99.9990) =     21.985 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.169 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.585 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.013 ms/op
Iteration   1: 4.213 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   7.739 ms/op
                 listUser·p0.999:  15.139 ms/op
                 listUser·p0.9999: 17.557 ms/op
                 listUser·p1.00:   21.463 ms/op

Iteration   2: 4.107 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.046 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  18.383 ms/op
                 listUser·p0.9999: 20.021 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   3: 4.080 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  19.180 ms/op
                 listUser·p0.9999: 23.069 ms/op
                 listUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232299
  mean =      4.133 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2236 
    [ 2.500,  5.000) = 197941 
    [ 5.000,  7.500) = 30059 
    [ 7.500, 10.000) = 1542 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      6.021 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     17.161 ms/op
     p(99.9900) =     22.726 ms/op
     p(99.9990) =     24.745 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.952 ± 1.350  ops/ms
ClientGrpc.existUser                       thrpt       3  10.447 ± 1.290  ops/ms
ClientGrpc.getUser                         thrpt       3  10.022 ± 2.836  ops/ms
ClientGrpc.listUser                        thrpt       3   7.592 ± 1.296  ops/ms
ClientGrpc.createUser                       avgt       3   3.169 ± 0.619   ms/op
ClientGrpc.existUser                        avgt       3   3.053 ± 1.432   ms/op
ClientGrpc.getUser                          avgt       3   3.216 ± 0.470   ms/op
ClientGrpc.listUser                         avgt       3   4.197 ± 0.453   ms/op
ClientGrpc.createUser                     sample  303599   3.162 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.344           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.113           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.936           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.493           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.108           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.326           ms/op
ClientGrpc.existUser                      sample  315148   3.049 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.681           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.015           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.793           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.043           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.637           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.144           ms/op
ClientGrpc.getUser                        sample  306037   3.138 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.731           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.628           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.004           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.892           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.020           ms/op
ClientGrpc.listUser                       sample  232299   4.133 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.046           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.924           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.341           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.021           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.356           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.161           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.726           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.035           ms/op
