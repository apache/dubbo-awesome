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
# Warmup Iteration   1: 4.044 ops/ms
# Warmup Iteration   2: 8.187 ops/ms
# Warmup Iteration   3: 9.532 ops/ms
Iteration   1: 10.073 ops/ms
Iteration   2: 10.152 ops/ms
Iteration   3: 10.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.142 ±(99.9%) 1.161 ops/ms [Average]
  (min, avg, max) = (10.073, 10.142, 10.199), stdev = 0.064
  CI (99.9%): [8.981, 11.302] (assumes normal distribution)


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
# Warmup Iteration   1: 7.137 ops/ms
# Warmup Iteration   2: 10.423 ops/ms
# Warmup Iteration   3: 10.922 ops/ms
Iteration   1: 10.830 ops/ms
Iteration   2: 11.160 ops/ms
Iteration   3: 10.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.976 ±(99.9%) 3.071 ops/ms [Average]
  (min, avg, max) = (10.830, 10.976, 11.160), stdev = 0.168
  CI (99.9%): [7.906, 14.047] (assumes normal distribution)


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
# Warmup Iteration   1: 6.605 ops/ms
# Warmup Iteration   2: 9.896 ops/ms
# Warmup Iteration   3: 10.131 ops/ms
Iteration   1: 10.091 ops/ms
Iteration   2: 10.345 ops/ms
Iteration   3: 10.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.274 ±(99.9%) 2.901 ops/ms [Average]
  (min, avg, max) = (10.091, 10.274, 10.384), stdev = 0.159
  CI (99.9%): [7.373, 13.175] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.440 ops/ms
# Warmup Iteration   2: 7.469 ops/ms
# Warmup Iteration   3: 7.694 ops/ms
Iteration   1: 7.781 ops/ms
Iteration   2: 7.866 ops/ms
Iteration   3: 7.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.867 ±(99.9%) 1.573 ops/ms [Average]
  (min, avg, max) = (7.781, 7.867, 7.954), stdev = 0.086
  CI (99.9%): [6.294, 9.440] (assumes normal distribution)


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
# Warmup Iteration   1: 4.227 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.003 ms/op
Iteration   1: 3.133 ±(99.9%) 0.009 ms/op
Iteration   2: 3.127 ±(99.9%) 0.004 ms/op
Iteration   3: 3.119 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.126 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (3.119, 3.126, 3.133), stdev = 0.007
  CI (99.9%): [3.000, 3.253] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.091 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.003 ms/op
Iteration   1: 2.903 ±(99.9%) 0.003 ms/op
Iteration   2: 2.951 ±(99.9%) 0.003 ms/op
Iteration   3: 2.907 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.920 ±(99.9%) 0.485 ms/op [Average]
  (min, avg, max) = (2.903, 2.920, 2.951), stdev = 0.027
  CI (99.9%): [2.435, 3.405] (assumes normal distribution)


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
# Warmup Iteration   1: 4.434 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.005 ms/op
Iteration   1: 3.099 ±(99.9%) 0.005 ms/op
Iteration   2: 3.097 ±(99.9%) 0.003 ms/op
Iteration   3: 3.100 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.098 ±(99.9%) 0.028 ms/op [Average]
  (min, avg, max) = (3.097, 3.098, 3.100), stdev = 0.002
  CI (99.9%): [3.070, 3.126] (assumes normal distribution)


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
# Warmup Iteration   1: 5.391 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.276 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.040 ms/op
Iteration   1: 4.101 ±(99.9%) 0.024 ms/op
Iteration   2: 4.097 ±(99.9%) 0.021 ms/op
Iteration   3: 4.091 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.096 ±(99.9%) 0.088 ms/op [Average]
  (min, avg, max) = (4.091, 4.096, 4.101), stdev = 0.005
  CI (99.9%): [4.008, 4.184] (assumes normal distribution)


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
# Warmup Iteration   1: 4.443 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.007 ms/op
Iteration   1: 3.132 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  8.978 ms/op
                 createUser·p0.9999: 13.238 ms/op
                 createUser·p1.00:   15.270 ms/op

Iteration   2: 3.112 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  7.835 ms/op
                 createUser·p0.9999: 14.561 ms/op
                 createUser·p1.00:   14.729 ms/op

Iteration   3: 3.099 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.581 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  10.158 ms/op
                 createUser·p0.9999: 33.402 ms/op
                 createUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308280
  mean =      3.114 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16248 
    [ 2.500,  5.000) = 290043 
    [ 5.000,  7.500) = 1479 
    [ 7.500, 10.000) = 241 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      9.084 ms/op
     p(99.9900) =     32.965 ms/op
     p(99.9990) =     34.073 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.317 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
Iteration   1: 3.021 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.108 ms/op
                 existUser·p0.999:  8.209 ms/op
                 existUser·p0.9999: 16.218 ms/op
                 existUser·p1.00:   16.646 ms/op

Iteration   2: 3.009 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.026 ms/op
                 existUser·p0.9999: 14.713 ms/op
                 existUser·p1.00:   14.959 ms/op

Iteration   3: 2.961 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  10.795 ms/op
                 existUser·p0.9999: 19.956 ms/op
                 existUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320394
  mean =      2.997 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25066 
    [ 2.500,  5.000) = 293898 
    [ 5.000,  7.500) = 991 
    [ 7.500, 10.000) = 215 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     17.443 ms/op
     p(99.9990) =     20.054 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 4.301 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
Iteration   1: 3.137 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.591 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   5.120 ms/op
                 getUser·p0.999:  9.471 ms/op
                 getUser·p0.9999: 17.459 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   2: 3.086 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  7.966 ms/op
                 getUser·p0.9999: 32.375 ms/op
                 getUser·p1.00:   32.702 ms/op

Iteration   3: 3.072 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  7.698 ms/op
                 getUser·p0.9999: 25.336 ms/op
                 getUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309795
  mean =      3.098 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19674 
    [ 2.500,  5.000) = 287395 
    [ 5.000,  7.500) = 2189 
    [ 7.500, 10.000) = 323 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.907 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     31.163 ms/op
     p(99.9990) =     32.565 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


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
# Warmup Iteration   1: 5.362 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.324 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.012 ms/op
Iteration   1: 4.084 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.416 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.245 ms/op
                 listUser·p0.999:  15.320 ms/op
                 listUser·p0.9999: 21.571 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   2: 3.983 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.632 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  14.234 ms/op
                 listUser·p0.9999: 17.039 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   3: 4.038 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.046 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  16.689 ms/op
                 listUser·p0.9999: 23.136 ms/op
                 listUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238116
  mean =      4.034 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2377 
    [ 2.500,  5.000) = 211150 
    [ 5.000,  7.500) = 22897 
    [ 7.500, 10.000) = 1158 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.416 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     15.335 ms/op
     p(99.9900) =     21.729 ms/op
     p(99.9990) =     23.928 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.142 ± 1.161  ops/ms
ClientGrpc.existUser                       thrpt       3  10.976 ± 3.071  ops/ms
ClientGrpc.getUser                         thrpt       3  10.274 ± 2.901  ops/ms
ClientGrpc.listUser                        thrpt       3   7.867 ± 1.573  ops/ms
ClientGrpc.createUser                       avgt       3   3.126 ± 0.127   ms/op
ClientGrpc.existUser                        avgt       3   2.920 ± 0.485   ms/op
ClientGrpc.getUser                          avgt       3   3.098 ± 0.028   ms/op
ClientGrpc.listUser                         avgt       3   4.096 ± 0.088   ms/op
ClientGrpc.createUser                     sample  308280   3.114 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.581           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.666           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.620           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.084           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.965           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.210           ms/op
ClientGrpc.existUser                      sample  320394   2.997 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.797           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.405           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.443           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.054           ms/op
ClientGrpc.getUser                        sample  309795   3.098 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.591           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.907           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.602           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.163           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.702           ms/op
ClientGrpc.listUser                       sample  238116   4.034 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.416           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.875           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.335           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.729           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.150           ms/op
