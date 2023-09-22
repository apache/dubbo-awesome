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
# Warmup Iteration   1: 4.014 ops/ms
# Warmup Iteration   2: 8.395 ops/ms
# Warmup Iteration   3: 9.533 ops/ms
Iteration   1: 10.091 ops/ms
Iteration   2: 10.032 ops/ms
Iteration   3: 10.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.074 ±(99.9%) 0.665 ops/ms [Average]
  (min, avg, max) = (10.032, 10.074, 10.098), stdev = 0.036
  CI (99.9%): [9.409, 10.738] (assumes normal distribution)


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
# Warmup Iteration   1: 7.418 ops/ms
# Warmup Iteration   2: 10.128 ops/ms
# Warmup Iteration   3: 10.607 ops/ms
Iteration   1: 10.674 ops/ms
Iteration   2: 10.750 ops/ms
Iteration   3: 10.832 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.752 ±(99.9%) 1.441 ops/ms [Average]
  (min, avg, max) = (10.674, 10.752, 10.832), stdev = 0.079
  CI (99.9%): [9.311, 12.193] (assumes normal distribution)


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
# Warmup Iteration   1: 6.262 ops/ms
# Warmup Iteration   2: 9.607 ops/ms
# Warmup Iteration   3: 9.817 ops/ms
Iteration   1: 10.126 ops/ms
Iteration   2: 9.974 ops/ms
Iteration   3: 9.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.015 ±(99.9%) 1.770 ops/ms [Average]
  (min, avg, max) = (9.946, 10.015, 10.126), stdev = 0.097
  CI (99.9%): [8.245, 11.785] (assumes normal distribution)


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
# Warmup Iteration   1: 5.808 ops/ms
# Warmup Iteration   2: 7.552 ops/ms
# Warmup Iteration   3: 7.916 ops/ms
Iteration   1: 7.909 ops/ms
Iteration   2: 8.043 ops/ms
Iteration   3: 8.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.013 ±(99.9%) 1.685 ops/ms [Average]
  (min, avg, max) = (7.909, 8.013, 8.086), stdev = 0.092
  CI (99.9%): [6.328, 9.698] (assumes normal distribution)


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
# Warmup Iteration   1: 4.289 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.347 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.001 ms/op
Iteration   1: 3.117 ±(99.9%) 0.001 ms/op
Iteration   2: 3.151 ±(99.9%) 0.002 ms/op
Iteration   3: 3.100 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.123 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (3.100, 3.123, 3.151), stdev = 0.026
  CI (99.9%): [2.647, 3.599] (assumes normal distribution)


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
# Warmup Iteration   1: 3.944 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.003 ms/op
Iteration   1: 3.044 ±(99.9%) 0.002 ms/op
Iteration   2: 3.064 ±(99.9%) 0.002 ms/op
Iteration   3: 3.074 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.061 ±(99.9%) 0.275 ms/op [Average]
  (min, avg, max) = (3.044, 3.061, 3.074), stdev = 0.015
  CI (99.9%): [2.785, 3.336] (assumes normal distribution)


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
# Warmup Iteration   1: 4.165 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.309 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.002 ms/op
Iteration   1: 3.222 ±(99.9%) 0.001 ms/op
Iteration   2: 3.161 ±(99.9%) 0.001 ms/op
Iteration   3: 3.194 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.192 ±(99.9%) 0.560 ms/op [Average]
  (min, avg, max) = (3.161, 3.192, 3.222), stdev = 0.031
  CI (99.9%): [2.632, 3.752] (assumes normal distribution)


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
# Warmup Iteration   1: 4.975 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.012 ms/op
Iteration   1: 3.986 ±(99.9%) 0.039 ms/op
Iteration   2: 3.910 ±(99.9%) 0.041 ms/op
Iteration   3: 3.911 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.936 ±(99.9%) 0.789 ms/op [Average]
  (min, avg, max) = (3.910, 3.936, 3.986), stdev = 0.043
  CI (99.9%): [3.147, 4.725] (assumes normal distribution)


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
# Warmup Iteration   1: 4.394 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.340 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.007 ms/op
Iteration   1: 3.185 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.881 ms/op
                 createUser·p0.9999: 16.760 ms/op
                 createUser·p1.00:   17.990 ms/op

Iteration   2: 3.182 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  8.075 ms/op
                 createUser·p0.9999: 17.334 ms/op
                 createUser·p1.00:   19.268 ms/op

Iteration   3: 3.218 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   4.915 ms/op
                 createUser·p0.999:  12.914 ms/op
                 createUser·p0.9999: 22.861 ms/op
                 createUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300478
  mean =      3.195 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7414 
    [ 2.500,  5.000) = 291079 
    [ 5.000,  7.500) = 1406 
    [ 7.500, 10.000) = 323 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      8.872 ms/op
     p(99.9900) =     20.382 ms/op
     p(99.9990) =     26.050 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 4.260 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.005 ms/op
Iteration   1: 3.023 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.610 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  7.312 ms/op
                 existUser·p0.9999: 12.243 ms/op
                 existUser·p1.00:   12.468 ms/op

Iteration   2: 3.029 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.608 ms/op
                 existUser·p0.9999: 13.391 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   3: 3.061 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.511 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  8.864 ms/op
                 existUser·p0.9999: 16.346 ms/op
                 existUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315927
  mean =      3.038 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 637 
    [ 1.250,  2.500) = 16006 
    [ 2.500,  3.750) = 285548 
    [ 3.750,  5.000) = 12405 
    [ 5.000,  6.250) = 634 
    [ 6.250,  7.500) = 364 
    [ 7.500,  8.750) = 102 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 48 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      7.652 ms/op
     p(99.9900) =     15.860 ms/op
     p(99.9990) =     16.671 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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
# Warmup Iteration   1: 4.514 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.008 ms/op
Iteration   1: 3.156 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.145 ms/op
                 getUser·p0.999:  7.030 ms/op
                 getUser·p0.9999: 12.592 ms/op
                 getUser·p1.00:   13.124 ms/op

Iteration   2: 3.153 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.828 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  8.583 ms/op
                 getUser·p0.9999: 15.412 ms/op
                 getUser·p1.00:   15.647 ms/op

Iteration   3: 3.148 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.876 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  7.703 ms/op
                 getUser·p0.9999: 20.535 ms/op
                 getUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304607
  mean =      3.152 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4680 
    [ 2.500,  5.000) = 298271 
    [ 5.000,  7.500) = 1338 
    [ 7.500, 10.000) = 156 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.545 ms/op
     p(99.9900) =     19.603 ms/op
     p(99.9990) =     21.622 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 4.773 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.198 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.009 ms/op
Iteration   1: 4.065 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  13.353 ms/op
                 listUser·p0.9999: 15.075 ms/op
                 listUser·p1.00:   15.942 ms/op

Iteration   2: 3.936 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 16.834 ms/op
                 listUser·p1.00:   18.055 ms/op

Iteration   3: 4.027 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.802 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   6.856 ms/op
                 listUser·p0.999:  16.974 ms/op
                 listUser·p0.9999: 21.103 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239624
  mean =      4.009 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2134 
    [ 2.500,  5.000) = 220698 
    [ 5.000,  7.500) = 15478 
    [ 7.500, 10.000) = 797 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     14.361 ms/op
     p(99.9900) =     19.759 ms/op
     p(99.9990) =     21.568 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.074 ± 0.665  ops/ms
ClientGrpc.existUser                       thrpt       3  10.752 ± 1.441  ops/ms
ClientGrpc.getUser                         thrpt       3  10.015 ± 1.770  ops/ms
ClientGrpc.listUser                        thrpt       3   8.013 ± 1.685  ops/ms
ClientGrpc.createUser                       avgt       3   3.123 ± 0.476   ms/op
ClientGrpc.existUser                        avgt       3   3.061 ± 0.275   ms/op
ClientGrpc.getUser                          avgt       3   3.192 ± 0.560   ms/op
ClientGrpc.listUser                         avgt       3   3.936 ± 0.789   ms/op
ClientGrpc.createUser                     sample  300478   3.195 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.853           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.969           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.872           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.382           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.214           ms/op
ClientGrpc.existUser                      sample  315927   3.038 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.511           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.652           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.860           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.777           ms/op
ClientGrpc.getUser                        sample  304607   3.152 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.828           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.822           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.545           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.603           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.692           ms/op
ClientGrpc.listUser                       sample  239624   4.009 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.802           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.903           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.637           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.816           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.361           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.759           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.725           ms/op
